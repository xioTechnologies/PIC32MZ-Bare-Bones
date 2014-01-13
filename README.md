PIC32MZ-Bare-Bones
==================

This is a bare-bones development board for the new high-performance [Microchip PIC32MZ](http://www.microchip.com/pagehandler/en-us/press-release/microchips-pic32mz-32-bit-mcus.html), compatible with any of the 144-pin variants: [PIC32MZ2048EC(G/H/M)144](http://www.microchip.com/wwwproducts/Devices.aspx?product=PIC32MZ2048ECH144).  The board is a minimal design intended to be used in conjunction with an [ICD3](http://www.microchip.com/stellent/idcplg?IdcService=SS_GET_PAGE&nodeId=1406&dDocName=en537580).  All of the pins have been broken out to female headers for connections via jumper wires or a mating 'daughter-board' with a matching male headers, similar to [Arduino](http://arduino.cc/).

Features
--------

* Primary oscillator crystal
* Secondary oscillator crystal (32.768 kHz for RTC)
* [ICD3](http://www.microchip.com/stellent/idcplg?IdcService=SS_GET_PAGE&nodeId=1406&dDocName=en537580) socket or [PICKit2/3](http://www.microchip.com/stellent/idcplg?IdcService=SS_GET_PAGE&nodeId=1406&dDocName=en538340&redirects=pickit3) header
* Reset button
* [FTDI header](https://www.sparkfun.com/products/9716) with connections to UART1 (also provides power)
* JST connector for [common LiPo batteries](https://www.sparkfun.com/products/339)
* [3.3 V, 1 A dropout regulator](http://www.analog.com/en/power-management/linear-regulators/adp3338/products/product.html)


<img src="https://raw.github.com/xioTechnologies/PIC32MZ-Bare-Bones/master/PCB%20In%20Eagle.png"/>
