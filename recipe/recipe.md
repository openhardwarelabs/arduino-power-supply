# Arduino Power Supply Recipe

Recipe to build the Arduino Power Supply project

## Components

* Myrra 47122 AC/DC module 5V 2.75W ([http://canada.newark.com/myrra/47122/power-supply-2-75w-5vdc/dp/90R9579](http://canada.newark.com/myrra/47122/power-supply-2-75w-5vdc/dp/90R9579))
* 2-pin screw terminal 5mm pitch ([https://www.sparkfun.com/products/8432](https://www.sparkfun.com/products/8432))
* 4-pin header ([https://www.sparkfun.com/products/116](https://www.sparkfun.com/products/116))
* 3.3V voltage regulator ([https://www.sparkfun.com/products/526](https://www.sparkfun.com/products/526))
* 10uF polarized capacitor
* 100nF capacitor
* PCB (see Fabrication step)

## Fabrication

* Send the EAGLE files at [https://github.com/openhardwarelabs/arduino-power-supply/tree/master/pcb](https://github.com/openhardwarelabs/arduino-power-supply/tree/master/pcb) 
* Send these files to a PCB manufacturer
* Wait until your receive the PCB

## Assembly

* Mount all the small components on the PCB and solder them
* Mount the Myrra AC/DC module and solder it

## Test

* Connect the 2-pin screw terminal to the main power, for example with a male power plug
* Use a voltmeter to check the output 5V & 3.3V pins