# DexcomG6Reader
Attempt to read Dexcom G6 CGM values using ESP32.

## Current State
* The ESP is connecting in very rare cases (not more than 1 out of 100) successfully to the Dexcom G6 tranmitter.
* Usually the ESP stucks within the connection process until WDT resets it.
* If conncection is successfully, the G6 transmitter disconnects before caracteristic was read.
