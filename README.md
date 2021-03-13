# NMAP Port Scanner

## This program is similar to the nmap program implemented to check the open ports of an ip or fdqn address.

For more information about this program, you can refer to the [nmap page](https://nmap.org).

This program supports five scanning methods:
* Connect Scan
* Ack Scan
* Syn Scan
* Fin Scan
* Window Scan

 ## Usage
 
 ```
 pothon3 portScanner.py -t nmap.org -p 0-100 -s CS -d 3
 ```
