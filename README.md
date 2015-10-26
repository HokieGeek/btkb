# btkb

I have a fantastic Pok3r mech that, annoyingly, uses a cable to connect to my computer. I am building a module that includes a decent battery and bluetooth modem to replace the cable.

# Schematics
![Schematics](https://raw.githubusercontent.com/HokieGeek/btkb/btkb.png)

# Board
![Board](https://raw.githubusercontent.com/HokieGeek/btkb/btkb.brd.png)

# Parts list
## ICs
- [RN-42 HID](http://www.sparkfun.com/datasheets/Wireless/Bluetooth/rn-42-ds.pdfdf) - Bluetooth modem with HID firmware
- [BSS138](https://www.fairchildsemi.com/datasheets/BS/BSS138.pdf) - MOSFET N-Channel Logic
- [MCP73831T](https://www.sparkfun.com/datasheets/Prototyping/Batteries/MCP73831T.pdf) - Li-Ion battery 4.5V voltage regulator
- [LM25775](http://www.ti.com/lit/ds/symlink/uc2577-adj.pdf) - Adjustable step-up voltage regulatorr

## Discrete components
* 1x Red LED (data in to BT)
* 1x Green LED (data out of BT)
* Some sort of LED for battery status (TODO)
* 2x MOSFET N-Channel
* 7x 10 kOhm resistors
* 4x 4.7 kOhm resistors
* 1x 2 kOhm resistor
* 1x 1 kOhm resistor
* 3x 330 Ohm resistors
* 1x 100 Ohm resistor
* 2x 10 uF capacitors
* 2x 4.7 uF capacitors
* 2x 1 uF capacitors
* 1x 10 nF capacitor
