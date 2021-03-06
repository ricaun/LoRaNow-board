# LoRaNow v0

LoRaNow Boards v0 is a PCB to help wiring between Arduino Mini and RFM95 LoRa module to work with 2 AA batteries.

<img src="img/LoRaNow_v0.png" alt="LoRaNow_v0" width="640px">

## Detailed Description

This board has:
* Footprint for Arduino Pro Mini
* Footprint for RFM95
* Footprint for P-Channel Mosfet to turn on/off the RFM95
* Classic I2C connector (VCC, GND, SCL, SDA)
* Jumper to DIO1/DIO2/RST for RFM95
* Jumper to VCC the P-Channel Mosfet

Look at the schematics for more informations.

Pins board connections.
```
  Arduino       RFM9x Module
  13 <--------> CLK
  12 <--------> MISO
  11 <--------> MOSI
  10 <--------> CS
  9  <--DRST--> RST
  8  <--------> P-MOSFET
  7  <--DIO2--> DIO2
  6  <--DIO1--> DIO1
  2  <--------> DIO0
```

## Schematic

<img src="img/LoRaNow_v0s.png" alt="LoRaNow_v0s">

## Boards

<img src="img/LoRaNow_v0t.png" alt="LoRaNow_v0t" width="320px"><img src="img/LoRaNow_v0b.png" alt="LoRaNow_v0b" width="320px">

## Bill Of Material

* Arduino Pro Mini (8MHz)
* RFM95 (check Frequency)
* Capacitor 0.1u (603) (Optional)
* P-Channel Mosfet (SOT23) (Optional) 
* Resistor 10k (603) (Optional)
* Battery holder (2xAA)
* Antenna

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


If you want to do commercial stuff with this project, please contact [ricaun][1] so we can organize an simple agreement.

## Blog

See news and other projects on my [blog][2] 

[1]: http://www.ricaun.com.br/#contact
[2]: http://www.loranow.com