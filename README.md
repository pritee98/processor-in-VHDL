processor-in-VHDL
================

this is project in vhdl which acts like 2 bit micropressor.it consist of ROM which consist of data1,data2 which are 2 bit long and opcode which is first 3 bits of word in rom instructions.they are fetched in cpu.vhd in each clk cycle and according to opcode operation 
is performed.if intruppt is activated then instruction at 0003 location is executed.
