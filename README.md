# DMJX 2016



Node MCU

Introduction to Node MCU

Introduction to Micro Python

Installing prerequisites:

1. installing homebrew
http://brew.sh/

Tools we use:

http://nodemcu.com/

Micropython is [python](https://www.python.org/) almost. Python is pretty [rad](http://xkcd.com/353/). 

2. pip 
Getting started: 

1. Download the latest stable micropython firmware for esp8266: http://micropython.org/download/
2. Install esptool  
    $ pip install esptool
3. install using esptool:  
    $ python esptool.py -p /dev/tty.SLAB_USBtoUART --baud 460800 write_flash --flash_size=8m -fm dio 0 esp8266-20160809-v1.8.3.bin



Download esplorer:
http://esp8266.ru/esplorer/

with ESplorer:
set baud 115200
	set micropython in settings
	plugin 
	connect 
	reset


Libraries can be installed from:
https://github.com/micropython/micropython-lib



