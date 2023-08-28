
## Content

[Introduction to Networking](#introduction-to-networking)

[The Network Layer](#the-network-layer)

[The Transport and Application Layers](#the-transport-and-application-layers)

[Networking Services](#networking-services)

[Networking Servicess](#networking-servicess)

[Troubleshooting and the Future of Networking](#troubleshooting-and-the-future-of-networking)

[Content](#content)

[Courses list](README.md#contents)


# Introduction to Networking

Describe how the TCP/IP five layer network model works.
Identify basic networking devices.
Label each of the five layers in the TCP/IP network model.
Describe how the physical layer works.
Describe how the data link layer works.

## Introduction to Computer Networking

### Course Introduction

**Protocol:** A defined set of standards that computers must follow in order to communicate properly.

**Computer networking:** The name we've given to the full scope of how computers communicate with each other.

*"Networking involves ensuring that computers can hear each other, that they speak protocols other computers can understand, [and] that they repeat messages not fully delivered."*



## The TCP/IP Five-Layer Network Model

| # | Layer Name  |
|---|-------------|
| 5 | Application |
| 4 | Transport   |
| 3 | Network     |
| 2 | Data Link   |
| 1 | Physical    |

#### Physical Layer
- *Represents the physical devices that interconnect computers.*
- Includes specs for networking cables and connectors that join devices
- Also includes specs for how signals are sent over these connections

#### Data Link Layer
- (Also known as the "network interface", or "network access layer.")
- *Responsible for defining a common way of interpreting these signals so network devices can communicate.*- The data link layer is responsible for getting data across a single link.
- The most common (of many) protocols at the data link layer is Ethernet
  - The **Ethernet** standards also define a protocol responsible for getting data to nodes on the same network or link.

#### Network Layer
- (Also known as the "Internet layer.")
- *Allows different networks to communicate with each other through devices known as routers.*
- **Internetwork:** A collection of networks connected together through routers
  - The most famous of these is the **Internet**.
- This layer is responsible for getting data delivered across a connection of networks.
- The most common protocol of this layer is **Internet Protocol (IP)**
  - **IP** is the heart of the Internet and most smaller networks around the world
- Network software is usually divided into *client* and *server* categories
  - A single node may run multiple client or server applications

#### Transport Layer
- *While the network layer delivers data between two individual nodes, **the transport layer sorts out which client and server programs are supposed to get that data**.*
  - The network layer is responsible for getting data from one node to another;
  - The transport layer is responsible for ensuring that data gets to the right applications running on those nodes.
- **Transmission Control Protocol (TCP)** is the most common protocol used at this layer
- **User Datagram Protocol (UDP)** is an alternative protocol.

#### Application Layer
- Many different protocols exist at this layer, and they are all application-specific.
  - HTTP is one such protocol

#### The TCP/IP Mail Analogy

1. The *physical layer* is the delivery truck and the roads;
2. The *data link layer* is how the delivery trucks get from one intersection to the next, over and over;
3. The *network layer* identifies which roads need to taken to get from address A to address b;
4. The *transport layer* ensures that the delivery driver knows how to knock on your door to tell you that your package has arrived;
5. The *application layer* is the contents of the package itself.

#### Parting Notes
- The traditional TCP/IP Model only has four layers, as it doesn't differentiate between the physical layer and the data link layer. 
  - The fundamental concepts remain the same, however.
- The other well-known model is the **OSI model**, which is taught by network certification by Net+, Cisco, and others.
  - The main difference is the TCP/IP has five layers, whereas OSI has seven
  - The OSI model abstracts the application layer into three layers total



## The Basics of Networking Devices

### Cables

**Cables** are what connect different devices to each other, allowing data to be transmitted over them.

- Today's networking cables usually fall into one of two categories:
  1. Copper
  2. Fiber

#### Copper

- *Copper* cables are the most common form of networking cable.
  - They're made up of multiple pairs of copper wires inside plastic insulator.
  - These copper wires transmit binary data, using voltage between two ranges.
    - The system receiving the data interprets the voltage changes as binary ones and zeroes.

The most common forms of copper twisted-pair cables are **Cat5**, **Cat5e**, and **Cat6** cables. (Cat is short for "category.")
- The categories have different physical characteristics.
  - But differences in how the twisted pars are arranged inside can drastically alter how quickly data can be transmitted; and how resistant the signals are to outside interference.
- Cat5 has mostly been replaced by Cat5e, because Cat5e's internals reduce **crosstalk**.

- **Crosstalk** is when an electrical pulse on one wire is accidentally detected another wire.
  - This means the receiving end can't understand the data, resulting in a network error.

- Cat5e cables' higher quality specifications make it less likely that data needs to be retransmitted.

- Cat6 cables follow even more strict specification to avoid crosstalk, making those cables more expensive. 
  - Cat6 cables can transfer data faster and more reliably than Cat5e cables can.
  - However, due to their internal arrangement, they have a shorter maximum distance when used at higher speeds. 

#### Fiber
- Fiber is short for *fiber optic cables*.

- **Fiber cables** contain individual optical fibers, which are tiny tubes made out of glass about the width of a human hair.
  - These tubes of glass transport beams of light.
  - Unlike the voltage of copper cables, fiber cables use pulses of light to transmit binary data.
- You're more likely to encounter fiber cables at data centers than you are in offices or residences.

The advantages of fiber optic cables:
- Aren't effected by electromagnetic interference like copper wires are.
- Generally transport data quicker.
- Can transport data over much longer distances than copper, without suffering potential data loss.

However, fiber cables are much more expensive and fragile than copper cables.


### Hubs and Switches

- **Hub:** A physical layer device that allows for connections from many computers at once.
  - Hubs allow all computers to talk to each other, resulting in a lot of noise and creating a collision domain.
  - A **collision domain** is a network segment where only one device can communicate at a time.
    - If multiple systems try sending data at the same time, the electrical pulses sent across the cable can interfere with each other.
    - It causes systems to have to wait for a "quiet period" before they try resending the data.
  - Because of this, hubs are rare and mostly a historical artifact today.

Instead, the more common way of connecting many computers today is a network switch (originally known as a *switching hub*)

- A **switch** is very similar to a hub; but while a hub is a layer one (physical layer) device, a switch is a layer two (data link layer) device.
  - Thus, a switch acts like a postmaster at a mail center:
    - Inspecting the contents of ethernet protocol data;
    - Determining which system the data is intended for; 
    - And sending the data to only that particular system.

Switches drastically reduce (or totally eliminate) the problem of collision domains on a network; resulting in fewer re-transmissions and higher overall throughput.


### Routers

**Hubs and switches** are the primary devices used to connect computers on a single network, usually referred to as a *LAN*, or *local area network*.

But if you want to send or receive data to computers on other networks, you need a router.

#### Routers
A **router** is a device that knows how to forward data between independent networks.

- While a hub is a layer one device, and a switch is a layer two device, a router is a layer three (network layer) device.

- Routers inspect IP data to determine where to send things, like how switches inspect ethernet data to determine where to send things.

The purpose of most routers is to forward traffic coming from the home or office LAN, and forward it to the Internet service provider (ISP).
  - Once traffic is at the ISP, a more complex router known as a *core router* takes over.

- **Core ISP routers** are the backbone of the Internet.
  - They are directly responsible for how data is sent and received across the Internet every day.
  - Not only do core routers handle way more traffic than home routers, but they also make significantly more complex decisions about where to sent traffic.
  - They also usually have many different connections to many other routers.

Routers share data 

- Routers share data with each other via a protocol known as the **border gateway protocol (BGP)**.
  - The BGP lets them learn about the most optimal paths to forward traffic. 
  - When you open a web browser and load a web page, the traffic between computers and the web servers could have traveled over dozens of different routers.

In summary, routers are the global guides to getting Internet traffic to the right places.


### Servers and Clients

- A *server* is as something that provides data to something requesting that data. 
- The thing receiving the data, is referred to as a *client*.

- Not just nodes can be servers or clients--individual computer programs running on the same node can be servers and clients to each other, too.

- Most devices are not purely servers or clients--almost all nodes are both at some point in time. 
  - EX: An email server is referred to as a *server*, despite it itself being a client to a DNS server.
    - Why?
    - Because its primary purpose is to serve data to clients.
  - Another example is a desktop occasionally acts as a server, while its primary purpose is to act as a client so the computer user can perform tasks.

- Regardless, in most network topographies, each node is primarily either a server or client.

#### In summary
*"[A] server is anything that can provide data to a client, but we also use the words to refer to the primary purpose of various nodes on our network."*


## The Physical Layer

### Moving Bits Across the Wire

- *"The physical layer consists of devices and means of transmitting bits across computer networks."*

- A **bit** is the smallest representation fo data that a computer can understand; a one or a zero.
  - These ones and zeroes sent across networks are what make up the frames and packets of data in networking.
  - Copper network cables constantly carry an electrical charge
  - Bits travel across this network in a process called modulation
  - **Modulation** is a way of varying the voltage of this charge using across the cable

- Modulation, as applied to computer networking, is more specifically known as *line coding*
  - Line coding allows devices on either end of a link to understand whether an electrical charge is a one or a zero.


### Twisted Pair Cabling and Duplexing

- The most common cabling type for connecting computer devices is known as *twisted pair cable*.
  - Named because it contains pairs of copper wires that are twisted together.
  - The pair of wires act as a single conduit for information.
  - Being twisted helps protect against electromagnetic interference and crosstalk from other networks.
- Twisted pair cables allow for duplex communication.
  - **Duplex communication** is the concept that information can flow in both directions across the table. 
  - This is contrast to **simplex communication**, which is unidirectional.
    - Simplex communication: Baby monitor (only one way)
    = Duplex communication: Phone (two way)

- Networking cables ensure duplex communication is possible by reserving one or two pairs for communicating in one direction.
  - Then, they use the other pairs for communicating in the *other* direction.
- Both devices communicating at the exact same time is called **full-duplex**.
- **Half-duplex** is what happens when there are network connection problems;
  - Communication is still *possible* in each direction; 
  - But only one device can be communicating at a time.


### Network Ports and Patch Panels

The final part of the physical layer process are the endpoints of network links.

- Twisted pair cables terminate with a plug, which takes the individual internal wires and exposes them.
- The most common plug is the **Registered Jack 45 (RJ45)**.
- Network ports are generally directly attached to devices that make up a computer network.
  - Switches would have many network ports; whereas a server or desktop would only have one or two.

Most network ports have two small LED lights: The link LED, and the activity LED
  - The link LED will be lit when a cable is properly connected to two devices that are both powered on. 
  - The activity LED will flash when data is actively transmitted across the cable.

A **patch panel** is a device containing many network ports, but it does no other work.
  - It's just a container for the endpoints of many runs of cable.
  - Patch panels in turn run cables to switches or routers, to provide network access.


## The Data Link layer

### Ethernet and MAC Addresses

Despite widespread consumer adoption of Wi-Fi, traditional cable networks still make up the bulk of networking in businesses and data centers.

- **Ethernet** is the protocol most widely used to send data across individual links.
- Ethernet and the data link layer allow software at higher levels of the stack to send and receive data.
- The primary purpose of the data link layer is to do the handle interpreting the hardware and physical layers, for the higher layers.
  - By dumping this responsibility on the data link layer, the Internet, transport and application layers can all operate the same no matter how the device they're running on is connected.

- Ethernet was first invented in 1980, and published/standardized in 1983.
  - It's largely the same today as it was back then.
  - Ethernet came about because switches or switchable hubs hadn't yet been invented.
    - This meant basically all devices on a network shared a single collision domain (where only one device can speak at a time).
- Ethernet solved the unintelligible results of single collision domains by introducing *carrier sense multiple access with collision detection* (CSMA/CD).
  - **CSMA/CD** is used to determine when the communications channels are clear and when the device is free to transmit data.
    - With CSMA/CD, computers can detect data collision, then will wait a moment before trying to send data again.

- When a network segment is a collision domain, it means that all devices on that segment receive all communication across the entire segment. 
  - This means we need a way to identify which node the transmission was actually meant for. 
  - This is where something known as a *media access control address* (or MAC address) comes into play.

- A **MAC address** is a globally unique identifier attached to an individual network interface. 
  - It's a 48-bit number normally represented by six groupings of two hexadecimal numbers.

- **Hexadecimal** is a way to represent numbers using 16 digits (like how binary uses 2 digits)
    - Hexadecimal (or *hex*) represents the numbers 10 through 15 by the letters A through F, respectively.

- Another way to reference each group of numbers in a MAC address is an octet.
  - In computer networking, an **octet** is any number that can be represented by 8 bits.
  - Two hexadecimal digits can represent the same numbers that 8 bits can.

- MAC addresses are globally unique because a 48-bit number has literally hundreds of trillions of possible values.

- The first three octets of a MAC address are the **organizationally unique identifier (OUI)**
  - These are assigned to individual hardware manufacturers by the Institute of Electrical and Electronics Engineers (IEEE).
  - Hence, you can always identify the manufacturer of a network interface purely by its MAC address.
- The last three octets can be assigned any way, so long as they remain globally unique.

*"**Ethernet** uses **MAC** addresses to ensure that the data it sends has both an address for the machine that sent the transmission; as well as the one the transmission was intended for."*
- Thus, even on a single collision domain, each node on the network knows when traffic is intended for it.


### Unicast, Multicast, and Broadcast

- At the Ethernet level, you look at a special bit in the destination MAC address, to determine the type of transmission.

#### Unicast
If the least significant bit in the first octet of a destination address is set to zero, it means that Ethernet frame is intended for only the destination address.
- A **unicast** transmission is always meant for just one receiving address.
  - One device transmitting data to one other device.

#### Multicast
If the least significant bit in the first octet of a destination address is set to one, it means you're dealing with a multicast frame. 
- A **multicast** frame is similarly set to all devices on the local network signal.
- What's different is that it will be accepted or discarded by each device depending on criteria aside from their own hardware MAC address.
  - Network interfaces can be configured to accept lists of configured multicast addresses for these sort of communication.

#### Broadcast
An Ethernet broadcast is sent to every single device on a LAN.
- This is accomplished by using a special destination known as a broadcast address.
  - The Ethernet broadcast address is all Fs. 
- Ethernet broadcasts are used so that devices can learn more about each other.


### Dissecting an Ethernet Frame

- A **data packet** is an all-encompassing term that represents any single set of binary data being sent across a network link.
  - Data packets at the Ethernet level are known as Ethernet frames.
- An **Ethernet frame** is a highly structured collection of information presented in a specific order. 
  - It allows network interfaces at the physical layer to convert a string of bits into meaningful data (or vice versa).

#### Anatomy of an Ethernet Frame

- The first part of an Ethernet frame is known as the preamble. 
  - A **preamble** is 8 bytes (or 64 bits long) and can itself be split into two sections. 
  - The first seven bytes are a series of alternating ones and zeros. 
    - These act partially as a buffer between frames and can also be used by the network interfaces to synchronize internal clocks they use, to regulate the speed at which they send data. 
  - This last byte in the preamble is known as the **start frame delimiter (SFD)**. 
    - This signals to a receiving device that the preamble is over and that the actual frame contents will now follow. 
- Immediately following the start frame delimiter, comes the **destination MAC address**. 
  - This is the hardware address of the intended recipient. 
- Which is then followed by the source MAC address--where the frame originated from. 
  - *(Don't forget that each MAC address is 48 bits or 6 bytes long.)* 
- The next part of an Ethernet frame is called the **EtherType field***. 
  - It's 16 bits long and used to describe the protocol of the contents of the frame.

Instead of the EtherType field, you could also find a **VLAN header**.
- A VLAN header indicates that the frame itself is a VLAN frame.
- If a VLAN header is present, the EtherType field follows it.
- VLAN stands for virtual LAN.
  - It allows you to have multiple logical LANs operating on the same physical equipment.
  - VLAN tags will only be delivered out of a switch configured to relay that specific tag.
    - This allows a single network to operate like multiple LANs
    - Like IP phones operating on one VLAN, and desktops operating on another.

After this, you find the data payload of an Ethernet frame.
- A **payload** in networking terms, is the actual data being transported (which is everything that isn't a header).
  - The data payload of traditional Ethernet frames ranges from 46 to 1500 bytes long.
- The payload contains all of the data from the higher layers (like IP, transport, and application) that's actually being transmitted.

Following this is the **frame check sequence**.
- This is a 4-byte (or 32-bit) number that represents a checksum value for the entire frame.
  - The **checksum value** is calculated by performing what's known as a *cyclical redundancy check* against the frame.
- A **cyclical redundancy check (CRC)** is an important concept for data integrity, used across all computing (not just network transmissions).
  - It's basically a specified calculation that the sender computes, and logs.
  - The recipient then performs the calculation, and compares it against the sender's log.
  - If the calculation doesn't exactly match, the data is inferred to be corrupted or lost during transmission.
    - It's then up to a protocol at a higher layer to decide if that data should be retransmitted. 
    - *(Ethernet itself only reports on data integrity. It doesn't perform data recovery.)*

[Content](#content)

---------------------------------------------------------------------------------------------The Network Layer----------------------------------------------------------------------------



## The Network Layer

Lesson Goals:
- Identify an IP address
- Describe how IP datagrams are encapsulated inside the payload of an ethernet frame
- Correctly identify and describe the many fields of an IP datagram header.

### The Network Layer

Address Resolution Protocol (ARP)

### IP Addresses

- A single octet is 8 bits of data

- Dotted decimal notation

- IP addresses are distributed in large sections to various organizations and companies instead of being determined by hardware vendors.
  - Thus, IP addresses are more hierarchical, easier to store data about, than physical addresses

- IP addresses belong to networks, not to the devices attached to those networks.

- **Dynamic Host Configuration Protocol (DHCP)** is the technology that automatically assigns IP addresses.

#### Dynamic IP address vs Static IP address
- A dynamic IP address is distributed by the DHCP
- A static IP address must be configured on a node manually
  - *"In most cases, static IP addresses are reserved for servers and network devices, while dynamic IP addresses are reserved for clients."*

### IP Datagrams and Encapsulation

- Much as data packets at the Ethernet layer have a unique name--Ethernet frames--so do data packets at the network layer:
  - Under the IP protocol, a data packet at the network layer is known as an **IP datagram**.
  - An **IP datagram** is a highly-structured series of fields that are strictly defined.

The two primary sections of an IP datagram are the *header* and the *payload*.

IP datagram headers contain much more data than an Ethernet frame header:

- The very first field is the **Version field**, four bits indicating which version of Internet protocol is being used. 
  - The most common version of IP is version four (or, IPv4). 

- After the version field comes the **Header Length** field.
  - This is also a 4-bit field that declares how long the entire header is. 
    - This is almost always 20 bytes in length when dealing with IPv4. 
    - In fact, 20 bytes is the minimum length of an IP header.

- Next comes the **Service Type** field. 
  - These eight bits can be used to specify details about quality of service (QoS)  technologies. 
  - QOS services allow routers to make decisions about which IP datagram may be more important than others.

- The next field is a 16 bit field, known as the **Total Length** field. 
  - It indicate the total length of the IP datagram it's attached to.

- The **Identification** field, is a 16-bit number that's used to group messages together.
  - The maximum size of a single datagram is the largest number you can represent with 16 bits: 65,535.
  - If the total amount of data that needs to be sent is larger than what can fit in a single datagram, the IP layer needs to split this data up into many individual packets.
    - When this happens, the identification field is used so that the receiving end understands that every packet with the same value in that field is part of the same transmission.

- The **Flag** field is used to indicate if a datagram is allowed to be fragmented, or to indicate that the datagram has already been fragmented.
  - **Fragmentation** is the process of taking a single IP datagram and splitting it up into several smaller datagrams.
  - If a datagram originates from a network allowing for large datagram sizes, and arrives at a network requiring smaller datagram sizes, it will have to be fragmented. 

- The **Fragmentation Offset** field contains values used by the receiving end to take all the parts of a fragmented packet and put them back together in the correct order.

- The **Time to Live (TTL)** field is an 8-bit field that indicates how many router hops a datagram can traverse, before it's thrown away.
  - This value is a sort of countdown, decrements the field by one; at zero, routers know they don't have to forward the datagram any further.
  - The main purpose of this field is to make sure that when there's a misconfiguration in routing that causes an endless loop, datagrams don't spend all eternity trying to reach their destination. 

- Next is the **Protocol** field, another 8-bit field that contains data about what transport layer protocol is being used.
  - The most common transport Layer protocols are TCP and UDP.

- Next is the **Header Checksum** field, a checksum of the contents of the entire IP datagram header.
  - It functions just like the Ethernet checksum field in an Ethernet frame.
  - Since the TTL field is recomputed at every router hop, the checksum field changes along with it.

- The **Source IP address** and **Destination IP address** fields then follow; each is 32-bits.

- Finally, the **IP Options** field.
  - This is an optional field, and is used to set special characteristics for datagrams primarily used for testing purposes.
  - The IP options field is usually followed by a **Padding** field. 
    - Since the IP options field is both optional and variable in length, the padding field is just a series of zeros used to ensure the header is the correct total size. 

#### How does this fit into the big picture?
- The IP datagram is the *data payload section* in an Ethernet header; and this process is known as **encapsulation**.
  - The entire contents of an IP datagram are encapsulated as the payload of an Ethernet frame. 
  - The IP datagram also has a payload section: The contents of this payload are the entirety of a TCP or UDP packet.


### IP address Classes

IP addresses can be split into two sections:
1. The **network ID**
2. The **host ID**

- The network ID is the first octet in an IP address; while the host ID is the second, third, and fourth octets.
  - Example: `9.100.100.100`
  - The `9.` is the network ID; the `100.100.100` is the host ID

The **Address class system** is a way of defining how the global IP address space is split up.

There are three primary types of address classes:
1. Class A
2. Class B
3. Class C

- **Class A** addresses are those where the first octet is used for the network ID; and the last three are used for the host ID.
- **Class B** addresses are those where the first *two* octets are used for the network ID; and the last two are used for the network ID.
- **Class C** addresses are those where the first *three* octets are used for the network ID; and only the fourth octet is used for the host ID.

#### Binary trick to Identify IP address classes
- If the very first bit of an IP address is 0, it belongs to a Class A network. 0.0.0.0 - 127.255.255.255  [0-127] first octet
- If the first bits are 10, it belongs to a Class B network.                    128.0.0.0 - 191.255.255.255 [128-191]
- If the first bits are 110, it belongs to a Class C network.                   192.0.0.0 - 233.255.255.255 [192-233]


The class system has mostly been replaced by a system known as **classless inter-domain routing (CIDR)**. 


### Address Resolution Protocol

**Address resolution protocol (ARP)** is a protocol used to discover the hardware address of a node with a certain IP address.

- Once it IP datagram has been fully formed, it needs to be encapsulated inside an Ethernet frame. 
  - This means that the transmitting device needs a destination MAC address to complete the Ethernet frame header.

- Almost all network-connected devices will retain a local ARP table.
  - An **ARP table** is a list of IP addresses and the MAC addresses associated with them.

ARP table entries generally expire after a short amount of time, to ensure changes in the network are accounted for.

#### Further Reading
- [Traditional ARP: ARP Process](https://www.practicalnetworking.net/series/arp/traditional-arp/)
- [ARP explained](https://study-ccna.com/arp/)


## Subnetting

### Subnetting

**Subnetting** is the process of taking a large network and splitting it up into many individual and smaller subnetworks, or *subnets*.

*"Incorrect subnetting setups are a common problem you might run into as an IT Support Specialist, so it's important to have a strong understanding of how this works."*

- Core routers can identify when an address belongs to, for example, a Class A network.
  - They then route the message to the *gateway router* responsible for the network (determined by the network ID).
  - A gateway router specifically serves as the entry and exit path to a certain network.
    - This contrasts with core routers, which (might) only speak to other core routers.
- Once the packet gets to the aforementioned Class A network, the gateway router is now responsible for getting that data to the proper system, by referring to the host ID.
  - But a single Class A network has over 16 million IDs--way too many for one route.
  - This is where subnetting comes into play.
    - With subnets, you can split your large network into many smaller networks.
    - These subnets will each feature their own gateway routers, as entry and exit points for each subnet.


### Subnet Masks

- In subnetting, some bits normally used in the host ID are actually used for a *subnet ID*.
  - An example: 10.0.1.10, where `10.0` is the network ID; `1` is the subnet ID; and `10` is the host ID.

- Core Internet routers only care about the network ID, and use it to send the datagram to the appropriate gateway router to that network.
- That gateway router can send the datagram to the destination machine, or the next router in the path to the destination.
- Finally, the host ID is used by the last router, to deliver the datagram to the intended recipient machine.

#### Subnet Masks

Subnet IDs are calculated by what's known as a *subnet mask*.
- **Subnet masks** are 32-bit numbers that are normally written out as four octets in decimal. (In other words, they look like an IP address.)

A subnet mask is a binary number that has two sections:
- The beginning part -- the mask itself -- is a string of 1s.
- Just 0s come after it.
  - The subnet mask (the part with all the 1s) tells you *what you can ignore* when computing a host ID.
  - The part with all the 0s *tells us what to keep*.
- The purpose of the subnet mask -- again, all the 1s -- *is to tell a router what part of the IP address is the **subnet ID***.

After you've identified the host ID (for example, a Class A), you're left with the last three octets.
- Break these octets into their binary form, and align them with the subnet mask.
  - The binary octet numbers that have a corresponding one in the subnet mask are the *subnet ID*.
  - The binary octet numbers that have a corresponding zero are the *host ID*.

The size of a subnet is entirely defined by its subnet mask.
- Example: `255.255.255.0` tells you that only the last octet is available for host IDs, regardless of what size the network and subnet IDs are.
  - A single 8-bit number can represent 256 different numbers; specifically, the numbers 0-255.

In general, a subnet can only contain *two less* than the total number of host IDs available.
- Going back to that `255.255.255.0` example, 0 is generally not used for an ID; and 255 is normally reserved as a broadcast address for the subnet.
  - Thus, in reality, only the numbers 1-254 are available for assignment to a host.
- This "total number less-than-two" concept is almost always true.
  - Still, you'll generally refer to the number of hosts available in a subnet as the entire number.
    - EG, you'd still say 8 bits of a host ID's space have 256 addresses available, not 254.
    - That's because those 2 other IPs are still IP addresses, even if they aren't assigned directly to a node on that subnet.

#### Subnet Masks Beyond Octets

- `255.255.255.254` translates to twenty-seven 1s, and five 0s.
  - Thus, there are 5 bits of host ID space; or 32 addresses.
- Enter a shorthand way of writing subnet masks.
  - `255.255.255.254` could be referenced through the notation `/27`.
  - So an IP address of `9.100.100.100` with the subnet mask of `255.255.255.254`...
    - ... the entire IP and subnet mask could be written out as:
      - `9.100.100.100/27`
  - Bear in mind, neither notation is necessarily more common than the other.


### Basic Binary Math

- Because of the constraints of how logic gates work inside of a processor, it's way easier for computers to think of things only in terms of zero and one. 
  - This is also known as binary, or base two.

- You can represent all whole numbers in binary in the same way you can in decimal, it just looks a little different. 
  - When you count in decimal you move through all of the numerals upward until you run out then you add a second column with a higher significance.
- For example, in a base ten system, once you count past 9, you start a new column and continue counting.
  - Binary works exactly the same; but instead of counting past 9, a new column initiates when you count past 1.

<!-- Insert base 2/base 10 comparison chart here -->

There's a simple trick to figure out how many decimal numbers can be represented by a certain number of bits.
- 8-bit number = 2^8 = 256, or 0-255.
- 4-bit number = 2^16
- 16-bit number = 2^16 = 65,536

#### Counting in Binary
- 0 + 0 = 0
- 0 + 1 = 1
- 1 + 0 = 1
- 1 + 1 = 10 (because it can't go past 1, and starts a new column)

- Addition is what's known as an *operator*, and there are many operators that computers use to make calculations.
  - Two of the most important operators are **OR** and **AND**.
    - In computer logic, a **1** represents **true** and a **0** represents **false**.
  - The way the **OR** operator works is you look at each digit, and if either of them is true, the result is true.
  - The operator **AND** does what it sounds like it does: It returns true if both values are true.
    - This is why we say, "1 *and* 1 equals 0."

#### Bringing It All Together:

A **subnet mask** is a way for a computer to use **and operators** to determine if an IP address exists on the same network.


### CIDR

- Address classes were the first attempt at splitting up the global Internet IP space. 
- Subnetting was introduced when it became clear that address classes themselves weren't as efficient way of keeping everything organized. 
- But as the Internet continued to grow, traditional subnetting just couldn't keep up. 
  - See: The limitations of the Internet.

**Classless Inter-Domain Routing (CIDR)** 
- CIDR is an even more flexible approach to describing blocks of IP addresses. 
- It expands on the concept of subnetting by using subnet masks to demarcate networks. 
  - To *demarcate* something means to set something off.
  - A **demarcation point** refers to where one network or system ends and another one begins.
- CIDR combines the network ID and subnet ID into one.
  - *CIDR notation* is where you get the `9.100.100.100/27` discussed in the last lesson.
- CIDR abandons the concept of address classes entirely, allowing addresses to be defined by only two individual IDs.
  - This simplifies how routers and networks devices need to think about IP address parts.
  - It also avoids enterprise-level challenges, like needing more addresses than a single Class C provided.
  - It also means, that routers now only need to know one entry in their routing table to deliver traffic to these addresses instead of two.



## Routing

### Basic Routing Concepts

- A **router** is a network device that forwards traffic depending on the destination address of the traffic.
  - A router is a device that has at least 2 network interfaces, since it has to be connected to 2 networks to do its job.

Basic routing has a few steps:
1. A router receives a packet of data on one of its interfaces;
2. The router examines the destination IP of this packet;
3. The router looks up the destination network of this IP in its routing table;
4. The router forwards that out through the interface that's closest to the remote network (determined by info within the routing table).
- These steps are repeated as needed until the traffic reaches its destination.

To protect against breakages, core Internet routers are typically connected in a mesh--meaning there might be many different paths for a packet to take.

Remember, IP addresses belong to networks, *not individual nodes on a network*.

Routers inspect the destination IP; look at the routing table to determine which path is the quickest; and forward the packet along the path.


### Routing Tables

- The earliest routers were just regular computers of the era. 
  - They had two network interfaces, bridge to networks, and auto-routing table that was manually updated. 
  - In fact, all major operating systems today, still have a routing table that they consult before transmitting data.

Routing tables vary; but all share several characteristics.

- The most basic routing table will have 4 columns:
1. **Destination Network:** This column would contain a row for each network the router knows about. 
  - When the router receives an incoming packet, it examines the destination IP address, and determines which network it belongs to.
  - A routing table will generally have a catch-all entry that matches any IP address that it doesn't have an explicit network listing for.
2. **Next Hop:** This is the IP address of the next router that should receive data intended for the destination network in question.
  - Or, this could just state the network is directly connected, and that there aren't any additional hops needed.
3. **Total Hops:** The crucial part of understanding routing, and how routing tables work.
  - Routers try to pick the shortest possible path at all times, to ensure timely delivery of data.
  - But, this shortest possible path can change due to various circumstances.
  - So, neighboring routers communicate with each other to keep track of what the shortest/most efficient path to a destination is, at any given time.
4. **Interface:** The router needs to know which of its interfaces it should forward traffic--matching the destination--out of.

Many core Internet routers have *millions* of rows in the routing tables.


### Interior Gateway Protocols

In order to learn about the world around them, routers use what are known as *routing protocols*.
- **Routing protocols** are special protocols routers use to speak to each other, in order to share what information they might have.
  - This is how a router on one side of the planet can eventually learn about the best path to a network on the other side of the planet.

Routing protocols fall into two main categories: interior gateway protocols, and exterior gateway protocols.

**Interior gateway protocols** are used by routers to share information *within* a single autonomous system.
- In networking terms, an **autonomous system** is a collection of networks that all fall under the control of a single network operator.
  - The best example of this would be a large corporation that needs to route data between their many offices an each of which might have their own local area network.

- Interior gateway protocols are further split into two categories:
  1. Link state routing protocols;
  2. Distance-vector protocols.
- The goals are similar; but the routers employing them share different types of data to accomplish their task.

#### Distance-vector protocols
- These are an older standard. 
- A router using this protocol takes its routing table; then sends this list to every neighboring router (every router directly connected to it).
- In computer science, a *list* is known as a **vector**.
  - This is why a protocol that just sends a list of distances to networks is known as a distance-vector protocol.
- With a distance-vector protocol, routers don't really know that much about the total state of an autonomous system, they just have some information about their immediate neighbors.

Distance vector protocols are pretty simple, but they don't allow for a router to have much information about the state of the world outside of their own direct neighbors.
- Because of this, a router might be slow to react to a change in the network far away from it. 
  - This is why link state protocols were eventually invented.

The most common distance-vector protocols are Routing Information Protocol (RIP) and [Enhanced Interior Gateway Routing Protocol](https://www.cisco.com/c/en/us/support/docs/ip/enhanced-interior-gateway-routing-protocol-eigrp/16406-eigrp-toc.html) (EIGRP).

### Link state routing protocols
Routers using a link state protocol take a more sophisticated approach to determining the best path to a network.
- Link state protocols get their name because each router advertises the *state* of the *link* of each of its interfaces.
  - These interfaces could be connected to other routers, or they could be direct connections to networks.
  - The information about each router is propagated to every other router on the autonomous system.
- Thus, every router on the system knows every detail about every other router in the system.

Each router then uses this big set of information, and runs complicated algorithms against it, to determine what the best path to any destination network might be.

- Link state protocols require more memory to hold all of this data.
- They also require much more processing power, to compute the quickest path to update the routing tables.


### Exterior Gateway Protocols

Exterior gateway protocols are used to communicate data between routers representing the edges of an autonomous system.

Routers use exterior gateway protocols when they need to share information across different organizations [autonomous systems].

The Internet is an enormous mesh of autonomous systems.
- Core Internet routers need to know about autonomous systems in order to properly forward traffic.
- Since autonomous systems are known/defined collections of networks, getting data to the edge router of an autonomous system is the number-one goal of core Internet routers.

The **Internet Assigned Numbers Authority (IANA)** is a non-profit organization, that helps manage things like IP address allocation.
  - The Internet couldn't function without a single authority for these sorts of issues.
- The IANA is also responsible for **Autonomous System Number (ASN)** allocation.
  - ASNs are numbers assigned to individual autonomous systems.
  - Just like IP addresses, ASNs are 32-bit numbers.


But unlike IP addresses, they're usually referred to as just a single decimal number (instead of split out into readable bits).
- This is for two reasons:
  1. An ASN never needs to change in order for it to represent more networks or hosts.
    - It's just the core Internet routing tables that need to be updated, to know what the ASN represents.
  2. ASNs are looked at by humans far less than IP addresses are.
    - ASNs represent entire autonomous systems.
    - ED: AS19604 = IBM

The only exterior gateway protocol standard is Border Gateway Protocol (BGP).

### Non-Routable Address Space

RFCs (Request for Comments) started as a way for academics to discuss how their computers might talk to each other.

An RFC would be published, people would leave comments, eventually a consensus would be formed, and a new standard would be developed.

In 1996, **RFC 1989** defined several networks as non-routable address space.
- These are ranges of IPs set aside for use by anyone, that cannot be routed to.
  - After all, not every computer connected to the internet needs to be able to communicate with every other computer connected to the internet. 
= Non-routable address space allows for nodes on such a network to communicate with each other but no gateway router will attempt to forward traffic to this type of network.
- Network Address Translation (NAT) evolved as a way to allow nodes on non-routable address space networks to communicate with other devices on the Internet.

The primary 3 address ranges of non-routable address space are:
- 10.0.0.0/8
- 172.16.0.0/12
- 192.168.0.0/16

These ranges are free for anyone to use for their internal networks. 
- Note: Interior gateway protocols will route these address spaces.
  - Thus, they are appropriate for use within an autonomous system but exterior gateway protocols will not. 

Over many decades, RFCs have come to belong to the IETF, orInternet Engineering Task Force, which is an open community charged with developing and maintaining the standards required for the Internet to continue to operate.

[Content](#content)

-------------------------------------------------------------------------The Transport and Application Layers-------------------------------------------------

# The Transport and Application Layers

The **Transport layer** allows traffic to be directed to specific network applications.

The **Application layer** allows these applications to communicate in a way they understand.

## The Transport Layer

The transport layer is responsible for lots of important functions of reliable computer networking. These include multiplexing and demultiplexing traffic, establishing long running connections and ensuring data integrity through error checking and data verification.

### The Transport Layer

**Multiplexing** means that nodes on the network have the ability to direct traffic toward many different receiving services.
- EX: Processes -> Multiplexer -> IP

**Demultiplexing** is the same concept, just at the receiving end. It's taking traffic that's all aimed at the same node, and delivering it to the proper receiving service.
- IP -> Demultiplexer -> Processes

- The transport layer handles multiplexing and demultiplexing through ports.
  - A **port** is a 16-bit number that's used to direct traffic to specific services running on a networked computer.

Remember: 
- A *server* or *service* is a program running on a computer waiting to be asked for data. 
- A *client* is another program that is requesting this data.

Different network services run while listening on specific ports for incoming requests.

- Ports are normally denoted with a colon after the IP address.
  - Example: `10.1.1.100:80`
  - When written this way, it's known as a *socket address* or *socket number*.

#### File Transfer Protocol (FTP) Server
- FTP is an older method, used for transferring files from one computer to another.
  - It still sees use today.
- TFP traditionally listens on port `21`.

Multiplexing and demultiplexing, combined with ports, make it possible for a single server to host many applications (like an internal website, a mail server, a file server, and a print server).


### Dissection of a TCP Segment

Just like how an Ethernet frame encapsulates an IP datagram, an IP datagram encapsulates a TCP segment.

And just like the Ethernet frame's payload section is an entire IP datagram; the IP datagram's payload section is an entire TCP segment.

A **TCP segment** is made up of a TCP header and a data section.
- (This data section is yet another payload section, where the application layer places its data.)

#### TCP Header

A TCP header itself is split into many fields containing lots of information.

- First are the **source port** and **destination port** fields.
  - The source port is a high-numbered port, chosen from a special section of ports known as *ephemeral ports*.
    - A source port is required to keep lots of outgoing connections separate.
    - A source port is needed so that when a web server replies, the computer making the original request can send the data to the program that was actually requesting it.
  - The destination port is the port of the service the traffic is intended for.

- Next is the **sequence number**, a 32-bit number that's used to keep track of where in a sequence of TCP segments this one is expected to be.
  - Remember that large data packets are split into many segments.

- Next is the **acknowledgement number**, another 32-bit number.
  - The acknowledgement number is the number of the next expected segment.
  - It works in tandem with the sequence number; IE if the sequence = 1, the acknowledgement = 2.

- The **data offset field** is a 4-bit number that communicates how long the TCP header for this segment is.
  - This is so the device receiving the data knows when the header ends, and the payload begins.

- Then 6 empty bits follow, reserved for the 6 TCP control flags.

- Then comes another 16-bit field, the **TCP window**.
  - The TCP window specifies the range of sequence numbers that might be sent before an acknowledgement is required.

> TCP is a protocol that's heavily reliant on acknowledgements. This is to ensure that all expected data is actually being received, and that the sending device doesn't waste time sending data that isn't being received.

- The next field is a 16-bit checksum.
  - The **TCP checksum** operates just like the checksum fields at the IP and ethernet level.
    - *"Once all of this segment has been ingested by a recipient, the checksum is calculated across the entire segment and is compared with the checksum in the header to make sure that there was no data lost or corrupted along the way."*

- The **urgent pointer field** is another 16-bit field.
  - It's used in conjunction with one of the TCP control flags, to point out particular segments that might be more important than others.
  - *"This is a feature of TCP that hasn't really ever seen adoption and you'll probably never find it in modern networking."*

- Next is the **options field**, ranging from 0 to 16 bits.
  - This is another rarely-used field in the real world.
  - It's sometimes used for more complicated flow control protocols.

- Finally, there's **padding**, which is just as sequence of 0s to ensure that the **data payload** begins at the expected location.


### TCP Control Flags and the Three-Way Handshake

- TCP protocol oversees the transmission of long, segmented chains of data over a connection.
  - Contrast this to Ethernet and IP protocol, which just send individual packets of data.

- TCP establishes a connection through the use of different TCP control flags (used in a very specific order).

#### The 6 TCP Control Flags
*Note: This is in the order they appear in a TCP header, not ordered by frequency/importance*

1. **URG (urgent)**
  - A value of 1 here indicates that the segment is considered urgent, and that the urgent pointer field has more data about this.
2. **ACK (acknowledged)**
  - A value of 1 in this field means that the acknowledgement number field should be examined.
3. **PSH (push)**
  - The transmitting device wants the receiving device to push currently-buffered data to the application on the receiving end as soon as possible.
    - A **buffer** is a computing technique where a certain amount of data is held somewhere, before being sent somewhere else.
4. **RST (reset)**
  - One of the sides in a TCP connection hasn't been able to properly recover from a series of missing or malformed segments.
5. **SYN (synchronize)**
  - It's used when first establishing a TCP connection, and ensures the receiving end knows to examine the sequence number field.
6. **FIN (finish)**
  - When this flag is set to 1, it means the transmitting computer doesn't have any more data to send, and the connection can be closed.

#### The Three-Way Handshake
*How a TCP connection is established*

A **handshake** is a way for two devices to ensure that they're speaking the same protocol, and will be able to understand each other.


| Transmitter | Three-Way Handshake | Receiver   |
|-------------|:-------------------:|------------|
| Computer A  |       SYN --->      | Computer B |
| Computer A  |     <--- SYN/ACK    | Computer B |
| Computer A  |       ACK --->      | Computer B |


Once three-way handshake is complete (both sides have sent SYN/ACK pairs to each other), the TCP connection is operating in full duplex.

Once one of the devices involved with the TCP connection is ready to close the connection, something known as a *four-way handshake** happens:

#### The Four-Way Handshake


| Transmitter | Four-Way Handshake | Receiver   |
|-------------|:------------------:|------------|
| Computer A  |       <--- FIN     | Computer B |
| Computer A  |      ACK --->      | Computer B |
| Computer A  |      FIN --->      | Computer B |
| Computer A  |      <--- ACK      | Computer B |



### TCP Socket States

- A **socket** is the instantiation of an end-point in a potential TCP connection.
  - An **instantiation** is the actual implementation of something defined elsewhere.

TCP sockets require actual programs to actually instantiate them; as opposed to ports, which is more of a virtual/descriptive thing.
- IE: You can send traffic to any port you want, but you're only going to get a response if a program has opened a socket on that port. 


#### TCP Socket States
TCP sockets can exist in lots of states. Here are some common ones:

- **LISTEN**
  - A TCP socket is ready and listening for incoming connections.
  - Seen on server-side only.
- **SYN_SENT**
  - A synchronization request has been sent, but the connection hasn't been established yet.
  - Seen on client-side only.
- **SYN-RECEIVED**
  - A socket previously in a LISTEN state has received a synchronization request and sent a SYN/ACK back.
  - Seen on server-side only.
- **ESTABLISHED**
  - The TCP connection is in working order and both sides are free to send each other data.
  - Seen on both client- and server-sides.
- **FIN_WAIT**
  - A FIN has been sent; but the corresponding ACK from the other end hasn't been received yet.
  - Seen on both client- and server-sides.
- **CLOSE_WAIT**
  - The connection has been closed at the TCP layer; but the application that opened the socket hasn't released its hold on the socket yet.
  - Seen on both client- and server-sides.
- **CLOSED**
  - The connection has been fully terminated and no further communication is possible.
  - Seen on both client- and server-sides.

There are other TCP socket states that exist. Also, socket state definitions vary with operating systems.

*"When troubleshooting issues at the TCP layer, make sure you check out the exact socket state definitions for the systems you're working with."*


### Connection-oriented and Connectionless Protocols

TCP is a connection-oriented protocol.
- A **connection-oriented protocol** establishes a connection, and uses this to ensure that all data has been properly been transmitted.
- A connection at the transport layer implies that every segment of data sent is acknowledged.


TCP expects an ACK for every bit of data it sends.

Connection-oriented protocols safeguard against data transmission errors, by a constant stream of acknowledgements in a connection.
- This is why sequence numbers are important.
  - If data segments are resent due to errors at lower levels, and the segments are out of order, it isn't a problem thanks to the sequence number's guidance.

The high overhead of connection-oriented protocols are expensive in terms of traffic, however.
- Establish the connection; send constant ACK stream; tear down connection at the end; etc.

This is where **connectionless protocols** come into play.
- The most common is **User Datagram Protocol (UDP)**
  - UDP doesn't rely on connections; and doesn't even support acknowledgement.
  - Instead, you just set the destination port, and send the packet.

A great use-case for UDP is streaming video:
- By removing TCP's overhead, you can send higher-quality video.
- More available bandwidth will be reserved for actual data transfer (the video frames), rather than for establishing constant acknowledgements that each video frame was delivered and received.


### System Ports vs. Ephemeral Ports

Transportation layer protocols use a concept of ports and multiplexing/demultiplexing to deliver data to individual services listening on network nodes.
- These ports are represented by a single 16-bit number (thus represent numbers 0-65,535)

These ranges have been designated by the **Internet Assigned Numbers Authority (IANA)**:

- `Port 0` isn't in use for network traffic; but it's sometimes used in communication taking place between different programs on the same computer.
- `Ports 1-1023` are referred to as **system ports**, also known as **well-known ports**.
  - These represent official ports for most well-known network services.
    - EX: HTTP normally communicates over `Port 80`, FTP over `Port 21`.
  - (In most OS) administrator-level access is required to start a program that listens on a system port.
- `Ports 1024-49151` are known as **registered ports**.
  - These are used for many other network services, which are less common than those used for system ports.
    - EX: `Port 3306`, which is the port many databases listen on.
  - (On most OS) any user of any access level can start a program listening on a registered port.
- `Ports 49152-65535` are **private** or **ephemeral ports**.
  - Ephemeral ports can't be registered with the IANA, and are generally used for establishing outbound connections.
  - Remember that all TCP traffic uses a destination port and a source port.
    - When a client wants to communicate with a server, the client will be assigned an ephemeral port to be used for just that one connection, while the server listens on a static system or registered port.

Not all operating systems follow the ephemeral port recommendations of the IANA. It depends on the platform. Sometimes registered port ranges are used; but no modern operating system will ever use a system port for outbound communication.


### Firewalls

A **firewall** is a device that blocks traffic that meets certain criteria.

Firewalls are the primary way to stop traffic you don't want from entering a network.
- Thus, they are critical to network security.

Firewalls are most commonly used at the transportation layer; but they also exist at other levels:
- Inspection of application layer traffic; blocking ranges of IP addresses; etc.

Firewalls at the transportation layer focus on blocking traffic to certain ports, while allowing traffic to other ports.

Firewalls are sometimes independent network devices; but it's better to think of them as a program that can run anywhere.
- For many companies--and almost all home users--the functionality of a router and a firewall are performed by the same device.
- Firewalls can run on individual hosts, too, instead of being a network device.


## The Application Layer

### The Application Layer

Just like every other layer, the TCP segment's payload section is actually the entire contents of whatever data applications want to send to each other. Also known as the *message*.
- It could be:
  - Contents of a web page, if a web browser is connecting to a web server;
  - Streaming video content of the Netflix app on your PlayStation connecting with Netflix servers;
  - The contents of a document your word processor is sending to a printer; etc.

Unlike other layers in the OSI model, there is no de facto protocol at the application layer--there are many across many different applications.


### The Application Layer and the OSI Model

The TCP/IP Model defines five layers, based on the five layers of *encapsulation*.

The **Open Systems Interconnection (OSI)** model, by contrast, is a seven-layer model. The two other layers are an abstraction of the Applications Layer:
7. Application
6. Presentation
5. Session
4. Transport
3. Network
2. Data Link
1. Physical

The **Session Layer** facilitates the communication between the actual *applications* and the Transport Layer.
- It's the part of the operating system that takes the unencapsulated *application layer* data and hands it off to the presentation layer.

The **Presentation Layer** is responsible for making sure the unencapsulated *application layer* data is able to be understood by the application in question.
- It's the part of the operating system that might handle encryption or compression of data.

The OSI model is the most rigorously-defined, meaning it's often used in academic settings, or by network certification organizations.
- CISCO uses the OSI model, for example.

[Content](#content)

-----------------------------------------------------------------------------------------------------Networking Services--------------------------------------------


# Networking Services

*The main purpose of computer networking is so network services can be available to answer requests for the data from clients.*

## Name Resolution

### Why do we need DNS?

Remembering every single website by its IP address would be impossible for most people. Since humans tend to remember words better than numbers, the domain name system was created to fix this.

**Domain Name System (DNS)** is a global and highly-distributed network service, that resolves strings of letters into IP addresses for you.

- The IP address for a domain name can change all the time, for many different reasons.
- A **domain name** is the term we use for something that can be resolved by DNS.

- By using DNS, an organization can just change what IP a domain name resolves to, and the end user would never even know.
  - So not only does DNS make it easier for humans to remember sites; it allows admin changes to happen behind the scenes (without the user knowing).

DNS also helps global organizations resolving domains to local data centers (which use different IPs).


### The many Steps of Name Resolution

DNS converts domain names into IP addresses.
- It's a system based on the way humans think of things, resolved into the way computers think of things.
- The process of turning a domain name into an IP address is known as *domain resolution.*
- DNS servers need to be specifically configured at a node on a network.

For a computer to operate on a modern network, they need to have a certain number of things configured:
1. IP address
2. Subnet mask
3. Gateway for a host
4. DNS server
  - Technically, a computer can *operate* without DNS or a DNS server; but it wouldn't be *usable* for a human.

### Five Primary Types of DNS Servers
1. Caching name servers
2. Recursive name servers
3. Root name servers
4. TLD name servers
5. Authoritative name servers

*Note: Any given DNS server can fulfill many of these roles at once.*

**Caching name servers**
- Are generally provided by an ISP, or your local network
- Their purpose is to store known domain name lookups for a certain amount of time
  - This prevents the lengthy domain name lookup process from happening upon each TCP connection
- Most caching name servers are also recursive name servers.

**Recursive name servers**
- Perform full DNS resolution requests

#### DNS Time to live (TTL)

A value, in seconds, that can be configured by the owner of a domain name for how long a name server is allowed to cache an entry before it should discard it and perform a full resolution again.
- A length TTL means it can take up to the length of a total TTL for a change in DNS record to be known to the entire Internet.
- Short answer: *TTL stands for "Time to Live" and determines how long a DNS entry can be cached.*

#### A full recursive resolution

1. The first step is [for a user -> caching/recursive name server] always to contact a root name server.
  - There are 13 total root name servers; originally actual physical servers, but now lookup authorities distributed across the globe via *anycast*.
2. The root servers will respond to a DNS lookup with the TLD name server that should be queried.
3. The TLD name servers will respond with a redirect, informing the computer performing the name lookup with which authoritative name server to contact.
  - Authoritative name servers are responsible for the last two parts of any domain name (which is the resolution at which a single organization may be responsible for a DNS lookup).
  - Example: For `www.weather.com`, the TLD name server would point a lookup at the authoritative server for `Weather.com`, which would likely be controlled by The Weather Channel, the organization itself that runs the site.
    - Finally, the DNS lookup could be redirected at the authoritative server for `weather.com`, which would finally provide the actual IP of the server in question.

This strict hierarchy is critical to the stability of the Internet, making sure that all full DNS resolutions go through a strictly-regulated and controlled series of lookups to get the correct responses. 
- It's also the best way to protect against malicious parties redirecting traffic.


***Top level domain (TLD)** is the last part of any domain name (like `.com`), and represents the top of the hierarchical DNS name resolution system.
  - For each TLD in existence, there's a TLD name server. 
    - This doesn't mean one physical server; but instead probably a global distribution of anycast-accessible servers responsible for each TLD.

**Anycast** is a technique that's used to route traffic to different destinations depending on factors like location, congestion, or link health.
  - Using any cast, a computer can send a datagram to a specific IP, but could see it routed to one of many different actual destinations (depending on a few factors).


### DNS and UDP

DNS is an *application layer* service, that uses UDP for the transport layer instead of TCP.

A single DNS request and its response can usually fit inside of a single UDP datagram, making it an ideal candidate for a connectionless protocol.

Using TCP would bog down the resolution process with nearly four times as much traffic.

- DNS listens on `port 53`.

DNS over TCP does exist, and is in use.
- With the Web growing more complex, sometimes a DNS lookup response can't fit within a single UDP datagram.
- In this case, a DNS name server would respond with a packet, explaining the response is too large.
- The DNS client would then establish a TCP connection to perform the lookup.

Since UDP doesn't have the concept of error recovery, the DNS resolver simply asks again if it doesn't get a response.


## Name Resolution in Practice

### Resource Record Types

DNS operates with a set of defined resource record types. They allow for different kinds of DNS resolutions to take place. (There are many, but here are a few of the most basic ones.)

#### A Record
- An **A record** is used to point a certain domain name at a certain IPv4 IP address.
  - At its most basic use, a single A record is configured for a single domain name.
  - A single domain name can have multiple A records, too.
    - This allows for *DNS round robin* to balance traffic across multiple IPs.

*Round robin* is a concept that involves iterating over a list of items, one by one, in an orderly fashion.
- The goal is to ensure an equal balance of each entry on the list that's selected.

- The **AAAA (Quad A)** is an emerging record type that's becoming more popular.
  - It's different from an A record in that it returns an IPv6 IP address.

#### CNAME Record
- A **CNAME record** is used to redirect traffic from one domain name to another.
- CNAMEs are useful, because they ensure you only have to change the canonical IP address of a server in one place.
  - CNAME is just shorthand for *canonical name*.
- An example of a CNAME is `microsoft.com` pointing to `www.microsoft.com`

#### MX Record
- **MX** stands for *mail exchange*.
- This resource record is used to deliver email to the correct server.
- Company web and mail servers often run on different machines (with different IPs);
  - The MX record ensures that email gets delivered to a company's mail server, while web traffic gets delivered to the web server.

#### SRV Record
- **SRV** stands for *service record*.
- It's used to define the location of various specific services.
- It serves the exact same purpose as the MX record;
  - But while the MX is only for mail services, the SRV can return the specifics of many different service types.

#### TXT Record
- **TXT** stands for *text*.
- It was originally intended for providing descriptive text for human consumption.
- Now, it's used to convey additional data intended for other computers to process.
  - It is free form, so clever engineers can use it to communicate data not originally intended to be communicated by a system like DNS.
- It's often used to communicate configuration preferences about network services, that you've entrusted other organizations to handle for your domain.


### Anatomy of a Domain Name

Any given domain name has 3 primary parts, and they all serve specific purposes.

#### Top Level Domain
- The **top level domain (TLD)** is the last part of a domain name--or top level domain.
- Administration and definition of TLDs is handled by the **Internet Corporation for Assigned Names and Numbers (ICANN)**.
  - ICANN is a sister organization to the IANA.
  - Together, they help define and control both the global IP spaces, along with the global DNS system.

#### Domain
- The **domain** is the second (or middle) part of a domain name.
- Domains are used to demarcate where control moves from a TLD name server, to an authoritative name server.

#### Subdomain
- The first (such as "www") portion is known as the **subdomain**.
- It's also known as the *host name*, if it's been assigned to only one host.
- Subdomains can be freely chosen and assigned by anyone who controls such a registered domain.

#### Fully Qualified Domain Name
- Combined, the subdomain, domain, and top level domain form a **fully qualified domain name (FQDN)**.
- DNS can support up to 127 levels of domain in total for a single fully qualified domain name.
- Each individual part of the domain name (sub, domain, top) can only be 63 characters long.
- A complete FQDN is limited to a total of 255 characters.


### DNS Zones

Authoritative name servers are responsible for responding to name resolution requests for specific domains; but they do more than that.

An authoritative name server is actually responsible for a specific DNS zone.

DNS zones are a hierarchical concept.
- The root name servers are responsible for the root zone;
- Each TLD name server is responsible for the zone covering its specific TLD;
- Authoritative name servers are responsible for fine-grained zones under that.

The root and TLD name servers are actually just authoritative name servers, too.

Zone's *don't* overlap.

The purpose of **DNS zones** is to allow for easier control over multiple levels of a domain.

- Zones are configured through **zone files**
  - These are simple configuration files, that declare all resource records for a particular zone.
- A zone file has to contain a **start of authority (SOA)** resource declaration.
  - This declares the zone and the name of the name server that is authoritative for it.
- Also often found is **NS records**, which indicate other name servers that might also be responsible for this zone.
- You'll also find A, AAAA, and CNAME records; along with default TTL values for the records served by this zone.
- Zones can be configured to go many layers deep; but do have a limit.
- You may also see **reverse lookup zone files**.
  - These let DNS resolvers ask for an IP and get the FQDN associated with it returned.
  - In these files, you'll find mostly pointer resource record declarations.
- A **pointer resource record (PTR)** resolves an IP to a name.



## Dynamic Host Configuration Protocol

### Overview of DHCP

Every single computer on a modern TCP/IP network needs to have at least four things configured:
1. IP address
2. Subnet mask
3. Primary gateway
4. Name server
- The subnet mask, primary gateway, and DNS server are likely the same on every node on the network.
  - But an IP address must be different for every single node on the network.

To handle the tricky configuration of these unique IP addresses, DHCP comes into play.

#### Dynamic Host Configuration Protocol (DHCP)
- DHCP is an application layer protocol that automates the configuration process of hosts on a network.
- Through DHCP, a machine can query a DHCP server when the computer connects to the network, and receive all the networking configuration in one go.
- DHCP reduces administrative overhead;
- It also solves the problem of having to choose what IP to assign to what machine.
  - This can help if local DNS servers are malfunctioning, since network administrators would still need to connect to devices (like routers) through IP address.

There are several standard ways DHCP can operate:

#### Dynamic Allocation
- This is the most common way.
- A range of IP addresses is set aside for client devices and one of these IPs is issued to these devices when they request one.
- Under dynamic allocation, the IP of a computer could be different almost every time it connects to the network.

#### Automatic Allocation
- Works similar to dynamic allocation (a range of IP addresses is set aside for assignment purposes).
- Big difference is the DHCP server is asked to keep track of which IPs it's assigned to certain devices in the past.
  - Using that info, the DHCP sever will assign the same IP to the same machine each time, if possible.

#### Fixed Allocation
- Requires a manually-specified list of MAC address and their corresponding IPs.
- When a computer requests an IP, the DHCP server looks for its MAC address in a table and assigns the IP that corresponds to that MAC address.
- If the MAC address isn't found, the DHCP server could fall back to another allocation method; or refuse to assign an IP altogether.
  - This can be used as a security measure, to ensure that only devices with configured MAC addresses will be able to communicate on the network.

You can also use DCHP to assign NTP servers.
- **Network time protocol (NTP) servers** are used to keep all computers on a network synchronized in time.


### DHCP in Action

The entire point of DHCP is to configure the network layer itself. This is despite DHCP being an application layer protocol, atop the TCP/IP hierarchy.

The process by which a client configured to use DHCP attempts to get network configuration information, is known as **DHCP discovery**.

#### DHCP Discovery
This process has four steps:
1. **Server discovery**
  - The DHCP client sends a *DHCPDISCOVER* message out onto the network;
  - This is a specially-crafted broadcast message, since the client lacks an IP address and doesn't know the IP address of the server.
  - DHCP listens on UDP `port 67`, and DHCP discovery messages are always sent from UDP `port 68`.
  - The message is encapsulated inside an IP datagram with a destination IP of `255.255.255.255`, and a source IP of `0.0.0.0`
  - The message is broadcast to every node on the local area network.
- When the DHCP server receives the message, it examines its own configuration, and decides which (if any) IP address to offer to the client.
  - The response is sent as a **DHCPOFFER** message with a destination port of `68`, a source port of `67`, a destination broadcast IP of `255.255.255.255`, and its actual IP as the source.

2. Offer
- The DCHP offer is broadcast to every machine on the network; but the original client recognizes the message is for itself.
  - This is because DHCPOFFER specifies the MAC address of the client that sent the DHCPDISCOVER message.
- The client processes the offer to see what IP is being offered to it.
- In theory, a client could reject this offer;
  - Multiple DHCP servers could be running on the same network, and a client could be configured to only respond to an offer of an IP within a certain range.

3. Request
- But usually, the client responds to the offer with a **DHCPREQUEST** message.
- This is again sent from an IP of `0.0.0.0` to `255.255.255.255` (since the client still doesn't have an assigned IP).

4. Acknowledgement
- The DHCP server responds with a **DHCPACK** acknowledgement message. 
  - The client recognizes the message by its MAC address in one of the message fields.
- Now the client computer's networking stack can use the configuration information presented to it by the DHCP server, to set up its own network layer configuration.
- At this point, the client should have all the info it needs to operate in a fully-fledged manner on the network it's connected too.

All of this configuration is known as the **DHCP lease**, as it includes an expiration time.
- This could last for days, or a short amount of time.
- Once a lease has expired, the DHCP client would need to negotiate a new lease by repeating the entire DHCP discovery process all over again.
- A client can also release its lease to the DHCP server, which it would do when it disconnects from the network.
  - This would also the DHCP server to return the IP address assigned back into the pool of available IPs to lease out.



## Network Address Translation

NAT is not a protocol, but a technique.

### Basics of NAT

#### Network Address Translation (NAT)**
A technology that allows a gateway--usually a router or firewall--to rewrite the source IP of an outgoing IP datagram, while retaining the original IP in order to rewrite it into the response.

Normally, a router would simply take an IP datagram, inspect the contents, decrement the TTL by 1, recalculate the checksum, and forward the rest of the data at the network layer (without touching it).

But with NAT, the router will also rewrite the source IP address. It will make the message look like it originated from the *router*, not the computer that sent it.

- The point of all this, is to hide the IP address of the computer sending the message. 
- This is known as **IP masquerading**, an important security concept.
  - No one can establish a connection to your computer, if they don't know what IP address it has.
- Through NAT, you could have hundreds of computers on a network, with all of their IPs being translated by a router into its own IP address;
  - This would effectively render the entire address space of the network as invisible;
  - This technique is known as **one-to-many NAT**.


### NAT and the Transport Layer

To solve the issue of one-to-many NAT, port preservation comes into play.

#### Port Preservation
- **Port preservation** is a technique where the source port chosen by a client is the same port used by the router.
- Remember that outbound connections choose a source port at random from the ephemeral ports. 
- In the simplest setup, a router set up to NAT outbound traffic will just keep track of what this source port is, and use that to direct traffic back to the right computer.

If two different computers on the same network booth choose the same source port at the same time, the router (normally) selects an unused port at random to use instead.

#### Port Forwarding
- **Port forwarding** is a technique where specific destination ports can be configured to always be delivered to specific nodes.
- This technique allows for complete IP masquerading, while still having services that can respond to incoming traffic.
  - It also simplifies how external users might interact with many services, all run by the same organization.


### NAT, Non-Routable Address Space and the Limits of IPv4

#### Address Blocks
The IANA has primarily been responsible for assigning address blocks to five **regional Internet registries (RIRs)**:
- AFRINIC, which serves the continent of Africa;
- ARIN, which serves the United States, Canada, and parts of the Caribbean;
- APNIC, which is responsible for most of Asia, Australia and New Zealand, and Pacific Island nations;
- LACNIC, which covers Central and South America, and Caribbean parts not covered by ARIN;
- RIPE, which serves Europe, Russia, the Middle East, and portions of Central Asia.

But they all ran out of IP addresses to distribute (all 4.2 billion of them).

#### Solution

Implementation of IPv6 will take time, so NAT and non-routable address space have been temporary solutions to the limits of IPv4.

- With NAT, you can have hundreds (even thousands) of machines using non-routable address space.
- Yet with just a single, public IP, all those computers can still send traffic to--and receive traffic from--the Internet.


## VPNs and Proxies

### Virtual Private networks

**Virtual private networks (VPN)** are a technology that allows for the extension of a private or local network to hosts that might not be on that local network.

The most common example of how VPNs are used is for employees to access their business's network, when they're not in the office.

- VPNs are a *tunneling protocol*.
  - This means they provision access to something not locally available.
  - When establishing a VPN connection, you'd refer to it as a VPN tunnel being established.

For example:
- An employee uses a VPN client to establish a VPN tunnel to their company network.
- This would provision their computer with what's known as a *virtual interface*, with an IP that matches the address space of the network they've established a VPN connection to.

- Most VPNs work by using the payload section of the transport layer to carry an encrypted payload that actually contains an entire second set of packets:
  - The network, the transport, and the application layers of a packet intended to traverse the remote network.
  - This process is inverse, relative to normal TCP/IP process.
- *"Basically, this payload is carried to the VPNs end point where all the other layers are stripped away and discarded. Then the payload is unencrypted, leaving the VPN server with the top three layers of a new packet. This gets encapsulated with the proper data link layer information and sent out across the network. This process is completed in the inverse, in the opposite direction. "*

VPNs usually require strict authentication procedures.
- VPNs were one of the first technologies where two-factor authentication became common.
- **Two-factor authentication** is a technique where more than just a username and password are required to authenticate.

VPNs can also be used to establish site-to-site connectivity.
- The concept isn't too different; one router establishes the VPN tunnel to the router on another network.
  - The two physically-separated offices are then able to act as one network, and access network resources across the tunnel.

Remember that like NAT, VPN is a technique, not a protocol. So the details can differ.

#### VPN Summary
VPNs are a technology that use encrypted tunnels to allow for a remote computer or network to act as if it's connected to a network that it's not actually physically connected to.


### Proxy Services

A **proxy service** is a server that acts on behalf of a client in order to access another service.

Proxies sit between clients and servers, providing an additional benefit:
- Anonymity
- Security
- Content filtering
- Increased performance

An example is of a proxy a gateway router.

A proxy is just an *abstraction* or concept.

"Proxy" is usually referring to a *web proxy*.
- These are proxies specifically built for web traffic.
  - These originally were to increase performance, in the days when Internet connections were much slower.
- A common use of a modern web proxy would be to prevent sites (like Twitter) from being accessed on a company's network.

Another example is a **reverse proxy**:
- A service that might appear to be a single server to external clients, but actually represents many servers living behind it.
- Much like the concept of DNS Round Robin, this is a form of load balancing.
- Reverse proxies are also used to deal with decryption.
  - EX: Clients -> Decryption Hardware -> Reverse Proxy -> Application Servers

#### Proxy Summary
Proxies are any server that act as an intermediary between a client and another server.


[Content](#content)
-------------------------------------------------------------------------------------------------Networking Servicess--------------------------------------------------------



# Networking Servicess

## POTS and Dial-Up

### Dial-up, Modems and Point-to-Point Protocols

- Early networking technologies mostly focused on connecting devices within close physical proximity to each other.
- In the late 1970s, two grad students at Duke University realized they could piggyback off the public telephone network.
  - The public telephone network is known as the **Public Switched Telephone Network (PSTN)**
  - Colloquially called the **Plain Old Telephone Service (POTS)**
- Those two Duke grads built the system known as USENET

#### Dial-Up

A **dial-up connection** uses POTS for data transfer, and gets its name because the connection is established by actually dialing a phone number.

- Transferring data across a dial-up connection is done through devices called modems.
- **Modem** stands for "modulator/demodulator"
  - It takes data that computers can understand, and turns them into audio wavelengths that can be transmitted over POTS.
- Early modems had very low baud rates.
  - A **baud rate** is a measurement of how many bits can be passed across a phone line in a second.
  - In the 1950s, the average baud rate was 110 bits per second
  - By the days of USENET, the rate had increased to 300 bps
  - And by the time dial-up became a household service in the 1990s, it was 14.4 kbps

Dial-up Internet connectivity is very rare today; but it hasn't gone extinct. Some rural areas use it as the only Internet option.


## Broadband Connections

### What is broadband?

**Broadband** is any connectivity technology that isn't dial-up Internet.
- It refers to connections that are always on.
  - They're long-lasting connections that don't need to be established with each use
  - Thus, they're links that are always present.

A single dial-up connection would quickly be oversaturated by just a few users. So businesses began using T-carrier technologies in the 1990s to meet bandwidth needs.

**T-carrier technologies** were originally invented by AT&T in order to transmit multiple phone calls over a single link.
  - These technologies require dedicated lines, which makes them more expensive (and generally only used by businesses).


### T-Carrier Technologies

T-carrier technologies were first invented by AT&T in order to provision a system that allowed *lots of phone calls to travel across a single cable*.
- Before then, every individual phone call was made over individual pairs of copper wire.
- Then came *Transmission System 1 (T1)*, the first T-carrier specification
  - With T1, AT&T invented a way to carry up to 24 simultaneous phone calls across a single piece of twisted-pair copper.
    - Years later, this same technology was repurposed for data transfers.
  - Each of the 24 phone channels was capable of transmitting data at 64 kbps;
    - Thus, a single T1 line was capable of transmitting data at 1.544 megabits per second
- Over the years, "T1" has come to mean any twisted-pair copper connection capable of speeds of 1.544 mbps, even if it doesn't strictly follow the original Transmission System 1 specification.

T1 technology originally was only used to connect different telecom company sites to each other; and to connect these companies to other telecom companies.
- But with Internet progression in the 1990s, more businesses adopted T1 lines.
- The T1 line was improved by weaving multiple T1s to act as a single link.
  - So a T3 line is 28 T1s, all multiplexed, achieving a total throughput speed of 44.7 mbps


### Digital Subscriber Lines

The twisted-pair copper wires used by telephone lines was capable of transmitting way more data than what was needed for voice-to-voice calls.

By operating at a frequency range that didn't interfere with normal phone calls, a technology known as **digital subscriber line (DSL)** was able to send much more data across the wire than traditional dial-up technologies.
- It also allowed for normal voice phone calls and data transfer to occur at the same time, on the same line.

#### DSLAM

DSL technologies also use their own modems: **digital subscriber line access multiplexers (DSLAM)**.
- Like dial-up modems, these devices establish data connections across phone lines;
- Unlike dial-up modems, they're usually long-running connections.
  - Generally a connection lasts from the moment the DSLAM is powered on, until the DSLAM is powered off.

Many types of DSL exist, but the two most common are ADSL and SDSL.
- **Asymmetric digital subscriber line (ADSL)** connections feature different speeds for outbound and incoming data.
  - This generally means faster download speeds and slower upload speeds.
- **Symmetric digital subscriber line (SDSL)** features upload and download connections with the same speed.
  - This connection type was originally used by businesses, who hosted servers; but is now common for the home user.
  - SDSL generally has an upper cap of 1.544 mbps (the same as a T1 line).
- Advancements in SDSL led to **high bit-rate digital subscriber lines (HDSL)**, which can transfer above 1.544 mbps.


### Cable Broadband

In the 1940s, cable television technologies were developed. The idea was to provide television access to remote towns and rural homes, which were beyond the broadcast range of the era's television towers.

In 1984, Congress passed The Cable Communications Policy Act, which changed everything.
- The act deregulated the cable television business in the United States;
  - This sparked a boom in growth and adoption; and the rest of the world followed suit.
- By the 1990s, cable television infrastructure was on-par with the public telephone system's.
- And cable providers soon became interested in becoming a part of the Internet growth.

Cable companies realized coaxial cables were capable of transmitting much more data than what was required for TV viewing (just like the phone industry realized).
- Cable companies began using frequencies that didn't interfere with TV broadcasts;
  - Cable-based, high-speed Internet was born.
- And this is the technology we refer to when we say **cable broadband**.

Cable Internet access is generally a shared bandwidth technology.
- With DSL or dial-up, the home/business connection goes directly to a **central office (CO)**.
  - A long time ago, COs were actual offices staffed with telephone switchboard operators.
  - COs have since become smaller pieces of automated hardware, that retained the name.
- Technologies connected to COs are guaranteed a certain amount of bandwidth, since it's point-to-point.
- Cable Internet technologies, on the other side, use a shared bandwidth model.
  - Many users share a certain amount of bandwidth until the transmissions reach the ISP's core network.
  - This could be anywhere from a city block to an entire subdivision.

Cable Internet connections are usually managed by a **cable modem**.
- This is a device that sits at the edge of a consumer's network and connects it to the **cable modem termination system (CMTS)**
  - The CMTS is what connects many different cable connections to an ISP's core network.


### Fiber Connections

- The absolute maximum distance an electrical signal can travel across a copper cable, before it degrades too much and requires a repeater, is thousands of feet.
- Fiber can travel many, many miles before signal degradation, by contrast.

Core Internet networks have used fiber for a long time, due to its high speed and low degradation distance. 
- Producing and laying fiber is much more expensive than using copper cables, so fiber was long only used by ISPs or data centers.
- But technology advancements has brought fiber closer and closer to the end user.

#### FTTX
**FTTX** stands for **fiber to the X**, where X can be one of many things:
- **Fiber to the neighborhood (FTTN)**
  - Data delivered to a single cabinet that serves a certain amount of the population.
  - From the cabinet, twisted-pair copper or coaxial cables might be used for the last length of distance.
- **Fiber to the building/business/basement (FTTB)**
  - A setup where fiber tech is used for data delivery to an individual building.
  - After that, twisted-pair copper is typically used to actually connect what's inside the building.
- **Fiber to the home (FTTH)**
  - Fiber is actually run to each individual residence in a neighborhood/apartment building.
- **Fiber to the premises (FTTP)**
  - This is another way of referring to FTTH *or* FTTB.

#### Optical Network Terminator (ONT)
- Instead of a modem, the demarcation point for fiber technologies is known as an **optical network terminator (ONT)**.
- An ONT converts data from protocols the fiber network can understand, to those that more traditional twisted-pair copper networks can understand.


## WANs

### Wide Area Network Technologies

**Wide Area Network (WAN)** acts like a single network, but spans across multiple physical locations.

- WAN technologies usually require a special link, contracted through your ISP.
  - The ISP handles sending your data from one site to the other;
  - So it's like all of your computers are in the same physical location.
- WANs work by using a variety of protocols at the data link layer, to transfer data from one site to another.
  - These protocols have much in common with core Internet routing protocols, instead of ethernet protocols.

WAN technologies are great for when you need to transport large amounts of data across lots of sites, because WAN tech is built to be super-fast.
- A business cable or DSL line are cheaper, but just can't handle the load required in these situations.

#### Example
- Imagine one network of computers on one side of the country; and another network of computers on the other.
- Each of those networks ends at a demarcation point, which is where the ISP's network takes over.
- The area between each demarcation point and the ISP's actual core network is called a **local loop**.
  - This local loop is similar to a T-carrier line, or a high-speed optical connection to the provider's regional office.
- From there it connects out to the ISP's core network and the Internet at large.


### Point-to-Point VPNs

Point-to-point VPNs are a popular alternative to WAN technologies.
- With the advent of cloud computing services, the expense of WAN technologies are becoming unnecessary.
- Instead, businesses are turning to point-to-point VPNs, so different sites can still communicate with each other.

A **point-to-point VPN**, also known as a **site-to-site VPN**, establishes a VPN tunnel between two sites.
- It operates much like how traditional VPN setup does;
- But the VPN tunneling logic is handled by network devices at either end, so user don't all have to establish their own connections.



## Wireless Networking

- Describe how wireless communication works
- What is the difference between infrastructure networks and ad hoc networks
- How do wireless channels help wireless networks operate
- Wireless security protocol basics


### Introduction to Wireless Networking Technologies

**Wireless networking** is a way to network without wires.

#### IEEE 802.11 Standards
- The most common specs for how wireless networking devices should communicate are defined by the IEEE 802.11 standards.
  - This set, also called the 802.11 family, make up the set of technologies we call **Wi-Fi**.
- Different 802.11 standards generally use the same protocol, but might operate at different frequency bands.

A **frequency band** is a certain section of the radio spectrum, that's been agreed upon to be used for certain communications.
  - EX: North American FM radio operates between 88 and 108 megahertz; this frequency band is called the FM broadcast band.
- Wi-Fi networks most commonly operate at the 2.4 gigahertz and 5 gigahertz bands.

The most common specifications are (in order of adoption):
- 802.11b
- 802.11a
- 802.11g
- 802.11n
- 802.11ac

Naturally, each newer version of the specs is an improvement over the predecessor.

802.11 defines how we operate at both the physical and data link layer.

#### 802.11 Frames
An 802.11 frame has several fields:
- First is the **frame control field**, a 16-bit field divided into sub-fields, used to describe how the frame itself should be processed.
  - Which version of 802.11 was used, etc.
- Next is the **duration field**
  - It specifies how long the total frame is, so the receiver knows how long it should listen to the transmission.
- Then come four 6-bit long **address fields**:
  - Source address field (the MAC address of the sending device)
  - Intended network destination (on the network)
  - Receiving address (the MAC address of the access point that should receive the frame)
  - Transmitter address (the MAC address of whatever has just transmitted the frame)
    - Often, the destination and receiver addresses may be the same; and the source and transmitter addresses are also often the same.
- Between the third and fourth address field is the **sequence control field*
  - A 16-bit long field containing the sequence number used to keep track of ordering the frames.
- Then comes the **data payload** section
  - Which has all of the data of the protocols further up the stack.
- Finally comes the **frame check sequence** field
  - It contains a checksum for a cyclical redundancy check, just like how Ethernet does it.

#### Alphabet Soup
Networks that operate on the 5Ghz band are almost always faster, but have less of a range.

Most 2.4Ghz networks are slightly slower and more susceptible to interference, but cover a larger area.


### Wireless Network Configurations

There are a few main ways a wireless network can be configured:
- Ad-hoc networks
  - Where nodes all speak directly to each other
- Wireless LANs (WLANs)
  - Where one or more acmes points act as a bridge between a wireless and a wired network
- Mesh networks
  - A hybrid of ad-hoc and WLAN

#### Ad-hoc networks
- The simplest of the three
- No real supporting network infrastructure
- Every device involved with the network communicates with every other device within range, and all nodes help pass along messages

#### Wireless LANs (WLANs)
- The most common type of wireless network in the business world
- Consists of one ore more access points, which act as bridges between the wireless and wired networks.
- The wired network operates as a normal LAN; 
  - Wireless devices communicate with access points; 
  - Then they forward traffic to the gateway router, where everything proceeds as normal.

#### Mesh networks
- Similar to ad-hoc networks, since lots of the devices communicate with each other wirelessly (forming a *mesh*)
- Most mesh networks are made of only wireless access points, still connected to a wired network
- This kind of network lets you deploy more access points to the mesh, without having to run a cable to each of them
- This setup allows for increasing the performance and range of a wireless network.


### Wireless Channels

**Channels** are individual, smaller sections of the overall frequency band used by a wireless network.

- Channels are important because they address collision domains.
  - Remember that a **collision domain** is any one network segment where one computer can interrupt another.
- Switches are devices that solve the problem of collision domains, on wired networks.
  - But wireless networks don't have switches.
- Channels help fix this problem, to a certain extent.

Radio waves are imprecise things, so you need some buffers around what exact frequencies a transmission might actually arrive on.
- Some channels overlap, but some are far enough apart so they won't interfere with each other at all.
- Most wireless networking equipment today can auto-sense what channels are most congested.
  - Some access points will only perform this analysis on startup;
  - Others will dynamically change their channel as needed

The key point of channels is avoid collision domains wherever you can. Optimize wireless network deployments, and make sure both your own access points and those of neighboring businesses overlap channels as little as possible.


### Wireless Security

Wireless networking lacks the physical security measures of wired networking. In theory, anyone can intercept any wireless transmission. Enter WEP.

**Wired Equivalent Privacy (WEP)** is an encryption technology that provides a very low level of privacy.
- WEP is only as safe as sending unencrypted data over a wired connection.
- The WEP standard is a weak encryption algorithm, at only 40 bits for its keys.
- WEP was quickly replaced by WPA.

**Wi-Fi Protected Access (WPA)** was an improvement over WEP.
- WPA uses a 128-bit key, making it more difficult to crack.
- It was improved to a better specification: WPA2.

**WPA2** is today's wireless networking security standard.
- It uses a 256-bit key

Another way to help secure wireless networks is through MAC filtering.

**MAC filtering** configures access points to only allow for connections from a specific set of MAC addresses, belonging to trusted devices.


### Cellular Networking

Cellular networking--also called mobile networking--is becoming a predominant wireless networking method.

Cellular networks have much in common with 802.11 networks, featuring many specifications.

Just like Wi-Fi, cellular networks operate over radio waves, with specific frequency bands specifically reserved for cellular transmissions.

But what's different is cellular transmission frequencies can travel over longer distances more easily, usually over many miles.

Cellular networks are built around the concept of *cells*.
- Each cell is assigned a specific frequency band for use.
- Neighboring cells are set up to use bands that don't overlap 
  - (Like how an optimal WLAN is setup with multiple access points.)
- A good way to think of cell towers that broadcast and receive transmissions is as *access points*
- Cellular networks aren't reserved for only phones
  - Tablets, laptops, and even automobiles feature cellular antennas.


### Mobile Device Networks

Mobile devices use wireless networks to communicate with the Internet and other devices.
This can include:
- Cellular networks
- Wi-Fi
- Bluetooth
- Internet of Things network protocols

Mobile devices tend to use *non-metered connections* when available, to save on expenses.




#### Bluetooth Pairing
- Mobile devices connect to their peripherals using short-range wireless networks.
- The most common of these is called **Bluetooth**.
- This connection is called *pairing* the devices:
  - The two devices exchange information (sometimes a PIN or password) so they can remember each other.
  - From then on, the devices will automatically connect to each other when they're both powers on and in range.
  - Pairing can sometimes fail, and may require making the device forget the peripheral so it can be paired again.


[Content](#content)

---------------------------------------------------------------------------------------------Troubleshooting--------------------------------------------------------------------------------------

# Troubleshooting and the Future of Networking

### Intro
Protocols and devices feature built-in functionalities to help protect against issues. These functionalities are known as error detection and error recovery.
- **Error detection** is the ability for a protocol or program to determine that something went wrong.
- **Error recovery** is the ability for a protocol or program to attempt to fix it.


## Verifying Connectivity

### Ping: Internet Control Message Protocol

#### Internet Control Message Protocol (ICMP)
ICMP is mainly used by a router or remote host, to communicate why a transmission has failed, back to the origin of the transmission.

The makeup of an ICMP packet is a header and a data section:
- The first field is the **type field**, 8 bits long and specifying what type of message is being delivered.
  - Examples include `destination unreachable`, `time exceeded`, etc.
- Then comes the 8-bit **code field**, which indicates a more specific reason for the message than just the type.
  - Example: `destination network unreachable`, `destination port unreachable`, etc
- Next is a 16-bit checksum.
- Then the **rest of header** field, an optional 32-bit field.
  - Used to send more data by specific types and codes.
- Then the **data payload** for the ICMP packet.

The payload for an ICMP packet exists entirely so that the recipient of the message knows which of their transmissions caused the error being reported.
- It contains the entire IP header;
- And the first 8 bytes of the data payload section of the offending packet.

#### Ping
ICMP wasn't designed to be human-readable; it was intended for computers.

That's where ping comes into play.

- **Ping** lets you send a special type of ICMP message called an **Echo Request**.
  - If the destination is up and running and able to communicate on the network, it'll send back an ICMP **Echo Reply** message type.

Ping exists on basically every operating system.
- On Windows, Ping defaults to only four Echo requests.
- On MacOS and Linux, Ping will run forever until it's interrupted by the user inputs an interrupt event.
  - This is done with `^C`


### Traceroute

**Traceroute** is a utility that lets you discover the path between two nodes, and gives you information about each hop along the way.

This covers connections at the network layer.

- Traceroute uses the TTL field, setting it to 1 for the first ICMP packet; then 2 for the second; and so on.
- On Linux and MacOS, trace route sends UDP packets to very high port numbers.
- On Windows--the command is `tracert`--defaults to the ICMP echo request.

There are two other, long-running tools similar to traceroute:
- `mtr` on Linux and MacOS
  - Works in real time, and will continually update its output with all the current aggregate dta about the traceroute;
- `pathping` on Windows
  - Runs for 50 seconds and then displays the final aggregate data all at once.


### Testing Port Connectivity

There are two powerful tools to test connectivity at the transport layer:
- Netcat on Linux and MacOS,
- Test-NetConnection on Windows

#### Netcat
- The **Netcat** tool can be run through the command `nc` and has two mandatory arguments:
  1. A host;
  2. And a port.
- If the connection succeeds, the blinking cursor will await more input.
  - This is a way to actually send application layer data to the listening service from your own keyboard.
- If you're only curious about the status of a report, you can issue the command with the `-z` flag
- Or you can use the `-v` flag to issue a Verbose command
  - This makes the command output useful to human eyes
    - (This is opposed to non-verbose output, which is best for usage in scripts.)
- By issuing a command with the -z and -v flags, the command's output will simply tell you if a connection to the port in question is possible or not.

#### Test-NetConnection
- If you run Test-NetConnection with only a host specified, it will default to using an ICMP echo request (much like ping)
  - But it displays way more data than a ping, including the data link layer protocol being used
- Issuing Test-NetConnection with the `-port` flag, you can ask it to test connectivity to a specific port


## Digging into DNS

### Name Resolution Tools

The most common command line tool for investigating domain name resolution is **nslookup**

- `nslookup` is available on MacOS, Linux, and Windows
- Execute the command with the host name following it:
  - The output displays what server was used to perform the request and resolution result.
- The tool also features an interactive mode, to search for additional options and run many more queries.
  - Enter interactive mode by running `nslookup` without any host name following it;
  - The angle bracket will act as your prompt
    - You can ask for A records, AAAA records, MX records, or even txt records associated with the host.
    - This is done by entering `set type=` followed by a resource record type.
    - Or enter `set debug` to display the full response packets (though this is a lot of data)


### Public DNS Servers

An ISP almost always give you access to a recursive name server, as part of the server it provides.

Some Internet organizations run what are called public DNS servers.
- **Public DNS servers are name servers specifically set up so that anyone can use them, for free.
- Level 3 Communications has run arguably the most commonly-used public DNS servers
  - They range from `4.2.2.1` through `4.2.2.6`
- Google also operates public DNS servers
  - These are at `8.8.8.8` and `8.8.4.4`
- Most public DNS servers also respond to ICMP echo requests, so they're a good choice for testing general Internet connectivity using ping.

Always research before configuring any of your devices to public DNS servers, as crackers can easily hijack outbound DNS requests with faulty responses (which lead to malicious sites).


### DNS Registration and Expiration

A **registrar** is an organization responsible for assigning individual domain names to other organizations or individuals.

Originally, there were few registrars, with the most notable being Network Solutions Inc.

The U.S. government and Network Solutions Inc. came to an agreement to let other companies also sell domain names.


### Hosts Files

The original way that numbered network addresses were correlated with words, was through hosts files.

A **hosts file** is a flat file that contains, on each line, a network address followed by the host name it can be referred to as.
- For example, a line might read: 1.2.3.4 webserver
  - This means that oon the computer where this hosts file resides, a user could just refer to "webserver" instead of the IP address.
  - A user could just type "webserver" into a web browser's URL bar, or could issue a Ping webserver command and it would be translated to the IP address.

Hosts files are old, but all modern operating systems (including mobile) stil have hosts files
- This is because of a special IP address: The loopback address.
- A **loopback address** always points to itself, so a loopback address is a way of sending network traffic to yourself.
- Sending traffic to a loopback address bypasses all network infrastructure itself and traffic like that never leaves the node.

Almost every hosts file in existence will, in the very least, contain a line that reads `127.0.0.1 localhost`, most likely followed by `::1 localhost`, where ::1 is the loopback address for IPv6.

Also, hosts files are a popular way for computer viruses to disrupt and redirect users' traffic.

- Hosts files are examined before a DNS resolution attempt occurs on almost every major operating system
- This lets you force an individual computer to think a certain domain name always points to a specific IP


## The Cloud

### What is The Cloud?

The cloud isn't a single technology, or invention, or anything tangible at all.

**Cloud computing** is a technological approach where computing resources are provisioned in a shareable way, so that lots of users get what they need, when they need it.

#### Virtualization
- At the heart of cloud computing is a technology known as hardware virtualization
- Hardware virtualization is a core concept of how cloud computing technologies work
  - It allows the concept of a physical machine and a logical machine to be abstracted away from each other.
- With **virtualization**, a single physical machine, called a "host," could run many individual virtual instances, called "guests."
- Hardware virtualization platforms employ what's called a hypervisor.

A **hypervisor** is a piece of software that runs and manages virtual machines, while also offering these guests a virtual operating platform that's indistinguishable from actual hardware.

- Through virtualization, a single physical computer can act as the host for many independent virtual instances
- They each run on their own independent operating system and, in many ways, are indistinguishable from the same operating systems running on the physical hwrdware.
- The cloud takes this concept one step further.

#### Cloud Computing

A **public cloud** is a large cluster of machines run by another company.

A **private cloud** is used by a single large corporation, and generally physically hosted on its own premises.

A **hybrid cloud** is a term used to describe situations where companies might run things like their most sensitive proprietary technologies on a private cloud; while entrusting their less-sensitive servers to a public cloud.

In summary, cloud computing is a new model in computing where large clusters of machines let us use the total resources available in a better way.


### Everything as a Service

Anothe rterm used more and more with the rise of cloud computing is *X as a service*, where X stands for many different things.

#### Infrastructure as a Service (IaaS)
- The idea behind IaaS is you shouldn't have to worry about building your own network, or your own servers.
- You just pay someone else to provide you with that service.

#### Platform as a Service
- A subset of cloud computing, where a platform is provided for customers to run their services
- This basically means that an execution engine is provided for whatever software someone wants to run

#### Software as a Service
- While IaaS abstracts away the physical infrastructure you need; and PaaS abstracts the server instances you need;
- SaaS is essentially a way of licensing the use of software to others while keeping that software centrally-hosted and managed
  - An example would be email, such as Gmail (by Google) or Office 365 Outlook (by Microsoft)

More and more, the point of a business's network is just to provide an Internet connection to access different software or data in the cloud.


### Cloud Storage

In a **cloud storage system**, a customer contracts a cloud storage provider to keep their data secure, accessible, and available.

- Abstract away managing a storage array, and hardware issues
- Available across many geographic regions
  - This provides protection against data loss
- Grows with you, managing your expenses for what you actually need


## IPv6

### IPv6 Addressing and Subnetting

- The biggest difference between IPv4 and IPv6 is the number of bits reserved for an address.
  - IPv4 addresses are 32 bits; so there can be around 4.2 billion individual addresses;
  - IPv6 addresses are 128 bits in size; this is an unfathomable, 39 digit-long number.

- IPv6 addresses are usually written out as 8 groups of 16-bits each. 
  - These groups are further made up of four hexadecimal numbers.
- But the full IPv6 address is still way too long and unwieldy, so there is a notation that breaks them down even more:

There are two rules for shortening an IPv6 address:
1. You can remove any leading zeroes from a group.
2. Any number of consecutive groups composed of just zeroes can be replaced with two colons.
  - This can only happen once, for any specific address
  - Otherwise, you couldn't know exactly how many zeroes were replaced by the double colons.

The IPv6 loopback address is thirty-one 0s with a 1 at the end; which can be condensed to `::1`.

#### Reserved Spaces
- `2001:0db8` is reserved for documentation and education
- `FF00::` is reserved for multicast
  - **Multicast** is a way of addressing groups of hosts all at once
- `FE80::` are used for link-local unicast
  - **Link-local unicast addresses** allow for local network segment communications and are configured based upon a host's MAC address
    - Used by an IPv6 host to receive their network configuration (much like how DHCP works)
    - The host's MAC address is run through an algorithm to turn it from a 48-bit number into a unique 64-bit number;
    - Then it's inserted into the address's host ID.

#### Address Classes
These don't exist in IPv6, since the vast address space doesn't need them.

The first 64-bits of any IPv6 address is the network ID; and the second 64-bits of any IPv6 address is the host ID.


#### Subnetting
- IPv6 uses the same CIDR notation as IPv4.
- This is used to define a subnet mask against the network ID portion of an IPv6 address.


### IPv6 Headers

One of the more elegant improvements of IPv6 was in its header:
- The first field is the **version field**
  - A 4-bit field that defines what version of IP is in use
- The next field is the **traffic class** field
  - This is an 8-bit field that defines the type of traffic contained within the IP datagram, and allows for different classes of traffic to receive different priorities.
- Next is the **flow label field**
  - A 20-bit field that's used in conjunction with the traffic class field, for routers to make decisions about the quality of service level for a specific datagram.
- Next is the **payload length field**
  - A 16-bit field that defines how long the data payload section of the datagram is
- Then the **next header field**
  - A unique concept to IPv6
  - The IPv6 header was built to be as short as possible; this was accomplished by abstracting away many of the optional header fields from IPv4
  - The **next header field** allows to chain together different header fields, if there is a lot of optional configuration.
- Next is the **hop limit field**
  - An 8-bit field that's identical in purpose to the TTL field in an IPv4 header
- Finally come the **source address** and **destination address** fields
  - These are each 128 bits
- If the next header field specified another header, it would follow at this time.
- If not, a data payload (the same length as specified in the payload length field) would follow.


### IPv6 and IPv4 Harmony

The IPv6 specs have set aside a number of addresses that can be directly correlated to an IPv4 address.
- Any IPv6 address that begins with 80 zeroes, and is then followed by 16 ones, is understood to be part of the IPv4 mapped address space
- The remaining 32 bits of the IPv6 address is just the same 32 bits of the IPv4 address it's meant to represent.

IPv6, during its adoption, will need a way to travel over the old IPv4 remnants of the Internet backbone.
- This is being achieved with **IPv6 tunnels**
- They consist of IPv6 tunnel servers, on each side of a connection.
- **IPv6 tunnel** servers take incoming IPv6 traffic and encapsulate it within traditional IPv4 datagrams.
- This is then delivered across the IPv4 Internet space, where it's received by another IPv6 tunnel server
- That server de-encapsulates the datagram and passes the IPv6 traffic further along the network.

#### IPv6 tunnel broker
These are companies that provide IPv6 tunneling endpoints for you, so you don't have to introduce additional equipment to your network.

[Content](#content)