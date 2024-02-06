# MAA-SCP
Modular Automated Agriculture Sensing and Control Platform

Created as a group Senior Design Project for the NCSU biological and agricultural engineering department.

MAASCP was originally designed as a hydroponics automation solution but eventually became what it is now, a set of modular sensing and control components connected via LAN. 

Each module generally is comprised of a microcontroller, sensor/control component, and an ethernet interface. The software for each module is flashed during assembly and while parameters can be modified during operation, the software should generally be unchanged overall. A network of components relies on having a "management module" in order to process data and send commands. The managment module hosts a webserver enabling users on the network to interact with the modules or for external programs to process the data from the MAASCP system. 
