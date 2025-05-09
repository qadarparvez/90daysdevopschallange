#90daysdevopschallenge with Shubham Londhe


DAY 1 : Networking Basics


🌐 When two or more computers and computing devices Connected together with each other through communication channels, such as cables or wireless media and sharing , then it is a network. 


The Internet is the largest network in the world and can be called "the network of networks".

The OSI model

The OSI (Open System Interconnection) model is a set of rules that explains how different computer systems communicate over a network. OSI model was developed by the International Organisation for Standardisation (Iso). The OSI model consists of 7 layers and each layer has specific functions and responsibilities:
1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer



The TCP/IP model

The TCP/IP model, also known as the Internet Protocol Suite, is a simplified version of the OSI model with only 4 layers instead of 7.

1. Application Layer = (Application Layer + Presentation Layer + Session Layer) 2. Transport Layer
3. Internet Layer
4. Network Access Layer (Data Link Layer + Physical Layer)


IP
IP (Internet Protocol) is a set of rules that governs data transfer across networks, assigning unique addresses to devices for communication.

MAC Address
A MAC address (Media Access Control address) is a unique hardware identifier assigned to a device's network interface for local network communication.
 
Router
A router is a networking device that directs data between different networks, enabling communication between devices and the internet.

Switch
A switch is a networking device that connects multiple devices within a local network and directs data to the correct destination using MAC addresses.

Fire Wall
A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined rules.


DAY 2 : Networking Basics

IP:
IP (Internet Protocol) is a set of rules that governs data transfer across networks, assigning unique addresses to devices for communication.

Classes in IP:
Class A: 1.0.0.0-126.255.255.255
Class B: 128.0.0.0-191.255.255.255
Class C: 192.0.0.0-223.255.255.255
Class D: 224.0.0.0-223.255.255.255
Class E: 240.0.0.0-255.255.255.255


ARP:
ARP finds MAC address of a host from its known IP address. It is a Layer 2 protocol. ARP request is a broadcast, but ARP response is unicast.
ARP is of four types:
1. ARP
2. Proxy ARP
3. Reverse ARP
4. Gratuitous ARP

FTP(File Transfer Protocol):
File transfer protocol is an Application layer protocol. To transfer a file, 2 TCP connections are used by FTP in parallel.


DNS(Domain Name System):
DNS translates human readable domain names into IP addresses. It is an application layer protocol. It uses TCP port 53 and UDP port 53.



DAY 3 : Networking Basics

Dynamic Host Configuration Protocol (DHCP):
DHCP is a network management protocol used to automatically assign IP addresses and other network configuration settings (such as subnet mask, default gateway, and DNS servers) to devices on a network. This eliminates the need for manual IP configuration, making network management more efficient.

Secure Socket Shell(SSL):
SSL is a cryptographic protocol used to establish a secure and encrypted connection between a web server and a client (such as a browser). It ensures that data transmitted over the internet remains private and protected from hackers.

Transport Layer Security(TLS):
TLS is a cryptographic protocol that ensures secure communication over a network, preventing eavesdropping, data tampering, and forgery. It is the successor to SSL (Secure Sockets Layer) and is more secure and efficient.

Subnet:
A subnet or subnetwork is a smaller network inside a large network. Subnetting makes network routing much more efficient.

