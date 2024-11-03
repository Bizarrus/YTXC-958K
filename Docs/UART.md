# Connect via UART
### Connection Infos
```
Data bits:		8
Stop bits:		1
Parity:			None
Flow Control:	Dsr/Dtr	(otherwise you can't type with Keyboard)
Baudrate:		57600
```

Sample Connection:
> sudo minicom -b 57600 -o -D /dev/ttyUSB0

Or via Windows with some Serial-Terminals like Putty or other.