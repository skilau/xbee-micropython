Watchdog Sample Application
===========================

This example demonstrates the usage of the machine.WDT module. It
configures a watchdog and feeds the watchdog on progressively longer
intervals until it fires.

Requirements
------------

To run this example you need:

* One XBee3 radio module with MicroPython support.
* One carrier board for the radio module (XBIB-U-DEV or XBIB-C board).

Setup
-----

Make sure the hardware is set up correctly:

1. Plug the XBee3 radio module into the XBee adapter and connect it to your
   computer's USB port.

Run
---

The example is already configured, so all you need to do is to compile
and launch the application. It is recommended that you not set the
example to auto-start as it may be difficult to break in and resume
control.

Commented lines have been put in place for the possible response
strategies so that you can select one and explore the behavior of the
watchdog with each in place.

Supported platforms
-------------------

* Digi XBee3 Cellular LTE-M/NB-IoT - minimum firmware version: 11415
* Digi XBee3 Cellular LTE Cat 1 - minimum firmware version: x15
* Digi XBee 3 Global LTE-M/NB-IoT - minimum firmware version: 11618
* Digi XBee 3 Global LTE Cat 1 - minimum firmware version: 11519
* Digi XBee 3 North America LTE Cat 1 - minimum firmware version: 41519
* Digi XBee3 Zigbee 3 - minimum firmware version: 100A
* Digi XBee3 802.15.4 - minimum firmware version: 200A
* Digi XBee3 DigiMesh 2.4 - minimum firmware version: 300A

License
-------

Copyright (c) 2020, Digi International, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
