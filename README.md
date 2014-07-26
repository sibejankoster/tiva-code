tiva-code
=========

Serial rate converter with UART0 (console) and UART1 using Tiva-C
Upon interrupt, both ports are read into circular buffer and a flag is set.
The contents are transmitted to other UART at any baud rate (set in code)
UART0 is the console/debug port
Could be expanded to other UARTs, making a serial in-out converter with console echo 
