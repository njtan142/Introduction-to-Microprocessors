- A device which integrates a number of the components of a microprocessor system onto a single chip
- only need to be supplied power and clocking
- Microcontroller combines on the same chip:
	- CPU core
	- Memory (both ROM and RAM)
	- Some parallel digital I/O

![[Pasted image 20250206110310.png]]

## Why the name micro controller?
- Splitting the word micro-controller into two, Micro is derived from a Greek word micros which means small and Controller is the logic circuitry that does the control action based on the program written

## History of Microcontrollers
- The first computer system on a chip optimized for control applications - microcontroller was the Intel 8048 released in 1976, with both RAM and ROM on the same chip
- Development of some popular microcontrollers

| Model                | Architecture               | Year |
| -------------------- | -------------------------- | ---- |
| Intel 4004           | 4 bit                      | 1971 |
| intel 8048           | 8 bit                      | 1976 |
| intel 8031           | 8 bit(ROM-less)            |      |
| intel 8051           | 8 bit (mask ROM)           | 1980 |
| Microchip PIC16c64   | 8 bit                      | 1985 |
| motorola 68hc11      | 8 bit (on chip adc)        |      |
| Intel 80c196         | 16 bit                     | 1982 |
| Atmel AT89c51        | 8 bit (flash memory)       |      |
| Microchip pic 16f877 | 8 bit (flash memory + adc) |      |

## Most microcontrollers will also combine other devices such as:
- Timer module to allow the microcontroller to perform task for certain time periods.
- Serial I/O to allow data to flow between the microcontroller and other devices such as a PC or another microcontroller
- An ADC to allow the microcontroller to accept analogue input data for processing

![[Pasted image 20250206110459.png]]

## CPU
- The heart of the microcontroller
- traditionally based on a 8-bit processor unit
	- e.g., Motorola uses basic 6800 microprocessor core in M68HC11 microcontroller devices

![[Pasted image 20250206110557.png]]


## Registers:
- Serves as memory locations
- Help some perform various mathematical operations or any other operations with data wherever data can be found

## Memory Unit
- Memory
	- Part of the microcontroller whose function is to store data
- Types of memories:
	- Volatile
		- RAM - Random Access Memory
	- Non-Volatile
		- ROM - Read Only Memory
		- EPROM - Erasable Programmable Read Only Memory
		- EEPROM - Electrically Erasable Programmable Read Only Memory
			- Flash EEPROM

## Bus
- Connecting memory and central unit using busses in order to gain on functionality
- it represents a group of 8, 16, or more wires
- there are two types of buses
	- Address bus
		- consists of as many lines as the amount of memory we wish to address
		- serves to transmit address from CPU memory
	- Data bus
		- as wide as data, in our case 8 bits or the connection line
		- connect all blocks inside the microcontroller


## Input - Output Unit
- Are also called ports
- There are also several types of ports
	- Input
	- Output
	- Bi-directional

![[Pasted image 20250206110715.png]]

## Timer unit
- is basically a counter which is driven from either an external clock pulse or the microcontroller's internal oscillator
- timer unity generates signals in regular time intervals

## Watchdog
- is basically a timer that is refreshed by the user program. 
- whenever the program fails to refresh the watchdog, a reset occurs. 

## Serial Communication
- Serial communication enables a microcontroller to be connected to another microcontroller or to a PC using a serial cable

## Analog to Digital Converter
- An analog-to-digital converter is used to convert an analog signal, such as voltage, to digital form so a microcontroller can read and process it. 

## Analog Comparator
- Are used where two analog voltages need to be compared

