# First test with SPI connection on a Raspberry PI 64bit bookworm
Author: Stefan Soyka

Date: 23/03/2024


## Introduction
This program example should demonstrate the usage of a SPI for Raspberry PI. In this case we use ...



the AZdelivery module DS3231 (see Stefans datasheet lib. More detailed description about this project you will find in the book "C-Programming on raspberry pi",ISBN: 978-3-89576-431-8, chapter 7 "I2C Bus Interface.

## Configuration of the raspberry pi
            Acitivate SPI interface

            > pi@raspberrypi: $ sudo raspi-config
            - Move down to **Interface Option** and press **Enter**
            - Select **I2C** and press **Enter** to enable it

            ##  check I2C interface
            > pi@raspberrypi: $ sudo i2cdetect -y 1



