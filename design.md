# Resources
## Tutorials
* [Main ideea](http://www.instructables.com/id/Laser-Lumia-Light-Show/)
* [Stepper motor](https://www.youtube.com/watch?v=B86nqDRskVU)
* [Battery estimation](http://www.powerstream.com/battery-capacity-calculations.htm)


## Components
* 10mW 3V green laser [dx](http://www.dx.com/p/10mw-532nm-green-laser-module-3v-11-9mm-26886)
* 5mW 3v blue laser [dx](http://www.dx.com/p/5mw-405nm-blue-violet-royal-purple-laser-module-3v-80918)
* 5mW 3.5 - 4.5 V red laser [dx](http://www.dx.com/p/150mw-red-dot-laser-diode-module-154145)
* stepper motor + driver [dx](http://www.dx.com/p/5v-stepper-motor-uln2003-driver-board-set-158635)
* Pro Micro Atmega 32U4 5V 16MHz [dx](http://www.dx.com/p/pro-micro-atmega-32u4-5v-16mhz-development-board-module-for-arduino-deep-blue-320958)
* ESP-12 ESP8266 Serial WiFi Module [dx](http://www.dx.com/p/esp-12-esp8266-serial-wifi-wireless-module-w-pcb-antenna-adapter-board-for-arduino-raspberry-pi-379296)
* Power bank [pcgarage](http://www.pcgarage.ro/baterii-externe/hame/h13-10000-mah-silver/)

## Calculations
### Power usage
* 250mA green laser
* 250mA blue laser
* 40mA red laser
* ~250mA motor and driver
* ~100mA Pro Micro Atmega
* ~170mA ESP8266

## Notes
### Hardware
* Motor
  * Switch off signal on each line after each step is advisable
* Wifi Module
  * Remove middle resistor from shield if using 5V input [reasoning](http://club.dx.com/reviews/379296/722838)