# VasoMoto
## Monitor and control cannulated vessel pressure in one easy-to-build unit

This arduino-based code is used to program the VasoMoto controller.
Paired with [VasoTracker-2 software](https://github.com/VasoTracker/VasoTracker-2), intravascular pressure can be monitored and controlled without the need for costly interface units.

This system is also capable of simulating pulsatile changes in pressure at rates approaching normal murine heart rate (~400 bpm). A few notes:

* While adaptable to other Arduino versions, this code is specifically written to utilize SAMD51-based microcontrollers. The [ItsyBitsy by Adafruit Inc.](https://www.adafruit.com/product/3800) is recommended.
* A myriad of libraries are required in addition to the custom ones included here.
* a parts list and design files will be coming shortly.
