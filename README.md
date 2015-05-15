This project documents the technical details of Amazon Dash Button for those who want to tap into the potential of this simple IoT device.

The Dash Button is a device that allows customers to re-order items from Amazon by pressing a single button. The Dash Button connects home WiFi network and every time the button is pressed, an order for a certain item will be placed.

The indented usage couldn't be simpler. However, the hardware inside is a lot more powerful than its price suggests. So in the past few days I've been exploring and documenting the technical details of this device, which will be updated here as I go on.

##Specs:

#### STM32F205RG6 Microcontroller

* Cortex M3
* 120MHz
* 1M Flash Memory
* 128KB RAM

#### ADMP441 Digital Microphone

* I2S interface

#### SST25VF016B SPI Flash

* 16Mb 

#### Broadcom WICED WI-FI module

* Likely derived from BCM943362WCD4

#### RGB LED

#### AAA battery powered