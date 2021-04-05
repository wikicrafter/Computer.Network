IPv4 designed with a 32-bit address system | limited total address 4,294,967.296 | in real world that range is 
too small | 

larger address space is on IPv6

IPv6 has 128-bit address system

which has unbelivable range space | commonly expressed 3.4x10^38

Design advantages of IPv6 Address Space:
* Designed for efficient address allocation
* Designed to reflect topology of modern internet 
* Designed to accommodate 64-bit MAC address
* Allows flexibility in designing hierarchical addressing / routing 
* IPv6 described in RFC 3516

---
# IPv6 structure
* The 128-bit address is divided in 16-bit boundaries or sections 
* Each 16-bits represent by a 4-digit hexadecimal number
* Each adjacent block is separated by a colon

---
Subnetting in IPv6 
* ISPs normally give IPv6 addresses with minimume of a /48 prefix 
* This means first 48-bits of IP address used for Network ID 
* Remaining 80-bits are used for host IDs
* RFC 4291 recommends using at least a /64 prefix
---
6to4 Address 
* 6to4 tunneling is described in RFC 3056
* Tunneling is the process of establishing a connection through a public network 

ISATAP Address 
* Used between 2 nodes running both IPv4 and IPv6 over an IPv4 routing infrastructure

---
Teredo Address 
* Uses prefix 3ffe:831f::/32
* Used to represent host when using automatic tunneling mechanisms defined in internet draft Teredo: Tunneling 
IPv6 Over  UDP Through NAT
* Beyond the first 32-bits, Teredo addresses are used to encode the IPv4 address of a Teredo server 

--- 

# IPv6 Global Unicast Addresses
* Equivalent to public IPv4 addresses 
* Are globally routed 
* Are reachable on the IPv6 Internet 
* Global Unicast Address structures defined in RFC 3587

IPv6 Link-Local address
* They are used when communicating with neighboring nodes on a single-link network with no router 
* Link-local address equivalent to APIPA address
* Link-Local address always begins with fe80 

IPv6 Site-Local addresses
* Are equivalent to IPv4 private addresses
* it always start with fec0::/10

---
Dual IP Stacks
* Is a network that has both IPv6 and IPv4 enabled on the same node 
