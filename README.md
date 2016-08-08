My implementation of fast digital read/write for Arduino Leonardo. 

Place file in \Arduino\hardware\arduino\avr\cores\arduino\

Add the following line in Arduino.h: #include "digitalFast.h"
	
commands: 	set - set pin to high - use in place of digitalWrite(x,HIGH) 
		clr - set pin to low - use in place of digitalWrite(x,LOW)
		dr - digitalRead state of pin - use in place of digitalRead(x)

Commands are followed by the pin number eg. set13, clr13, dr13
