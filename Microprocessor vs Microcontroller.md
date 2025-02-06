- MP 
	- suited to processing information in computer systems
- MC 
	- suited to control I/O devices requiring a minimum of component count


Instructions sets:
- MP:
	- processing intensive
	- powerful addressing modes
	- instructions to perform complex operations & manipulate large volumes of data
	- processing capability of MCs never approaches those of MPs
	- large instructions , e.g. 80x86 7-bit long instructions
- MC
	- cater to control of inputs and outputs
	- instructions to set/clear bits
	- boolean operations (AND, OR, XOR, NOT, jump if a bit is set/cleared), etc.
	- Extremely compact instructions, many implemented in one byte

Hardware & Instruction set support:
- MP:
	- usually require external circuitry to do similar things (e.g., 8255 PPI, 8253 PIT, 8259 PIC)
- MC:
	- built-in I/O operations, event timing, enabling & Setting up priority levels for interrupts caused by external stimuli


Bus widths:
- MP:
	- very wide
	- large memory address spaces (>4GB)
	- lots of data (Data bus: 32, 64, 128 bits wide)
- MC: 
	- narrow 
	- relatively small memory address spaces (typically kBytes)
	- less data (Data bus typically 8, 16 bits wide)

Clock rates:
- MP
	- Very fast (> 1GHz)
- MC
	- Relatively slow (typically 10-20 MHz) since most I/O devices being controlled are relatively slow

Cost:
- MP:
	- Expensive
- MC:
	- cheap