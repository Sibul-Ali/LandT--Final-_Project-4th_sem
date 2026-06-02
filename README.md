# LandT--Final-_Project-4th_sem
DESIGN AND IMPLEMENTATION OF A    UART-TO-AXI LITE BRIDGE ON FPGA

About:

This project report details the design, simulation, and physical hardware implementation of a custom UART-to-AXI Bridge developed in Verilog HDL. The architecture functions as an on-chip protocol translation gateway, bridging asynchronous serial communication networks with synchronous parallel internal system register buses. The design processes external character streams (UART protocol) and translates them into memory-mapped configurations (AXI-Lite style fabric operations). This approach allows an external terminal to read and write directly to internal FPGA registers using a physical footprint of just two wires (Rx and Tx). Synthesized, placed, and routed using the AMD Vivado Design Suite on an Artix-7 FPGA, the framework demonstrates ultra-low resource overhead, utilizing less than or equal to 0.03% of the device's internal slice logic. This efficiency makes it an optimal solution for modular hardware debugging, configuration, and remote testing systems.
