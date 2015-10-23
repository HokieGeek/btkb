# btkb

I have a fantastic Pok3r mech that, annoyingly, uses a cable to connect to my computer. I am building a module that includes a decent battery and bluetooth modem to replace the cable.

# Schematics
![Schematics](https://raw.githubusercontent.com/HokieGeek/btkb/btkb.png)

# Board
![Board](https://raw.githubusercontent.com/HokieGeek/btkb/btkb.brd.png)

# Parts list
## ICs
- [RN-42 HID](http://cdn.sparkfun.com/datasheets/Wireless/Bluetooth/BlueSMiRF-ChipAnt-v16.pdf) - Bluetooth modem with HID firmware
- [BSS138](https://www.fairchildsemi.com/datasheets/BS/BSS138.pdf) - MOSFET N-Channel Logic
- [MCP73831T](https://www.sparkfun.com/datasheets/Prototyping/Batteries/MCP73831T.pdf) - Li-Ion battery 4.5V voltage regulator
- [MAX17043G+U](http://cdn.sparkfun.com/datasheets/Prototyping/MAX17043-MAX17044.pdf) - Battery gauge (really cool)
- [LM25775]() - Some sort of regulator

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
