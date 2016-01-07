# wakeonlan-s60

## Open source Symbian S60 application to wake a computer over WiFi

This simple application allows you to power on your computer wirelessly using your Symbian phone. It works by sending the famous magic packet over WIFI to a computer connected to an ethernet wired network. The main feature of this application is the single click wake on lan : once the application is configured, every time you click on the icon, your computer is powered on and the application automatically exit after a few seconds.

Limitations :

    only one computer is supported in this version
    it only works on local network 

Requirements :

    a Symbian phone (it has been tested on my Nokia E60 which is a S60 3rd edition Symbian)
    a computer with an ethernet card where the Wake On Lan option has been enabled 

Installation :

    just download and execute the .sis file on your phone 

Configuration :

    MAC address of your computer
    broadcast IP address of the network 

This project has been developed really quickly thanks to the PyS60 platform that allow to code in python on Symbian S60 OS. 
