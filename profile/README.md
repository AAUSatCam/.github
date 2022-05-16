# Reading instructions
This organisation is used to provide source code for the AAU Sat Cam project for group es-22-eit-4-410 <es-22-eit-4-410@student.aau.dk> at Aalborg University, anno 2022.

The code has been structured in different ways:
- FPGA
  - Consist only of VHDL files. This is relevant to understanding the FPGA part of the project, i.e. different blocks used in the project.
- CPU
  - Consists only of C and Header files. This is relevant to understand the CPU part of the project, i.e. CAN/CSP drivers, FreeRTOS tasks and calling to compression algorithm.
- StandaloneCompression
  - Consists only of C and Header files. This is relevant to understand the Compression part of the project, i.e. DCT, Quantization, Zigzag encoding, Runlength encoding and Huffman encoding.
- Vivado
  - Consists of all the files needed to recreate the project in Vivado, to be able to generate bitstream files and/or continue development of project.
- Vitis
  - Consists of all the files needed to recreate the project in Vitis, to be able to compile elf files and/or continue development of project.
- CSPClient
  - Contains the software used to act as a CSP client on CAN bus.
- Python
  - Contains the python scripts used in the project.

- .github
  - Repo with files specific for presentation of the github organisation
