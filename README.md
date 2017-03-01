# pybluez-test
Test bluez and pybluez with RPi 3  

1.ติดตั้ง bluez, pybluez  
----------------------------------  
$ sudo apt-get update  
$ sudo apt-get upgrade  
$  
$ sudo apt-get install python-pip python-dev ipython  
$  
$ sudo apt-get install bluetooth libbluetooth-dev bluez  
$ sudo pip install pybluez  
  
ที่มา:   
https://community.home-assistant.io/t/raspberry-pi-3-bluetooth/951  
  
  
2.Android Appinventor 2  
----------------------------------  
Part1: Basic Bluetooth communications using App Inventor  
--BTServer.aia   
 http://appinventor.pevest.com/source/tutorials/BTServer1.aia  
--BTClient.aia  
 http://appinventor.pevest.com/source/tutorials/BTClient1.aia  
  
ที่มา:    
http://appinventor.pevest.com/?p=520   

3.pybluez programming  
----------------------------------  
Chapter 3. Bluetooth programming with Python - PyBluez  
http://people.csail.mit.edu/albert/bluez-intro/c212.html  
  
4.bluez-tools  
----------------------------------  
tutorial part1,2
https://adityakadambi.wordpress.com/2009/09/18/bluez-tools-and-programming-part-i/   
https://adityakadambi.wordpress.com/2009/10/02/bluez-tools-and-programming-part-ii/  


5.Misc Test  
-----  
aquaPi - python bluetooth rfcomm server for aquarium control  
blog: http://blog.davidvassallo.me/2014/05/11/android-linux-raspberry-pi-bluetooth-communication/  
source: https://gist.github.com/dvas0004/8209b67ff556cb18651d/  


<br><br>  
A1. Misc Installation Guide  
----
Everything You Need to Set Up Bluetooth on the Raspberry Pi 3  
http://lifehacker.com/everything-you-need-to-set-up-bluetooth-on-the-raspberr-1768482065  


<br><br>  
A2. Reference
------------------------------------  
==github/publuez  
https://github.com/karulis/pybluez  
https://github.com/karulis/pybluez/tree/master/examples/simple  
  
==List of Bluetooth Protocol Wiki  
https://en.wikipedia.org/wiki/List_of_Bluetooth_protocols#Radio_frequency_communication_.28RFCOMM.29  
  
==Radio frequency communication (RFCOMM)  
The Bluetooth protocol RFCOMM is a simple set of transport protocols, made on top of the L2CAP protocol, providing emulated RS-232 serial ports (up to sixty simultaneous connections to a Bluetooth device at a time). The protocol is based on the ETSI standard TS 07.10.  
  
RFCOMM is sometimes called serial port emulation. The Bluetooth serial port profile is based on this protocol.  
  
RFCOMM provides a simple reliable data stream to the user, similar to TCP. It is used directly by many telephony related profiles as a carrier for AT commands, as well as being a transport layer for OBEX over Bluetooth.  
  
Many Bluetooth applications use RFCOMM because of its widespread support and publicly available API on most operating systems. Additionally, applications that used a serial port to communicate can be quickly ported to use RFCOMM
  
In the protocol stack, RFCOMM is bound to L2CAP.  



