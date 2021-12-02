## RISC 16-Bit Processor 

The processor is built on VHDL and uses the Cyclone V device to ensure 1 MB of RAM. Please ensure Cyclone V is installed on your VHDL setup.

The main entity is called iitbproc, it outputs the current value of register 0 and current state (for ease of debugging)

To run the setup please use the supplied testbench (`iitbproc_tb.vhd`), simply change the location of the input and output files. The input file contains the assembly code in binary format, to convert assembly code into binary, please use the `asm2bin.py` script present in `example_code` folder. A sample binary file has already been provided by the name `input_file.txt` in the same folder.

You can use the `asm2bin.py` script to convert assembly to binary. We have supplied one example program (`fibonacci.asm`) that prints first 21 fibonacci numbers (starting from 1,2,3,5,8..). The output file will contain the value of register 0 so ensure that the output is stored in register 0.


