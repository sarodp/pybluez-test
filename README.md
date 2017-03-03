# pybluez-test
Test bluez and pybluez with RPi 3  

1. ติดตั้ง bluez, pybluez 
---- 
```shell
$ sudo apt-get update    
$ sudo apt-get upgrade    
$  
$ sudo apt-get install python-pip python-dev ipython  
$  
$ sudo apt-get install bluetooth libbluetooth-dev bluez bluez-tools  
$ sudo pip install pybluez  
$    
```  
  
ที่มา:   
https://community.home-assistant.io/t/raspberry-pi-3-bluetooth/951  
  
<br>  
2. Adroid Appinventor 2  
----  
Part1: Basic Bluetooth communications using App Inventor  
* BTServer.aia   
 http://appinventor.pevest.com/source/tutorials/BTServer1.aia  
* BTClient.aia  
 http://appinventor.pevest.com/source/tutorials/BTClient1.aia  
  
ที่มา:    
http://appinventor.pevest.com/?p=520   

<br>
3. pybluez programming  
----  
Tutorial Bluetooth programming with Python - PyBluez  
http://people.csail.mit.edu/albert/bluez-intro/c212.html  
<br>
<br>
aquaPi - python bluetooth rfcomm server for aquarium control  
* youtube:  
https://www.youtube.com/watch?v=hvykOO73LbM  
* blog:  
http://blog.davidvassallo.me/2014/05/11/android-linux-raspberry-pi-bluetooth-communication/  
* source:  
https://gist.github.com/dvas0004/8209b67ff556cb18651d/  

<br>
4. bluez-tools  
----  
* tutorial part1  
https://adityakadambi.wordpress.com/2009/09/18/bluez-tools-and-programming-part-i/   
* tutorial part2  
https://adityakadambi.wordpress.com/2009/10/02/bluez-tools-and-programming-part-ii/  

5. bluetoothctl  
---- 
bluetoothctl - Bluetooth Manager - Linux CLI  
https://www.youtube.com/watch?v=CB1E4Ir3AV4&list=FLzkCOg-3Ig6TM7giLiI8TCw&index=1&t=12s  
  


<br><br>  
98. Misc Installation Guide   
----  
* Everything You Need to Set Up Bluetooth on the Raspberry Pi 3  
http://lifehacker.com/everything-you-need-to-set-up-bluetooth-on-the-raspberr-1768482065  
  

<br><br>  
99. Reference  
----
* github/publuez  
https://github.com/karulis/pybluez  
https://github.com/karulis/pybluez/tree/master/examples/simple  

*  Using BlueZ in the Automotive World - Gustavo Padovan, Collabora Ltd  
https://www.youtube.com/watch?v=FozB5m-8Ogg&list=FLzkCOg-3Ig6TM7giLiI8TCw&index=2  
  
* List of Bluetooth Protocol Wiki  
https://en.wikipedia.org/wiki/List_of_Bluetooth_protocols#Radio_frequency_communication_.28RFCOMM.29  

<br>
* RFCOMM  
Radio frequency communication  
```  
The Bluetooth protocol RFCOMM is a simple set of transport protocols
It is made on top of the L2CAP protocol.   
It provides emulated RS-232 serial ports  
(up to sixty simultaneous connections to a Bluetooth device at a time).  
  
The protocol is based on the ETSI standard TS 07.10.  
    
RFCOMM is sometimes called serial port emulation.  
The Bluetooth serial port profile is based on this protocol.  
  
RFCOMM provides a simple reliable data stream to the user, similar to TCP.  
It is used directly by many telephony related profiles as a carrier for AT commands,  
as well as being a transport layer for OBEX over Bluetooth.  
  
Many Bluetooth applications use RFCOMM because of  
its widespread support and publicly available API on most operating systems.  
Additionally, applications that used a serial port  
to communicate can be quickly ported to use RFCOMM
  
In the protocol stack, RFCOMM is bound to L2CAP.  
```  
