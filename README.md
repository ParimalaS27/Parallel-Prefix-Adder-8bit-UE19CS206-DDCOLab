# Parallel-Prefix-Adder-8bit-UE19CS206-DDCOLab
This repo consists of the icarus verilog implementation of a Parallel Prefix adder - 8bit (I/P - O/P). This was done as a part of a project Under UE19CS206 - Digital Design and Computer Organization Laboratory Course at PES University.

Created and tested on Linux Environment. 

# Compilation
Use the following commands to compile the file with the testbench and create the waveform image:

iverilog -o prefix prefix_adder.v tb_prefix_adder.v
vvp prefix

Finally, view the waveform using:
gtkwave dump.vcd
