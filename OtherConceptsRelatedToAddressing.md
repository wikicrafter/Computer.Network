# Other concepts related to addressing

## Ports:

* Port serves as an endpoint in an operating system for different types of communications

* Associated with IP address of host and the protocol type of the communication

* Identified by 16-bit numbers called port numbers 

# Three Categories of Ports 

* Well-known ports <br> Use port address range 0 to 1023 <br> By convention they are used to identify specific 
service types <br> Well-known port numbers assigned by Internet Assigned Numbers Authority (IANA) <br> Only used 
for standard defined protocols and services 

* Registered ports <br> 
Uses Port addresses 1024 through 49151 <br> Assigned by IANA <br> Can be purchased by anybody 
 

* Dynamic or private ports <br> Uses port address range of 49152-65535 <br> Assigned by the operating system as 
needed 

---

## What are network packets?

> They are formated units of data carried across a packet switched network <br>

* Packets have several benefits <br>

> Bandwidth of the communication can be shared across multiple devices <br>

> Each packets is able to find its own way across a network 


# Two Parts of a Packet

* Control information found in header 

> Provides data needed to deliver packet safely <br>

> Includes source and destination addresses, error detection codes, and sequencing information <br>

* Payload or user information found in body <br>

> Contains the actual data being transmitted 

---
# What is a remote access ?

* The ability to communicate with a computer  or a network for a remote location using a data link such as the 
internet 

* Can be accomplished by Virtual Private Network (VPN)

* Can be accomplished by by Remote Desktop Software

* Can be accomplished by terminal emulation 

## VPN 

* Allows for the establishment of a virtual point-to-point link between a client and server using the internet 

* Needs client side and server side software installed

* Gives rempote user access to a corporate network as if they were present in the building 

## Remote Desktop Software 

* Can be done with either third party software or built-in features of an OS

* Requires software or service to be running on both the client and server sides of the computer 

* Allows end users to interact with programms running on server sied 

## Terminal emulation

* Method of remotely control devices connected to a network via a command line interface 

* There are two commonly used methods:
1. Telnet
2. SSh 		

---


