# Task-2
Design and integration of memory - mapped IP.

In this task, a custom GPIO output IP (gipo_out.v) was designed, integrated into a wrapper (soc_wrapper.v), and verified using a testbench (tb_soc.v).

FILES

gipo_out.v – Custom GPIO IP implementation

soc_wrapper.v – Wrapper module integrating GPIO IP

tb_soc.v – Testbench applying reset, write, and readback stimulus

tb_soc.vcd – Required output

terminal output.

OUTPUT OBTAINED.

At Time=0, GPIO output was 00000000 

At Time=25000, GPIO output updated to deadbeef.

VERIFICATION.

Reset behavior: GPIO output initialized to zero

Write operation: GPIO output correctly updated with deadbeef

Readback: rdata matched the written value

EVIDENCE.

Terminal Output Screenshot: Shows GPIO output transition from 00000000 to deadbeef

GTKWave Screenshot: Displays waveform of clk, rst_n, and gpio_o

CONCLUSION.

Task‑2 is successfully completed. The GPIO IP was integrated and verified through terminal output.Hence it proves the correct functioning of the design.
