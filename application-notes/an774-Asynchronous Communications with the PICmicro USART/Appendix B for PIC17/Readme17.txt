There are five code examples for the PIC17C756A. They can be applied to any PIC17 part, with minor changes. Each file has a brief functional description in the header at the top of the file. They all receive data and transmit the data back, but do so in different ways to demonstrate typical applications of the USART.

Here is a summary of the features of each code example:

P17_TIRI.ASM    Use interrupts for transmit and receive, Circular buffers, Eight bit data
P17_TPRP.ASM    Poll for transmit and receive, Simple buffers, Eight bit data
P17_TWRP.ASM    Poll to receive, Wait to transmit, No buffers, Eight bit data
P17_2STP.ASM    Poll to receive, Wait to transmit, No buffers, Eight bit data, Two stop bits
P17_PRTY.ASM    Poll to receive, Wait to transmit, No buffers, Eight bit data, Even parity bit 

