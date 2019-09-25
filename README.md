# nodemcu-thermal-photo-printer
Photo printer using Nodemcu and Thermal panel printer

Used hardware serial instead of Software Serial.

TTL interface of the panel printer
----------------------------------
Yellow wire of the panel printer connected to Tx pin of the nodemcu (Tx -> GPIO1).
Green wire of the panel printer connected to Rx pin of the nodemcu (Rx -> GPIO3).
Black wire of the panel printer connected to a Ground pin of the nodemcu.

Nodemcu powered up with its Vin & Ground pin together with panel printer using a 5V 2A power supply. (Need real 2A or higher rated power supply, otherwise nodemcu will crash (or unknown charactors printed) when low current is supplied.)

How to use
-----------
Upload the sketch & power up the project.
Now get connected to the printer's access point (It will available as "Printer"). 
Once connected to it, nice capative portal will open to select wifi network. (It uses WiFiManager - https://github.com/tzapu/WiFiManager).
Then enter coonected ip address in ther browser to access Ian Jackson's nice image printing UI for thermal printer.

Copied from **Arduino Thermal Printer** July 13, 2018 by **Ian Jackson** and made small changes to fit it with nodemcu development board.
https://builtbyian.com/2018/07/13/arduino-thermal-printer/
