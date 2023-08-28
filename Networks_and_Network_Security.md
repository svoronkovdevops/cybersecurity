# OS

## Content

[Terms](#terms)

[Network components, devices, and diagrams](#network-components-devices-and-diagrams)

[Cloud computing and software-defined networks](#cloud-computing-and-software-defined-networks)

[The TCP/IP model](#the-tcpip-model)

[TCP/IP model versus OSI model](#tcpip-model-versus-osi-model)

[The OSI model](#the-osi-model)

[Network protocols](#network-protocols)

[Additional network protocols](#additional-network-protocols)

[Wireless communication protocols](#wireless-communication-protocols)

[Subnetting and CIDR](#subnetting-and-cidr)

[Virtual networks and privacy](#virtual-networks-and-privacy)

[Network security tools and practices](#network-security-tools-and-practices)

[Tcpdump logs](#tcpdump-logs)

[DoS](#dos)

[Interception tactics](#interception-tactics)

[Portfolio: analyze DNS and ICMP traffic(Incident report)](#portfolio-analyze-dns-and-icmp-traffic-in-transit-using-data-from-a-network-protocol-analyzer-tool) 

[Portfolio: Analyze network attacks](#portfolio-analyze-network-attacks)

[Brute force attacks and OS hardening](#brute-force-attacks-and-os-hardening)

[Portfolio: Apply OS hardening techniques](#portfolio-apply-os-hardening-techniques)

[Network security applications](#network-security-applications)

[Portfolio: Security risk assessment report](#portfolio-security-risk-assessment-report)

[Secure the cloud](#secure-the-cloud)

[Content](#content)

[Courses list](README.md#contents)


## Terms


### A

Active packet sniffing: A type of attack where data packets are manipulated in transit
Address Resolution Protocol (ARP): Used to determine the MAC address of the next router or device to traverse

### B

Bandwidth: The maximum data transmission capacity over a network, measured by bits per second
Baseline configuration: A documented set of specifications within a system that is used as a basis for future builds, releases, and updates
Bluetooth: Used for wireless communication with nearby physical devices
Botnet: A collection of computers infected by malware that are under the control of a single threat actor, known as the “bot herder"

### C

Cloud-based firewalls: Software firewalls that are hosted by the cloud service provider
Cloud computing: The practice of using remote servers, application, and network services that are hosted on the internet instead of on local physical devices
Cloud network: A collection of servers or computers that stores resources and data in remote data centers that can be accessed via the internet
Controlled zone: A subnet that protects the internal network from the uncontrolled zone

### D

Data packet: A basic unit of information that travels from one device to another within a network
Denial of service (DoS) attack: An attack that targets a network or server and floods it with network traffic
Distributed denial of service (DDoS) attack: A type of denial of service attack that uses multiple devices or servers located in different locations to flood the target network with unwanted traffic
Domain Name System (DNS): A networking protocol that translates internet domain names into IP addresses

### E

Encapsulation: A process performed by a VPN service that protects your data by wrapping sensitive data in other data packets

### F

File Transfer Protocol (FTP): Used to transfer files from one device to another over a network
Firewall: A network security device that monitors traffic to or from your network
Forward proxy server: A server that regulates and restricts a person’s access to the internet

### H

Hardware: The physical components of a computer
Hub: A network device that broadcasts information to every device on the network
Hypertext Transfer Protocol (HTTP): An application layer protocol that provides a method of communication between clients and website servers
Hypertext Transfer Protocol Secure (HTTPS): A network protocol that provides a secure method of communication between clients and servers

### I

Identity and access management (IAM): A collection of processes and technologies that helps organizations manage digital identities in their environment 
IEEE 802.11 (Wi-Fi): A set of standards that define communication for wireless LANs
Internet Control Message Protocol (ICMP): An internet protocol used by devices to tell each other about data transmission errors across the network
Internet Control Message Protocol (ICMP) flood: A type of DoS attack performed by an attacker repeatedly sending ICMP request packets to a network server
Internet Protocol (IP): A set of standards used for routing and addressing data packets as they travel between devices on a network
Internet Protocol (IP) address: A unique string of characters that identifies the location of a device on the internet
IP spoofing: A network attack performed when an attacker changes the source IP of a data packet to impersonate an authorized system and gain access to a network

### L

Local area network (LAN): A network that spans small areas like an office building, a school, or a home

### M

Media Access Control (MAC) address: A unique alphanumeric identifier that is assigned to each physical device on a network
Modem: A device that connects your router to the internet and brings internet access to the LAN
Multi-factor authentication (MFA): A security measure that requires a user to verify their identity in two or more ways to access a system or network

### N

Network: A group of connected devices
Network log analysis: The process of examining network logs to identify events of interest
Network protocols: A set of rules used by two or more devices on a network to describe the order of delivery of data and the structure of data
Network segmentation: A security technique that divides the network into segments

### O

Operating system (OS): The interface between computer hardware and the user
Open systems interconnection (OSI) model: A standardized concept that describes the seven layers computers use to communicate and send data over the network
On-path attack: An attack where a malicious actor places themselves in the middle of an authorized connection and intercepts or alters the data in transit

### P

Packet sniffing: The practice of capturing and inspecting data packets across a network
Passive packet sniffing: A type of attack where a malicious actor connects to a network hub and looks at all traffic on the network
Patch update: A software and operating system update that addresses security vulnerabilities within a program or product
Penetration testing: A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes
Ping of death: A type of DoS attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB
Port: A software-based location that organizes the sending and receiving of data between devices on a network
Port filtering: A firewall function that blocks or allows certain port numbers to limit unwanted communication
Proxy server: A server that fulfills the requests of its clients by forwarding them to other servers

### R

Replay attack: A network attack performed when a malicious actor intercepts a data packet in transit and delays it or repeats it at another time
Reverse proxy server: A server that regulates and restricts the Internet's access to an internal server
Router: A network device that connects multiple networks together

### S

Secure File Transfer Protocol (SFTP): A secure protocol used to transfer files from one device to another over a network
Secure shell (SSH): A security protocol used to create a shell with a remote system 
Security hardening: The process of strengthening a system to reduce its vulnerabilities and attack surface 
Security information and event management (SIEM): An application that collects and analyzes log data to monitors critical activities for an organization
Security zone: A segment of a company’s network that protects the internal network from the internet
Simple Network Management Protocol (SNMP): A network protocol used for monitoring and managing devices on a network
Smurf attack: A network attack performed when an attacker sniffs an authorized user’s IP address and floods it with ICMP packets
Speed: The rate at which a device sends and receives data, measured by bits per second
Stateful: A class of firewall that keeps track of information passing through it and proactively filters out threats
Stateless: A class of firewall that operates based on predefined rules and that does not keep track of information from data packets
Subnetting: The subdivision of a network into logical groups called subnets
Switch: A device that makes connections between specific devices on a network by sending and receiving data between them
Synchronize (SYN) flood attack: A type of DoS attack that simulates a TCP/IP connection and floods a server with SYN packets

### T

TCP/IP model: A framework used to visualize how data is organized and transmitted across a network
Transmission Control Protocol (TCP): An internet communication protocol that allows two devices to form a connection and stream data
Transmission control protocol (TCP) 3-way handshake: A three-step process used to establish an authenticated connection between two devices on a network

### U

Uncontrolled zone: The portion of the network outside the organization
User Datagram Protocol (UDP): A connectionless protocol that does not establish a connection between devices before transmissions

### V

Virtual Private Network (VPN): A network security service that changes your public IP address and masks your virtual location so that you can keep your data private when you are using a public network like the internet

### W

Wide Area Network (WAN): A network that spans a large geographic area like a city, state, or country
Wi-Fi Protected Access (WPA): A wireless security protocol for devices to connect to the internet

[Content](#content)


## Network components, devices, and diagrams

In this section of the course, you will learn about network architecture.
Once you have a foundational understanding of network architecture, sometimes referred to as network design, you will learn about security vulnerabilities inherent in all networks and how malicious actors attempt to exploit them. In this reading, you will review network devices and connections and investigate a simple network diagram similar to those used every day by network security professionals. Essential tasks of a security analyst include setting up the tools, devices, and protocols used to observe and secure network traffic. 

### Devices on a network

Network devices are the devices that maintain information and services for users of a network. These devices connect over wired and wireless connections. After establishing a connection to the network, the devices send data packets. The data packets provide information about the source and the destination of the data.


### Devices and desktop computers

Most internet users are familiar with everyday devices, such as personal computers, laptops, mobile phones, and tablets. Each device and desktop computer has a unique MAC address and IP address, which identify it on the network, and a network interface that sends and receives data packets. These devices can connect to the network via a hard wire or a wireless connection.




### Firewalls

A f`irewall `is a network security device that monitors traffic to or from your network. Firewalls can also restrict specific incoming and outgoing network traffic. The organization configures the security rules. Firewalls often reside between the secured and controlled internal network and the untrusted network resources outside the organization, such as the internet.

### Servers

`Servers `provide a service for other devices on the network. The devices that connect to a server are called clients. The following graphic outlines this model, which is called the client-server model. In this model, clients send requests to the server for information and services. The server performs the requests for the clients. Common examples include DNS servers that perform domain name lookups for internet sites, file servers that store and retrieve files from a database, and corporate mail servers that organize mail for a company. 

### Hubs and switches

Hubs and switches both direct traffic on a local network. A `hub `is a device that provides a common point of connection for all devices directly connected to it. Hubs additionally repeat all information out to all ports. From a security perspective, this makes hubs vulnerable to eavesdropping. For this reason, hubs are not used as often on modern networks; most organizations use switches instead. 
A `switch `forwards packets between devices directly connected to it. It maintains a MAC address table that matches MAC addresses of devices on the network to port numbers on the switch and forwards incoming data packets according to the destination MAC address.
A switch makes connections between specific devices on a network by sending and receiving data between them. A switch is more intelligent than a hub. It only passes data to the intended destination. This makes switches more secure than hubs, and enables them to control the flow of traffic and improve network performance.


### Routers

`Routers `sit between networks and direct traffic, based on the IP address of the destination network. The IP address of the destination network is contained in the IP header. The router reads the header information and forwards the packet to the next router on the path to the destination. This continues until the packet reaches the destination network. Routers can also include a firewall feature that allows or blocks incoming traffic based on information in the transmission. This stops malicious traffic from entering the private network and damaging the local area network. 
Modems and wireless access points

### Modems

`Modems `usually interface with an internet service provider (ISP). ISPs provide internet connectivity via telephone lines or coaxial cables. Modems receive transmissions from the internet and translate them into digital signals that can be understood by the devices on the network. Usually, modems connect to a router that takes the decoded transmissions and sends them on to the local network. 
Note: Enterprise networks used by large organizations to connect their users and devices often use other broadband technologies to handle high-volume traffic, instead of using a modem. 

### Wireless access point

A `wireless access point `sends and receives digital signals over radio waves creating a wireless network. Devices with wireless adapters connect to the access point using Wi-Fi. Wi-Fi refers to a set of standards that are used by network devices to communicate wirelessly. Wireless access points and the devices connected to them use Wi-Fi protocols to send data through radio waves where they are sent to routers and switches and directed along the path to their final destination.


### Example of sending information

For example, if a computer in one network wants to send information to a tablet on another network, then the information will be transferred as follows: First, the information travels from the computer to the router. Then, the router reads the destination address, and forwards the data to the intended network's router. Finally, the receiving router directs that information to the tablet. 
If a computer from one network wants to send information to a device on a network in a different geographic location, it would be transferred as follows: The computer would send information to the router, and the router would then transfer the information through the modem to the internet. The intended recipient's modem receives the information, and transfers it to the router. Finally, the recipient's
router forwards that information to the destination device. 

### Using network diagrams as a security analyst

Network diagrams allow network administrators and security personnel to imagine the architecture and design of their organization’s private network.
Network diagrams are topographical maps that show the devices on the network and how they connect. Network diagrams use small representative graphics to portray each network device and dotted lines to show how each device connects to the other. Security analysts use network diagrams to learn about network architecture and how to design networks. 

[Content](#content)


## Cloud computing and software-defined networks

In this section of the course, you’ve been learning the basic architecture of networks. You’ve learned about how physical network devices like workstations, servers, routers, and switches connect to each other to create a network. Networks may cover small geographical areas, as is the case in a `local area network (LAN). `Or they may span a large geographic area, like a city, state, or country, as is the case in a `wide area network (WAN). `You also learned about cloud networks and how cloud computing has grown in recent years.


### Computing processes in the cloud

Traditional networks are called on-premise networks, which means that all of the devices used for network operations are kept at a physical location owned by the company, like in an office building, for example. Cloud computing, however, refers to the practice of using remote servers, applications, and network services that are hosted on the internet instead of at a physical location owned by the company.
A `cloud service provider (CSP) `is a company that offers cloud computing services. These companies own large data centers in locations around the globe that house millions of servers. Data centers provide technology services, such as storage, and compute at such a large scale that they can sell their services to other companies for a fee. Companies can pay for the storage and services they need and consume them through the CSP’s `application programming interface (API) `or web console.
CSPs provide three main categories of services:

    • Software as a service (SaaS) refers to software suites operated by the CSP that a company can use remotely without hosting the software. 
    • Infrastructure as a service (Iaas) refers to the use of virtual computer components offered by the CSP. These include virtual containers and storage that are configured remotely through the CSP’s API or web console. Cloud-compute and storage services can be used to operate existing applications and other technology workloads without significant modifications. Existing applications can be modified to take advantage of the availability, performance, and security features that are unique to cloud provider services.
    • Platform as a service (PaaS) refers to tools that application developers can use to design custom applications for their company. Custom applications are designed and accessed in the cloud and used for a company’s specific business needs.

### Hybrid cloud environments

When organizations use a CSP’s services in addition to their on-premise computers, networks, and storage, it is referred to as a hybrid cloud environment. When organizations use more than one CSP, it is called a multi-cloud environment. The vast majority of organizations use hybrid cloud environments to reduce costs and maintain control over network resources.

### Software-defined networks

CSPs offer networking tools similar to the physical devices that you have learned about in this section of the course. Next, you’ll review  software-defined networking in the cloud. Software-defined networks (SDNs) are made up of virtual network devices and services. Just like CSPs provide virtual computers, many SDNs also provide virtual switches, routers, firewalls, and more. Most modern network hardware devices also support network virtualization and software-defined networking. This means that physical switches and routers use software to perform packet routing. In the case of cloud networking, the SDN tools are hosted on servers located at the CSP’s data center.

### Benefits of cloud computing and software-defined networks 

Three of the main reasons that cloud computing is so attractive to businesses are reliability, decreased cost, and increased scalability. 

#### Reliability

Reliability in cloud computing is based on how available cloud services and resources are, how secure connections are, and how often the services are effectively running. Cloud computing allows employees and customers to access the resources they need consistently and with minimal interruption. 

#### Cost

Traditionally, companies have had to provide their own network infrastructure, at least for internet connections. This meant there could be potentially significant upfront costs for companies. However, because CSPs have such large data centers, they are able to offer virtual devices and services at a fraction of the cost required for companies to install, patch, upgrade, and manage the components and software themselves.

#### Scalability

Another challenge that companies face with traditional computing is scalability. When organizations experience an increase in their business needs, they might be forced to buy more equipment and software to keep up. But what if business decreases shortly after? They might no longer have the business to justify the cost incurred by the upgraded components. CSPs reduce this risk by making it easy to consume services in an elastic utility model as needed. This means that companies only pay for what they need when they need it. 
Changes can be made quickly through the CSPs, APIs, or web console—much more quickly than if network technicians had to purchase their own hardware and set it up. For example, if a company needs to protect against a threat to their network, web application firewalls (WAFs), intrusion detection/protection systems (IDS/IPS), or L3/L4 firewalls can be configured quickly whenever necessary, leading to better network performance and security.

[Content](#content)


## The TCP/IP model

The TCP/IP model is a framework used to visualize how data is organized and transmitted across a network. This model helps network engineers and network security analysts conceptualize processes on the network and communicate where disruptions or security threats occur. 
The TCP/IP model has four layers: network access layer, internet layer, transport layer, and application layer. When troubleshooting issues on the network, security professionals can analyze and deduce which layer or layers an attack occurred based on what processes were involved in an incident. 

### Network access layer

The network access layer, sometimes called the data link layer, organizes sending and receiving data frames within a single network. This layer corresponds to the physical hardware involved in network transmission. Hubs, modems, cables, and wiring are all considered part of this layer. The address resolution protocol (ARP) is part of the network access layer. ARP assists IP with directing data packets on the same physical network by mapping IP addresses to MAC addresses on the same physical network.
Internet layer
The internet layer, sometimes referred to as the network layer, is responsible for ensuring the delivery to the destination host, which potentially resides on a different network. The internet layer determines which protocol is responsible for delivering the data packets. Here are some of the common protocols that operate at the internet layer:
    • Internet Protocol (IP). IP sends the data packets to the correct destination and relies on the Transmission Control Protocol/User Datagram Protocol (TCP/UDP) to deliver them to the corresponding service. IP packets allow communication between two networks. They are routed from the sending network to the receiving network. The TCP/UDP retransmits any data that is lost or corrupt.
    • Internet Control Message Protocol (ICMP). The ICMP shares error information and status updates of data packets. This is useful for detecting and troubleshooting network errors. The ICMP reports information about packets that were dropped or that disappeared in transit, issues with network connectivity, and packets redirected to other routers.

### Transport layer

The transport layer is responsible for reliably delivering data between two systems or networks. TCP and UDP are the two transport protocols that occur at this layer. 
Transmission Control Protocol 
The TCP ensures that data is reliably transmitted to the destination service. TCP contains the port number of the intended destination service, which resides in the TCP header of an TCP/IP packet.
User Datagram Protocol 
The UDP is used by applications that are not concerned with the reliability of the transmission. Data sent over UDP is not tracked as extensively as data sent using TCP. Because UDP does not establish network connections, it is used mostly for performance sensitive applications that operate in real time, such as video streaming.

### Application layer

The application layer in the TCP/IP model is similar to the application, presentation, and session layers of the OSI model. The application layer is responsible for making network requests or responding to requests. This layer defines which internet services and applications any user can access. Some common protocols used on this layer are: 
    • Hypertext transfer protocol (HTTP)
    • Simple mail transfer protocol (SMTP)
    • Secure shell (SSH)
    • File transfer protocol (FTP)
    • Domain name system (DNS)
Application layer protocols rely on underlying layers to transfer the data across the network.


[Content](#content)

## TCP/IP model versus OSI model

The OSI visually organizes network protocols into different layers. Network professionals often use this model to communicate with each other about potential sources of problems or security threats when they occur. 
The TCP/IP model combines multiple layers of the OSI model. There are many similarities between the two models. Both models define standards for networking and divide the network communication process into different layers. The TCP/IP model is a simplified version of the OSI model.

[Content](#content)

## The OSI model

So far in this section of the course, you learned about the components of a network, network devices, and how network communication occurs across a network.
All communication on a network is organized using network protocols. Previously, you learned about the Transmission Control Protocol (TCP), which establishes connections between two devices, and the Internet Protocol (IP), which is used for routing and addressing data packets as they travel between devices on a network. This reading will continue to explore the seven layers of the Open Systems Interconnection (OSI) model and the processes that occur at each layer. We will work backwards from layer seven to layer one, going from the processes that involve the everyday network user to those that involve the most basic networking components, like network cables and switches. This reading will also review the main differences between the TCP/IP and OSI models.

### The TCP/IP model vs. the OSI model

The TCP/IP model is a framework used to visualize how data is organized and transmitted across a network. This model helps network engineers and network security analysts design the data network and conceptualize processes on the network and communicate where disruptions or security threats occur.
The TCP/IP model has four layers: network access layer, internet layer, transport layer, and application layer. When analyzing network events, security professionals can determine what layer or layers an attack occurred in based on what processes were involved in the incident. 
The OSI model is a standardized concept that describes the seven layers computers use to communicate and send data over the network. Network and security professionals often use this model to communicate with each other about potential sources of problems or security threats when they occur.
Some organizations rely heavily on the TCP/IP model, while others prefer to use the OSI model. As a security analyst, it’s important to be familiar with both models. Both the TCP/IP and OSI models are useful for understanding how networks work. 

`Layer 7: Application layer`

The application layer includes processes that directly involve the everyday user. This layer includes all of the networking protocols that software applications use to connect a user to the internet. This characteristic is the identifying feature of the application layer—user connection to the network via applications and requests.
An example of a type of communication that happens at the application layer is using a web browser. The internet browser uses HTTP or HTTPS to send and receive information from the website server. The email application uses simple mail transfer protocol (SMTP) to send and receive email information. Also, web browsers use the domain name system (DNS) protocol to translate website domain names into IP addresses which identify the web server that hosts the information for the website. 

`Layer 6: Presentation layer`

Functions at the presentation layer involve data translation and encryption for the network. This layer adds to and replaces data with formats that can be understood by applications (layer 7) on both sending and receiving systems. Formats at the user end may be different from those of the receiving system. Processes at the presentation layer require the use of a standardized format.
Some formatting functions that occur at layer 6 include encryption, compression, and confirmation that the character code set can be interpreted on the receiving system. One example of encryption that takes place at this layer is SSL, which encrypts data between web servers and browsers as part of websites with HTTPS.

`Layer 5: Session layer`

A session describes when a connection is established between two devices. An open session allows the devices to communicate with each other. Session layer protocols occur to keep the session open while data is being transferred and terminate the session once the transmission is complete. 
The session layer is also responsible for activities such as authentication, reconnection, and setting checkpoints during a data transfer. If a session is interrupted, checkpoints ensure that the transmission picks up at the last session checkpoint when the connection resumes. Sessions include a request and response between applications. Functions in the session layer respond to requests for service from processes in the presentation layer (layer 6) and send requests for services to the transport layer (layer 4).

`Layer 4: Transport layer`

The transport layer is responsible for delivering data between devices. This layer also handles the speed of data transfer, flow of the transfer, and breaking data down into smaller segments to make them easier to transport. Segmentation is the process of dividing up a large data transmission into smaller pieces that can be processed by the receiving system. These segments need to be reassembled at their destination so they can be processed at the session layer (layer 5). The speed and rate of the transmission also has to match the connection speed of the destination system. TCP and UDP are transport layer protocols. 

`Layer 3: Network layer`

The network layer oversees receiving the frames from the data link layer (layer 2) and delivers them to the intended destination. The intended destination can be found based on the address that resides in the frame of the data packets. Data packets allow communication between two networks. These packets include IP addresses that tell routers where to send them. They are routed from the sending network to the receiving network. 

`Layer 2: Data link layer`

The data link layer organizes sending and receiving data packets within a single network. The data link layer is home to switches on the local network and network interface cards on local devices.
Protocols like network control protocol (NCP), high-level data link control (HDLC), and synchronous data link control protocol (SDLC) are used at the data link layer.

`Layer 1: Physical layer`

As the name suggests, the physical layer corresponds to the physical hardware involved in network transmission. Hubs, modems, and the cables and wiring that connect them are all considered part of the physical layer. To travel across an ethernet or coaxial cable, a data packet needs to be translated into a stream of 0s and 1s. The stream of 0s and 1s are sent across the physical wiring and cables, received, and then passed on to higher levels of the OSI model.


### Components of network layer communication

In the reading about the OSI model, you learned about the seven layers of the OSI model that are used to conceptualize the way data is transmitted across the internet. In this reading, you will learn more about operations that take place at layer 3 of the OSI model: the network layer.

### Operations at the network layer

Functions at the network layer organize the addressing and delivery of data packets across the network and internet from the host device to the destination device. This includes directing the packets from one router to another router across the internet, based on the internet protocol (IP) address of the destination network. The destination IP address is contained within the header of each data packet. This address will be stored for future routing purposes in  routing tables along the packet’s path to its destination.
All data packets include an IP address; this is referred to as an IP packet or datagram. A router uses the IP address to route packets from network to network based on information contained in the IP header of a data packet. Header information communicates more than just the address of the destination. It also includes information such as the source IP address, the size of the packet, and which protocol will be used for the data portion of the packet.

### Format of an IPv4 packet

Next, you can review the format of an IP version 4 (IPv4) packet and review a detailed graphic of the packet header. An IPv4 packet is made up of two sections, the header and the data:
    • The size of the IP header ranges from 20 to 60 bytes. The header includes the IP routing information that devices use to direct the packet. The format of an IP packet header is determined by the IPv4 protocol.
    • The length of the data section of an IPv4 packet can vary greatly in size. However, the maximum possible size of an IP packet is 65,536 bytes. It contains the message being transferred to the transmission, like website information or email text. 


    There are 13 fields within the header of an IPv4 packet:
    • `Version: `The first 4-bit header tells receiving devices what protocol the packet is using. The packet used in the illustration above is an IPv4 packet.
    • `IP Header Length (HLEN): `HLEN is the packet’s header length. This value indicates where the packet header ends and the data segment begins. 
    • `Type of Service (ToS): `Routers prioritize packets for delivery to maintain quality of service on the network. The ToS field provides the router with this information.
    • `Total Length: `This field communicates the total length of the entire IP packet, including the header and data. The maximum size of an IPv4 packet is 65,535 bytes.
    • `Identification: `For IPv4 packets that are larger than 65, 535 bytes, the packets are divided, or fragmented, into smaller IP packets. The identification field provides a unique identifier for all the fragments of the original IP packet so that they can be reassembled once they reach their destination. 
    • `Flags: `This field provides the routing device with more information about whether the original packet has been fragmented and if there are more fragments in transit.
    • `Fragmentation Offset: `The fragment offset field tells routing devices where in the original packet the fragment belongs.
    • `Time to Live (TTL): `TTL prevents data packets from being forwarded by routers indefinitely. It contains a counter that is set by the source. The counter is decremented by one as it passes through each router along its path. When the TTL counter reaches zero, the router currently holding the packet will discard the packet and return an ICMP Time Exceeded error message to the sender. 
    • `Protocol: `The protocol field tells the receiving device which protocol will be used for the data portion of the packet.
    • `Header Checksum: `The header checksum field contains a checksum that can be used to detect corruption of the IP header in transit. Corrupted packets are discarded.
    • `Source IP Address: `The source IP address is the IPv4 address of the sending device.
    • `Destination IP Address: `The destination IP address is the IPv4 address of the destination device.
    • `Options: `The options field allows for security options to be applied to the packet if the HLEN value is greater than five. The field communicates these options to the routing devices.



### Difference between IPv4 and IPv6

In an earlier part of this course, you learned about the history of IP addressing. As the internet grew, it became clear that all of the IPv4 addresses would eventually be depleted; this is called IPv4 address exhaustion. At the time, no one had anticipated how many computing devices would need an IP address in the future. IPv6 was developed to mitigate IPv4 address exhaustion and other related concerns. 
One of the key differences between IPv4 and IPv6 is the length of the addresses. IPv4 addresses are numeric, made of 4 bytes, and allow for up to 4.3 billion possible addresses. IPv4 addresses are made up of four strings and the numbers range from 0 to 255. An example of an IPv4 address would be: 198.51.100.0. IPv6 addresses are hexadecimal, made up of 16 bytes, and allow for up to 340 undecillion addresses (340 followed by 36 zeros). An example of an IPv6 address would be: 2002:0db8:0000:0000:0000:ff21:0023:1234.
There are also some differences in the layout of an IPv6 packet header. The IPv6 header format is much simpler than IPv4. For example, the IPv4 Header includes the HLEN, Identification, and Flags fields, whereas the IPv6 does not. The IPv6 header introduces different fields not included in IPv4 headers, such as the Flow Label and Traffic Class.  

[Content](#content)
 

## Network protocols

A `network protocol `is a set of rules used by two or more devices on a network to describe the order of delivery and the structure of data. Network protocols serve as instructions that come with the information in the data packet. These instructions tell the receiving device what to do with the data. Protocols are like a common language that allows devices all across the world to communicate with and understand each other.
Even though network protocols perform an essential function in network communication, security analysts should still understand their associated security implications. Some protocols have vulnerabilities that malicious actors exploit. For example, a nefarious actor could use the Domain Name System (DNS) protocol, which resolves web addresses to IP addresses, to divert traffic from a legitimate website to a malicious website containing malware. 

### Three categories of network protocols

Network protocols can be divided into three main categories:`communication protocols, management protocols, and security protocols. `There are dozens of different network protocols, but you don’t need to memorize all of them for an entry-level security analyst role. However, it’s important for you to know the ones listed in this reading. 


### Communication protocols

Communication protocols govern the exchange of information in network transmission. They dictate how the data is transmitted between devices and the timing of the communication. They also include methods to recover data lost in transit. Here are a few of them.

    • Transmission Control Protocol (TCP) is an internet communication protocol that allows two devices to form a connection and stream data. TCP uses a three-way handshake process. First, the device sends a synchronize (SYN) request to a server. Then the server responds with a SYN/ACK packet to acknowledge receipt of the device's request. Once the server receives the final ACK packet from the device, a TCP connection is established. In the TCP/IP model, TCP occurs at the transport layer.
    • User Datagram Protocol (UDP) is a connectionless protocol that does not establish a connection between devices before a transmission. This makes it less reliable than TCP. But it also means that it works well for transmissions that need to get to their destination quickly. For example, one use of UDP is for internet gaming transmissions. In the TCP/IP model, UDP occurs at the transport layer.
    • Hypertext Transfer Protocol (HTTP) is an application layer protocol that provides a method of communication between clients and website servers. HTTP uses port 80. HTTP is considered insecure, so it is being replaced on most websites by a secure version, called HTTPS. However, there are still many websites that use the insecure HTTP protocol. In the TCP/IP model, HTTP occurs at the application layer.
    • Domain Name System (DNS) is a protocol that translates internet domain names into IP addresses. When a client computer wishes to access a website domain using their internet browser, a query is sent to a dedicated DNS server. The DNS server then looks up the IP address that corresponds to the website domain. DNS normally uses UDP on port 53. However, if the DNS reply to a request is large, it will switch to using the TCP protocol. In the TCP/IP model, DNS occurs at the application layer.

### Management Protocols

The next category of network protocols is management protocols. Management protocols are used for monitoring and managing activity on a network. They include protocols for error reporting and optimizing performance on the network.

    • Simple Network Management Protocol (SNMP) is a network protocol used for monitoring and managing devices on a network. SNMP can reset a password on a network device or change its baseline configuration. It can also send requests to network devices for a report on how much of the network’s bandwidth is being used up. In the TCP/IP model, SNMP occurs at the application layer.
    • Internet Control Message Protocol (ICMP) is an internet protocol used by devices to tell each other about data transmission errors across the network. ICMP is used by a receiving device to send a report to the sending device about the data transmission. ICMP is commonly used as a quick way to troubleshoot network connectivity and latency by issuing the “ping” command on a Linux operating system. In the TCP/IP model, ICMP occurs at the internet layer.

### Security Protocols

Security protocols are network protocols that ensure that data is sent and received securely across a network. Security protocols use encryption algorithms to protect data in transit. Below are some common security protocols.

    • Hypertext Transfer Protocol Secure (HTTPS) is a network protocol that provides a secure method of communication between clients and website servers. HTTPS is a secure version of HTTP that uses secure sockets layer/transport layer security (SSL/TLS) encryption on all transmissions so that malicious actors cannot read the information contained. HTTPS uses port 443. In the TCP/IP model, HTTPS occurs at the application layer.
    • Secure File Transfer Protocol (SFTP) is a secure protocol used to transfer files from one device to another over a network. SFTP uses secure shell (SSH), typically through TCP port 22. SSH uses Advanced Encryption Standard (AES) and other types of encryption to ensure that unintended recipients cannot intercept the transmissions. In the TCP/IP model, SFTP occurs at the application layer. SFTP is used often with cloud storage. Every time a user uploads or downloads a file from cloud storage, the file is transferred using the SFTP protocol.
Note: The encryption protocols mentioned do not conceal the source or destination IP address of network traffic. This means a malicious actor can still learn some basic information about the network traffic if they intercept it.

[Content](#content)


## Additional network protocols

In previous readings and videos, you learned how network protocols organize the sending and receiving of data across a network. You also learned that protocols can be divided into three categories: communication protocols, management protocols, and security protocols.
This reading will introduce you to a few additional concepts and protocols that will come up regularly in your work as a security analyst. Some protocols are assigned port numbers by the Internet Assigned Numbers Authority (IANA). These port numbers are included in the description of each protocol, if assigned. 


### Network Address Translation

The devices on your local home or office network each have a private IP address that they use to communicate directly with each other. In order for the devices with private IP addresses to communicate with the public internet, they need to have a public IP address. Otherwise, responses will not be routed correctly. Instead of having a dedicated public IP address for each of the devices on the local network, the router can replace a private source IP address with its public IP address and perform the reverse operation for responses. This process is known as Network Address Translation (NAT) and it generally requires a router or firewall to be specifically configured to perform NAT. NAT is a part of layer 2 (internet layer) and layer 3 (transport layer) of the TCP/IP model. 


`Private IP Addresses`
  - Assigned by network admins
  - Unique only within private network
  - No cost to use
  - Address ranges:

                    - 10.0.0.0-10.255.255.255
                    - 172.16.0.0-172.31.255.255
                    - 192.168.0.0-192.168.255.255

`Public IP Addresses`
  - Assigned by ISP and IANA
  - Unique address in global internet
  - Costs to lease a public IP address
  - Address ranges:
                  
                   - 1.0.0.0-9.255.255.255
                   - 11.0.0.0-126.255.255.255
                   - 128.0.0.0-172.15.255.255
                   - 172.32.0.0-192.167.255.255
                   - 192.169.0.0-233.255.255.255


### Dynamic Host Configuration Protocol

Dynamic Host Configuration Protocol (DHCP) is in the management family of network protocols. DHCP is an application layer protocol used on a network to configure devices. It assigns a unique IP address and provides the addresses of the appropriate DNS server and default gateway for each device. DHCP servers operate on UDP port 67 while DHCP clients operate on UDP port 68.


### Address Resolution Protocol

By now, you are familiar with IP and MAC addresses. You’ve learned that each device on a network has both an IP address that identifies it on the network and a MAC address that is unique to that network interface. A device’s IP address may change over time, but its MAC address is permanent. Address Resolution Protocol (ARP) is an internet layer protocol in the TCP/IP model used to translate the IP addresses that are found in data packets into the MAC address of the hardware device. 
Each device on the network performs ARP and keeps track of matching IP and MAC addresses in an ARP cache. ARP does not have a specific port number.

### Telnet

Telnet is an application layer protocol that allows a device to communicate with another device or server. Telnet sends all information in clear text. It uses command line prompts to control another device similar to secure shell (SSH), but Telnet is not as secure as SSH. Telnet can be used to connect to local or remote devices and uses TCP port 23. 

### Secure shell

Secure shell protocol (SSH) is used to create a secure connection with a remote system. This application layer protocol provides an alternative for secure authentication and encrypted communication. SSH operates over the TCP port 22 and is a replacement for less secure protocols, such as Telnet.

### Post office protocol

Post office protocol (POP) is an application layer (layer 4 of the TCP/IP model) protocol used to manage and retrieve email from a mail server. Many organizations have a dedicated mail server on the network that handles incoming and outgoing mail for users on the network. User devices will send requests to the remote mail server and download email messages locally. If you have ever refreshed your email application and had new emails populate in your inbox, you are experiencing POP and internet message access protocol (IMAP) in action. Unencrypted, plaintext authentication uses TCP/UDP port 110 and encrypted emails use Secure Sockets Layer/Transport Layer Security (SSL/TLS) over TCP/UDP port 995.  When using POP, mail has to finish downloading on a local device before it can be read and it does not allow a user to sync emails. 

### Internet Message Access Protocol (IMAP)

IMAP is used for incoming email. It downloads the headers of emails, but not the content. The content remains on the email server, which allows users to access their email from multiple devices. IMAP uses TCP port 143 for unencrypted email and TCP port 993 over the TLS protocol. Using IMAP allows users to partially read email before it is finished downloading and to sync emails. However, IMAP is slower than POP3.

### Simple Mail Transfer Protocol

Simple Mail Transfer Protocol (SMTP) is used to transmit and route email from the sender to the recipient’s address. SMTP works with Message Transfer Agent (MTA) software, which searches DNS servers to resolve email addresses to IP addresses, to ensure emails reach their intended destination. SMTP uses TCP/UDP port 25 for unencrypted emails and TCP/UDP port 587 using TLS for encrypted emails. The TCP port 25 is often used by high-volume spam. SMTP helps to filter out spam by regulating how many emails a source can send at a time.

### Protocols and port numbers

Remember that port numbers are used by network devices to determine what should be done with the information contained in each data packet once they reach their destination. Firewalls can filter out unwanted traffic based on port numbers. For example, an organization may configure a firewall to only allow access to TCP port 995 (POP3) by IP addresses belonging to the organization.
As a security analyst, you will need to know about many of the protocols and port numbers mentioned in this course. They may be used to determine your technical knowledge in interviews, so it’s a good idea to memorize them. You will also learn about new protocols on the job in a security position.


[Content](#content)



## Wireless communication protocols

Many people today refer to wireless internet as Wi-Fi. Wi-Fi refers to a set of standards that define communication for wireless LANs. Wi-Fi is a marketing term commissioned by the Wireless Ethernet Compatibility Alliance (WECA). WECA has since renamed their organization Wi-Fi Alliance. 
Wi-Fi standards and protocols are based on the 802.11 family of internet communication standards determined by the Institute of Electrical and Electronics Engineers (IEEE). So, as a security analyst, you might also see Wi-Fi referred to as IEEE 802.11.
Wi-Fi communications are secured by wireless networking protocols. Wireless security protocols have evolved over the years, helping to identify and resolve vulnerabilities with more advanced wireless technologies.
In this reading, you will learn about the evolution of wireless security protocols from WEP to WPA, WPA2, and WPA3. You’ll also learn how the Wireless Application Protocol was used for mobile internet communications.

### Wired Equivalent Privacy

`Wired equivalent privacy (WEP) `is a wireless security protocol designed to provide users with the same level of privacy on wireless network connections as they have on wired network connections. WEP was developed in 1999 and is the oldest of the wireless security standards.
WEP is largely out of use today, but security analysts should still understand WEP in case they encounter it. For example, a network router might have used WEP as the default security protocol and the network administrator never changed it. Or, devices on a network might be too old to support newer Wi-Fi security protocols. Nevertheless, a malicious actor could potentially break the WEP encryption, so it’s now considered a high-risk security protocol.

### Wi-Fi Protected Access

`Wi-Fi Protected Access (WPA) `was developed in 2003 to improve upon WEP, address the security issues that it presented, and replace it. WPA was always intended to be a transitional measure so backwards compatibility could be established with older hardware.
The flaws with WEP were in the protocol itself and how the encryption was used. WPA addressed this weakness by using a protocol called Temporal Key Integrity Protocol (TKIP). WPA encryption algorithm uses larger secret keys than WEPs, making it more difficult to guess the key by trial and error.
WPA also includes a message integrity check that includes a message authentication tag with each transmission. If a malicious actor attempts to alter the transmission in any way or resend at another time, WPA’s message integrity check will identify the attack and reject the transmission.
Despite the security improvements of WPA, it still has vulnerabilities. Malicious actors can use a key reinstallation attack (or KRACK attack) to decrypt transmissions using WPA. Attackers can insert themselves in the WPA authentication handshake process and insert a new encryption key instead of the dynamic one assigned by WPA. If they set the new key to all zeros, it is as if the transmission is not encrypted at all.
Because of this significant vulnerability, WPA was replaced with an updated version of the protocol called WPA2. 

### WPA2 & WPA3

#### WPA2

The second version of Wi-Fi Protected Access—known as WPA2—was released in 2004. WPA2 improves upon WPA by using the Advanced Encryption Standard (AES). WPA2 also improves upon WPA’s use of TKIP. WPA2 uses the Counter Mode Cipher Block Chain Message Authentication Code Protocol (CCMP), which provides encapsulation and ensures message authentication and integrity. Because of the strength of WPA2, it is considered the security standard for all Wi-Fi transmissions today. WPA2, like its predecessor, is vulnerable to KRACK attacks. This led to the development of WPA3 in 2018. 
Personal
WPA2 personal mode is best suited for home networks for a variety of reasons. It is easy to implement, initial setup takes less time for personal than enterprise version. The global passphrase for WPA2 personal version needs to be applied to each individual computer and access point in a network. This makes it ideal for home networks, but unmanageable for organizations. 
Enterprise
WPA2 enterprise mode works best for business applications. It provides the necessary security for wireless networks in business settings. The initial setup is more complicated than WPA2 personal mode, but enterprise mode offers individualized and centralized control over the Wi-Fi access to a business network. This means that network administrators can grant or remove user access to a network at any time. Users never have access to encryption keys, this prevents potential attackers from recovering network keys on individual computers.

#### WPA3

WPA3 is a secure Wi-Fi protocol and is growing in usage as more WPA3 compatible devices are released. These are the key differences between WPA2 and WPA3:
    • WPA3 addresses the authentication handshake vulnerability to KRACK attacks, which is present in WPA2. 
    • WPA3 uses Simultaneous Authentication of Equals (SAE), a password-authenticated, cipher-key-sharing agreement. This prevents attackers from downloading data from wireless network connections to their systems to attempt to decode it.
    • WPA3 has increased encryption to make passwords more secure  by using 128-bit encryption, with WPA3-Enterprise mode offering optional 192-bit encryption.


 [Content](#content)



## Subnetting and CIDR

Earlier in this course, you learned about network segmentation, a security technique that divides networks into sections. A private network can be segmented to protect portions of the network from the internet, which is an unsecured global network. 
For example, you learned about the uncontrolled zone, the controlled zone, the demilitarized zone, and the restricted zone. Feel free to review the video about security zones for a refresher on how network segmentation can be used to add a layer of security to your organization’s network operations. Creating security zones is one example of a networking strategy called subnetting.

### Overview of subnetting

Subnetting is the subdivision of a network into logical groups called subnets. It works like a network inside a network. Subnetting divides up a network address range into smaller subnets within the network. These smaller subnets form based on the IP addresses and network mask of the devices on the network. Subnetting creates a network of devices to function as their own network. This makes the network more efficient and can also be used to create security zones. If devices on the same subnet communicate with each other, the switch changes the transmissions to stay on the same subnet, improving speed and efficiency of the communications.


### Classless Inter-Domain Routing notation for subnetting

`Classless Inter-Domain Routing (CIDR) `is a method of assigning subnet masks to IP addresses to create a subnet. Classless addressing replaces classful addressing. Classful addressing was used in the 1980s as a system of grouping IP addresses into classes (Class A to Class E). Each class included a limited number of IP addresses, which were depleted as the number of devices connecting to the internet outgrew the classful range in the 1990s. Classless CIDR addressing expanded the number of available IPv4 addresses. 
CIDR allows cybersecurity professionals to segment classful networks into smaller chunks. CIDR IP addresses are formatted like IPv4 addresses, but they include a slash (“/’”) followed by a number at the end of the address, This extra number is called the IP network prefix.  For example, a regular IPv4 address uses the 198.51.100.0 format, whereas a CIDR IP address would include the IP network prefix at the end of the address, 198.51.100.0/24. This CIDR address encompasses all IP addresses between 198.51.100.0 and 198.51.100.255. The system of CIDR addressing reduces the number of entries in routing tables and provides more available IP addresses within networks. You can try converting CIDR to IPv4 addresses and vice versa through an online conversion tool, like IPAddressGuide, for practice and to better understand this concept.
Note: You may learn more about CIDR during your career, but it won't be covered in any additional depth in this certificate program. For now, you only need a basic understanding of this concept.

### Security benefits of subnetting

Subnetting allows network professionals and analysts to create a network within their own network without requesting another network IP address from their internet service provider. This process uses network bandwidth more efficiently and improves network performance. Subnetting is one component of creating isolated subnetworks through physical isolation, routing configuration, and firewalls.


## Virtual networks and privacy

This section of the course covered a lot of information about network operations. You reviewed the fundamentals of network architecture and communication and can now use this knowledge as you learn how to secure networks. Securing a private network requires maintaining the confidentiality of your data and restricting access to authorized users. 
In this reading, you will review several network security topics previously covered in the course, including virtual private networks (VPNs), virtual local area networks (VLANs), proxy servers, firewalls, tunneling, and security zones. You'll continue to learn more about these concepts and how they relate to each other as you continue through the course. 

### Common network protocols
Network protocols are used to direct traffic to the correct device and service depending on the kind of communication being performed by the devices on the network. Protocols are the rules used by all network devices that provide a mutually agreed upon foundation for how to transfer data across a network.

There are three main categories of network protocols: communication protocols, management protocols, and security protocols.

    1. Communication protocols are used to establish connections between servers. Examples include TCP, UDP, and Simple Mail Transfer Protocol (SMTP), which provides a framework for email communication. 
    2. Management protocols are used to troubleshoot network issues. One example is the Internet Control Message Protocol (ICMP).
    3. Security protocols provide encryption for data in transit. Examples include IPSec and SSL/TLS.

Some other commonly used protocols are:

    • HyperText Transfer Protocol (HTTP). HTTP is an application layer communication protocol. This allows the browser and the web server to communicate with one another. 
    • Domain Name System (DNS). DNS is an application layer protocol that translates, or maps, host names to IP addresses.
    • Address Resolution Protocol (ARP). ARP is a network layer communication protocol that maps IP addresses to physical machines or a MAC address recognized on the local area network.

### Wi-Fi

This section of the course also introduced various wireless security protocols, including WEP, WPA, WPA2, and WPA3. WPA3 encrypts traffic with the Advanced Encryption Standard (AES) cipher as it travels from your device to the wireless access point. WPA2 and WPA3 offer two modes: personal and enterprise. Personal mode is best suited for home networks while enterprise mode is generally utilized for business networks and applications.


## Network security tools and practices

### Firewalls

Previously, you learned that firewalls are network virtual appliances (NVAs) or hardware devices that inspect and can filter network traffic before it’s permitted to enter the private network. Traditional firewalls are configured with rules that tell it what types of data packets are allowed based on the port number and IP address of the data packet. 
There are two main categories of firewalls.

A `hardware firewall `is considered the most basic way to defend against threats to a network. A hardware firewall inspects each data packet before it's allowed to enter the network. 

A `software firewall `performs the same functions as a hardware firewall, but it's not a physical device. Instead, it's a software program installed on a computer or on a server. If the software firewall is
installed on a computer, it will analyze all the traffic received by that computer. If the software firewall is installed on a server, it will protect all the devices connected to the server. A software firewall typically costs less than purchasing a separate physical device, and it doesn't take up any extra space. 

`Cloud service providers offer firewalls as a service, `or FaaS, for organizations. Cloud-based firewalls are software firewalls hosted by a cloud service provider. Organizations can configure the firewall rules on the cloud service provider's interface, and the firewall will perform security operations on all incoming traffic before it reaches the organization’s onsite network. 

    • Stateless: A class of firewall that operates based on predefined rules and does not keep track of information from data packets
    • Stateful: A class of firewall that keeps track of information passing through it and proactively filters out threats. Unlike stateless firewalls, which require rules to be configured in two directions, a stateful firewall only requires a rule in one direction. This is because it uses a "state table" to track connections, so it can match return traffic to an existing session 
Next generation firewalls (NGFWs) are the most technologically advanced firewall protection. They exceed the security offered by stateful firewalls because they include deep packet inspection (a kind of packet sniffing that examines data packets and takes actions if threats exist) and intrusion prevention features that detect security threats and notify firewall administrators. NGFWs can inspect traffic at the application layer of the TCP/IP model and are typically application aware. Unlike traditional firewalls that block traffic based on IP address and ports, NGFWs rules can be configured to block or allow traffic based on the application. Some NGFWs have additional features like Malware Sandboxing, Network Anti-Virus, and URL and DNS Filtering.  

### Proxy servers

A proxy server is another way to add security to your private network. Proxy servers utilize network address translation (NAT) to serve as a barrier between clients on the network and external threats. Forward proxies handle queries from internal clients when they access resources external to the network. Reverse proxies function opposite of forward proxies; they handle requests from external systems to services on the internal network. Some proxy servers can also be configured with rules, like a firewall.  For example, you can create filters to block websites identified as containing malware.

### Virtual Private Networks (VPN)

A `VPN `is a service that encrypts data in transit and disguises your IP address. VPNs use a process called encapsulation. Encapsulation wraps your encrypted data in an unencrypted data packet, which allows your data to be sent across the public network while remaining anonymous. Enterprises and other organizations use VPNs to help protect communications from users’ devices to corporate resources. Some of these resources include connecting to servers or virtual machines that host business applications. VPNs can also be used for personal use to increase personal privacy. They allow the user to access the internet without anyone being able to read their personal information or access their private IP address. Organizations are increasingly using a combination of VPN and SD-WAN capabilities to secure their networks. A software-defined wide area network (SD-WAN) is a virtual WAN service that allows organizations to securely connect users to applications across multiple locations and over large geographical distances.  


### Security zone 

`Security zones `are a segment of a network that protects the internal network from the internet. They are a part of a security technique called network segmentation that divides the network into segments. Each network segment has its own access permissions and security rules. Security zones control who can access different segments of a network. Security zones act as a barrier to internal networks, maintain privacy within corporate groups, and prevent issues from spreading to the whole network. One example of network segmentation is a hotel that offers free public Wi-Fi. The unsecured guest network 
is kept separate from another encrypted network used by the hotel staff. Additionally, an organization's network can be divided into subnetworks, or subnets, to maintain privacy for each department in a organization. For instance, at a university, there may be a faculty subnet and a separate students subnet. If there is contamination on the student's subnet, network administrators can isolate it and keep the rest of the network free from contamination. 
An organization's network is classified into two types of security zones. First, there's the `uncontrolled zone, `which is any network outside of the organization's control, like the internet. Then, there's the `controlled zone,` which is a subnet that protects the internal network from the uncontrolled zone. 
There are several types of `networks within the controlled zone.` On the outer layer is the `demilitarized zone, or DMZ,` which contains public-facing services that can access the internet. This includes web servers, proxy servers that host websites for the public, and DNS servers that provide IP addresses for internet users. It also includes email and file servers that handle external communications. The DMZ acts as a network perimeter to the internal network. The `internal network `contains private servers and data that the organization needs to protect. 
Inside the internal network is another zone called the restricted zone. The `restricted zone `protects highly confidential information that is only accessible to employees with certain privileges. 
Now, let's try to picture these security zones. Ideally, the DMZ is situated between two firewalls. One of them filters traffic outside the DMZ, and one of them filters traffic entering the internal network. This protects the internal network with several lines of defense. If there's a restricted zone, that too would be protected with another firewall. This way, attacks that penetrate into the DMZ network cannot spread to the internal network, and attacks that penetrate the internal network cannot access the restricted zone. As a security analyst, you may be responsible for regulating access control policies
on these firewalls. Security teams can control traffic reaching the DMZ and the internal network by restricting IPs and ports. 


[Content](#content)



## How intrusions compromise your system

In this section of the course, you learned that every network has inherent vulnerabilities and could become the target of a network attack.
Attackers could have varying motivations for attacking your organization’s network. They may have financial, personal, or political motivations, or they may be a disgruntled employee or an activist who disagrees with the company's values and wants to harm an organization’s operations. Malicious actors can target any network. Security analysts must be constantly alert to potential vulnerabilities in their organization’s network and take quick action to mitigate them.
In this reading, you’ll learn about network interception attacks and backdoor attacks, and the possible impacts these attacks could have on an organization.

### Network interception attacks

`Network interception attacks `work by intercepting network traffic and stealing valuable information or interfering with the transmission in some way.
Malicious actors can use hardware or software tools to capture and inspect data in transit. This is referred to as packet sniffing. In addition to seeing information that they are not entitled to, malicious actors can also intercept network traffic and alter it. These attacks can cause damage to an organization’s network by inserting malicious code modifications or altering the message and interrupting network operations. For example, an attacker can intercept a bank transfer and change the account receiving the funds to one that the attacker controls.
Later in this course you will learn more about malicious packet sniffing, and other types of network interception attacks: on-path attacks and replay attacks.

### Backdoor attacks

A `backdoor attack `is another type of attack you will need to be aware of as a security analyst. An organization may have a lot of security measures in place, including cameras, biometric scans and access codes to keep employees from entering and exiting without being seen. However, an employee might work around the security measures by finding a backdoor to the building that is not as heavily monitored, allowing them to sneak out for the afternoon without being seen.
In cybersecurity, backdoors are weaknesses intentionally left by programmers or system and network administrators that bypass normal access control mechanisms. Backdoors are intended to help programmers conduct troubleshooting or administrative tasks. However, backdoors can also be installed by attackers after they’ve compromised an organization to ensure they have persistent access.
Once the hacker has entered an insecure network through a backdoor, they can cause extensive damage: installing malware, performing a denial of service (DoS) attack, stealing private information or changing other security settings that leaves the system vulnerable to other attacks. A DoS attack is an attack that targets a network or server and floods it with network traffic.

### Possible impacts on an organization

As you’ve learned already, network attacks can have a significant negative impact on an organization. Let’s examine some potential consequences.
    • `Financial: `When a system is taken offline with a DoS attack, or business operations are halted or slowed down by some other tactic, they prevent a company from performing the tasks that generate revenue. Depending on the size of an organization, interrupted operations can cost millions of dollars. In addition, if a malicious actor gets access to the personal information of the company’s clients or customers, the company may face heavy litigation and settlement costs if customers seek legal recourse.
    • `Reputation: `Attacks can also have a negative impact on the reputation of an organization. If it becomes public knowledge that a company has experienced a cyber attack, the public may become concerned about the security practices of the organization. They may stop trusting the company with their personal information and choose a competitor to fulfill their needs.
    • `Public safety: `If an attack occurs on a government network, this can potentially impact the safety and welfare of the citizens of a country. In recent years, defense agencies across the globe are investing heavily in combating cyber warfare tactics. If a malicious actor gained access to a power grid, a public water system, or even a military defense communication system, the public could face physical harm due to a network intrusion attack.

[Content](#content)


## Tcpdump logs

A network protocol analyzer, sometimes called a packet sniffer or a packet analyzer, is a tool designed to capture and analyze data traffic within a network. They are commonly used as investigative tools to monitor networks and identify suspicious activity. There are a wide variety of network protocol analyzers available, but some of the most common analyzers  include:
    • SolarWinds NetFlow Traffic Analyzer
    • ManageEngine OpManager
    • Azure Network Watcher
    • Wireshark
    • tcpdump
This reading will focus exclusively on tcpdump, though you can apply what you learn here to many of the other network protocol analyzers you'll use as a cybersecurity analyst to defend against any network intrusions. In an upcoming activity, you’ll review a tcpdump data traffic log and identify a DoS attack to practice these skills. 

### tcpdump

tcpdump is a command-line network protocol analyzer. It is popular, lightweight–meaning it uses little memory and has a low CPU usage–and uses the open-source libpcap library. tcpdump is text based, meaning all commands in tcpdump are executed in the terminal. It can also be installed on other Unix-based operating systems, such as macOS®. It is preinstalled on many Linux distributions.
tcpdump provides a brief packet analysis and converts key information about network traffic into formats easily read by humans. It prints information about each packet directly into your terminal. tcpdump also displays the source IP address, destination IP addresses, and the port numbers being used in the communications. 

### Interpreting output
tcpdump prints the output of the command as the sniffed packets in the command line, and optionally to a log file, after a command is executed. The output of a packet capture contains many pieces of important information about the network traffic.

```txt
20:00:29.538395 IP 198.168.10.1.41 > 198.111.123.1.61012: Flags
[P.], seq 120:176, ack 1, win 501, options [nop,nop,TS val
4106659748 ecr 2979487360], length 144
```

Some information you receive from a packet capture includes: 
    • `Timestamp: `The output begins with the timestamp, formatted as hours, minutes, seconds, and fractions of a second. `20:00:29.538395`
    • `Source IP: `The packet’s origin is provided by its source IP address.`198.168.10.1.`
    • `Source port: `This port number is where the packet originated.`41`
    • `Destination IP: `The destination IP address is where the packet is being transmitted to.`198.111.123.1`
    • `Destination port: `This port number is where the packet is being transmitted to.`61012`
Note: By default, tcpdump will attempt to resolve host addresses to hostnames. It'll also replace port numbers with commonly associated services that use these ports.

### Common uses

tcpdump and other network protocol analyzers are commonly used to capture and view network communications and to collect statistics about the network, such as troubleshooting network performance issues. They can also be used to:

    • Establish a baseline for network traffic patterns and network utilization metrics.
    • Detect and identify malicious traffic
    • Create customized alerts to send the right notifications when network issues or security threats arise.
    • Locate unauthorized instant messaging (IM), traffic, or wireless access points.
However, attackers can also use network protocol analyzers maliciously to gain information about a specific network. For example, attackers can capture data packets that contain sensitive information, such as account usernames and passwords. As a cybersecurity analyst, It’s important to understand the purpose and uses of network protocol analyzers. 

[Content](#content)

## DoS

A `denial of service attack `is an attack that targets a network or server and floods it with network traffic. The objective of a denial of service attack, or a DoS attack, is to disrupt normal business
operations by overloading an organization's network. The goal of the attack is to send so much information to a network device that it crashes or is unable to respond to legitimate users.

A `distributed denial of service attack, or DDoS, `is a kind of DoS attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic. Use of numerous devices makes it more likely that the total amount of traffic sent will overwhelm the target server. Remember, DoS stands for denial of service. So it doesn't matter what part of the network the
attacker overloads; if they overload anything, they win.

 Let's learn about three common network level DoS attacks. 
 The first is called a `SYN flood attack. `A SYN flood attack is a type of DoS attack that simulates the TCP connection and floods the server with SYN packets. Let's break this definition down a bit more by taking a closer look at the handshake process that is used to establish a TCP connection between a device and a server. The first step in the handshake is for the device to send a SYN, or synchronize,
request to the server. Then, the server responds with a SYN/ACK packet to acknowledge the receipt of the device's request and leaves a port open for the final step of the handshake. Once the server receives the final ACK packet from the device, a TCP connection is established. Malicious actors can take advantage of the protocol by flooding a server with SYN packet requests for the first part of the handshake. But if the number of SYN requests is larger than the number of available ports on the server, then the server will be overwhelmed and become unable to function. 
Let's discuss two other common DoS attacks that use another protocol called `ICMP. `ICMP stands for `Internet Control Message Protocol. `ICMP is an internet protocol used by devices to tell each other about data transmission errors across the network. Think of ICMP like a request for a status update from a device. The device will return error messages if there is a network concern. You can think of this like the ICMP request checking in with the device to make sure that all is well. An ICMP flood attack is a type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server. This forces the serverto send an ICMP packet. This eventually uses up all the bandwidth for incoming and outgoing traffic and causes the server to crash. Both of the attacks we've discussed so far, SYN flood and ICMP flood, take advantage of communication protocols by sending an overwhelming number of requests. 
There are also attacks that can`` overwhelm the server with one big request. `One example that we'll discuss is called the `ping of death. `A ping of death attack is a type of DoS attack that is caused when a hacker pings a system by sending it an oversized ICMP packet that is` bigger than 64 kilobytes, `the maximum size for a correctly formed ICMP packet. Pinging a vulnerable network server with an oversized ICMP packet will overload the system and cause it to crash. 

### Real-life DDoS attack

Previously, you were introduced to Denial of Service (DoS) attacks. You also learned that volumetric distributed DoS (DDoS) attacks overwhelm a network by sending unwanted data packets in such large quantities that the servers become unable to service normal users. This can be detrimental to an organization. When systems fail, organizations cannot meet their customers' needs. They often lose money, and in some cases, incur other losses. An organization’s reputation may also suffer if news of a successful DDoS attack reaches consumers, who then question the security of the organization.
In this reading you’ll learn about a 2016 DDoS attack against DNS servers that caused major outages at multiple organizations that have millions of daily users. 

### A DDoS targeting a widely used DNS server

As a review, DNS servers translate website domain names into the IP address of the system that contains the information for the website. For instance, if a user were to type in a website URL, a DNS server would translate that into a numeric IP address that directs network traffic to the location of the website’s server. 
On the day of the DDoS attack we are studying, many large companies were using a DNS service provider. The service provider was hosting the DNS system for these companies. This meant that when internet users typed in the URL of the website they wanted to access, their devices would be directed to the right place. On October 21, 2016, the service provider was the victim of a DDoS attack.

### Leading up to the attack

Before the attack on the service provider, a group of university students created a botnet. A botnet is a collection of computers infected by malware that are under the control of a single threat actor, known as the “bot-herder." Each computer in the botnet can be remotely controlled to send a data packet to a target system. In a botnet attack, cyber criminals instruct all the bots on the botnet to send data packets to the target system at the same time, resulting in a DDoS attack.
The group of university students posted the code for the botnet online so that it would be accessible to thousands of internet users and authorities wouldn’t be able to trace the botnet back to the students. In doing so, they made it possible for other malicious actors to learn the code to the botnet and control it remotely. This included the cyber criminals who attacked the DNS service provider.

### The day of attack

At 7:00 a.m. on the day of the attack, the botnet sent tens of millions of DNS requests to the service provider. This overwhelmed the system and the DNS service shut down. This meant that all of the websites that used the service provider could not be reached. When users tried to access various websites that used the service provider, they were not directed to the website they typed in their browser. Outages for each web service occurred all over North America and Europe. 
The service provider’s systems were restored after only two hours of downtime. Although the cyber criminals sent subsequent waves of botnet attacks, the DNS company was prepared and able to mitigate the impact. 


[Content](#content)


## Interception tactics

In the previous course items, you learned how packet sniffing and IP spoofing are used in network attacks. Because these attacks intercept data packets as they travel across the network, they are called interception attacks.
This reading will introduce you to some specific attacks that use packet sniffing and IP spoofing. You will learn how hackers use these tactics and how security analysts can counter the threat of interception attacks.

### A closer review of packet sniffing

As you learned in a previous video, packet sniffing is the practice of capturing and inspecting data packets across a network. On a private network, data packets are directed to the matching destination device on the network. 
The device’s Network Interface Card (NIC) is a piece of hardware that connects the device to a network. The NIC reads the data transmission, and if it contains the device’s MAC address, it accepts the packet and sends it to the device to process the information based on the protocol. This occurs in all standard network operations. However, a NIC can be set to promiscuous mode, which means that it accepts all traffic on the network, even the packets that aren’t addressed to the NIC’s device. You’ll learn more about NIC’s later in the program. Malicious actors might use software like Wireshark to capture the data on a private network and store it for later use. They can then use the personal information to their own advantage. Alternatively, they might use the IP and MAC addresses of authorized users of the private network to perform IP spoofing.

### A closer review of IP spoofing
After a malicious actor has sniffed packets on the network, they can impersonate the IP and MAC addresses of authorized devices to perform an IP spoofing attack. Firewalls can prevent IP spoofing attacks by configuring it to refuse unauthorized IP packets and suspicious traffic. Next, you’ll examine a few common IP spoofing attacks that are important to be familiar with as a security analyst.
On-path attack
An on-path attack happens when a hacker intercepts the communication between two devices or servers that have a trusted relationship. The transmission between these two trusted network devices could contain valuable information like usernames and passwords that the malicious actor can collect. An on-path attack is sometimes referred to as a meddler-in-the middle attack because the hacker is hiding in the middle of communications between two trusted parties.
Or, it could be that the intercepted transmission contains a DNS system look-up. You’ll recall from an earlier video that a DNS server translates website domain names into IP addresses. If a malicious actor intercepts a transmission containing a DNS lookup, they could spoof the DNS response from the server and redirect a domain name to a different IP address, perhaps one that contains malicious code or other threats. The most important way to protect against an on-path attack is to encrypt your data in transit, e.g. using TLS. 

### Smurf attack

A smurf attack is a network attack that is performed when an attacker sniffs an authorized user’s IP address and floods it with packets. Once the spoofed packet reaches the broadcast address, it is sent to all of the devices and servers on the network. 
In a smurf attack, IP spoofing is combined with another denial of service (DoS) technique to flood the network with unwanted traffic. For example, the spoofed packet could include an Internet Control Message Protocol (ICMP) ping. As you learned earlier, ICMP is used to troubleshoot a network. But if too many ICMP messages are transmitted, the ICMP echo responses overwhelm the servers on the network and they shut down. This creates a denial of service and can bring an organization’s operations to a halt.
An important way to protect against a smurf attack is to use an advanced firewall that can monitor any unusual traffic on the network. Most next generation firewalls (NGFW) include features that detect network anomalies to ensure that oversized broadcasts are detected before they have a chance to bring down the network.

### DoS attack

As you’ve learned, once the malicious actor has sniffed the network traffic, they can impersonate an authorized user. A Denial of Service attack is a class of attacks where the attacker prevents the compromised system from performing legitimate activity or responding to legitimate traffic. Unlike IP spoofing, however, the attacker will not receive a response from the targeted host. Everything about the data packet is authorized including the IP address in the header of the packet. In IP spoofing attacks, the malicious actor uses IP packets containing fake IP addresses. The attackers keep sending IP packets containing fake IP addresses until the network server crashes.
Pro Tip: Remember the principle of defense-in-depth. There isn’t one perfect strategy for stopping each kind of attack. You can layer your defense by using multiple strategies. In this case, using industry standard encryption will strengthen your security and help you defend from DoS attacks on more than one level. 


## Portfolio: analyze DNS and ICMP traffic in transit using data from a network protocol analyzer tool


### Scenario

```log

13:24:32.192571 IP 192.51.100.15.52444 > 203.0.113.2.domain: 35084+ A? yummyrecipesforme.com. (24)
13:24:36.098564 IP 203.0.113.2 > 192.51.100.15: ICMP 203.0.113.2 
udp port 53 unreachable length 254

13:26:32.192571 IP 192.51.100.15.52444 > 203.0.113.2.domain: 35084+ A? yummyrecipesforme.com. (24)
13:27:15.934126 IP 203.0.113.2 > 192.51.100.15: ICMP 203.0.113.2 
udp port 53 unreachable length 320

13:28:32.192571 IP 192.51.100.15.52444 > 203.0.113.2.domain: 35084+ A? yummyrecipesforme.com. (24)
13:28:50.022967 IP 203.0.113.2 > 192.51.100.15: ICMP 203.0.113.2 
udp port 53 unreachable length 150
```

Review the scenario below. Then complete the step-by-step instructions.
You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 
You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 
In the DNS and ICMP log, you find the following information:
    1. In the first two lines of the log file, you see the initial outgoing request from your computer to the DNS server requesting the IP address of yummyrecipesforme.com. This request is sent in a UDP packet.
    2. Next you find timestamps that indicate when the event happened. In the log, this is the first sequence of numbers displayed. For example: 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 seconds.
    3. The source and destination IP address is next. In the error log, this information is displayed as: 192.51.100.15.52444 > 203.0.113.2.domain. The IP address to the left of the greater than (>) symbol is the source address. In this example, the source is your computer’s IP address. The IP address to the right of the greater than (>) symbol is the destination IP address. In this case, it is the IP address for the DNS server: 203.0.113.2.domain
    4. The second and third lines of the log show the response to your initial ICMP request packet. In this case, the ICMP 203.0.113.2 line is the start of the error message indicating that the ICMP packet was undeliverable to the port of the DNS server.
    5. Next are the protocol and port number, which displays which protocol was used to handle communications and which port it was delivered to. In the error log, this appears as: udp port 53 unreachable. This means that the UDP protocol was used to request a domain name resolution using the address of the DNS server over port 53. Port 53, which aligns to the .domain extension in 203.0.113.2.domain, is a well-known port for DNS service. The word “unreachable” in the message indicates the message did not go through to the DNS server. Your browser was not able to obtain the IP address for yummyrecipesforme.com, which it needs to access the website because no service was listening on the receiving DNS port as indicated by the ICMP error message “udp port 53 unreachable.”
    6. The remaining lines in the log indicate that ICMP packets were sent two more times, but the same delivery error was received both times. 
Now that you have captured data packets using a network analyzer tool, it is your job to identify which network protocol and service were impacted by this incident. Then, you will need to write a follow-up report. 



1. Provide a summary of the problem found in the DNS and ICMP traffic log
The network traffic analyzer tool inspects all IP packets traveling through the network interfaces of the machine it runs on. Network packets are recorded into a file. After analyzing the data presented to you from the DNS and ICMP traffic log, identify trends in the data. Assess which protocol is producing the error message when resolving the URL with the DNS server for the yummyrecipesforme.com website. Recall that one of the ports that is displayed repeatedly is port 53, commonly used for DNS. In your analysis: 
    • Include a brief summary of the DNS and ICMP log analysis and identify which protocol was used for the ICMP traffic.
    • Provide a few details about what was indicated in the logs.
    • Interpret the issues found in the logs.
Record your responses in part one of the cybersecurity incident report. 

2. Explain your analysis of the data and provide one solution to implement 
Now that you’ve inspected the traffic log and identified trends in the traffic, describe why the error messages appeared on the log. Use your answer in the previous step and the scenario to identify the reason behind the ICMP error messages. The error messages indicate that there is an issue with a specific port. What do the different protocols involved in the log reveal about the incident? In your response:
    • State when the problem was first reported.
    • Provide the scenario, events, and symptoms identified when the event was first reported.  \
    • Describe the information discovered while investigating the issue up to this point.
    • Explain the current status of the issue.
    • Provide the suspected root cause of the problem.
    • List the next steps needed to troubleshoot and resolve the issue.
Record your responses in part two of the cybersecurity incident report. 



The Exemplar Explained
Cybersecurity Incident Report: Network Traffic Analysis 
    A. The UDP protocol reveals that the DNS server is down or unreachable. 
Explanation
    A. Offers a brief summary of the DNS and ICMP log analysis.
Following the instructions, you should have identified "which network protocol and service were impacted by this incident." The scenario states: “[The log file] displays which protocol was used to handle communications and which port it was delivered to. In the error log, this shows as udp port 53 unreachable. This means that the UDP protocol was used to request a domain name resolution using the address for the DNS server over port 53.” 
   
 B. As evident by the results of the network scan, the ICMP echo reply returned the error message: "udp port 53 unreachable".” 
 Explanation
     B. Gives a few details on what was indicated in the logs:
The Scenario section states that you performed a network analysis using tcpdump, which recorded ICMP packets from your source computer to the IP address and port for the website (203.0.113.2.domain). It also recorded the ICMP responses from the website back to your computer. If you check the DNS and ICMP error log, the ICMP replies include an error message type, which tcpdump represents as “udp port 53 unreachable.”

C. Port 53 is commonly used for DNS protocol traffic. It is highly likely the DNS server is not responding.
Explanation
C. Interpret the issues found in the logs.
The Scenario section (or a quick internet search for “port 53”) will show that this port number is commonly used for DNS protocol communications. Since port 53 is unreachable and that port is commonly used for DNS server communications, you can conclude that the DNS server is unreachable or “not responding.” This could be caused by a DoS attack against the DNS server, for example. 

    D. The incident occurred today at 1:23 p.m..
Explanation
    D. States when the problem was first reported:
This info was obtained from the log file date and time stamps. In the log, this is the first sequence of numbers displayed: 13:24:32.192571. This displays the time 1:24 p.m., 32.192571 seconds, with the hour in 24-hour format. The Scenario indicates this event occurred today.
    
    E. Provides the scenario, events, and symptoms identified when the event was first reported:
The Scenario states that, “A handful of customers contacted your company to report that they were not able to access the company website, and saw the error “destination port unreachable” after waiting for the page to load.”
Explanation
E. Customers called the organization to notify the IT team they received the message “destination port unreachable” when they attempted to visit the website.

    F. Explains the current status of the issue:
The Scenario states that, "This incident, in the meantime, is being handled by security engineers after you and other analysts have reported the issue to your direct supervisor."
   Explanation
   F. The network security professionals within the organization are currently investigating the issue so customers can access the website again.

    G. Describes info discovered from investigating the issue up to this point in time:
Provides a concise recap of what you did to investigate the issue. The Scenario states,“You visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. In the analyzer, you send UDP packets and receive an ICMP response to return to the host. The results contain an error message: “udp port 53 unreachable.””
Explanation
 G. In our investigation into the issue, we conducted packet sniffing tests using tcpdump. In the resulting log file, we found that DNS port 53 was unreachable.

    H. Lists the next steps in troubleshooting and resolving the issue:
The next step in troubleshooting is to determine if the DNS server is not functioning properly. If the DNS server is fine, the team should check the firewall settings to see if someone changed the configuration to block network traffic on port 53. Firewalls offer the ability to block network traffic on specific ports. Port blocking can be used to stop or prevent an attack.
Explanation
H. The next step is to identify whether the DNS server is down or traffic to port 53 is blocked by the firewall.

    I. Provides the suspected root cause of the problem:
Previously, you learned about several types of Denial of Service (DoS) attacks. The goal of a DoS attack is to send a flood of information to a network device, like a DNS server, to crash it or make it unable to respond to legitimate network traffic. It is possible that an attacker disabled the DNS server with a DoS attack. Alternatively, someone from your team could have made a configuration change on the firewall that blocked port 53.
Explanation
I. DNS server might be down due to a successful Denial of Service attack or a misconfiguration.
    
Cybersecurity Incident Report: Network Traffic

Analysis

Part 1: Provide a summary of the problem found in the DNS and ICMP
traffic log

The UDP protocol reveals that the DNS server is down or unreachable. As
evident by the results of the network analysis, the ICMP echo reply returned
the error message “udp port 53 unreachable,” Port 53 is commonly used for
DNS protocol traffic. It is highly likely that the DNS server is not responding.

Part 2: Explain your analysis of the data and provide one solution to implement.
The incident occurred today at 1:23 p.m.. Customers called the organization to
notify the IT team that they received the message “destination port
unreachable” when they attempted to visit the website. The network security
professionals within the organization are currently investigating the issue so
customers can access the website again. In our investigation into the issue, we
conducted packet sniffing tests using tcpdump. In the resulting log file, we
found that DNS port 53 was unreachable. The next step is to identify whether
the DNS server is down or traffic to port 53 is blocked by the firewall. The DNS
server might be down due to a successful Denial of Service attack or a
misconfiguration.
   
[Content](#content)


## Portfolio: Analyze network attacks


### Scenario


You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 
One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.
You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 
You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.


    
### Step 2. Access supporting materials

[Wireshark TCP/HTTP log](https://docs.google.com/spreadsheets/d/1enpRzrIao3J2Lp2tOI0hmu1Cu7D7CjLGhFAiTiR9J64/template/preview?usp=sharing)

| No.  | Time            | Source        | Destination   | Protocol | Info                                    |
|------|-----------------|---------------|---------------|----------|-----------------------------------------|
| 47   | 3.144521        | 198.51.100.23 | 192.0.2.1     | TCP      | 42584->443 [SYN] Seq=0 Win-5792 Len=120 |
| 48   | 3.195755        | 192.0.2.1     | 198.51.100.23 | TCP      | 443->42584 [SYN, ACK] Seq=0 Win-5792 Len=120 |
| 49   | 3.246989        | 198.51.100.23 | 192.0.2.1     | TCP      | 42584->443 [ACK] Seq=1 Win-5792 Len=120 |
| 50   | 3.298223        | 198.51.100.23 | 192.0.2.1     | HTTP     | GET /sales.html HTTP/1.1                |
| 51   | 3.349457        | 192.0.2.1     | 198.51.100.23 | HTTP     | HTTP/1.1 200 OK (text/html)             |
| ...  | ...             | ...           | ...           | ...      | ...                                     |
| 205  | 46.9778230000001| 203.0.113.0   | 192.0.2.1     | TCP      | 54770->443 [SYN] Seq=0 Win=5792 Len=0   |




### How to Read the Wireshark TCP/HTTP Log

In this reading, you'll learn how to read the provided Wireshark TCP/HTTP log for network traffic between employee website visitors and the company's web server. Most network protocol/traffic analyzer tools used to capture packets will provide this same information.

### Log Entry Number and Time

| No.  | Time      |
|------|-----------|
| 47   | 3.144521  |
| 48   | 3.195755  |
| 49   | 3.246989  |

The Wireshark TCP log section provided to you starts at log entry number (No.) 47, which is three seconds and .144521 milliseconds after the logging tool started recording. This indicates that approximately 47 messages were sent and received by the web server in the 3.1 seconds after starting the log. This rapid traffic speed is why the tool tracks time in milliseconds.

#### Source and Destination IP Addresses

| Source       | Destination  |
|--------------|--------------|
| 198.51.100.23 | 192.0.2.1    |
| 192.0.2.1     | 198.51.100.23 |
| 198.51.100.23 | 192.0.2.1    |

The source and destination columns contain the source IP address of the machine that is sending a packet and the intended destination IP address of the packet. In this log file, the IP address 192.0.2.1 belongs to the company's web server. The range of IP addresses in 198.51.100.0/24 belong to the employees' computers.

#### Protocol Type and Related Information

| Protocol | Info                                      |
|----------|-------------------------------------------|
| TCP      | 42584->443 [SYN] Seq=0 Win-5792 Len=120... |
| TCP      | 443->42584 [SYN, ACK] Seq=0 Win-5792 Len=120... |
| TCP      | 42584->443 [ACK] Seq=1 Win-5792 Len=120... |

The `Protocol column `indicates that the packets are being sent using the TCP protocol, which is at the transport layer of the TCP/IP model. In the given log file, you will notice that the protocol will eventually change to HTTP, at the application layer, once the connection to the web server is successfully established.

The Info column provides information about the packet. It lists the source port followed by an arrow` → `pointing to the destination port. In this case, port 443 belongs to the web server. Port 443 is normally used for encrypted web traffic.

The next data element given in the Info column is part of the `three-way handshake process `to establish a connection between two machines. In this case, employees are trying to connect to the company's web server:

- The [SYN] packet is the initial request from an employee visitor trying to connect to a web page hosted on the web server. SYN stands for "synchronize."
- The [`SYN, ACK`] packet is the web server's response to the visitor's request agreeing to the connection. The server will reserve system resources for the final step of the handshake. SYN, ACK stands for "synchronize acknowledge."
- The [ACK] packet is the visitor's machine acknowledging the permission to connect. This is the final step required to make a successful TCP connection. ACK stands for "acknowledge."

#### Normal Website Traffic

A normal transaction between a website visitor and the web server would be like:

| No.  | Time      | Source       | Destination  | Protocol | Info                                      |
|------|-----------|--------------|--------------|----------|-------------------------------------------|
| 47   | 3.144521  | 198.51.100.23| 192.0.2.1    | TCP      | 42584->443 [SYN] Seq=0 Win=5792 Len=120... |
| 48   | 3.195755  | 192.0.2.1    | 198.51.100.23| TCP      | 443->42584 [SYN, ACK] Seq=0 Win=5792 Len=120... |
| 49   | 3.246989  | 198.51.100.23| 192.0.2.1    | TCP      | 42584->443 [ACK] Seq=1 Win=5792 Len=120... |
| 50   | 3.298223  | 198.51.100.23| 192.0.2.1    | HTTP     | GET /sales.html HTTP/1.1                  |
| 51   | 3.349457  | 192.0.2.1    | 198.51.100.23| HTTP     | HTTP/1.1 200 OK (text/html)               |

Notice that the handshake process takes a few milliseconds to complete. Then, you can identify the employee's browser requesting the sales.html webpage using the HTTP protocol at the application level of the TCP/IP model. Followed by the web server responding to the request.

#### The Attack

As you learned previously, malicious actors can take advantage of the TCP protocol by flooding a server with SYN packet requests for the first part of the handshake. However, if the number of SYN requests is greater than the server resources available to handle the requests, then the server will become overwhelmed and unable to respond to the requests. This is a network level denial of service (DoS) attack, called a `SYN flood attack, `that targets network bandwidth to slow traffic. A SYN flood attack simulates a TCP connection and floods the server with SYN packets. A DoS direct attack originates from a single source. A distributed denial of service (DDoS) attack comes from multiple sources, often in different locations, making it more difficult to identify the attacker or attackers.

#### Color Coded TCP Log

There are two tabs at the bottom of the log file. One is labeled "Color coded TCP log." If you click on that tab, you will find the server interactions with the attacker's IP address (203.0.113.0) marked with red highlighting (and the word "red" in column A).

| Color | No.  | Time      | Source       | Destination  | Protocol | Info                                      |
|-------|------|-----------|--------------|--------------|----------|-------------------------------------------|
| red   | 52   | 3.390692  | 203.0.113.0  | 192.0.2.1    | TCP      | 54770->443 [SYN] Seq=0 Win=5792 Len=0... |
| red   | 53   | 3.441926  | 192.0.2.1    | 203.0.113.0  | TCP      | 443->54770 [SYN, ACK] Seq=0 Win=5792 Len=120... |
| green | 54   | 3.493160  | 203.0.113.0  | 192.0.2.1    | TCP      | 54770->443 [ACK]Seq=1 Win=5792 Len=0... |
| green | 55   | 3.544394  | 198.51.100.14| 192.0.2.1    | TCP      | 14785->443 [SYN] Seq=0 Win=5792 Len=120... |
| ...   | ...  | ...       | ...          | ...          | ...      | ...                                       |

Initially, the attacker’s SYN request is answered normally by the web server (log items 52-54). However, the attacker keeps sending more SYN requests, which is abnormal. At this point, the web server is still able to respond to normal visitor traffic, which is highlighted and labeled as green. An employee visitor with the IP address of 198.51.100.14 successfully completes a SYN/ACK connection handshake with the webserver (log item nos. 55, 56, 58). Then, the employee’s browser requests the sales.html webpage with the GET command and the web server responds (log item no. 60 and 62).

In the next 20 rows, the log begins to reflect the struggle the web server is having to keep up with the abnormal number of SYN requests coming in at a rapid pace. The attacker is sending several SYN requests every second. The rows highlighted and labeled yellow are failed communications between legitimate employee website visitors and the web server.

---
The two types of errors in the logs include:

    • An HTTP/1.1 504 Gateway Time-out (text/html) error message. This message is generated by a gateway server that was waiting for a response from the web server. If the web server takes too long to respond, the gateway server will send a timeout error message to the requesting browser.
    • An [RST, ACK] packet, which would be sent to the requesting visitor if the [SYN, ACK] packet is not received by the web server. RST stands for reset, acknowledge. The visitor will receive a timeout error message in their browser and the connection attempt is dropped. The visitor can refresh their browser to attempt to send a new SYN request.

yellow
121
19.844731
192.0.2.1
198.51.100.9
TCP
443->4631 [RST, ACK] Seq=1 Win=5792 Len=0...

s you scroll through the rest of the log, you will notice the web server stops responding to  legitimate employee visitor traffic. The visitors receive more error messages indicating that they cannot establish or maintain a connection to the web server. From log item number 125 on, the web server stops responding. The only items logged at that point are from the attack. As there is only one IP address attacking the web server, you can assume this is a direct DoS SYN flood attack.

red
125
21.136783
203.0.113.0
192.0.2.1
TCP
54770->443 [SYN] Seq=0 Win=5792 Len=0...



### Step 3. Identify the type of attack causing this network interruption

Reflect on the types of network intrusion attacks that you have learned about in this course so far. As a security analyst, identifying the type of network attack based on the incident is the first step to managing the attack and preventing similar attacks in the future.

### Step 4. Explain how the attack is causing the website to malfunction

Describe how the network attack is causing problems in the worksheet. Review the network activity log, reflect on your answer to the prompts in the first section of this activity, and write a report in the space provided in the template. 
When writing your report, discuss the network devices and activities that are involved in the interruption. 

### Report

Activity Exemplar: Analyze network attacks

Section 1: Identify the type of attack that may have caused this 
network interruption
One potential explanation for the website’s connection timeout error message is a DoS attack. The logs show that the web server stops responding after it is overloaded with SYN packet requests. This event could be a type of DoS attack called SYN flooding.

Section 2: Explain how the attack is causing the website malfunction
When the website visitors try to establish a connection with the web server, a three-way handshake occurs using the TCP protocol. The handshake consists of three steps: 

    1. A SYN packet is sent from the source to the destination, requesting to connect.
    2. The destination replies to the source with a SYN-ACK packet to accept the connection request. The destination will reserve resources for the source to connect.
    3. A final ACK packet is sent from the source to the destination acknowledging the permission to connect. 

In the case of a SYN flood attack, a malicious actor will send a large number of SYN packets all at once, which overwhelms the server’s available resources to reserve for the connection. When this happens, there are no server resources left for legitimate TCP connection requests. 

The logs indicate that the web server has become overwhelmed and is unable to process the visitors’ SYN requests. The server is unable to open a new connection to new visitors who receive a connection timeout message.
 
[Content](#content)



## Brute force attacks and OS hardening

In this reading, you’ll learn about brute force attacks. You’ll consider how vulnerabilities can be assessed using virtual machines and sandboxes, and learn ways to prevent brute force attacks using a combination of authentication measures. Implementing various OS hardening tasks can help prevent brute force attacks. An attacker can use a brute force attack to gain access and compromise a network.
Usernames and passwords are among the most common and important security controls in place today. They are used and enforced on everything that stores or accesses sensitive or private information, like personal phones, computers, and restricted applications within an organization. However, a major issue with relying on login credentials as a critical line of defense is that they’re vulnerable to being stolen and guessed by malicious actors. 

### Brute force attacks

A brute force attack is a trial-and-error process of discovering private information. There are different types of brute force attacks that malicious actors use to guess passwords, including: 
    • `Simple brute force attacks. `When attackers try to guess a user's login credentials, it’s considered a simple brute force attack. They might do this by entering any combination of usernames and passwords that they can think of until they find the one that works.
    • `Dictionary attacks `use a similar technique. In dictionary attacks, attackers use a list of commonly used passwords and stolen credentials from previous breaches to access a system. These are called “dictionary” attacks because attackers originally used a list of words from the dictionary to guess the passwords, before complex password rules became a common security practice. 
Using brute force to access a system can be a tedious and time consuming process, especially when it’s done manually. There are a range of tools attackers use to conduct their attacks. 

### Assessing vulnerabilities

Before a brute force attack or other cybersecurity incident occurs, companies can run a series of tests on their network or web applications to assess vulnerabilities. Analysts can use virtual machines and sandboxes to test suspicious files, check for vulnerabilities before an event occurs, or to simulate a cybersecurity incident.

### Virtual machines (VMs)

Virtual machines (VMs) are software versions of physical computers. VMs provide an additional layer of security for an organization because they can be used to run code in an isolated environment, preventing malicious code from affecting the rest of the computer or system. VMs can also be deleted and replaced by a pristine image after testing malware. 
VMs are useful when investigating potentially infected machines or running malware in a constrained environment. Using a VM may prevent damage to your system in the event its tools are used improperly. VMs also give you the ability to revert to a previous state. However, there are still some risks involved with VMs. There’s still a small risk that a malicious program can escape virtualization and access the host machine. 
You can test and explore applications easily with VMs, and it’s easy to switch between different VMs from your computer. This can also help in streamlining many security tasks.

### Sandbox environments

A sandbox is a type of testing environment that allows you to execute software or programs separate from your network. They are commonly used for testing patches, identifying and addressing bugs, or detecting cybersecurity vulnerabilities. Sandboxes can also be used to evaluate suspicious software, evaluate files containing malicious code, and simulate attack scenarios. 
Sandboxes can be stand-alone physical computers that are not connected to a network; however, it is often more time- and cost-effective to use software or cloud-based virtual machines as sandbox environments. Note that some malware authors know how to write code to detect if the malware is executed in a VM or sandbox environment. Attackers can program their malware to behave as harmless software when run inside these types of  testing environments. 

### Prevention measures

Some common measures organizations use to prevent brute force attacks and similar attacks from occurring include: 
    • `Salting and hashing: `Hashing converts information into a unique value that can then be used to determine its integrity. It is a one-way function, meaning it is impossible to decrypt and obtain the original text. Salting adds random characters to hashed passwords. This increases the length and complexity of hash values, making them more secure.
    • `Multi-factor authentication (MFA) `and two-factor authentication (2FA): MFA is a security measure which requires a user to verify their identity in two or more ways to access a system or network. This verification happens using a combination of authentication factors: a username and password, fingerprints, facial recognition, or a one-time password (OTP) sent to a phone number or email. 2FA is similar to MFA, except it uses only two forms of verification.
    • `CAPTCHA and reCAPTCHA: `CAPTCHA stands for Completely Automated Public Turing test to tell Computers and Humans Apart. It asks users to complete a simple test that proves they are human. This helps prevent software from trying to brute force a password. reCAPTCHA is a free CAPTCHA service from Google that helps protect websites from bots and malicious software.
    • `Password policies: `Organizations use password policies to standardize good password practices throughout the business. Policies can include guidelines on how complex a password should be, how often users need to update passwords, and if there are limits to how many times a user can attempt to log in before their account is suspended.


[Content](#content)

## Portfolio: Apply OS hardening techniques

### Scenario

You are a cybersecurity analyst for yummyrecipesforme.com, a website that sells recipes and cookbooks. A disgruntled baker has decided to publish the website’s best-selling recipes for the public to access for free. 
The baker executed a brute force attack to gain access to the web host. They repeatedly entered several known default passwords for the administrative account until they correctly guessed the right one. After they obtained the login credentials, they were able to access the admin panel and change the website’s source code. They embedded a javascript function in the source code that prompted visitors to download and run a file upon visiting the website. After running the downloaded file, the customers are redirected to a fake version of the website where the seller’s recipes are now available for free.
Several hours after the attack, multiple customers emailed yummyrecipesforme’s helpdesk. They complained that the company’s website had prompted them to download a file to update their browsers. The customers claimed that, after running the file, the address of the website changed and their personal computers began running more slowly. 
In response to this incident, the website owner tries to log in to the admin panel but is unable to, so they reach out to the website hosting provider. You and other cybersecurity analysts are tasked with investigating this security event.
To address the incident, you create a sandbox environment to observe the suspicious website behavior. You run the network protocol analyzer tcpdump, then type in the URL for the website, yummyrecipesforme.com. As soon as the website loads, you are prompted to download an executable file to update your browser. You accept the download and allow the file to run. You then observe that your browser redirects you to a different URL, greatrecipesforme.com, which is designed to look like the original site. However, the recipes your company sells are now posted for free on the new website.  
The logs show the following process:
    1. The browser requests a DNS resolution of the yummyrecipesforme.com URL.
    2. The DNS replies with the correct IP address. 
    3. The browser initiates an HTTP request for the webpage.
    4. The browser initiates the download of the malware.
    5. The browser requests another DNS resolution for greatrecipesforme.com.
    6. The DNS server responds with the new IP address.
    7. The browser initiates an HTTP request to the new IP address.
A senior analyst confirms that the website was compromised. The analyst checks the source code for the website. They notice that javascript code had been added to prompt website visitors to download an executable file. Analysis of the downloaded file found a script that redirects the visitors’ browsers from yummyrecipesforme.com to greatrecipesforme.com. 
The cybersecurity team reports that the web server was impacted by a brute force attack. The disgruntled baker was able to guess the password easily because the admin password was still set to the default password. Additionally, there were no controls in place to prevent a brute force attack. 
Your job is to document the incident in detail, including identifying the network protocols used to establish the connection between the user and the website.  You should also recommend a security action to take to prevent brute force attacks in the future.
Step-By-Step Instructions



### Step 2: Access supporting materials
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 
To use the supporting materials for this course item, click the link below and select Use Template. 
Links to supporting materials: 
    • DNS & HTTP traffic log(https://docs.google.com/document/d/1mLq-qSedt4ZS8SSAQMWuOQ2djibob38wkUJZS3zTCrw/template/preview?usp=sharing&resourcekey=0-yvXQeSsKts64mfpFG8Jm3Q)

```txt
14:18:32.192571 IP your.machine.52444 > dns.google.domain: 35084+ A? yummyrecipesforme.com. (24)
14:18:32.204388 IP dns.google.domain > your.machine.52444: 35084 1/0/0 A 203.0.113.22 (40)


14:18:36.786501 IP your.machine.36086 > yummyrecipesforme.com.http: Flags [S], seq 2873951608, win 65495, options [mss 65495,sackOK,TS val 3302576859 ecr 0,nop,wscale 7], length 0
14:18:36.786517 IP yummyrecipesforme.com.http > your.machine.36086: Flags [S.], seq 3984334959, ack 2873951609, win 65483, options [mss 65495,sackOK,TS val 3302576859 ecr 3302576859,nop,wscale 7], length 0
14:18:36.786529 IP your.machine.36086 > yummyrecipesforme.com.http: Flags [.], ack 1, win 512, options [nop,nop,TS val 3302576859 ecr 3302576859], length 0
14:18:36.786589 IP your.machine.36086 > yummyrecipesforme.com.http: Flags [P.], seq 1:74, ack 1, win 512, options [nop,nop,TS val 3302576859 ecr 3302576859], length 73: HTTP: GET / HTTP/1.1
14:18:36.786595 IP yummyrecipesforme.com.http > your.machine.36086: Flags [.], ack 74, win 512, options [nop,nop,TS val 3302576859 ecr 3302576859], length 0
…<a lot of traffic on the port 80>... 


14:20:32.192571 IP your.machine.52444 > dns.google.domain: 21899+ A? greatrecipesforme.com. (24)
14:20:32.204388 IP dns.google.domain > your.machine.52444: 21899 1/0/0 A 192.0.2.17 (40)

14:25:29.576493 IP your.machine.56378 > greatrecipesforme.com.http: Flags [S], seq 1020702883, win 65495, options [mss 65495,sackOK,TS val 3302989649 ecr 0,nop,wscale 7], length 0
14:25:29.576510 IP greatrecipesforme.com.http > your.machine.56378: Flags [S.], seq 1993648018, ack 1020702884, win 65483, options [mss 65495,sackOK,TS val 3302989649 ecr 3302989649,nop,wscale 7], length 0
14:25:29.576524 IP your.machine.56378 > greatrecipesforme.com.http: Flags [.], ack 1, win 512, options [nop,nop,TS val 3302989649 ecr 3302989649], length 0
14:25:29.576590 IP your.machine.56378 > greatrecipesforme.com.http: Flags [P.], seq 1:74, ack 1, win 512, options [nop,nop,TS val 3302989649 ecr 3302989649], length 73: HTTP: GET / HTTP/1.1
14:25:29.576597 IP greatrecipesforme.com.http > your.machine.56378: Flags [.], ack 74, win 512, options [nop,nop,TS val 3302989649 ecr 3302989649], length 0
…<a lot of traffic on the port 80>... 

```


    • How to read the DNS & HTTP log(https://docs.google.com/document/d/1NzNMIYK3J8bs7jAL3dGYjAal4pqkq1XLrzTxLcZLaXw/template/preview?usp=sharing)

    ```txt
    How to read the DNS & HTTP traffic log


This reading explains how to identify the brute force attack using tcpdump. 


14:18:32.192571 IP your.machine.52444 > dns.google.domain: 35084+ A? yummyrecipesforme.com. (24)

14:18:32.204388 IP dns.google.domain > your.machine.52444: 35084 1/0/0 A 203.0.113.22 (40)

The first section of the DNS & HTTP traffic log file shows the source computer (your.machine.52444) using port 52444 to send a DNS resolution request to the DNS server (dns.google.domain) for the destination URL (yummyrecipesforme.com). Then the reply comes back from the DNS server to the source computer with the IP address of the destination URL (203.0.113.22). 



14:18:36.786501 IP your.machine.36086 > yummyrecipesforme.com.http: Flags [S], seq 2873951608, win 65495, options [mss 65495,sackOK,TS val 3302576859 ecr 0,nop,wscale 7], length 0

14:18:36.786517 IP yummyrecipesforme.com.http > your.machine.36086: Flags [S.], seq 3984334959, ack 2873951609, win 65483, options [mss 65495,sackOK,TS val 3302576859 ecr 3302576859,nop,wscale 7], length 0

The next section shows the source computer sending a connection request (Flags [S]) from the source computer (your.machine.36086) using port 36086 directly to the destination (yummyrecipesforme.com.http). The .http suffix is the port number; http is commonly associated with port 80. The reply shows the destination acknowledging it received the connection request (Flags [S.]). The communication between the source and the intended destination continues for about 2 minutes, according to the timestamps between this block (14:18) and the next DNS resolution request (see below for the 14:20 timestamp). 


TCP Flag codes include:

Flags [S]  - Connection Start 
Flags [F]  - Connection Finish 
Flags [P]  - Data Push
Flags [R]  - Connection Reset
Flags [.]  - Acknowledgment

14:18:36.786589 IP your.machine.36086 > yummyrecipesforme.com.http: Flags [P.], seq 1:74, ack 1, win 512, options [nop,nop,TS val 3302576859 ecr 3302576859], length 73: HTTP: GET / HTTP/1.1


The log entry with the code HTTP: GET / HTTP/1.1 shows the browser is requesting data from yummyrecipesforme.com with the HTTP: GET method using HTTP protocol version 1.1. This could be the download request for the malicious file. 



14:20:32.192571 IP your.machine.52444 > dns.google.domain: 21899+ A? greatrecipesforme.com. (24)

14:20:32.204388 IP dns.google.domain > your.machine.52444: 21899 1/0/0 A 192.0.2.172 (40)

14:25:29.576493 IP your.machine.56378 > greatrecipesforme.com.http: Flags [S], seq 1020702883, win 65495, options [mss 65495,sackOK,TS val 3302989649 ecr 0,nop,wscale 7], length 0

14:25:29.576510 IP greatrecipesforme.com.http > your.machine.56378: Flags [S.], seq 1993648018, ack 1020702884, win 65483, options [mss 65495,sackOK,TS val 3302989649 ecr 3302989649,nop,wscale 7], length 0

Then, a sudden change happens in the logs. The traffic is routed from the source computer to the DNS server again using port .52444 (your.machine.52444 > dns.google.domain) to make another DNS resolution request. This time, the DNS server routes the traffic to a new IP address (192.0.2.172) and its associated URL (greatrecipesforme.com.http). The traffic changes to a route between the source computer and the spoofed website (outgoing traffic: IP your.machine.56378 > greatrecipesforme.com.http and incoming traffic: greatrecipesforme.com.http > IP your.machine.56378). Note that the port number (.56378) on the source computer has changed again when redirected to a new website.


Resources for more information
    • An introduction to using tcpdump at the Linux command line: Lists several tcpdump commands with example output. The article describes the data in the output and explains why it is useful.(https://opensource.com/article/18/10/introduction-tcpdump)
    • tcpdump Cheat Sheet: Lists tcpdump commands, packet capturing options, output options, protocol codes, and filter options(https://www.comparitech.com/net-admin/tcpdump-cheat-sheet/)
    • What is a computer port? | Ports in networking: Provides a short list of the most common ports for network traffic and their associated protocols. The article also provides information about ports in general and using firewalls to block ports.(https://www.cloudflare.com/learning/network-layer/what-is-a-computer-port/)
    • Service Name and Transport Protocol Port Number Registry: Provides a database of port numbers with their service names, transport protocols, and descriptions(https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml)
    • How to Capture and Analyze Network Traffic with tcpdump?: Provides several tcpdump commands with example output. Then, the article describes each data element in examples of tcpdump output.(https://geekflare.com/tcpdump-examples/) 
    • Masterclass – Tcpdump – Interpreting Output: Provides a color-coded reference guide to tcpdump output (https://packetpushers.net/masterclass-tcpdump-interpreting-output/)



    
    ```

### Step 3: Identify the network protocol involved in the incident

Imagine that you are one of the cybersecurity analysts in this scenario and you are tasked with writing an incident report for this security event. Using the DNS & HTTP log file you produced with tcpdump, determine which network protocol is identified in the packet captures during the investigation. You will use what you learned about the four layers of the TCP/IP model and which protocols happen at each layer. If needed, you can review the video and reading about the TCP/IP model to use as guides for your response. Then review the DNS & HTTP traffic log and record which protocol you identified in the first section of the security incident report template.

### Step 4: Document the incident

Summarize the incident in the second section of the report. Provide as many details and facts as possible in your documentation. When writing the documentation, be sure to:
    • Avoid using strong emotional language (good, terrible, awful, etc.).
    • Include as many facts about the issue as you can, including where the incident occurred, how it happened, whether anyone witnessed it, how it was discovered, etc.
    • Indicate your sources for information and evidence.
Writing accurate and detailed documentation for cybersecurity incidents can serve as a reference point for other cybersecurity analysts. Additionally, quality documentation can be used to educate other employees about cybersecurity measures taken within the company when incidents occur and can help businesses comply with various security audits.

### Step 5: Recommend one remediation for brute force attacks

After documenting the incident, write one recommendation to help your organization prevent brute force attacks in the future.
Some of the common security methods used to prevent brute force attacks include:
    • Requiring strong passwords
    • Enforcing two-factor authentication (2FA)
    • Monitoring login attempts
    • Limiting the number of login attempts
Select one security measure, and explain why it is effective in section three of the security incident report template.
The more safety measures that are in place, the less likely a malicious actor will be able to access sensitive information.

### The Exemplar Explained: Security Incident Report 


Section 1: Identify the network protocol involved in the incident
The protocol impacted in the incident is Hypertext transfer protocol (HTTP). Running tcpdump and accessing the yummyrecipesforme.com website to detect the problem, capture protocol, and traffic activity in a DNS & HTTP traffic log file provided the evidence needed to come to this conclusion. The malicious file is observed being transported to the users’ computers using the HTTP protocol at the application layer.


The primary goal of this activity was to identify the network protocol used in the incident. The first line of the report announces the answer to that step. The protocol involved was determined by using information presented in the scenario, the DNS & HTTP log, and the knowledge you have learned about the TCP/IP model in this course: 

    • The DNS & HTTP log shows a request is sent to the DNS server to resolve the IP address for the yummyrecipesforme.com URL. The DNS server replies with the correct IP address. The browser uses this to direct users to the correct website. 
    • The scenario states that when the website loads, a function on the website prompts users to download a file to update their browsers. Both the scenario and the logs indicate this activity occurs over the HTTP protocol, which you previously learned is part of the application layer of the TCP/IP model. Please review the article “How to read the DNS & HTTP traffic log” linked in Step 2 of the activity for an explanation of the evidence found in the log.
    • After the user downloads and runs the file, the logs show that the user’s browser sends a new request to the DNS server to resolve the IP address for a different URL: greatrecipesforme.com. The DNS server resolves the URL and the users are redirected to this new website over HTTP.





Section 2: Document the incident
Several customers contacted the website owner stating that when they visited the website, they were prompted to download and run a file that asked them to update their browsers. Their personal computers have been operating slowly ever since. The website owner tried logging into the web server but noticed they were locked out of their account.

The cybersecurity analyst used a sandbox environment to test the website without impacting the company network. Then, the analyst ran tcpdump to capture the network and protocol traffic packets produced by interacting with the website. The analyst was prompted to download a file claiming it would update the user’s browser, accepted the download and ran it. The browser then redirected the analyst to a fake website (greatrecipesforme.com) that looked identical to the original site (yummyrecipesforme.com). 

The cybersecurity analyst inspected the tcpdump log and observed that the browser initially requested the IP address for the yummyrecipesforme.com website. Once the connection with the website was established over the HTTP protocol, the analyst recalled downloading and executing the file. The logs showed a sudden change in network traffic as the browser requested a new IP resolution for the greatrecipesforme.com URL. The network traffic was then rerouted to the new IP address for the greatrecipesforme.com website. 

The senior cybersecurity professional analyzed the source code for the websites and the downloaded file. The analyst discovered that an attacker had manipulated the website to add code that prompted the users to download a malicious file disguised as a browser update. Since the website owner stated that they had been locked out of their administrator account, the team believes the attacker used a brute force attack to access the account and change the admin password. The execution of the malicious file compromised the end users’ computers.  


Section 2 of the report should contain your interpretation of the log file and the Scenario section in the activity. You should have connected these events to what you have learned in the course to help you describe the investigation and analysis process. Note that it is a common practice for report writing to refer to all people involved in the third person (e.g., “the cybersecurity analyst” or “they”), even when you are the cybersecurity analyst describing actions you performed.  


    1. The first paragraph summarizes the events and problems identified when the incident was first reported. This information can be found at the beginning of the scenario.
    2. The second paragraph describes the testing activities involved in investigating this event. This information is also provided in the scenario section. You should have summarized these activities in your own words. 
    3. The third paragraph describes the analysis work. This information is available in the scenario and the log file. The article “How to read the DNS & HTTP traffic log” is available in Step 2 of the activity to help you interpret the log file. 
    4. The final paragraph adds what the senior cybersecurity analyst and the incident management team concluded about the root cause of the attack. 

Section 3: Recommend one remediation for brute force attacks
One security measure the team plans to implement to protect against brute force attacks is two-factor authentication (2FA). This 2FA plan will include an additional requirement for users to validate their identification by confirming a one-time password (OTP) sent to either their email or phone. Once the user confirms their identity through their login credentials and the OTP, they will gain access to the system. Any malicious actor that attempts a brute force attack will not likely gain access to the system because it requires additional authorization. 


In the third section, you were to write about addressing brute force attacks. You should have selected one of the options provided in the reading about brute force attacks. Then you should have explained the remediation method and how it works in your own words.

### Activity Exemplar: Apply OS hardening techniques

Section 1: Identify the network protocol involved in the incident
The protocol impacted in the incident is Hypertext transfer protocol (HTTP). Running tcpdump and accessing the yummyrecipesforme.com website to detect the problem, capture protocol, and traffic activity in a DNS & HTTP traffic log file provided the evidence needed to come to this conclusion. The malicious file is observed being transported to the users’ computers using the HTTP protocol at the application layer.


Section 2: Document the incident
Several customers contacted the website owner stating that when they visited the website, they were prompted to download and run a file that asked them to update their browsers. Their personal computers have been operating slowly ever since. The website owner tried logging into the web server but noticed they were locked out of their account.

The cybersecurity analyst used a sandbox environment to test the website without impacting the company network. Then, the analyst ran tcpdump to capture the network and protocol traffic packets produced by interacting with the website. The analyst was prompted to download a file claiming it would update the user’s browser, accepted the download and ran it. The browser then redirected the analyst to a fake website (greatrecipesforme.com) that looked identical to the original site (yummyrecipesforme.com). 

The cybersecurity analyst inspected the tcpdump log and observed that the browser initially requested the IP address for the yummyrecipesforme.com website. Once the connection with the website was established over the HTTP protocol, the analyst recalled downloading and executing the file. The logs showed a sudden change in network traffic as the browser requested a new IP resolution for the greatrecipesforme.com URL. The network traffic was then rerouted to the new IP address for the greatrecipesforme.com website. 

The senior cybersecurity professional analyzed the source code for the websites and the downloaded file. The analyst discovered that an attacker had manipulated the website to add code that prompted the users to download a malicious file disguised as a browser update. Since the website owner stated that they had been locked out of their administrator account, the team believes the attacker used a brute force attack to access the account and change the admin password. The execution of the malicious file compromised the end users’ computers. 

Section 3: Recommend one remediation for brute force attacks
One security measure the team plans to implement to protect against brute force attacks is two-factor authentication (2FA). This 2FA plan will include an additional requirement for users to validate their identification by confirming a one-time password (OTP) sent to either their email or phone. Once the user confirms their identity through their login credentials and the OTP, they will gain access to the system. Any malicious actor that attempts a brute force attack will not likely gain access to the system because it requires additional authorization. 

[Content](#content)

## Network security applications

This section of the course covers the topic of network hardening and monitoring. Each device, tool, or security strategy put in place by security analysts further protects—or hardens—the network until the network owner is satisfied with the level of security. This approach of adding layers of security to a network is referred to as defense in depth.
In this reading, you are going to learn about the role of four devices used to secure a network—firewalls, intrusion detection systems, intrusion prevention systems, and security incident and event management tools. Network security professionals have the choice to use any or all of these devices and tools depending on the level of security that they hope to achieve. 
This reading will discuss the benefits of layered security. Each tool mentioned is an additional layer of defense that can incrementally harden a network, starting with the minimum level of security (provided by just a firewall), to the highest level of security (provided by combining a firewall, an intrusion detection and prevention device, and security event monitoring). 

Take note of where each tool is located on the network. Each tool has its own place in the network’s architecture. Security analysts are required to understand the network topologies shown in the diagrams throughout this reading.

### Firewall

So far in this course, you learned about stateless firewalls, stateful firewalls, and next-generation firewalls (NGFWs), and the security advantages of each of them.
Most firewalls are similar in their basic functions. Firewalls allow or block traffic based on a set of rules. As data packets enter a network, the packet header is inspected and allowed or denied based on its port number. NGFWs are also able to inspect packet payloads. Each system should have its own firewall, regardless of the network firewall.

### Intrusion Detection System 

An `intrusion detection system (IDS) `is an application that monitors system activity and alerts on possible intrusions. An IDS alerts administrators based on the signature of malicious traffic.
The IDS is configured to detect known attacks. IDS systems often sniff data packets as they move across the network and analyze them for the characteristics of known attacks. Some IDS systems review not only for signatures of known attacks, but also for anomalies that could be the sign of malicious activity. When the IDS discovers an anomaly, it sends an alert to the network administrator who can then investigate further.
The limitations to IDS systems are that they can only scan for known attacks or obvious anomalies. New and sophisticated attacks might not be caught. The other limitation is that the IDS doesn’t actually stop the incoming traffic if it detects something awry. It’s up to the network administrator to catch the malicious activity before it does anything damaging to the network. 
When combined with a firewall, an IDS adds another layer of defense. The IDS is placed behind the firewall and before entering the LAN, which allows the IDS to analyze data streams after network traffic that is disallowed by the firewall has been filtered out. This is done to reduce noise in IDS alerts, also referred to as false positives.

### Intrusion Prevention System 

An intrusion prevention system (IPS) is an application that monitors system activity for intrusive activity and takes action to stop the activity. It offers even more protection than an IDS because it actively stops anomalies when they are detected, unlike the IDS that simply reports the anomaly to a network administrator.
An IPS searches for signatures of known attacks and data anomalies. An IPS reports the anomaly to security analysts and blocks a specific sender or drops network packets that seem suspect. 
The IPS (like an IDS) sits behind the firewall in the network architecture. This offers a high level of security because risky data streams are disrupted before they even reach sensitive parts of the network. However, one potential limitation is that it is inline: If it breaks, the connection between the private network and the internet breaks. Another limitation of IPS is the possibility of false positives, which can result in legitimate traffic getting dropped.


### Full packet capture devices

Full packet capture devices can be incredibly useful for network administrators and security professionals. These devices allow you to record and analyze all of the data that is transmitted over your network. They also aid in investigating alerts created by an IDS. 

### Security Information and Event Management 

A security information and event management system (SIEM) is an application that collects and analyzes log data to monitor critical activities in an organization. SIEM tools work in real time to report suspicious activity in a centralized dashboard. SIEM tools additionally analyze network log data sourced from IDSs, IPSs, firewalls, VPNs, proxies, and DNS logs. SIEM tools are a way to aggregate security event data so that it all appears in one place for security analysts to analyze. This is referred to as a single pane of glass. 
Below, you can review an example of a dashboard from Google Cloud’s SIEM tool, Chronicle. Chronicle is a cloud-native tool designed to retain, analyze, and search data.
Splunk is another common SIEM tool. Splunk offers different SIEM tool options: Splunk Enterprise and Splunk Cloud. Both options include detailed dashboards which help security professionals to review and analyze an organization's data. There are also other similar SIEM tools available, and it's important for security professionals to research the different tools to determine which one is most beneficial to the organization.
A SIEM tool doesn’t replace the expertise of security analysts, or of the network- and system-hardening activities covered in this course, but they’re used in combination with other security methods. Security analysts often work in a Security Operations Center (SOC) where they can monitor the activity across the network. They can then use their expertise and experience to determine how to respond to the information on the dashboard and decide when the events meet the criteria to be escalated to oversight.

| Devices / Tools               | Advantages                                                                                             | Disadvantages                                                                                            |
|------------------------------|--------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Firewall                     | A firewall allows or blocks traffic based on a set of rules.                                       | A firewall is only able to filter packets based on information provided in the header of the packets. |
| Intrusion Detection System   | An IDS detects and alerts admins about possible intrusions, attacks, and other malicious traffic.  | An IDS can only scan for known attacks or obvious anomalies; new and sophisticated attacks might not be caught. It doesn’t actually stop the incoming traffic. |
| Intrusion Prevention System  | An IPS monitors system activity for intrusions and anomalies and takes action to stop them.       | An IPS is an inline appliance. If it fails, the connection between the private network and the internet breaks. It might detect false positives and block legitimate traffic. |
| Security Information and Event Management (SIEM) | A SIEM tool collects and analyzes log data from multiple network machines. It aggregates security events for monitoring in a central dashboard. | A SIEM tool only reports on possible security issues. It does not take any actions to stop or prevent suspicious events. |



## Portfolio: Security risk assessment report

Scenario

Review the following scenario. Then complete the step-by-step instructions.
You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 
After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:
    1. The organization’s employees' share passwords.
    2. The admin password for the database is set to the default.
    3. The firewalls do not have rules in place to filter traffic coming in and out of the network.
    4. Multifactor authentication (MFA) is not used. 
If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 
In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.
Step-By-Step Instructions

Follow the instructions and answer the following question to complete the activity. Then, go to the next course item to compare your work to a completed exemplar.

### Step 2: Access supporting materials

The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

`Network hardening tools`


| Security Hardening Tasks                                 | Description                                                                                                                              | Common Uses                                                                                                                                                                                                                     |
|--------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Baseline Configurations              | A documented set of specifications within a system that is used as a basis for future builds, releases, and updates.                   | To restore a system to a previous baseline after a network outage, or unauthorized changes on a baseline.                                                                                                                      |
| Configuration Checks                 | Updating the encryption standards for data that is stored in databases.                                                                  | To see if there are any unauthorized changes to the system.                                                                                                                                                                    |
| Disabling Unused Ports               | Ports can be blocked on firewalls, routers, servers, and more to prevent potentially dangerous network traffic from passing through.    | Before an incident occurs, to prevent malicious actors from entering the network through the open port. Can be used after an incident to prevent future attacks from happening through unused open ports.                              |
| Encryption Using the Latest Standards | Rules or methods used to conceal outgoing data and uncover or decrypt the incoming data.                                               | Can be implemented regularly to assess if the current encryption standards are secure and effective for your organization. The encryption standards can also be updated after a data breach.                                       |
| Firewall Maintenance                 | Firewall maintenance entails checking and updating security configurations regularly to stay ahead of potential threats.                 | This can happen regularly. Firewall rules can be updated in response to an event that allows abnormal network traffic into the network. This measure can be used to protect against various DDoS attacks.                      |
| Hardware & Software Disposal         | Ensures that all old hardware is properly wiped of all data and disposed of.                                                            | Prevent the network from various threats by removing outdated or unused software or hardware that do not have the latest security patches or updates. Unpatched devices can allow malicious actors to easily access the network. |
| Multifactor Authentication (MFA)     | A security measure which requires a user to verify their identity in two or more ways to access a system or network.                   | Can help protect against brute force attacks and similar security events. MFA can be implemented at any time, and is mostly a technique that is set up once then maintained.                                            |
| Network Access Privileges             | Network access privileges involves permitting, limiting, and/or blocking access privileges to network assets for people, roles, groups, etc. | Reduces the risk of unauthorized users and outside traffic from accessing the internal network. This can be implemented once, or revisited depending on the likelihood of social engineering or brute force attacks.             |
| Network Log Analysis                 | The process of examining network logs to identify events of interest.                                                                    | Can be configured to alert the security team when there is abnormal traffic on the network. This can be used either before an incident occurs, during to track network traffic, and can be configured in the response of a... |



### Step 3: Select up to three hardening tools and methods to implement

Think about all of the network hardening tools and methods you have learned about in this course that can protect the organization’s network from future attacks. What hardening tasks would be the most effective way to respond to this situation? Write your response in part one of the worksheet.

### Step 4: Provide and explain 1-2 recommendations

You recommended one or two security hardening practices to help prevent this from occurring again in the future. Explain why the security hardening tool or method selected is effective for addressing the vulnerability. Here are a couple questions to get you started:
    • Why is the recommended security hardening technique effective?
    • How often does the hardening technique need to be implemented?
Write your response in part two of the worksheet.

### Security risk assessment report

Part 1: Select up to three hardening tools and methods to implement
Three hardening tools the organization can use to address the vulnerabilities
found include:
1. Implementing multi-factor authentication (MFA)
2. Setting and enforcing strong password policies
3. Performing firewall maintenance regularly
MFA requires users to use more than one way to identify and verify their
credentials before accessing an application. Some MFA methods include
fingerprint scans, ID cards, pin numbers, and passwords.
Password policies can be refined to include rules regarding password length, a
list of acceptable characters, and a disclaimer to discourage password sharing.
They can also include rules surrounding unsuccessful login attempts, such as
the user losing access to the network after five unsuccessful attempts.
Firewall maintenance entails checking and updating security configurations
regularly to stay ahead of potential threats.

Part 2: Explain your recommendation(s)
Enforcing multi-factor authentication (MFA) will reduce the likelihood that a
malicious actor can access a network through a brute force or related attack.
MFA will also make it more difficult for people within the organization to share
passwords. Identifying and verifying credentials is especially critical among
employees with administrator level privileges on the network. MFA should be
enforced regularly.
Creating and enforcing a password policy within the company will make it
increasingly challenging for malicious actors to access the network. The rules
that are included in the password policy will need to be enforced regularly within
the organization to help increase user security.
Firewall maintenance should happen regularly. Firewall rules should be updated
whenever a security event occurs, especially an event that allows suspicious
network traffic into the network. This measure can be used to protect against
various DoS and DDoS attacks.

[Content](#content)

## Secure the cloud

Earlier in this course, you were introduced to cloud computing. Cloud computing is a model for allowing convenient and on-demand network access to a shared pool of configurable computing resources. These resources can be configured and released with minimal management effort or interaction with the service provider. 
Just like any other IT infrastructure, a cloud infrastructure needs to be secured. This reading will address some main security considerations that are unique to the cloud and introduce you to the shared responsibility model used for security in the cloud. Many organizations that use cloud resources and infrastructure express concerns about the privacy of their data and resources. This concern is addressed through cryptography and other additional security measures, which will be discussed later in this course.

### Cloud security considerations

Many organizations choose to use cloud services because of the ease of deployment, speed of deployment, cost savings, and scalability of these options. Cloud computing presents unique security challenges that cybersecurity analysts need to be aware of. 

### Identity access management

Identity access management (IAM) is a collection of processes and technologies that helps organizations manage digital identities in their environment. This service also authorizes how users can use different cloud resources. A common problem that organizations face when using the cloud is the loose configuration of cloud user roles. An improperly configured user role increases risk by allowing unauthorized users to have access to critical cloud operations. 

### Configuration

The number of available cloud services adds complexity to the network. Each service must be carefully configured to meet security and compliance requirements. This presents a particular challenge when organizations perform an initial migration into the cloud. When this change occurs on their network, they must ensure that every process moved into the cloud has been configured correctly. If network administrators and architects are not meticulous in correctly configuring the organization’s cloud services, they could leave the network open to compromise. Misconfigured cloud services are a common source of cloud security issues. 

### Attack surface

Cloud service providers (CSPs) offer numerous applications and services for organizations at a low cost. 
Every service or application on a network carries its own set of risks and vulnerabilities and increases an organization’s overall attack surface. An increased attack surface must be compensated for with increased security measures.
Cloud networks that utilize many services introduce lots of entry points into an organization’s network. However, if the network is designed correctly, utilizing several services does not introduce more entry points into an organization’s network design. These entry points can be used to introduce malware onto the network and pose other security vulnerabilities. It is important to note that CSPs often defer to more secure options, and have undergone more scrutiny than a traditional on-premises network. 

### Zero-day attacks

Zero-day attacks are an important security consideration for organizations using cloud or traditional on-premise network solutions. A zero day attack is an exploit that was previously unknown. CSPs are more likely to know about a zero day attack occurring before a traditional IT organization does. CSPs have ways of patching hypervisors and migrating workloads to other virtual machines. These methods ensure the customers are not impacted by the attack. There are also several tools available for patching at the operating system level that organizations can use.

### Visibility and tracking

Network administrators have access to every data packet crossing the network with both on-premise and cloud networks. They can sniff and inspect data packets to learn about network performance or to check for possible threats and attacks.
This kind of visibility is also offered in the cloud through flow logs and tools, such as packet mirroring. CSPs take responsibility for security in the cloud, but they do not allow the organizations that use their infrastructure to monitor traffic on the CSP’s servers. Many CSPs offer strong security measures to protect their infrastructure. Still, this situation might be a concern for organizations that are accustomed to having full access to their network and operations. CSPs pay for third-party audits to verify how secure a cloud network is and identify potential vulnerabilities. The audits can help organizations identify whether any vulnerabilities originate from on-premise infrastructure and if there are any compliance lapses from their CSP. 

### Things change fast in the cloud

CSPs are large organizations that work hard to stay up-to-date with technology advancements. For organizations that are used to being in control of any adjustments made to their network, this can be a potential challenge to keep up with. Cloud service updates can affect security considerations for the organizations using them. For example, connection configurations might need to be changed based on the CSP’s updates. 
Organizations that use CSPs usually have to update their IT processes. It is possible for organizations to continue following established best practices for changes, configurations, and other security considerations. However, an organization might have to adopt a different approach in a way that aligns with changes made by the CSP. 
Cloud networking offers various options that might appear attractive to a small company—options that they could never afford to build on their own premises. However, it is important to consider that each service adds complexity to the security profile of the organization, and they will need security personnel to monitor all of the cloud services. 

### Shared responsibility model

A commonly accepted cloud security principle is the shared responsibility model. The shared responsibility model states that the CSP must take responsibility for security involving the cloud infrastructure, including physical data centers, hypervisors, and host operating systems. The company using the cloud service is responsible for the assets and processes that they store or operate in the cloud.
The shared responsibility model ensures that both the CSP and the users agree about where their responsibility for security begins and ends. A problem occurs when organizations assume that the CSP is taking care of security that they have not taken responsibility for. One example of this is cloud applications and configurations. The CSP takes responsibility for securing the cloud, but it is the organization’s responsibility to ensure that services are configured properly according to the security requirements of their organization. 

[Content](#content)





