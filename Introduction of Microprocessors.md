## History of Microprocessors
- First invented by the company led by Gordan Moore and Robert Noyce in 1968 (from Fairchild semiconductor company and start-up Intel)
- The first microprocessor like Intel 4004 was invented by Ted Hoff, Masatoshi Shima, Federico Faggin, and Stanley Mazor
- Marcian Edward "Ted" Hoff, a young scientist at Intel, was assigned to work with minicomputers and in June 1968. Join a group of Japanese engineers from a company called Busicom. They'd approached intel with a design for a small calculator
- Hoff felt that programming through read-only memory and general purpose registers could replace the separate components the Busicom engineers had requested
- Federico Faggin, took him 9 months  to turn Hoff's ideas into hardware while Mazor helped define the architecture and instruction set for the revolutionary new chip


## Development of some of the microprocessors

| Model                                                           | Architecture                                    | Year                         |
| --------------------------------------------------------------- | ----------------------------------------------- | ---------------------------- |
| Intel 4004                                                      | 4 bit (2300 PMOS transistors)                   | 1971                         |
| Intel 8080<br>8085                                              | 8 bit(nmos)<br>8 bit                            | 1974                         |
| Intel 8088<br>8086                                              | 16 bit<br>16 bit                                | 1978                         |
| Intel 80186<br>80286                                            | 16 bit<br>16 bit                                | 1982<br>                     |
| Intel 80386                                                     | 32bit (275000 transistors)                      | 1985                         |
| Intel 80486 sx<br>dx                                            | 32 bit<br>32 bit (built in floating point unit) | 1989<br>                     |
| Intel 80586 I<br>MMX<br>Celeron II<br>Celeron III<br>Celeron IV | 64 bit                                          | 1993<br>1997<br>1999<br>2000 |
| Z-80 (Zilog)                                                    | 8 bit                                           | 1976                         |
| Motorola Power PC 601<br>602<br>603                             | 32 bit                                          | 1993<br>1995                 |
![[Pasted image 20250204134347.png]]


## What is a microprocessor?
- Is the integration of a number of useful functions into a single IC package
- The functions are:
	- Execute a stored set of instructions to carry out user defined tasks
	- Access external memory chips to both read and write data from and to the memory
	- Interface with I/O devices

![[Pasted image 20250206110110.png]]
![[Pasted image 20250206110135.png]]
## Components of the microprocessor
- Components of this processor are ALU, Control Unit, Input-output devices, and register array
	- ALU performs both arithmetic and logical operations. Arithmetic operations such as addition subtraction, multiplications, divisions, and logical operations such as NOR, AND, NAND, OR, XOR, NOT, XNOR, etc.
	- The control unit is used to control the instructions and it generates the signals to operate the other components

## Basic Components of the Microprocessor
- The register array consists of registers. Registers that are used by the programmer to store arbitrary data are known as general0purpose registers and the registers which are not used by a programmer to store the data are known as the reserved registers. The length of the register is known as the word length of the computer
- Input-output devices are used to transfer data between microcomputers and external devices



## Evolution of Microprocessors
- First Generation (4-bit Microprocessors)
	- The first generation microprocessors were introduced in the year 1971-1972 by Intel Corporation. It was named Intel 4004 since it was a 40bit processor.
	- It was a processor on a single chip. it could perform simple arithmetic and logical operations such as Addition, Subtraction, Boolean OR and Boolean AND.
	- It had a control unit capable of performing control functions like fetching and instruction from storage memory, decoding it, and then generating control pulses to execute it. 
- Second generation ( 8 - bit Microprocessor )
	- The second generation microprocessors were introduced in 1973 again by Intel. It was a first 8 - bit microprocessor which could perform arithmetic and logic operations on 8-bit words. It was Intel 8008 and another improved version was 8088
- Third Generation (16-bit Microprocessor)
	- The third generation microprocessors, introduced in 1978 were represented by Intel's 8086, Zilog Z800 and 80286, which were 16-bit processors with a performance like minicomputers
- Fourth Generation (32-bit Microprocessors)
	- Several different companies introduced the 32-bit microprocessors, but the most popular one is the Intel 80386.
- Fifth Generation (64-bit Microprocessors)
	- From 1995 to now we are in the fifth generation. After 80856, Intel came out with a new processor namely Pentium processor followed by Pentium Pro CPU, which allows multiple CPUs in a single system to achieve multiprocessing
	- Other improved 64-bit processors are Celeron, Dual, Quad, Octa Core processors



## Working of Microprocessor
- Follows a sequence to execute the instruction, Fetch, Decode, and then Execute.
- Initially, the instructions are stored in the storage memory of the computer in sequential order. The microprocessor fetches those instructions from the stored area, then decodes it and executes those instructions till STOP instruction is met. Then it sends the result in binary form to the output port. Between these processes, the register stores the temporary data and ALU performs the computing functions

