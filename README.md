![alt text](http://i.imgur.com/AXVI86K.jpg)

This project documents the technical details of Amazon Dash Button for those who want to tap into the potential of this inexpensive yet powerful IoT device.

## Specs:

#### STM32F205RG6 Microcontroller

* Cortex M3
* 120MHz
* 1M Flash Memory
* 128KB RAM

#### ADMP441 Digital Microphone

* I2S interface

#### SST25VF016B SPI Flash

* 16Mb 

#### RGB LED

#### BCM943362 WIFI module

* Single-Chip IEEE 802.11 b/g/n MAC/Baseband/Radio + SDIO


## Pinout

See [This PDF](Pinouts_and_Components.pdf).

## Programming

Connect SWDIO and SWDCLK to your favourite programmer to upload your own program into the Dash Button, I used the built-in ST-Link 2 on a STM32F0 Discovery board.

I use Coocox IDE since it's free, a simple Blink project that blinks the RGB LED is provided.

![alt text](http://i.imgur.com/hVwJHi3.jpg)

## Flash Dump and Debug Output

See their respective folders