# Übungsfragen

### Netzwerke
1. Schreibe die Folgende Netzmasken als CIDR auf:
	 - __255.255.240.0__ 
	 - __255.255.128.0__

2. Nenne eine Adresse aus dem Loopback Interface.

3. Wozu dient ein DHCP-Service?

4. Was ist der Unterschied zwischen einem Hub und Switch?
___
### Elektrotechnik

1. Was ist das Formelzeichen für die Ladung in Columb?

2. Eine Glühlampe hat 30W und 230V. Wie hoch ist der Strom, der fließt?

3. Nenne die Kirhoffschen Gesetze.

4. Wie Groß ist __Uges__ der zwei in Reihe geschalteten Widerstände 

		R1 = 400 Ω
		R2 = 600 Ω
		
	- a.) 1000 Ω
	- b.) 240 Ω
	- c.) 500 Ω
___

### Microcontroller

1. Gegeben ist folgender Code-Schnipsel:
	```
	.....
	int i = 0;
	void foo( uint8_t bar)
	{
		TCCR0 = 0b11111000 | bar;
		OCR0  = 250;
		TMISK |= (1<< 0CIE0) 
		sei();
	}
	
	ISR(TIMER0_COMP_vect)
	{
		TCNT0 = 0;
		i++;
	}
	
	void main()
	{
		while(i < 20)
		{
		}
		return 0;	
	}
	
	```
	1. Ist das Programm eine Enldosschleife?
	2. Was wird in der Funktion foo gemacht?
	
2. Ist eine Logische "1" im CAN-Bus Regressiv oder Dominant?

3. Wie groß ist das Identifier-Segment im CAN-Bus?

	- a.) 8  Bit
	- b.) 15 Bit
	- c.) 11 Bit 

