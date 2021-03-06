# btkb

I have a fantastic Pok3r mech that, annoyingly, uses a cable to connect to my computer. I am building a module that includes a decent battery and bluetooth modem to replace the cable.

## Prototype
![Current](http://i.imgur.com/KuKHyuh.jpg)

# Schematics
## Power module
![Power module schematics](https://raw.githubusercontent.com/HokieGeek/btkb/master/power.png)
## Bluetooth module
![Bluetooth module schematics](https://raw.githubusercontent.com/HokieGeek/btkb/master/bt.png)

# Board
## Power module
![Power module board](https://raw.githubusercontent.com/HokieGeek/btkb/master/power.brd.png)
## Bluetooth Module
![Bluetooth module board](https://raw.githubusercontent.com/HokieGeek/btkb/master/bt.brd.png)

# Parts list
[Mouser project](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?ProjectGUID=d7660f5c-4cd6-4143-9f81-287e7d12060d)

## ICs
- [RN-42 HID](http://www.sparkfun.com/datasheets/Wireless/Bluetooth/rn-42-ds.pdf) - Bluetooth modem with HID firmware
- [BSS138](https://www.fairchildsemi.com/datasheets/BS/BSS138.pdf) - MOSFET N-Channel Logic
- [MCP73831T](https://www.sparkfun.com/datasheets/Prototyping/Batteries/MCP73831T.pdf) - Li-Ion battery 4.5V voltage regulator
- [LM25775](http://www.ti.com/lit/ds/symlink/uc2577-adj.pdf) - Adjustable step-up voltage regulator

## Other components

* LEDs
 * 1x Red (data in to BT)
 * 1x Green (data out of BT)
 * Some sort of LED for battery status (TODO)
* Resistors
 * 7x 10 kΩ
 * 1x 2 kΩ
 * 3x 330 Ω
* Capacitors
 * 2x 10 µF (polarized)
 * 2x 4.7 µF
 * 2x 1 µF
