HOW TO RUN IN WINDOWS 
Install Iverilog along with gtkwave. 
iverilog.exe -o NOC tb_route_3x2.v
vvp.exe NOC
VCD info: dumpfile router3.vcd opened for output.
gtkwave.exe router3.vcd
