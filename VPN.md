# Here i'll discuss about VPN meaning and  functions


## VPN or Virtual Private Networking is a set of technology which allows devices to connect through protected 
tunnel. VPNS are used buy many organizations to use protected tunneling. 

## VPN basics:
VPN operates two different layers, like: layer 2(data link layer) transmission of frames between devices <br> 
and layer 3(Network 
layer) this is a layer where IP's  operates. Transmission of packets <br>
* layer 2 VPN is called Bridged VPN / Layer 2 virtual devices are called TAP (tap0, tap1)
* layer 3 VPN is called Routed VPN / Layer 3 virtual devices called TUN (tun0, tun1)

## PPP: Point-to-Point Protocol (Layer 2) / Creates connection between two hosts with a virtual network adaptor 
at each end 

### PPTP - Point to Point Tunneling Protocol <br>
> one of the oldest VPN protocol / if you want to setup VPN server you probably shouldn't use it
> Considered obsolete because most of the ciphers it uses are easily broken 
> it doesn't have any specific protection or security 
> it uses TCP port 1723 to set up GRE(Generic routing encapsulation) tunnel, through which a PPP connection 
(Protocol 47) transfers encrypted packets 
### L2TP/IPsec
> Layer 2 tunneling protocol over IPSec(IP security)
> IPSec creates a secure channel through which an L2TP tunnel transfer data
### IKEv2 
> Internet key exchange, version 2
> IKEv2 manages the SA for an IPsec connection 
### OpenVPN 
> OpenVPN is a popular open-source software option and protocol / server and cliet software are available free 
for various platforms 
> Uses OpenSSL library to handle key exchanges via SSL/TLS
> Creates layer 2 or layer 3 tunneling connection 
> Uses a cutomer security protocol based on TLS 
> Works well through NAT and proxies 
## Other Protocols 
 
### SSTP 
> secure socket tunneling protocol 
> create secure channel using SSL/TLS

### WireGuard
> Software and protocol 
> It can create both layer 2 and layer 3 connections 
> Packets are encripted with publick key of the destination host 
> It's a opensource, with goal of easy auditability 
> it's still onder development 

### SoftEther 
> SOftware Ethernet 
> Offers IPsec, SSTP, and other protocols, in additional to it's own protocol 
> sending traffic through https 
> Open-source

## Algo VPN 

## VPN server :
> While we can configure VPN server almost every operating system there are also approach ways to do that: <br> 
 some manufactures sell appliancesor stand alone devices that act as a VPN host. 
> This dedicated  devices called as: VPN concentrators or security gateways <br>
### 
ultifunction devices like a Wi-Fi routers often offer a VPN service <br>
Some devices without this feature can be upgraded with new firmware(like <h1>OpenWrt</h1>) that does offer the 
capability
<br> 
