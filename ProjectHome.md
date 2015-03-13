This project is about implementation of SDLX a 32-bit RISC processor on Xilinx Sparatan-3 FPGA.

I, alongwith, Rajiv Kumar implemented the same.
Following are the salient features -
1. 5-stage pipeline (IF, ID, EX, LSU, WB)
2. Hazard Handling (RAW are possible in this design)
3. Data Forwarding (from EX, LSU and WB to EX)
4. Cache modeling (instruction cache, data cache and corresponding arbiter)