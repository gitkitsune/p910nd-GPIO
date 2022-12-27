# p910nd-GPIO

This is a udpate od https://github.com/unwireddevices/p910nd

The task is to change the state of the GPIO pin to which the relay disconnecting the power supply for the printer is connected. When a data stream to the printer is detected, the relay is switched on, and after a certain time the printer is switched off. Sending a new printout refreshes the printer shutdown timer from zero.

patch from Mario Izquierdo - with simple adaptation was add to p910nd 0.97 version

Work great with OpenWRT on R6220 router with USB to i2c adapter and PCF8574 expander. In my case, it works with the old SAMSUNG-ML2010
