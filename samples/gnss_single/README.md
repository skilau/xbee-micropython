GNSS Module Sample Application
===========================

This example demonstrates the usage of the GNSS single acquisition API
by periodically reading location data and reporting the location.

Requirements
------------

To run this example you need:

* One XBee 3 Cellular module and GNSS antenna.
* One carrier board for the radio module (XBIB-U-DEV or XBIB-C board).

Setup
-----

Make sure the hardware is set up correctly:

1. Plug the XBee3 radio module into the XBee adapter and connect it to your
   computer's USB port.
2. Install the GNSS antenna to the appropriate u.fl connector.

Run
---

The example is already configured, so all you need to do is to compile and
launch the application.

The application displays the values of latitude and longitude every
hour. Location data is requested infrequently as the
single-acquisition API must leave the cellular network to obtain a
location.

    - Requesting GPS data... [OK]
    - Latitude:
    - Longitude:
    --------------------------------
    - Requesting GPS data... [OK]
    - Latitude:
    - Longitude:
    --------------------------------
    - Requesting GPS data... [OK]
    - Latitude:
    - Longitude:
    --------------------------------

Supported platforms
-------------------

* Digi XBee 3 Global LTE-M/NB-IoT - minimum firmware version: 11618
* Digi XBee 3 Global LTE Cat 1 - minimum firmware version: 11519
* Digi XBee 3 North America LTE Cat 1 - minimum firmware version: 41519

License
-------

Copyright (c) 2021, Digi International, Inc.

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
