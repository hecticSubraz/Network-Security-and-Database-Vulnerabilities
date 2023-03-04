
# 30 days of Network security and Database vulnerabilities
I will be learning Network security and Database vulnerabilities for 30 days and I will be updating daily about my progress and understanding.

# Day 1 of #Network security and Database vulnerabilities 
## Introduction to TCP/IP 
 Today I learned  about TCP/IP protocol as well as model, how was it  developed and its different layers used in network communication communication.
 
### TCP/IP
TCP/IP stands for Transmission Control Protocol/Internet Protocol and is a suite of communication protocols used to interconnect network devices on the internet. TCP/IP is also used as a communications protocol in a private computer network (an intranet or extranet).

### History of TCP/IP
* TCP/IP protocol suite, was designed in 1970s by 2 DARPA scientists—Vint Cerf and Bob Kahn.
 * In 1973, they started researching  on reliable data communications across packet radio networks, factored in lessons learned from the Networking Control Protocol, and then created the next generation Transmission Control Protocol (TCP), the standard protocol used on the Internet today.
* The early versions of this technology was only one core protocol, which was named TCP. 
* The first version of this predecessor of modern TCP was written in 1973, then revised and formally documented in RFC 675, Specification of Internet Transmission Control Program from December 1974.

### TCP/IP model and its layers
There are four layers of the TCP/IP model: network access, internet, transport, and application. Used together, these layers are a suite of protocols. The TCP/IP model passes data through these layers in a particular order when a user sends information, and then again in reverse order when the data is received.

