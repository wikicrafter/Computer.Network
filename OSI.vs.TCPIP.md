## OSI vs TCP/IP
## What is OSI model?

The OSI stands for Open System Interconnection, which was developed in 1980s. It is a conceptual model used for network communication. It is not implemented entirely, but it is still referenced today. This OSI model consists of seven layers, and each layer is connected to each other. The data moves down the OSI model, and each layer adds additional information. The data moves down until it reaches the last layer of the OSI model. When the data is received at the last layer of the OSI model, then the data is transmitted over the network. Once the data is reached on the other side, then the process will get reversed.

## What is TCP/IP model?

The TCP model stands for Transmission Control Protocol, whereas IP stands for Internet Protocol. A number of protocols that make the internet possibly comes under the TCP/IP model. Nowadays, we do not hear the name of the TCP/IP model much, we generally hear the name of the IPv4 or IPv6, but it is still valid. This model consists of 4 layers. Now, we will list down the diagrammatic representation of the TCP/IP model.
## OSI
- Application
High-level API. resource sharing ... 
- Presentation 
Data formating, encoding, encryption, compression 
- Session
Authentication, manage sessions and reconnections
- Transport
Manage segmentation, acknowledgment, reliable 
- Network
Nulti node routing and addressing 
- Data link
Flow and error control on physical link
- Physical 
Transmission of physical bit stream 

As we see in OSI model we have 7 layers but in TCP/IP it's 4 with update TCP/IP model. 
## TCP/IP
- Application 
- Transport 
- Internet
- Network Access 


As shown in the above diagram, the TCP/IP model has 4 layers, while the OSI model consists of 7 layers. Diagrammatically, it looks that the 4 layers of the TCP/IP model exactly fit the 7 layers of the OSI model, but this is not reality. The application layer of the TCP/IP model maps to the first three layers, i.e., application, session, and presentation layer of the OSI model. The transport layer of the TCP maps directly to the transport layer of the OSI model. The internet layer of the TCP/IP model maps directly to the network layer of the OSI model. The last two layers of the OSI model map to the network layer of the TCP/IP model. TCP/IP is the most widely used model as compared to the OSI model for providing communication between computers over the internet.

## Similarities between the OSI and TCP/IP model

## The following are the similarities between the OSI and TCP/IP model:

Share common architecture
Both the models are the logical models and having similar architectures as both the models are constructed with the layers.

Define standards
Both the layers have defined standards, and they also provide the framework used for implementing the standards and devices.

Simplified troubleshooting process
Both models have simplified the troubleshooting process by breaking the complex function into simpler components.

Pre-defined standards
The standards and protocols which are already pre-defined; these models do not redefine them; they just reference or use them. For example, the Ethernet standards were already defined by the IEEE before the development of these models; instead of recreating them, models have used these pre-defined standards.

Both have similar functionality of 'transport' and 'network' layers
The function which is performed between the 'presentation' and the 'network' layer is similar to the function performed at the transport layer.

## Differences between the OSI and TCP/IP model
Let's see the differences between the OSI and TCP/IP model in a tabular form:

## OSI Model
It stands for Open System Interconnection.
OSI model has been developed by ISO (International Standard Organization).

It is an independent standard and generic protocol used as a communication gateway between the network and the end user.
In the OSI model, the transport layer provides a guarantee for the delivery of the packets.

This model is based on a vertical approach.
In this model, the session and presentation layers are separated, i.e., both the layers are different.

It is also known as a reference model through which various networks are built. For example, the TCP/IP model is built from the OSI model. It is also referred to as a guidance tool.

In this model, the network layer provides both connection-oriented and connectionless service.
Protocols in the OSI model are hidden and can be easily replaced when the technology changes.

It consists of 7 layers.
OSI model defines the services, protocols, and interfaces as well as provides a proper distinction between them. It is protocol independent.

The usage of this model is very low.
It provides standardization to the devices like router, motherboard, switches, and other hardware devices.

## TCP/IP Model
It stands for Transmission Control Protocol.
It was developed by ARPANET (Advanced Research Project Agency Network).

It consists of standard protocols that lead to the development of an internet. It is a communication protocol that provides the connection among the hosts.
The transport layer does not provide the surety for the delivery of packets. But still, we can say that it is a reliable model.

This model is based on a horizontal approach.
In this model, the session and presentation layer are not different layers. Both layers are included in the application layer.
It is an implemented model of an OSI model.

The network layer provides only connectionless service.
In this model, the protocol cannot be easily replaced.

It consists of 4 layers.
In the TCP/IP model, services, protocols and interfaces are not properly separated. It is protocol dependent.

This model is highly used.
It does not provide the standardization to the devices. It provides a connection between various computers.

____________________________________________________________________________________________________________

