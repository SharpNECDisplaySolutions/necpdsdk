CHANGELOG

All changes to this project are documented in this file.
-----------
Version 23.8.21
================
Add new IR command codes.
Add new diagnostic error codes.
Add command_get_terminal_list() function.
Add try: for command_ip_address_read() command since not always supported.
Various small fixes and typos.
Update copyright and revision information.

Version 18.2.231
================
585be3e (origin/fan_control, fan_control) Modified fan control to use FAN_MODE_AUTO instead of FAN_MODE_ON so that if the fan is on when the CM power is turned off, the fan will also turn off.

Version 18.2.221
================
d722224 Updates for new release
a703043 Merge branch 'fan_control'
337dd4e Add CPU temperature based cooling fan control Add additional parameters Improve logging Add "command_ip_address_read" function to read the IP address of the display Add test routines for "command_lan_mac_address_read" and "command_ip_address_read" Add OPCODE definitions for new COMPUTE MODULE FAN CONTROL  and AUTO SHUTDOWN Add missing IR remote keys Add new OPCODES and values to controls.txt
3b3f891 Rename functions so they are more descriptive Add validation for datetime values
c169088 Fix the year to work with python datetime Add more helpers for the bitfields Define a class for the bitfields
21cc699 Changes for schedule, holiday, etc.
5902717 Updates for Athlon5 schedule, weekend and holidays


Version 17.9.191
=================
* 

Version 17.4.61
=================
* Changes to support Python 3

Version v17.3.231
=================
* Initial commit