![TCP/IP model](https://www.guru99.com/images/1/093019_0615_TCPIPModelW1.png)
#### Network Access layer(Layer 1):
* It is a group of applications requiring network communications
* Responsible for generating the data and requesting connections
* Acts on behalf of the sender and the Network Access layer on the behalf of the receiver 
* TCP/IP is identified by the this layer
* Error prevention and “framing” are also provided by this  layer
#### Internet layer(Layer 3):
* parallels the functions of OSI’s Network layer
* defines the protocols which are responsible for the logical transmission of data over the entire network
* protocals such as IP,ICMP and ARP lies in this layer
#### Transport layer(Layer 4):
* exchange data receipt acknowledgments and retransmit missing packets to ensure that packets arrive in order and without error  
* protocals such as TCP and UDP are used in this layer
#### Application layer( Layer 5):
* responsible for end-to-end communication and error-free delivery of data
* shields the upper-layer applications from the complexities of data

# Day 2 of #Network security and Database vulnerabilities 
## Networking fundamentals and its security
 Today I learned  about networking fundamentals and  basic concepts of network security 
 
## Computer Network
A Computer Network is defined as a set of two or more computers that are linked together either via wired cables or wireless networks i.e., WiFi with the purpose of communicating, exchanging, sharing or distributing data, files and resources

## Computer network types
There are different types of computer network used in todays world.
Here we disscussed about important computer network types used in todays world.
### Local Area Network(LAN)
* Group of devices connecting the computers and other devices such as switches, servers, printers etc over a short distance such as office, home and so on.
* The most commonly used LAN is Ethernet LAN
### Wireless Local Area Network(WLAN)
* similar to LAN with the difference that it uses wireless communication between devices instead of wired connections
* WLAN typically involves a Wi-Fi router or wireless access point for devices, unlike smartphones, laptops, desktops etc.
### Campus Area Network(CAN)
* It is a closed corporate communication network
* A CAN is a mobile network that may contain a private or public part
* widely used colleges, academies, and corporate sites
### Metropolitian Area Network(MAN)
* Typically a more extensive network when compared to LANs 
* Network ranges between several buildings in the same city
*  Man networks are connected via fiber optic cable (usually high-speed connection)
### Personal Area Network(PAN)
* type of network used personally and usually serves one person 
* usually connects devices unlike your smartphones, laptop, or desktop to sync content and share small files, unlike songs, photos, videos, calendars, etc. 
* These devices connect via wireless networks such as Wi-Fi, Bluetooth, Infrared.
### Storage Area Network(SAN)
* specialized high-speed network that stores and provides access to block-level storage 
* dedicated shared network that is used for cloud data storage that appears and works like a storage drive
* consists of various switches, servers, and disks array 
* it is fault-tolerant, which means if any switch or server goes down, the data can still be accessed
### Virtual Private Network(VPN)
* secure tool that encrypts point-to-point internet connection and hides the user's IP address and virtual location 
* determines an encrypted network to boost user's online privacy so as their identity and data are inaccessible to hackers
### Wide Area Network(WAN)
* the most significant network type connecting computers over a wide geographical area, such as a country, continent 
* includes several LANs, MANs, and CANs
* the Internet, which connects billions of computers globally  is also a example of WAN

## Networking terms
1. ### IP address
A unique number that represents the address where you live on the Internet.Every device that is connected to the network has a string of numbers or IP addresses unlike house addresses
 When your computer sends data to another different, the sent data contains a 'header' that further contains the devices' IP address, i.e., the source computer and the destination device.

2. ### Nodes
A node refers to a networking connection point where a connection occurs inside a network that further helps in receiving, transmitting, creating, or storing files or data.Multiple devices could be connected to the Internet or network using wired or wireless nodes. To form a network connection, one requires two or more nodes where each node carries its unique identification to obtain access, such as an IP address. Some examples of nodes are computers, printers, modems, switches, etc.

3. ### Routers
A router is a physical networking device, which forwards data packets between networks. Routers do the data analysis, perform the traffic directing functions on the network, and define the top route for the data packets to reach their destination node. A data packet may have to surpass multiple routers present within the network until it reaches its destination.

4. ### Switches
Switch is a device that connects other devices and helps in node-to-node communication by deciding the best way of transmitting data within a network (usually if there are multiple routes in a more extensive network).Switches forwards data between nodes present in a single network.Switching is further classified into three types, which are as follows:
##### Circuit Switching: 
A secure communication path is established between nodes (or the sender and receiver) in a network. It establishes a dedicated connection path before transferring the data, and this path assures a good transmission bandwidth and prevents any other traffic from traveling on that path. For example, the Telephone network.
#### Packet Switching: 
A message is broken into independent components known as packets. Because of their small size, each packet is sent individually. The packets traveling through the network will have their source and destination IP address.
#### Message Switching: 
It uses the store and forward mechanism. It sends the complete unit of the message from the source node, passing from multiple switches until it reaches its intermediary node. It is not suitable for real-time applications.

5. ### Ports
A port allows the user to access multiple applications by identifying a connection between network devices. Each port is allocated a set of string numbers. If you relate the IP address to a hotel's address, you can refer to ports as the hotel room number. Network devices use port numbers to decide which application, service, or method is used to forward the detailed information or the data.

6. ### Network cable types
Network cables are used as a connection medium between different computers and other network devices. Typical examples of network cable types are Ethernet cables, coaxial, and fiber optic. Though the selection of cable type usually depends on the size of the network, the organization of network components, and the distance between the network devices.

## Network Topology
"Network topology is defined as the arrangement of computers or nodes of a computer network to establish communication among all."

1. ### Bus Topology
* supports a common transmission medium where each node is directly connected with the main network cable.
* data is transmitted through the main network cable and is received by all nodes simultaneously.
* signal is generated through the source machine, which contains the address of the receiving machine. The signal travels in both the direction to all the nodes connected to the bus network until it reaches the destination node.
* Bus topology is not fault-tolerant and has a limited cable length.
2. ### Ring Topology
* modified version of bus topology where every node is connected in a closed-loop forming peer-to-peer LAN topology.
* Every node in a ring topology has precisely two connections. The Adjacent node pairs are connected directly, whereas the non-adjacent nodes are indirectly connected via various nodes.
* Ring topology supports a unidirectional communication pattern where sending and receiving of data occurs via TOKEN
3. ### Star Topology
* every node is connected using a single central hub or switch.
* The hub or switch performs the entire centralized administration. Each node sends its data to the hub, and later hub shares the received information to the destination device.
* Two or more-star topologies can be connected to each other with the help of a repeater.
4. ### Mesh Topology
* every node in the network connection is directly connected to one other forming overlapping connections between the nodes.
* delivers better fault tolerance because if any network device fails, it won't affect the network, as other devices can transfer information
* Mesh networks self-configure and self-organize, finding the quickest, most secure way to transmit the data
## Network security
Network Security involves access control, virus and antivirus software, application security, network analytics, types of network-related security (endpoint, web, wireless), firewalls, VPN encryption and more

### Types of Network security
### Firewall
Firewalls control incoming and outgoing traffic on networks, with predetermined security rules. Firewalls keep out unfriendly traffic and is a necessary part of daily computing. Network Security relies heavily on Firewalls, and especially Next Generation Firewalls, which focus on blocking malware and application-layer attacks.

### Network Segmentation
Network segmentation defines boundaries between network segments where assets within the group have a common function, risk or role within an organization. For instance, the perimeter gateway segments a company network from the Internet. Potential threats outside the network are prevented, ensuring that an organization’s sensitive data remains inside. Organizations can go further by defining additional internal boundaries within their network, which can provide improved security and access control.



