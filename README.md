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

## Other components
* LEDs
** 1x Red (data in to BT)
** 1x Green (data out of BT)
** Some sort of LED for battery status (TODO)
* 2x MOSFET N-Channel
* Resistors
** 7x 10 kΩ
** 4x 4.7 kΩ
** 1x 2 kΩ
** 1x 1 kΩ
** 3x 330 Ω
** 1x 100 Ω
* Capacitors
** 2x 10 µF
** 2x 4.7 µF
** 2x 1 µF
** 1x 10 nF
