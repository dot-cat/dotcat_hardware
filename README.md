# .CAT hardware
Hardware designs for Creative Home Project and not only

## In this repo:
* sr_lights - PCB design of low-power LED driver module with serial interface (based on 8-bit shift register)
* sr_motors - PCB design of low-power motor driver module with serial interface (based on 8-bit shift register)
* sr_motors and sr_lights modules can be easily connected in series; but parrallel connection is recommended for power pins (to not overload input reverse polarity protection transistor)

## Notes:
For reverse polarity protection in cases of high load (more than 3 amps) try to replace an IRLML2244TRPbF transistor with AOD417. Example: https://learn.adafruit.com/16-channel-pwm-servo-driver/downloads
