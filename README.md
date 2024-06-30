

# Network

This program simulates a network with multiple subnets, DHCP servers, mail servers, a DNS server, and other network components. It allows the configuration and operation of your own network in a virtual environment. This README file provides an overview of the network configuration and usage instructions.
## Features

The network consists of several subnets, each with different roles and configurations. Here are the details:

Subnet 1

Address: 19.111.65.0
Subnet Mask: 255.255.255.0
DHCP 1 Address Range: xxx.1 to xxx.250
Mail Server 1 Address: 19.111.65.1
Connection: Directly connected to Router 1
Subnet 2

Address: 24.121.85.0
Subnet Mask: 255.255.255.192
DHCP 2 Address Range: xxx.1 to xxx.60
Mail Server 2 Address: 24.121.85.1
Connection: Directly connected to Router 1
Subnet 3

Address: 24.121.85.64
Subnet Mask: 255.255.255.192
DHCP 3 Address Range: xxx.65 to xxx.125
Client Addresses: 24.121.85.65, 24.121.85.66
Connection: Directly connected to Router 2
Subnet 4

Address: 44.126.80.48
Subnet Mask: 255.255.255.248
DHCP 4 Address Range: xxx.49 to xxx.53
Connection: Directly connected to Router 2
Subnet 5

Address: 44.126.80.57
Subnet Mask: 255.255.255.248
DHCP 5 Address Range: xxx.57 to xxx.60
Connection: Directly connected to Router 3
Subnet 6

Purpose: For the DNS server and web server
Subnet Mask: 255.255.255.0
Connection: Directly connected to Router 3
Router Configuration
Each router has been manually configured with forwarding tables instead of using automatic routing. They have their respective IP addresses and subnet masks entered.

Mail Servers
Mail Server 1: Domain schueler.de, contains accounts for Mika and Kai, password 1234.
Mail Server 2: Domain lehrer.de, contains accounts for Jonas and Annika, password 1234.
Both mail servers allow communication between students and teachers, with pre-configured email clients on laptops with IP addresses 19.111.65.1 and 24.121.85.1.

DNS Server
The DNS server facilitates the resolution of domain names. It includes three domain names:

schueler.de
lehrer.de
www.infokurs.de (accessible via the web browser on the laptop with IP address 19.111.65.1)
Web Server
A web server hosts an HTML page accessible via the domain www.infokurs.de, which can be opened on the laptop with IP address 19.111.65.1.

Gnutella File Sharing
Gnutella is installed on the laptops with IP addresses 24.121.85.65 and 24.121.85.66, allowing file sharing between clients. Files created using a text editor can be saved in the peer2peer folder and shared between these laptops.


## Usage

Starting the Network:

Ensure all routers, DHCP servers, and other network components are properly configured and started.
Email Communication:

Use the pre-configured email clients on the specified laptops to send and receive emails between the student and teacher accounts.
Accessing the Web Server:

Open a web browser on the laptop with IP address 19.111.65.1 and navigate to www.infokurs.de.
File Sharing with Gnutella:

Configure Gnutella clients on the specified laptops, create files using the text editor, and share them using the peer2peer folder.
## Documentation

[Documentation German](./Netzwerke/Filius%20Eigenes%20Netzwerk.pdf)



