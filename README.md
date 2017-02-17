# Aprilaire-Emulator
A quick and dirty crestron module that will emulate an aprilaire thermostat. Used to integrate CHV-TSTATS with other control systems.

This module is written in Simple+ and is released under the BSD License.

To use this module, simply add one to your simple program for each CHV-TSTAT (Firmware 2.0) you have in the system. Then connect the telnet-in and telnet-out to either a telnet server module or a serial input module. Be sure to set a unique Thermostat address for each module.

This has been tested with a Savant system emulating an Aprilaire 8811 protocol adapter and 8818 distribution panel. This required an RS232 connection. It can emulate a telnet thermostat, but Savant requires each telnet Thermostat to have the same address, so you would need to create a telnet server for each.

