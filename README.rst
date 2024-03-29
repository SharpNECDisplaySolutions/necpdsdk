NEC PD SDK
=======================

Python library interface for communicating via LAN or RS232 with NEC large-screen displays.  


Documentation
--------------
Documentation can be found in the doc directory and in the examples.

Install
--------------
The recommended installation method is via pip:

pip install nec_pd_sdk

OR for python3:

pip3 install nec_pd_sdk

License
--------------
The MIT License

Copyright (c) 2023 Sharp NEC Display Solutions, Ltd.

Copyright (c) 2017-20 NEC Display Solutions, Ltd.

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

What's New
-----------
Added scheduling functions
Added CPU Temperature based cooling fan control
Added "command_ip_address_read" function to read the IP address of the display
Added OPCODE definitions for new COMPUTE MODULE FAN CONTROL and AUTO SHUTDOWN
Added new IR remote keys definitions
Added new OPCODES definitions and controls.txt
