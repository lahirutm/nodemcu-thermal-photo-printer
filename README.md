# nodemcu-thermal-photo-printer
Photo printer using Nodemcu and Thermal panel printer

Used hardware serial instead of Software Serial.

TTL interface of the panel printer
----------------------------------
Yellow wire of the panel printer connected to Tx pin of the nodemcu (Tx -> GPIO1).
Green wire of the panel printer connected to Rx pin of the nodemcu (Rx -> GPIO3).
Black wire of the panel printer connected to a Ground pin of the nodemcu.

Nodemcu powered up with its Vin & Ground pin together with panel printer using a 5V 2A power supply.

Copied from **Arduino Thermal Printer** July 13, 2018 by **Ian Jackson** and made small changes to fit it with nodemcu development board.
https://builtbyian.com/2018/07/13/arduino-thermal-printer/
