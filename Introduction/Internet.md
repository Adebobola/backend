## How the internet works? 

- A network is a group of computers or other devices which are connected to each other 
- The internet is a network of networks 
- The internet works by connecting devices and computer systems together, using a set of standardized protocols 

## Basic Concepts and Terminology 

- IP - Internet Protocol - responsible for routing packets to their correct destinations. 
- TCP - Transmission Control Protocol - ensures that packets are transmitted reliably and in the correct order.
- Packet - A small unit of data that is transmitted over the internet. 
- Router - A device that directs packets of data between different networks 
- UDP - User Data Protocol 
- IP Address - A unique identifier assigned to each device on a network, used to route data to the correct destination
- Domain Name - A human-readable name that is used to identify a website e.g google.com
- DNS - Domain Name System - responsible for translating domain name into IP addresses
- HTTP - Hypertext Transfer Protocol - used to transfer data between a client (e.g web browser) and a server (e.g website)
- HTTPS - encrypted version of HTTP that is used to provide secure communication between a client and a server 
- SSL/TLS - Secure Sockets Layer/Transport Layer Security - are used to provide secure communication over the internet. 

## Role of Protocols in Internet 

- A protocol is a set of rules and standards that define how information is exchanged between devices and systems 

## Building Applications with TCP/IP 
- Ports - Ports are used to identify the application or service running on a device. Each application or service is assigned a unique port number, allowing data to be sent to the correct destination. 
- Sockets - A socket is a combination of an IP address and a port number, representing a specific endpoint for communication. Sockets are used to establish connections between devices and transfer data between applications. 
- Connections - A connection is established between two sockets when two devices want to communicate with each other. 
- Data transfer - Data is typically transmitted in segments, with each segment containing a sequence number and other metadata to ensure reliable delivery. 

## Securing Internet Communication with SSL/TLS 
- Certificates - SSL/TLS certificates are used to establish trust between the client and server. They contain information about the identity of the server and are signed by a trusted third party to verify the authneticity
- Handshake - During the SSL/TLS handshake process, the client and server exchange information to negotiate the encryption algorithm and other parameters for the secure connection. 
- Encryption - Once the secure connection is established, data is encrypted using the agreed upon algorithm and can be transmitted securely between the client and server. 

## Internet Addresses 
- Each computer connected to the internet must have a unique address in the form nnn.nnn.nnn.nnn, where nnn must be a number from 0 to 255 known as an IP address (Internet Protocol)
- A device connected to the internet through an Internet Service Provider (ISP) is given a temporary IP address for the duration of a dial-in session
A device connected to the internet from a Local Area Network (LAN) might have a permanent IP address. 

## The Ping Program 
- Sends a ping - an ICMP (Internet Control Message Protocol) echo request to the named computer 
- The ping program will count the time expired until the reply comes back 
- e.g ping www.yahoo.com

## Protocol Stacks and Packets 
- The protocol stack translates a message from alphabetic texts into electronic signals, transmited over the internet, then translated back into alphabetic texts 
- The protocol stack used on the internet is referred to as the TCP/IP protocol 

| Protocol Layer                         | Comments                                                                 |
|---------------------------------------|--------------------------------------------------------------------------|
| Application Protocols Layer            | Protocols specific to applications such as WWW, e-mail, FTP               |
| Transmission Control Protocol Layer    | TCP directs packets to a specific application on a computer using a port number |
| Internet Protocol Layer                | IP directs packets to a specific computer using an IP address             |
| Hardware Layer                         | Converts binary packet data to network signals and back (e.g. Ethernet, modem for phone lines) |

- A packet is a small chunk of data 

## The traceroute program 
- It shows the path your packets are taking to a given internet destination 
- e.g tracert www.yahoo.com