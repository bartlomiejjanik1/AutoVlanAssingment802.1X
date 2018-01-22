#AutoVlanAssingment802.1X

Scenario:

User from PC with Windows 10 is logging in by Radius credentials.
Based on user credentials, switch interface facing PC is being changed to access vlan 149.
On windows 10 only wat we need to configure is to change Ethernet settings.
In authentication tab "Enable Authentication IEEE 802.1X" and select auth metod as PEAP.
To check windows10 ethernet settings you can use in commandline:
>netsh lan show profiles

Software Used:
freeradius: FreeRADIUS Version 2.2.8, for host x86_64-pc-linux-gnu, built on Jul 26 2017 at 15:27:21
Copyright (C) 1999-2015 The FreeRADIUS server project and contributors.

Hardware Used:
S4600#show version 
  S4600-28P-SI Device, Compiled on Dec 14 15:06:04 2017
  sysLocation China
  CPU Mac 00:03:0f:64:eb:40
  Vlan MAC 00:03:0f:64:eb:3f
  SoftWare Version 7.0.3.5(R0241.0208)
  BootRom Version 7.2.33
  HardWare Version 2.0.1

PC with Windows 10 802.1x auth enabled.

