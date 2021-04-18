# install SSH server 

apt/yum install openssh-server 

### Forwarding ssh connection 

to forward we can use similar command: ssh -L 8080:10.1.1.4:80 user@12.34.56.77

## You can use alswo ssh as a SOCKS proxy 

### similar command: ssh -D 1080 user@ip / then you need to configure on network connection manual proxy 
configuration then type on SOCKS host localhost /port N:1080
