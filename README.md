
# 30 days of Network security and Database vulnerabilities
I will be learning Network security and Database vulnerabilities for 30 days and I will be updating daily about my progress and understanding.

- [Day 1](#Day-1)
- [Day 2](#Day-2)
- [Day 3](#Day-3)
- [Day 4](#Day-4)
- [Day 5](#Day-5)
- [Day 6](#Day-6)
- [Day 7](#Day-7)
- [Day 8](#Day-8)
- [Day 9](#Day-9)
- [Day 10](#Day-10)
- [Day 11](#Day-11)
- [Day 12](#Day-12)
- [Day 13](#Day-13)
- [Day 14](#Day-14)

# Day 1
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

# Day 2 
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

# Day 3
## Inspection and Firewall Filters
 Today I learned  about basic of types of inspection in the packets and general knowledge of firewall filters and its difference 
 
## Packets
A packet normally represents the smallest amount of data that can traverse over a network at a single time. Generally a  TCP/IP network packet contains several pieces of information, including the data it is carrying, source destination IP addresses, and other constraints required for quality of service and packet handling.
## Inspection
Inspection is a process in which a outgoing packet or incomming packet  is being inspected either it is harmful or not, has destination and source address or not with the help of firewall.
Generally there are two types of Inspection
### Stateless Inspection:
Stateless inspection is the process of inspection in which it doesn’t track individual connections  sessions but makes a “go  no go” decision on a packet-by-packet basis. It’s better for stopping certain types of DDoS attacks (i.e. TCP-state exhaustion) and blocking reputational-based IoCs in bulk.
### Stateful Inspection
Stateful inspection is a process in which it monitors the state of active connections and uses this information to determine which network packets to allow through the firewall.
## Firewall Filters 
Generally there are two types of firewall filters which are discussed below
### Intrusion Detection System(IDS)
An Intrusion Detection System (IDS) is a monitoring system that detects suspicious activities and generates alerts when they are detected. Based upon these alerts, a security operations center (SOC) analyst or incident responder can investigate the issue and take the appropriate actions to remediate the threat.An IDS is designed to detect a potential incident, generate an alert, and do nothing to prevent the incident from occurring. While this may seem inferior to an IPS, it may be a good solution for systems with high availability requirements, such as industrial control systems (ICS) and other critical infrastructure. For these systems, the most important thing is that the systems continue running, and blocking suspicious (and potentially malicious) traffic may impact their operations. Notifying a human operator of the issue enables them to evaluate the situation and make an informed decision on how to respond.
### Intrusion Prevention System(IPS)
An intrusion prevention system (IPS) is a network security tool (which can be a hardware device or software) that continuously monitors a network for malicious activity and takes action to prevent it, including reporting, blocking, or dropping it, when it does occur.As malware attacks become faster and more sophisticated, this is a useful capability because it limits the potential damage than an attack can cause. An IPS is ideal for environments where any intrusion could cause significant damage, such as databases containing sensitive Datas.
### Difference betwen IDS and IPS are as follows
The  difference between Intrusion Detection system and intrusion Prevention System (IDS/IPS) technology in computer network is  IDS are out of band in system, means it cannot sit within the network path but IPS are in-line in the system, means it can pass through in between the devices.IDS generates only alerts if anomaly traffic passes in network traffic, it would be false positive or false negative, means IDS detects only malicious activities but no action taken on those activities but IPS has feature of detection and prevention with auto or manual action taken on those detected malicious activities like drop or block or terminate the connections. Here IDS and IPS systems stability, performance and accuracy wise result.

# Day 4
## Ethernet and LAN-Ethernet operations
 Today I learned  about working principle of Ethernet networks, collision domain and  Broadcast domain,Network Segmentation and its working principle,Virtual LAN and its working principle and  addressing scheme and IP scheme in modern networks.
 
### Ethernet Network:
Ethernet is the traditional technology for connecting devices in a wired local area network (LAN) or wide area network (WAN). It enables devices to communicate with each other via a protocol, which is a set of rules or common network language.

#### Working principle of Ethernet:
Ethernet works by breaking up information being sent to or from devices like a personal computer into short pieces of different sized bits of information called frames. Those frames contain standardized information such as the source and destination address that helps the frame route its way through a network.
Computers on a LAN typically shared a single connection, Ethernet was built around the principal of CSMA/CD, or carrier-sense multiple access with collision detection. Basically, the protocol makes sure that the line is not in use before sending any frames out. Today, that is far less important than it was in the early days of networking because devices generally have their own private connection to a network through a switch or node. And because Ethernet now operates using full duplex, the sending and receiving channels are also completely separate, so collisions can’t actually occur over that leg of their journey.

### Collision Domain 
A collision domain is a network segment connected by a shared medium or through repeaters where simultaneous data transmissions collide with one another. The collision domain applies particularly in wireless networks, but also affected early versions of Ethernet. A network collision occurs when more than one device attempts to send a packet on a network segment at the same time. Members of a collision domain may be involved in collisions with one another. Devices outside the collision domain do not have collisions with those inside.

### Broadcast Domain
A broadcast domain is a logical division of a computer network, in which all nodes can reach each other by broadcast at the data link layer. A broadcast domain can be within the same LAN segment or it can be bridged to other LAN segments.Any computer connected to the same set of interconnected switches/repeaters is a member of the same broadcast domain. Routers and other higher-layer devices form boundaries between broadcast domains.

### Network Segmentation
Network segmentation is an architectural approach that divides a network into multiple segments or subnets, each acting as its own small network. This allows network administrators to control the flow of network traffic between subnets based on granular policies. Organizations use segmentation to improve monitoring, boost performance, localize technical issues and – most importantly – enhance security.

Let us imagine a large bank with several branch offices. The bank's security policy restricts branch employees from accessing its financial reporting system. Network segmentation can enforce the security policy by preventing all branch traffic from reaching the financial system. And by reducing overall network traffic, the financial system will work better for the financial analysts who use it.

#### working principle:
Segmentation works by controlling how traffic flows among the parts. You could choose to stop all traffic in one part from reaching another, or you can limit the flow by traffic type, source, destination, and many other options. How you decide to segment your network is called a segmentation policy.

### Virtual Local Area Network(VLAN)
VLAN is a custom network which is created from one or more local area networks. It enables a group of devices available in multiple networks to be combined into one logical network. The result becomes a virtual LAN that is administered like a physical LAN.

Without VLANs, a broadcast sent from a host can easily reach all network devices. Each and every device will process broadcast received frames. It can increase the CPU overhead on each device and reduce the overall network security.

#### working principle of VLAN
Adding virtual LAN (VLAN) support to a Layer 2 switch offers some of the benefits of both bridging and routing. Like a bridge, a VLAN switch forwards traffic based on the Layer 2 header, which is fast. Like a router, it partitions the network into logical segments, which provides better administration, security, and management of multicast traffic.

Each VLAN in a network has an associated VLAN ID, which appears in the IEEE 802.1Q tag in the Layer 2 header of packets transmitted on a VLAN. An end station might omit the tag, or the VLAN portion of the tag, in which case the first switch port to receive the packet can either reject it or insert a tag using its default VLAN ID. A given port can handle traffic for more than one VLAN, but it can support only one default VLAN ID.

The Private Edge VLAN feature lets you set protection between ports located on the switch. This means that a protected port cannot forward traffic to another protected port on the same switch. The feature does not provide protection between ports located on different switches.

### Addressing schemes in modern networks
An addressing scheme is clearly a requirement for communications in a computer network. With an addressing scheme, packets are forwarded from one location to another.

![Frame structure](https://ptgmedia.pearsoncmg.com/images/chap1_9780133814743/elementLinks/01fig12.jpg)

Each of the three layers, 2, 3, and 4, of the TCP/IP protocol stack model produces a header, as indicated in figure.In this figure, host 1 communicates with host 2 through a network of seven nodes, R1 through R7, and a payload of data encapsulated in a frame by the link layer header, the network layer header, and the transport layer header is carried over a link. Within any of these three headers, each source or destination is assigned an address as identification for the corresponding protocol layer.The three types of addresses are summarized as follows.

#### Link layer (layer 2) address:
 A 6-byte (48-bit) field called Media Access Control (MAC) address that is represented by a 6-field hexadecimal number, such as 89-A1-33-2B-C3-84, in which each field is two bytes long. Every input or output of a networking device has an interface to its connected link, and every interface has a unique MAC address. A MAC address is known only locally at the link level. Normally, it is safe to assume that no two interfaces share the same MAC address. A link layer header contains both MAC addresses of a source interface and a destination interface, as seen in the figure.
 #### Network layer (layer 3) address:
  A 4-byte (32-bit) field called Internet Protocol (IP) address that is represented by a 4-field dot-separated number, such as 192.2.32.83, in which each field is one byte long. Every entity in a network must have an IP address in order to be identified in a communication. An IP address can be known globally at the network level. A network layer header contains both IP addresses of a source node and a destination node, as seen in the figure.
  #### Transport layer (layer 4) address:
   A 2-byte (16-bit) field called port number that is represented by a 16-bit number, such as 4,892. The port numbers identify the two end hosts’ ports in a communication. Any host can be running several network applications at a time and thus each application needs to be identified by another host communicating to a targeted application. For example, source host 1 in Figure 1.12 requires a port number for communication to uniquely identify an application process running on the destination host 2. A transport layer header contains the port numbers of a source host and a destination host, as seen in the figure. Note that a transport-layer “port” is a logical port and not an actual or a physical one, and it serves as the end-point application identification in a host.


   ### IP Addressing Scheme:
   The IP header has 32 bits assigned for addressing a desired device on the network. An IP address is a unique identifier used to locate a device on the IP network. To make the system scalable, the address structure is subdivided into the network ID and the host ID. The network ID identifies the network the device belongs to; the host ID identifies the device. This implies that all devices belonging to the same network have a single network ID. Based on the bit positioning assigned to the network ID and the host ID, the IP address is further subdivided into classes A, B, C, D (multicast), and E (reserved) as shown in figure below.
   
   ![Classes of IP Address](https://ptgmedia.pearsoncmg.com/images/chap1_9780133814743/elementLinks/01fig13.jpg)

* Class A starts with 0 followed by 7 bits of network ID and 24 bits of host ID.
* Class B starts with 10 followed by 14 bits of network ID and 16 bits of host ID.
* Class C starts with 110 followed by 21 bits of network ID and 8 bits of host ID.
* Class D starts with 1110 followed by 28 bits. Class D is used only for multicast addressing by which a group of hosts form a multicast group and each group requires a multicast address.
* Class E starts with 1111 followed by 28 bits. Class E is reserved for network experiments only.

# Day 5  
## Address Resolution Protocol(ARP) and MAC address Spoofing
 Today I learned  about Address Resolution protocol(ARP) ad MAC Address spoofing.

 ## Address Resolution Protocol(ARP)
 Address Resolution Protocol (ARP) is a procedure for mapping a dynamic IP address to a permanent physical machine address in a local area network (LAN). The physical machine address is also known as a media access control (MAC) address.

The job of ARP is essentially to translate 32-bit addresses to 48-bit addresses and vice versa. This is necessary because IP addresses in IP version 4 (IPv4) are 32 bits, but MAC addresses are 48 bits.

ARP works between Layers 2 and 3 of the Open Systems Interconnection model (OSI model). The MAC address exists on Layer 2 of the OSI model, the data link layer. The IP address exists on Layer 3, the network layer.

ARP can also be used for IP over other LAN technologies, such as token ring, fiber distributed data interface (FDDI) and IP over ATM.

### Working principle Address Resolution Protocal(ARP)
When a new computer joins a LAN, it is assigned a unique IP address to use for identification and communication. When an incoming packet destined for a host machine on a particular LAN arrives at a gateway, the gateway asks the ARP program to find a MAC address that matches the IP address. A table called the ARP cache maintains a record of each IP address and its corresponding MAC address. All operating systems in an IPv4 Ethernet network keep an ARP cache. Every time a host requests a MAC address in order to send a packet to another host in the LAN, it checks its ARP cache to see if the IP to MAC address translation already exists. If it does, then a new ARP request is unnecessary. If the translation does not already exist, then the request for network addresses is sent and ARP is performed.

ARP broadcasts a request packet to all the machines on the LAN and asks if any of the machines are using that particular IP address. When a machine recognizes the IP address as its own, it sends a reply so ARP can update the cache for future reference and proceed with the communication.

Host machines that don't know their own IP address can use the Reverse ARP (RARP) protocol for discovery.

ARP cache size is limited and is periodically cleansed of all entries to free up space. Addresses tend to stay in the cache for only a few minutes. Frequent updates enable other devices in the network to see when a physical host changes their requested IP addresses. In the cleaning process, unused entries are deleted along with any unsuccessful attempts to communicate with computers that are not currently powered on.

### Proxy Address Resolution Protocal(Proxy ARP)
Proxy ARP enables a network proxy to answer ARP queries for IP addresses that are outside the network. This enables packets to be successfully transferred from one subnetwork to another.

When an ARP inquiry packet is broadcast, the routing table is examined to find which device on the LAN can reach the destination fastest. This device, which is often a router, acts as a gateway for forwarding packets outside the network to their intended destinations.
### ARP spoofing and ARP cache poisoning
LANs that use ARP are vulnerable to ARP spoofing, also called ARP poison routing or ARP cache poisoning.

ARP spoofing is a device attack in which a hacker broadcasts false ARP messages over a LAN in order to link an attacker's MAC address with the IP address of a legitimate computer or server within the network. Once a link has been established, the target computer can send frames meant for the original destination to the hacker's computer first as well as any data meant for the legitimate IP address.

ARP spoofing can seriously affect enterprises. When used in their simplest form, ARP spoofing attacks can steal sensitive information. However, the attacks can also facilitate other malicious attacks, including the following

#### Man-in-the-middle attacks(MitM)
A man in the middle (MITM) attack is a general term for when a perpetrator positions himself in a conversation between a user and an application—either to eavesdrop or to impersonate one of the parties, making it appear as if a normal exchange of information is underway.

The goal of an attack is to steal personal information, such as login credentials, account details and credit card numbers. Targets are typically the users of financial applications, SaaS businesses, e-commerce sites and other websites where logging in is required.

Information obtained during an attack could be used for many purposes, including identity theft, unapproved fund transfers or an illicit password change.

Additionally, it can be used to gain a foothold inside a secured perimeter during the infiltration stage of an advanced persistent threat (APT) assault.

Broadly speaking, a MITM attack is the equivalent of a mailman opening your bank statement, writing down your account details and then resealing the envelope and delivering it to your door.

####  Denial-of-Service (DoS) attack:
It is an attack meant to shut down a machine or network, making it inaccessible to its intended users. DoS attacks accomplish this by flooding the target with traffic, or sending it information that triggers a crash. In both instances, the DoS attack deprives legitimate users (i.e. employees, members, or account holders) of the service or resource they expected.

Victims of DoS attacks often target web servers of high-profile organizations such as banking, commerce, and media companies, or government and trade organizations. Though DoS attacks do not typically result in the theft or loss of significant information or other assets, they can cost the victim a great deal of time and money to handle.

There are two general methods of DoS attacks: flooding services or crashing services. Flood attacks occur when the system receives too much traffic for the server to buffer, causing them to slow down and eventually stop. Popular flood attacks include:

* Buffer overflow attacks:
The most common DoS attack. The concept is to send more traffic to a network address than the programmers have built the system to handle. It includes the attacks listed below, in addition to others that are designed to exploit bugs specific to certain applications or networks
* ICMP flood:
It take advantages of  misconfigured network devices by sending spoofed packets that ping every computer on the targeted network, instead of just one specific machine. The network is then triggered to amplify the traffic. This attack is also known as the smurf attack or ping of death.
* SYN flood :
It sends a request to connect to a server, but never completes the handshake. Continues until all open ports are saturated with requests and none are available for legitimate users to connect to.
Other DoS attacks simply exploit vulnerabilities that cause the target system or service to crash. In these attacks, input is sent that takes advantage of bugs in the target that subsequently crash or severely destabilize the system, so that it can’t be accessed or used.

An additional type of DoS attack is
#### Distributed Denial of Service (DDoS) attack:
 A DDoS attack occurs when multiple systems orchestrate a synchronized DoS attack to a single target. The essential difference is that instead of being attacked from one location, the target is attacked from many locations at once. The distribution of hosts that defines a DDoS provide the attacker multiple advantages:

* attacker can leverage(take advantage of)the greater volume of machine to execute a seriously disruptive attack
* The location of the attack is difficult to detect due to the random distribution of attacking systems (often worldwide)
* It is more difficult to shut down multiple machines than one
* The true attacking party is very difficult to identify, as they are disguised behind many (mostly compromised) systems

Modern security technologies have developed mechanisms to defend against most forms of DoS attacks, but due to the unique characteristics of DDoS, it is still regarded as an elevated threat and is of higher concern to organizations that fear being targeted by such an attack.

### Session Hijacking:
Session hijacking is a technique used by hackers to gain access to a target’s computer or online accounts. In a session hijacking attack, a hacker takes control of a user’s browsing session to gain access to their personal information and passwords. This article will explain what session hijacking is, how it works, and how to prevent it from happening.

* How Does Session Hijacking Work?

A session hijacker can take control of a user’s session in several ways. One common method is to use a packet sniffer to intercept the communication between the user and the server, which allows the hacker to see what information is being sent and received. They can then use this information to log in to the account or access sensitive data.

Session hijacking can also be performed by deploying malware to infect the user’s computer. This gives the hacker direct access to the machine, enabling them to then hijack any active sessions.

* What Are the Different Types of Session Hijacking?

Session hijacking can be either active or passive. In active session hijacking, the attacker takes control of the target’s session while it is still active. The attacker does this by sending a spoofed request to the server that includes the target’s session ID. This type of attack is more challenging to execute because it requires the attacker to have an OnPath (also known as “man-in-the-middle”) position between the target and the server.

Passive session hijacking occurs when the attacker eavesdrops on network traffic to steal the target’s session ID. This type of attack is easier to execute because all an attacker needs is access to network traffic, which can be easily accomplished if they are on the same network as the target.

* How to Prevent Session Hijacking:

There are several ways to prevent session hijacking from happening:
1. Use strong passwords and multifactor authentication:
 
 These techniques protect accounts from being accessed by hackers if they manage to steal a user’s session ID (Alkove, 2021).

2. Only share session IDs with trusted sources:
 Be careful when sharing links or sending requests to websites, as these may include session IDs.
3. Use a VPN:
 A VPN helps prevent attackers from intercepting traffic, making it more difficult for them to steal session IDs (McCann & Hardy, 2022).

4. Keep software up to date:
 Make sure to keep operating systems and software up to date with the latest security patches to prevent attackers from exploiting vulnerabilities to access users’ sessions.

5. Take cybersecurity training:
 Cybersecurity threats are constantly evolving, so it’s essential to stay informed on the latest attack techniques and how to prevent them. Consider getting certified in various cybersecurity domains, including ethical hacking, incident handling, and penetration testing.

#### The Dangers of Session Hijacking Attacks
There are many risks associated with not taking steps to prevent session hijacking. Some of these dangers include:

1. Theft of personal information:
 Session hijacking can give hackers access to confidential information, including passwords and credit card numbers, leading to identity theft or financial fraud.

2. Malware infection:
 If a hacker can steal a user’s session ID, they may also be able to infect the user’s computer with malware (Marino, 2021). This can allow them to gain control of the target’s computer and steal their data.

3. Denial-of-Service (DoS) attacks:
 A hacker who gains control of a user’s session could launch a DoS attack against the website or server to which they’re connected, disrupting service or causing the site to crash.


## MAC Address spoofing
MAC Spoofing is a type of attack used to exploit flaws in the authentication mechanism implemented by wired and wireless networking hardware. This can be accomplished through a variety of means, such as modifying the hardware itself with an inline switch to forward messages from one MAC address to another, spoofing the identity of that device by forwarding messages from an innocent bystander’s device (a “spoofing victim”), tampering with messages sent from legitimate access points, or capturing packets that contain response data that is ultimately manipulated before it reaches its destination
MAC spoofing is most commonly known as the method of attack used in Wireless Network Hacking. MAC spoofing is commonly used to break into wireless networks and steal wireless network credentials. It can also be used to install an unauthorized access point or simulate an access point with a packet sniffer from within the same operating system and without being on the same network segment.
A commonly known attack method is the use of an unauthorized access point to capture user credentials. If a user, for instance, decides to share a network resource with another user and does not know that it has been compromised in some way, then this is an example of how a MAC spoofing attack can be used to make it difficult for the non-malicious party to log on and share resources over that network. All they need to do is create an unauthorized access point of their own with the same MAC address as that of another’s. When that client tries to log in, the unauthorized access point will redirect the authentication query from the user’s device and vice versa. 

# Day 6  
## Router and Routing Tables in Computer Network
 Today I learned about Router,Routing tables,Entries of IP routing table and use of routing table entries in computer Network.

## Routers:
A Router is a networking device that forwards data packets between computer network. This device is usually connected to two or more different networks. When a data packet comes to a router port, the router reads address information in packet to determine out which port the packet will be sent. For example, a router provides you with the internet access by connecting your LAN with the Internet.

When a packet arrives at a Router, it examines destination IP address of a received packet and make routing decisions accordingly. Routers use Routing Tables to determine out which interface the packet will be sent. A routing table lists all networks for which routes are known. Each router’s routing table is unique and stored in the RAM of the device.

### Routing Table:
A routing table is a set of rules, often viewed in table format, that is used to determine where data packets traveling over an Internet Protocol (IP) network will be directed. All IP-enabled devices, including routers and switches, use routing tables. See below a Routing Table:

 The entry corresponding to the default gateway configuration is a network destination of 0.0.0.0 with a network mask (netmask) of 0.0.0.0. The Subnet Mask of default route is always 0.0.0.0 

### Sample of routing table is 
![Routing table](https://geek-university.com/wp-content/images/ccna/route_print_windows.jpg)

### Entries of an IP Routing Table:
A routing table contains the information necessary to forward a packet along the best path toward its destination. Each packet contains information about its origin and destination. Routing Table provides the device with instructions for sending the packet to the next hop on its route across the network.

Each entry in the routing table consists of the following entries:

* Network ID:
The network ID or destination corresponding to the route.
* Subnet Mask:
The mask that is used to match a destination IP address to the network ID.
* Next Hop:
The IP address to which the packet is forwarded
* Outgoing Interface:
Outgoing interface the packet should go out to reach the destination network.
* Metric:
A common use of the metric is to indicate the minimum number of hops (routers crossed) to the network ID.


Routing table entries can be used to store the following types of routes:

1. Directly Attached Network IDs
![Directly Attached Newtork](https://campus.barracuda.com/resources/attachments/image/79462765/1/direct_rt.png)
The Directly Attached Network ID Routes entry is used for routes that are connected to the local network. The Remote Network ID Routes entry is used for routes that can be accessed only via routers, or remotely. Host Routes allows you to enter a specific route to a specific host.

2. Remote Network IDs
Network remote identification, or remote ID, is the ability of an uncrewed aircraft system (UAS) to provide the identification of its operator, its location, and related operational information that can be received by authorised and public parties through the duration of the flight. A routing table is a database that keeps track of paths, like a map, and uses these to determine which way to forward traffic as well as stores route information about remote networks.

3. Host Routes
IT is a  route to a specific internetwork address (Network ID and Host ID). Host routes allow intelligent routing decisions to be made for each network address. Host routes are used to create custom routes to control or optimize specific types of network traffic.

Whenever a packet is sent through a router to be forwarded to a host on another network, the router consults the routing table to find the IP address of the destination device and the best path to reach it.

4. Default Route
![Default Route](https://cdn.networklessons.com/wp-content/uploads/2017/01/rip-default-route-lab-topology.png)
The default route is a route that a router uses to forward an incoming packet when no other route is available for that packet in the routing table. Routers use the routing table to make the forwarding decision. A routing table entry consists of two pieces: the remote network and the local interface that is connected to that network.

5. Destination Route

The main purpose of a routing table is to help routers make effective routing decisions. Whenever a packet is sent through a router to be forwarded to a host on another network, the router consults the routing table to find the IP address of the destination device and the best path to reach it.



# Day 7
## Internet Protocol(IP)and IP Address
 Today I learned about Internet Protocol(IP), IP Address,its working process, types of IP address, IP address security threats and method of protecting and hiding IP address.

## Internet Protocol(IP)
The Internet Protocol (IP) is the network layer communications protocol in the Internet protocol suite for relaying datagrams across network boundaries. Its routing function enables internetworking, and essentially establishes the Internet.

IP has the task of delivering packets from the source host to the destination host solely based on the IP addresses in the packet headers. For this purpose, IP defines packet structures that encapsulate the data to be delivered. It also defines addressing methods that are used to label the datagram with source and destination information.

### Function of Internet Protocol(IP)
The Internet Protocol is responsible for addressing host interfaces, encapsulating data into datagrams (including fragmentation and reassembly) and routing datagrams from a source host interface to a destination host interface across one or more IP networks.For these purposes, the Internet Protocol defines the format of packets and provides an addressing system.

Each datagram has two components: a header and a payload. The IP header includes source IP address, destination IP address, and other metadata needed to route and deliver the datagram. The payload is the data that is transported. This method of nesting the data payload in a packet with a header is called encapsulation.

IP addressing entails the assignment of IP addresses and associated parameters to host interfaces. The address space is divided into subnetworks, involving the designation of network prefixes. IP routing is performed by all hosts, as well as routers, whose main function is to transport packets across network boundaries. Routers communicate with one another via specially designed routing protocols, either interior gateway protocols or exterior gateway protocols, as needed for the topology of the network.

## IP Address
An IP address is a unique address that identifies a device on the internet or a local network. IP stands for "Internet Protocol," which is the set of rules governing the format of data sent via the internet or local network.
IP addresses are not random. They are mathematically produced and allocated by the Internet Assigned Numbers Authority (IANA), a division of the Internet Corporation for Assigned Names and Numbers (ICANN). ICANN is a non-profit organization that was established in the United States in 1998 to help maintain the security of the internet and allow it to be usable by all.

### Working Process of IP Address
Internet Protocol Address by communicating using set guidelines to pass information. All devices find, send, and exchange information with other connected devices using Internet protocol.

The process works like this

1. Your device indirectly connects to the internet by connecting at first to a network connected to the internet, which then grants your device access to the internet.
2. When you are at home, that network will probably be your Internet Service Provider (ISP). At work, it will be your company network.
3. Your IP address is assigned to your device by your ISP.
4. Your internet activity goes through the ISP, and they route it back to you, using your IP address. Since they are giving you access to the internet, it is their role to assign an IP address to your device.
5. However, your IP address can change. For example, turning your modem or router on or off can change it. Or you can contact your ISP, and they can change it for you.
6. When you are out and about; for example, traveling; and you take your device with you, your home IP address does not come with you. This is because you will be using another network (Wi-Fi at a hotel, airport, or coffee shop, etc.) to access the internet and will be using a different (and temporary) IP address, assigned to you by the ISP of the hotel, airport or coffee shop.

### Types of IP addresses
There are different categories of IP addresses, and within each category, different types.
#### Consumer IP addresses
Every individual or business with an internet service plan will have two types of IP addresses: their private IP addresses and their public IP address. The terms public and private relate to the network location that is, a private IP address is used inside a network, while a public one is used outside a network.

* Private IP Address:
Every device that connects to your internet network has a private IP address. This includes computers, smartphones, and tablets but also any Bluetooth-enabled devices like speakers, printers, or smart TVs. With the growing internet of things, the number of private IP addresses you have at home is probably growing. Your router needs a way to identify these items separately, and many items need a way to recognize each other. Therefore, your router generates private IP addresses that are unique identifiers for each device that differentiate them on the network.

* Public IP Address:
A public IP address is the primary address associated with your whole network. While each connected device has its own IP address, they are also included within the main IP address for your network. As described above, your public IP address is provided to your router by your ISP. Typically, ISPs have a large pool of IP addresses that they distribute to their customers. Your public IP address is the address that all the devices outside your internet network will use to recognize your network.

Public IP addresses are further classified into two forms

1. Dynamic IP addresses:
Dynamic IP addresses change automatically and regularly. ISPs buy a large pool of IP addresses and assign them automatically to their customers. Periodically, they re-assign them and put the older IP addresses back into the pool to be used for other customers. The rationale for this approach is to generate cost savings for the ISP. Automating the regular movement of IP addresses means they don’t have to carry out specific actions to re-establish a customer's IP address if they move home, for example. There are security benefits, too, because a changing IP address makes it harder for criminals to hack into your network interface.

2. Static IP addresses:
In contrast to dynamic IP addresses, static addresses remain consistent. Once the network assigns an IP address, it remains the same. Most individuals and businesses do not need a static IP address, but for businesses that plan to host their own server, it is crucial to have one. This is because a static IP address ensures that websites and email addresses tied to it will have a consistent IP address — vital if you want other devices to be able to find them consistently on the web.

#### Website IP Address:
For website owners who don’t host their own server, and instead rely on a web hosting package which is the case for most websites there are two types of website IP addresses. These are shared and dedicated.

1. Shared IP addresses
Websites that rely on shared hosting plans from web hosting providers will typically be one of many websites hosted on the same server. This tends to be the case for individual websites or SME websites, where traffic volumes are manageable, and the sites themselves are limited in terms of the number of pages, etc. Websites hosted in this way will have shared IP addresses.

2. Dedicated IP addresses:
Some web hosting plans have the option to purchase a dedicated IP address (or addresses). This can make obtaining an SSL certificate easier and allows you to run your own File Transfer Protocol (FTP) server. This makes it easier to share and transfer files with multiple people within an organization and allow anonymous FTP sharing options. A dedicated IP address also allows you to access your website using the IP address alone rather than the domain name — useful if you want to build and test it before registering your domain.

### IP address security Threats
Cybercriminals can use various techniques to obtain your IP address. Two of the most common are social engineering and online stalking.

1. Social Engineering:
Attackers can use social engineering to deceive you into revealing your IP address. For example, they can find you through Skype or a similar instant messaging application, which uses IP addresses to communicate. If you chat with strangers using these apps, it is important to note that they can see your IP address. Attackers can use a Skype Resolver tool, where they can find your IP address from your username.

2. Online stalking:
Criminals can track down your IP address by merely stalking your online activity. Any number of online activities can reveal your IP address, from playing video games to commenting on websites and forums.
Once they have your IP address, attackers can go to an IP address tracking website, such as whatismyipaddress.com, type it in, and then get an idea of your location. They can then cross-reference other open-source data if they want to validate whether the IP address is associated with you specifically. They can then use LinkedIn, Facebook, or other social networks that show where you live, and then see if that matches the area given.

If a Facebook stalker uses a phishing attack against people with your name to install spying malware, the IP address associated with your system would likely confirm your identity to the stalker.

If cybercriminals know your IP address, they can launch attacks against you or even impersonate you. It is important to be aware of the risks and how to mitigate them.

When The Hacker gets IP Address, there is high chance of  misusing it.

#### Risks:

1. Downloading illegal content using your IP address:

Hackers are known to use hacked IP addresses to download illegal content and anything else they do not want to be traced back to them. For example, using the identity of your IP address, criminals could download pirated movies, music, and video – which would breach your ISP’s terms of use and much more seriously, content related to terrorism or child pornography. This could mean that you go through no fault of your own and could attract the attention of law enforcement.

2. Tracking down your location:

If they know your IP address, hackers can use geolocation technology to identify your region, city, and state. They only need to do a little more digging on social media to identify your home and potentially burgle it when they know you are away.

3. Directly attacking your network:
Criminals can directly target your network and launch a variety of assaults. One of the most popular is a DDoS attack (distributed denial-of-service). This type of cyberattack occurs when hackers use previously infected machines to generate a high volume of requests to flood the targeted system or server. This creates too much traffic for the server to handle, resulting in a disruption of services. Essentially, it shuts down your internet. While this attack is typically launched against businesses and video game services, it can occur against an individual, though this is much less common. Online gamers are at particularly high risk for this, as their screen is visible while streaming (on which an IP address can be discovered).

4. Hacking into your device:
The internet uses ports as well as your IP address to connect. There are thousands of ports for every IP address, and a hacker who knows your IP can try those ports to attempt to force a connection. For example, they could take over your phone and steal your information. If a criminal does obtain access to your device, they could install malware on it.

#### Method of Protecting and Hiding IP Address:
Hiding your IP address is a way to protect your personal information and online identity. The two primary ways to hide your IP address are:

1. Using a proxy server:

A proxy server is an intermediary server through which your traffic is routed.
The internet servers you visit see only the IP address of that proxy server and not your IP address.When those servers send information back to you, it goes to the proxy server, which then routes it to you.

A drawback of proxy servers is that some of the services can spy on you, so you need to trust it. Depending on which one you use, they can also insert ads into your browser.

2. Using a Virtual Private Network:

When you connect your computer or smartphone or tablet to a VPN, the device acts as if it is on the same local network as the VPN.All your network traffic is sent over a secure connection to the VPN.Because your computer behaves as if it is on the network, you can securely access local network resources even when you are in another country.You can also use the internet as if you were present at the VPN’s location, which has benefits if you are using public Wi-Fi or want to access geo-blocked websites.


# Day 8
##  Transport Protocols UDP and TCP
 Today I was introduced to two major transport protocol, Transmission Control Protocol(TCP)and the User Datagram Protocol(UDP) and their working process.

 ### Transmission Control Protocol(TCP):
 TCP (Transmission Control Protocol) is one of the main protocols of the Internet protocol suite. It lies between the Application and Network Layers which are used in providing reliable delivery services. It is a connection-oriented protocol for communications that helps in the exchange of messages between different devices over a network. The Internet Protocol (IP), which establishes the technique for sending data packets between computers, works with TCP. So, Generally it is represented as TCP/IP.

 ### Working Process of TCP:
 To make sure that each message reaches its target location intact, the TCP/IP model breaks down the data into small bundles and afterward reassembles the bundles into the original message on the opposite end. Sending the information in little bundles of information makes it simpler to maintain efficiency as opposed to sending everything in one go. 

After a particular message is broken down into bundles, these bundles may travel along multiple routes if one route is jammed but the destination remains the same.

![Breaking down of Data](https://media.geeksforgeeks.org/wp-content/uploads/20211104135754/tcp3-660x322.PNG)

In above figure, we can see that the message is being broken down, then reassembled from a different order at the destination

For example, When a user requests a web page on the internet, somewhere in the world, the server processes that request and sends back an HTML Page to that user. The server makes use of a protocol called the HTTP Protocol. The HTTP then requests the TCP layer to set the required connection and send the HTML file.

Now, the TCP breaks the data into small packets and forwards it toward the Internet Protocol (IP) layer. The packets are then sent to the destination through different routes.

The TCP layer in the user’s system waits for the transmission to get finished and acknowledges once all packets have been received.

## User Datagram Protocal(UDP):
User Datagram Protocol (UDP) is a Transport Layer protocol. UDP is a part of the Internet Protocol suite, referred to as UDP/IP suite. Unlike TCP, it is an unreliable and connectionless protocol. So, there is no need to establish a connection prior to data transfer. The UDP helps to establish low-latency and loss-tolerating connections establish over the network.The UDP enables process to process communication.

Though Transmission Control Protocol (TCP) is the dominant transport layer protocol used with most of the Internet services; provides assured delivery, reliability, and much more but all these services cost us additional overhead and latency. Here, UDP comes into the picture. For real-time services like computer gaming, voice or video communication, live conferences; we need UDP. Since high performance is needed, UDP permits packets to be dropped instead of processing delayed packets. There is no error checking in UDP, so it also saves bandwidth. 
User Datagram Protocol (UDP) is more efficient in terms of both latency and bandwidth. 

### Working Process of UDP
User datagram protocol is a standardized communication protocol that transfers data between computers in a network. However, unlike other protocols such as TCP, UDP simplifies data transfer by sending packets (or, more specifically, datagrams) directly to the receiver without first establishing a two-way connection. UDP does not indicate the transmission order for its datagrams or even confirm their arrival.

UDP features checksums for ensuring data integrity and port numbers for defining the role played by the data being transmitted. However, it does not feature a mandatory ‘handshake’ between the sender and the receiver before the commencement of data transfer.

This makes UDP less than ideal for transferring sensitive information, as the receiver may obtain data that is out of order, glitchy, or with blank spaces. As discussed above, UDP is seen in applications where sending data to its destination on time is more critical than transmitting it without any glitches.

#### UDP Header

UDP header is an 8-bytes fixed and simple header, while for TCP it may vary from 20 bytes to 60 bytes. The first 8 Bytes contains all necessary header information and the remaining part consist of data. UDP port number fields are each 16 bits long, therefore the range for port numbers is defined from 0 to 65535; port number 0 is reserved. Port numbers help to distinguish different user requests or processes. 

1. Source Port: Source Port is a 2 Byte long field used to identify the port number of the source.
2. Destination Port: It is a 2 Byte long field, used to identify the port of the destined packet.
3. Length: Length is the length of UDP including the header and the data. It is a 16-bits field.
4. Checksum: Checksum is 2 Bytes long field. It is the 16-bit one’s complement of the one’s complement sum of the UDP header, the pseudo-header of information from the IP header, and the data, padded with zero octets at the end (if necessary) to make a multiple of two octets.

Notes – Unlike TCP, the Checksum calculation is not mandatory in UDP. No Error control or flow control is provided by UDP. Hence UDP depends on IP and ICMP for error reporting. Also UDP provides port numbers so that is can differentiate between users requests.

#### Applications of UDP: 
* Used for simple request-response communication when the size of data is less and hence there is lesser concern about flow and error control.
* It is a suitable protocol for multicasting as UDP supports packet switching.
* UDP is used for some routing update protocols like RIP(Routing Information Protocol).
* Normally used for real-time applications which can not tolerate uneven delays between sections of a received message.
* Following implementations uses UDP as a transport layer protocol: 
1. NTP (Network Time Protocol)
2. DNS (Domain Name Service)
3. BOOTP, DHCP.
4. NNP (Network News Protocol)
5. Quote of the day protocol
6. TFTP, RTSP, RIP.
* The application layer can do some of the tasks through UDP- 
1. Trace Route
2. Record Route
3. Timestamp
* UDP takes a datagram from Network Layer, attaches its header, and sends it to the user. So, it works fast.
* Actually, UDP is a null protocol if you remove the checksum field.
1. Reduce the requirement of computer resources.
2. When using the Multicast or Broadcast to transfer.
3. The transmission of Real-time packets, mainly in multimedia applications.

#### UDP PSEUDO HEADER:
The purpose of using a pseudo-header is to verify that the UDP packet has reached its correct destination. The correct destination consist of a specific machine and a specific protocol port number within that machine.

![UDP pseudo header](https://media.geeksforgeeks.org/wp-content/uploads/20230209140709/udp.png)

#### UDP pseudo header details:

* The UDP header itself specify only protocol port number.thus , to verify the destination UDP on the sending machine computes a checksum that covers the destination IP address as well as the UDP packet.
* At the ultimate destination, UDP software verifies the checksum using the destination IP address obtained from the header of the IP packet that carried the UDP message.
* If the checksum agrees, then it must be true that the packet has reached the intended destination host as well as the correct protocol port within that host.

# Day 9
##  Transport Protocols UDP and TCP
 Today I continued my study on this topic and learned the features, Advantages and Disadvantages as well as  vulnerabilities of Transmission Control Protocol(TCP) and User Datagram Protocol(UDP).

### Features of Transmission Control Protocol(TCP)
Some of the most prominent features of Transmission control protocol are

1. Segment Numbering System
* TCP keeps track of the segments being transmitted or received by assigning numbers to each and every single one of them.
* A specific Byte Number is assigned to data bytes that are to be transferred while segments are assigned sequence numbers.
* Acknowledgment Numbers are assigned to received segments.
2. Flow Control
* Flow control limits the rate at which a sender transfers data. This is done to ensure reliable delivery.
* The receiver continually hints to the sender on how much data can be received (using a sliding window)
3. Error Control
* TCP implements an error control mechanism for reliable data transfer
* Error control is byte-oriented
* Segments are checked for error detection
* Error Control includes – Corrupted Segment & Lost Segment Management, Out-of-order segments, Duplicate segments, etc.
4. Congestion Control
* TCP takes into account the level of congestion in the network
* Congestion level is determined by the amount of data sent by a sender

### Advantages of TCP
* It is a reliable protocol.
* It provides an error-checking mechanism as well as one for recovery.
* It gives flow control.
* It makes sure that the data reaches the proper destination in the exact order that it was sent.
* Open Protocol, not owned by any organization or individual.
* It assigns an IP address to each computer on the network and a domain name to each site thus making each device site to be distinguishable over the network.

### Disadvantages
* TCP is made for Wide Area Networks, thus its size can become an issue for small networks with low resources.
* TCP runs several layers so it can slow down the speed of the network.
* It is not generic in nature. Meaning, it cannot represent any protocol stack other than the TCP/IP suite. E.g., it cannot work with a Bluetooth connection.
* No modifications since their development around 30 years ago.

### Vulnerabilities in TCP:
TCP may be attacked in a variety of ways. The results of a thorough security assessment of TCP, along with possible mitigations for the identified issues, were published in 2009, and is currently being pursued within the IETF.

1. Denial of service:
By using a spoofed IP address and repeatedly sending purposely assembled SYN packets, followed by many ACK packets, attackers can cause the server to consume large amounts of resources keeping track of the bogus connections. This is known as a SYN flood attack. Proposed solutions to this problem include SYN cookies and cryptographic puzzles, though SYN cookies come with their own set of vulnerabilities. Sockstress is a similar attack, that might be mitigated with system resource management. An advanced DoS attack involving the exploitation of the TCP Persist Timer was analyzed in Phrack #66. PUSH and ACK floods are other variants.

2. Connection hijacking
An attacker who is able to eavesdrop a TCP session and redirect packets can hijack a TCP connection. To do so, the attacker learns the sequence number from the ongoing communication and forges a false segment that looks like the next segment in the stream. Such a simple hijack can result in one packet being erroneously accepted at one end. When the receiving host acknowledges the extra segment to the other side of the connection, synchronization is lost. Hijacking might be combined with Address Resolution Protocol (ARP) or routing attacks that allow taking control of the packet flow, so as to get permanent control of the hijacked TCP connection.

Impersonating a different IP address was not difficult prior to RFC 1948, when the initial sequence number was easily guessable. That allowed an attacker to blindly send a sequence of packets that the receiver would believe to come from a different IP address, without the need to deploy ARP or routing attacks: it is enough to ensure that the legitimate host of the impersonated IP address is down, or bring it to that condition using denial-of-service attacks. This is why the initial sequence number is now chosen at random.

3. TCP veto:
An attacker who can eavesdrop and predict the size of the next packet to be sent can cause the receiver to accept a malicious payload without disrupting the existing connection. The attacker injects a malicious packet with the sequence number and a payload size of the next expected packet. When the legitimate packet is ultimately received, it is found to have the same sequence number and length as a packet already received and is silently dropped as a normal duplicate packet the legitimate packet is "vetoed" by the malicious packet. Unlike in connection hijacking, the connection is never desynchronized and communication continues as normal after the malicious payload is accepted. TCP veto gives the attacker less control over the communication, but makes the attack particularly resistant to detection. The large increase in network traffic from the ACK storm is avoided. The only evidence to the receiver that something is amiss is a single duplicate packet, a normal occurrence in an IP network. The sender of the vetoed packet never sees any evidence of an attack.

4. TCP Reset Attack:
TCP reset attack also known as a "forged TCP reset" or "spoofed TCP reset", is a way to terminate a TCP connection by sending a forged TCP reset packet. This tampering technique can be used by a firewall or abused by a malicious attacker to interrupt Internet connections.

### Feaatures of UDP
1. Provides connectionless, unreliable service.
2. UDP faster than TCP.
3. Adds only checksum and process-to-process addressing to IP.
4. Used for DNS and NFS.
5. Used when socket is opened in datagram mode.
6. It sends bulk quantity of packets.
8. No acknowledgment.
9. Good for video streaming it is an unreliable protocol.
10. It does not care about the delivery of the packets or the sequence of delivery.
11. No flow control /congestion control, sender can overrun receiver's buffer.
12. Real time application like video conferencing needs (Because it is faster).
13. An UDP datagram is used in Network File System (NFS), DNS, SNMP, TFTP etc.
14. It has no handshaking or flow control.
15. It not even has windowing capability.
16. It is a fire and forget type protocol.
17. An application can use a UDP port number and another application can use the same port number for a TCP session from the same IP address.
18. UDP and IP are on different levels of the OSI stack and corresponds to other protocols like TCP and ICMP.
19. No connection establishment tear down; data is just sent right away.

### Advantages of UDP:
* UDP does not need to require a connection to be established and maintained
* UDP uses a small packet size with a small header. This fewer bytes in the overhead makes UDP protocol need for less time in processing the packet as well as needless memory
* UDP uses checksum with all packets for error detection
* UDP can be used in events where a single packet of data needs to be exchanged between the hosts
* Broadcast and multicast transmission are available with UDP
* UDP doesn't restrict you to a connection based communication model, so startup latency in distributed applications is much lower, as is operating system overhead fast.

### Disadvantages of UDP:
* UDP is an unreliable and connectionless protocol. 
* UDP has no windowing and no function to ensure data is received in the same order as it was transmitted
* UDP does not use any error control. So UDP detects an error in the received packet. It silently drops it
* The router can be careless with UDP. They do not retransmit a UDP datagram after the collision and will often discard UDP packets before TCP packets
* There is no flow control and no acknowledgement for received data
Only the application layer deals with error recovery. Hence applications can simply turn to the user to send the message again

### Vulnerabilities in UDP:
UDP is not protected by any encryption. You can add encryption to UDP, but it is not available by default. The lack of encryption means that anyone can see the traffic, change it, and send it on to its destination. Changing the data in the traffic will alter the 16-bit checksum, but the checksum is optional and is not always used. When the checksum is used, the hacker can create a new checksum based on the new data payload, and then record it in the header as a new checksum. The destination device will find that the checksum matches the data without knowing that the data has been altered. This type of attack is not widely used.

1. UDP Flood Attacks:
We are more likely to see a UDP flood attack. In a UDP flood attack, all the resources on a network are consumed. The hacker must use a tool like UDP Unicorn or Low Orbit Ion Cannon. These tools send a flood of UDP packets, often from a spoofed host, to a server on the subnet. The program will sweep through all the known ports trying to find closed ports. This will cause the server to reply with an ICMP port unreachable message. Because there are many closed ports on the server, this creates a lot of traffic on the segment, which uses up most of the bandwidth. The result is very similar to a DoS attack.

2. DNS Amplification:
A DNS amplification attack involves a hacker sending UDP packets with a spoofed IP address, which corresponds to the IP of the victim, to its DNS resolvers. The DNS resolvers then send their response to the victim. The attack is crafted such that the DNS response is much larger than the original request, which creates amplification of the original attack.

3. UDP Port Scan:
Attackers send UDP packets to ports on a server to determine which ports are open. If a server responds with an ICMP ‘Destination Unreachable’ message, the port is not open. If there is no such response, the attacker infers that the port is open, and then use this information to plan an attack on the system.


# Day 10

##  Next Generation Firewalls Overview
 Today I learned about  next generation firewalls, its features,benefits, able to compare next generation firewalls and traditional firewalls, importance and its types. 

 ### Next Generation Firewalls(NGFW)
 A next-generation firewall is within the third generation of firewall technology, designed to address advanced security threats at the application level through intelligent, context-aware security features. An NGFW combines traditional firewall capabilities like packet filtering and stateful inspection with others to make better decisions about what traffic to allow. 

 A next-generation firewall has the ability to filter packets based on applications and to inspect the data contained in packets (rather than just their IP headers). In other words, it operates at up to layer 7 (the application layer) in the OSI model, whereas previous firewall technology operated only up to level 4 (the transport layer). Attacks that take place at layers 4–7 of the OSI model are increasing, making this an important capability.

 ### Features of Next Generation Firewalls:
 Next-generation firewall specifications vary by provider, but they generally include some combination of the following features:

#### Application awareness: 
Application awareness or the ability to filter traffic and apply complex rules based on application (rather than just based on port). This is a key feature of next-generation firewalls: They can block traffic from certain applications, as well as maintain greater control over individual applications.

#### Deep-packet inspection:
NGFW  inspects the data contained in packets. Deep-packet inspection is an improvement over traditional firewall technology, which only inspected a packet’s IP header to determine its source and destination. 

#### Intrusion Prevention System (IPS):
It monitors the network for malicious activity and blocks it where it occurs. This monitoring can be signature-based (matching activity to signatures of well-known threats), policy-based (blocking activity that violates security policies), or anomaly-based (monitoring for abnormal behavior).

#### High performance:
This features allows the firewall to monitor large amounts of network traffic without slowdown. Next-generation firewalls include a number of security features that require processing time, so high performance are important to avoid disrupting business operations.

#### External threat intelligence:
External Threat intelligence or communication with a threat intelligence network to ensure that threat information is up to date and help identify bad actors.

In addition to these foundational features, next-generation firewalls may include additional features such as antivirus and malware protection. They may also be implemented as a Firewall as a Service (FWaaS), a cloud-based service that provides scalability and easier maintenance. With FWaaS, the firewall software is maintained by the service provider, and resources scale automatically to meet processing demand. This frees enterprise IT teams from dealing with the burden of handling patches, upgrades, and sizing.

### Benifits of NGFW:
#### Application-level security functions such as IDS and IPS:
An NGFW has added the level of application security functions such as intrusion detection systems aka IDS, and intrusion prevention systems aka IPS.

These applications help you to improve packet-content filtering. These features can also identify, analyse and act against irregular deviations from the standard set of activities, threat signatures and intelligent attacks based on user behavior.

#### Single Console Access:
A new generation firewall can be easily accessed from a single console, unlike the case of the traditional firewall where you need to set up and individually configure the firewall manually.

#### Multi-Layered Protection:
A traditional firewall can block access through ports (single layer protection), which proves insignificant in the complex and evolving landscape of data architecture.

NGFW offers multi-layered protection by inspecting traffic from layer 2 to layer 7 and at the same time understanding the exact nature of data transfer.So if the data transfer is within the limits of defined firewall policy, will be transferred else it will be blocked.

#### Simplified Infrastructure:
We need to have a separate security appliance for every new threat. But with the new generation firewall, you can easily manage and update the security protocols from a single authorized device.This simplifies the complicated security infrastructure and saves time on day-to-day operational activities.

#### Optimal Use of Network Speed:
In the case of the traditional firewall, the network speed decreases as the number of security protocols and devices increases.
This happens because the dedicated network speed does not reach its expected potential with the increase in security devices and services.But, with the next-generation firewall, you can constantly achieve the potential throughput irrespective of the number of devices and security protocols.

#### Antivirus, Ransomware and Spam Protection & Endpoint Security:
An NGFW comes with a complete package of antivirus, ransomware & spam protection along with endpoint security to protect your business data.
With the help of these features, you don’t necessarily need separate tools for those purposes.

Since NGFW comprises all these features, you do not only save the time and effort required, but it also helps you to monitor and control the cyber threats easily.

#### Capability to Implement Role-based Access
New generation firewalls have an inherent ability to detect user identity. It can also work with different user roles and limit the scope of access for an individual and/or group.
This feature helps the organizations to set role-based access to certain portions of their data and its content.
Organizations can also make some of their data public and keep the rest of the confidential data with themselves.

#### Key Takeaways:
An NGFW does not only cover all the traditional firewall features but is also more than capable of tackling the modern-day cyber threats with conviction too.
With the number of features that an NGFW provides, it is undoubtedly becoming a useful technology in cybersecurity.

### Next Generation Firewalls vs Traditional Firewalls:
Traditional firewalls rely on port/protocol inspection and blocking to protect enterprise networks at the data link and transport layers (layers 2 and 4 of the OSI model). This static approach was effective in the past, when the IT environment was less dynamic than it is now, and applications could be identified by port. But with the increasing complexity of virtualized networks and more advanced security threats, it’s no longer enough. Next-generation firewalls are smarter: They can filter packets based on application (layer 7 of the OSI model), and even based on behavior, making fine-grained distinctions that are far more effective than the generic methods used by traditional firewalls. They also refer to external data to identify threats. This dynamic, flexible approach allows them to identify and defend against attackers that are much more sophisticated than in the past.

### Importance:
Targeted and sophisticated security threats are causing more damage to internal networks than ever before. Traditional firewall technologies are heavily reliant on port/protocol inspection, which is ineffective in a virtualized environment where addresses and ports are assigned dynamically. By comparison, a next-generation firewall uses deep-packet filtering to inspect the contents of packets, provides layer 7 application filtering, and can even monitor and block suspicious activity. These capabilities are a must to ensure security in a complex, dynamic environment.

### Types of NGFW:
* Packet filtering firewall: Looks at the IP header of packets and drops ones that are flagged. 

* Circuit-level gateway: Flags malicious content based on TCP handshakes and other network protocol session initiation messages, rather than looking at the packets themselves.

* Stateful inspection firewall: Combines packet filtering with session monitoring for an additional level of security.

* Application-level gateway: Filters packets by destination port and HTTP request string. Also known as a proxy firewall.

* Next-generation firewall: Employs application-level, context-aware, intelligent technology to protect against advanced threats.


# Day 11

##  Next Generation Firewalls(NGFW) Packet Flow
 Today I learned  the flow of packets through a NGFW(Allied Telesis firewall ), Deep Packet inspection(DPI), Working process,uses,benefits, DPI techniques as well as limitation and challanges of DPI
 ### Firewall architecture
 The Allied Telesis Next Generation Firewall is built and configured around an application and
protocol decoding engine that performs Deep Packet Inspection (DPI). Firewall and Network Address Translation(NAT)  rules are
defined to allow or deny IPv4 and/or IPv6 application traffic between network entities, such as
individual hosts, servers, subnets, and networks.
Typically, a network administrator might use an NGFW to provide security zones based on business
functions such as admin, sales, IT, and R&D staff etc. Alternatively, they might use an NGFW to
implement security based on the traditional three zone approach - public zone, private zone and
de-militarized zone (DMZ). Typical configuration could involve many network entity definitions (often
involving several networks per zone), including several hundred rules to control access between
hosts, networks, zones, and the Internet.


### Packet Flow 
When protecting a private LAN from a public WAN, packets are most commonly forwarded by the
firewall. Network packets pass through the firewall using a fixed set of processing steps as discussed below.

![Packet flow](https://raw.githubusercontent.com/hecticSubraz/Network-Security-and-Database-Vulnerabilities/main/file%20dumps/Screenshot%202023-03-13%20205907.png)

This is the packet processing order:
1. Packets are received on one of the firewall's physical interfaces (LAN or WAN) and follow the Forward path shown in figure

2. Stream processing always happens straight after the packet is received on the physical interface. Stream processing is DPI, IPS, IP Reputation, Malware Protection, and URL Filtering.

3. Policy Based Routing and Port Forwarding is applied before packets are routed to their
destination.

4. After routing, firewall and NAT rules are matched.

5. Finally, NAT processing and traffic control is applied before packet transmission

The other two important processing packet paths in the firewall are Input and Output.

* The Input path is applied to packets that are destined to the firewall itself:
Along with management and network protocol packets received by the firewall, this also includes
tunnel packets for which the firewall is the tunnel decapsulation endpoint and proxied packets
where the firewall terminates both sides of HTTP(S) connections (web-control and antivirus).

* The Output path is applied to packets generated by the firewall itself:

Along with management and network protocol packets generated by the firewall, this also
includes tunnel packets encapsulated by the firewall and proxied packets where the firewall
terminates both sides of HTTP(S) connections.

Note that because packets generated by the firewall were never received on a physical interface,
stream processing is also applied first in the Output path.

Be aware that when tunnel packets are encapsulated or decapsulated they skip stream processing
the second time around unless tunnel security-reprocessing is enabled in a configuration.Pacekt
file

### Types Packet Inspection:
 Generally the major types of packet inspection are as follows 

 #### Deep packet inspection:
 
Deep packet inspection (DPI), is a form of packet filtering used every day by organizations and your internet service provider (ISP) to detect and prevent cyber-attacks, monitor traffic patterns, combat malware, optimize servers, and analyze user behavior.

Conventional packet filtering only examines the packet's header, so the value of DPI is that it locates, identifies, classifies and reroutes or blocks packets with specific data or code payloads.
So while stateful packet inspection only evaluates packet header information, such as source IP address, destination IP address, and port number, deep packet inspection looks at a more comprehensive range of data and metadata associated with individual packets. 

![Deep packet inspection](https://dl.acm.org/cms/attachment/7c1fdc9a-1f7c-4617-9920-183fe82d2629/7296f1.png)

 As packets reach an inspection point, DPI intercepts any non-compliance to protocol, viruses, spam, and other anomalies, and blocks the packet from passing through the inspection point.

 #### Working process of DPI
 As mentioned, conventional packet filtering doesn't have the capabilities of a DPI which can scan the contents of a message and identify the specific application or service that sent it. You can also reroute network traffic from a specific Internet Protocol (IP) address range or online service (like Facebook or Twitter) by programming filters.

Traditional firewalls didn't always have the processing power necessary to perform more in-depth inspections on large volumes of traffic in real time. These days, however, technological advancements mean that DPI can perform more advanced inspections to check both packet headers and data.

Tech leaders and network administrators have welcomed deep packet inspection technology as an important tool to help cope with the increase in the rising volume, complexity and frequency of internet-related threats. DPI is mainly used by firewalls with intrusion detection systems.

#### Uses of DPI:

Deep packet inspection functions are vital for network security, because it they determine whether a particular packet is moving through network traffic towards the right destination.

Unlike conventional network packet filtering, in which packets are sorted based on the source and destination, deep packet inspection goes beyond examining the incoming packets to pick up protocol anomaly, analyze, locate, and block the packets if and when required.

A DPI system also offers packet-level analysis to identify the root-cause of application or network performance issues. It’s considered one of the most accurate techniques to monitor and analyze application behavior, network usage issues, data breaches and more. Additionally, deep packet analysis also helps with:

* Measuring business-critical applications with high network latency

* Improving application availability and meet SLAs

* Generating reports on historic data and performing forensics

Deep packet inspection can also help copyright holders such as record labels by blocking their content from being downloaded illegally. DPI can also be used to serve targeted advertising to users, lawful interception, and policy enforcement.

#### Benefits of DPI
Deep packet inspections offer several important benefits when it comes to a corporate network or any organization's network performance.

1. DPI is an important network security tool:

By analyzing packets other than just the packet header, DPIs are able to catch threats or block detected attacks that may be hidden in the contents of the data. This allows an organization to more readily identify usage patterns, and block malware, data leaks, and other security threats to the network and its end users.


![Deep packet inspection](https://www.okta.com/sites/default/files/media/image/2022-08/DEEPPACKETINSPECTION_GRAPHIC_1.png)



2. DPI provides additional options for managing network traffic flows:



Deep packet inspection allows for the programming of rules that look for specific types of data and identify high and low priority packets. In this way, deep packet inspection can give preference to higher-priority or mission critical packets throughout the data stream, and pass them through the network first, ahead of ordinary browsing packets or lower priority messages.

These rules and policies, once clearly defined by an organization, allow the network to detect if there are prohibited uses of approved applications.

Deep packet inspection can also be used to inspect outbound traffic as it attempts to exit the network. This means that organizations can create filters designed to prevent data leaks. You can also use deep packet inspection to learn where your data packet is going.

3. Predetermined rules guide how DPI handles packets in real time:

All packet information, from the header to its contents, are checked and automatically handled based on the pre-programmed rules that your team puts in place. This way your system can automatically sort, filter, and prioritize each packet without slowing down the network.

Deep packet inspection provides the ability to do something about traffic that fits a profile, such as generating an alert for dropped or lost packets, or limiting the bandwidth available to that traffic.

### Deep Packet Inspection Techniques:

* Pattern or signature matching:

A firewall with Intrusion Detection System (IDS) capability analyzes each packet against a database of known network attacks. The IDS looks for specific patterns that are known to be malicious and blocks the traffic if it finds such a pattern. The disadvantage of the signature matching approach is that it can only be effective if signatures are updated regularly.

Additionally, this method only works against known threats or attacks. As new threats are discovered daily, ongoing signature updates are critical to ensure that the firewall can detect the threats and continue to keep the network safe and secure.


![Pattern or Signature Matching](https://devopedia.org/images/article/262/4328.1587058436.jpg)



*  Heuristic and Behavior Analysis:

Understanding an application or protocol begins with studying its behavior. For example, measuring packet sizes and the timing between packets etc. Even if the protocol or application changes its signature, the behavior is likely to remain the same. For example, Voice over IP (VoIP) traffic usually starts with session initiation and then many smaller-sized UDP packets are used to deliver the call traffic.

* Protocol anomaly:
 
 The protocol anomaly technique is also used by firewalls with an IDS but here, it follows a default deny approach, where the firewall determines which content/traffic should be allowed based on protocol definitions. So the difference is that unlike signature matching, this method also protects the network against unknown attacks.

 * Intrusion prevention system (IPS)
IPS solutions can block detected attacks in real time by preventing malicious packets from being delivered based on the contents of the packets. So, if a particular packet represents a known security threat, the IPS will proactively deny network traffic based on a defined rule set. However, the database needs to be updated regularly with information about new threats.

The downside of IPS is the risk of false positives, although these can be curtailed by establishing proper baseline behaviors for network components, creating conservative policies and custom thresholds, and regularly reviewing alerts and logged incidents to improve network monitoring and alerting.


### Limitation and challanges of DPI

All technology has its challenges and limitations that sit alongside its benefits. In the case of deep packet inspection, there are three main issues:

1. While DPI functionality provides protection against existing vulnerabilities, it can also create new vulnerabilities in the network. While deep packet inspection is effective against buffer overflow attacks, denial-of-service attacks and malware threats, it can also facilitate attacks in those same categories.

2. Deep packet filtering can increase the complexity of existing firewalls and other security software. And, to remain optimally effective, DPI requires periodic updates and revisions, which can cause extra admin headaches for security teams.

3. DPI is notorious for reducing or interfering with network speed and performance because it creates network bottlenecks and increases the burden on firewall processors for data decryption and inline inspection



# Day 12

## Intrusion Detection System(IDS) and Intrusion Prevention system(IPS)
 Today I learned about Intrusion Detection system(IDS),Intrusion Prevention System(IPS),how they works,their classification as well as benefits and their detection method. 

### Intrusion Detection System(IDS):

A system called an intrusion detection system (IDS) observes network traffic for malicious transactions and sends immediate alerts when it is observed. It is software that checks a network or system for malicious activities or policy violations. Each illegal activity or violation is often recorded either centrally using a SIEM system or notified to an administration. IDS monitors a network or system for malicious activity and protects a computer network from unauthorized access from users, including perhaps insiders. The intrusion detector learning task is to build a predictive model (i.e. a classifier) capable of distinguishing between ‘bad connections’ (intrusion/attacks) and ‘good (normal) connections’.

### Working process of IDS
* An IDS (Intrusion Detection System) monitors the traffic on a computer network to detect any suspicious activity.
* It analyzes the data flowing through the network to look for patterns and signs of abnormal behavior.
* The IDS compares the network activity to a set of predefined rules and patterns to identify any activity that might indicate an attack or intrusion.
* If the IDS detects something that matches one of these rules or patterns, it sends an alert to the system administrator.
* The system administrator can then investigate the alert and take action to prevent any damage or further intrusion.

### Classification of IDS
 IDS are classified into 5 types:

#### Network Intrusion Detection System (NIDS): 
Network intrusion detection systems (NIDS) are set up at a planned point within the network to examine traffic from all devices on the network. It performs an observation of passing traffic on the entire subnet and matches the traffic that is passed on the subnets to the collection of known attacks. Once an attack is identified or abnormal behavior is observed, the alert can be sent to the administrator. An example of a NIDS is installing it on the subnet where firewalls are located in order to see if someone is trying to crack the firewall.

![Network Intrusion Detection System](https://media.geeksforgeeks.org/wp-content/uploads/20220630185949/NIDS.png)



#### Host Intrusion Detection System (HIDS): 
Host intrusion detection systems (HIDS) run on independent hosts or devices on the network. A HIDS monitors the incoming and outgoing packets from the device only and will alert the administrator if suspicious or malicious activity is detected. It takes a snapshot of existing system files and compares it with the previous snapshot. If the analytical system files were edited or deleted, an alert is sent to the administrator to investigate. An example of HIDS usage can be seen on mission-critical machines, which are not expected to change their layout.

![Host Intrusion Detection System](https://media.geeksforgeeks.org/wp-content/uploads/20220630185950/HIDS.png)


#### Protocol-based Intrusion Detection System (PIDS): 

Protocol-based intrusion detection system (PIDS) comprises a system or agent that would consistently reside at the front end of a server, controlling and interpreting the protocol between a user/device and the server. It is trying to secure the web server by regularly monitoring the HTTPS protocol stream and accepting the related HTTP protocol. As HTTPS is unencrypted and before instantly entering its web presentation layer then this system would need to reside in this interface, between to use the HTTPS.

#### Application Protocol-based Intrusion Detection System(APIDS): 

An application Protocol-based Intrusion Detection System (APIDS) is a system or agent that generally resides within a group of servers. It identifies the intrusions by monitoring and interpreting the communication on application-specific protocols. For example, this would monitor the SQL protocol explicitly to the middleware as it transacts with the database in the web server.

#### Hybrid Intrusion Detection System:
 Hybrid intrusion detection system is made by the combination of two or more approaches to the intrusion detection system. In the hybrid intrusion detection system, the host agent or system data is combined with network information to develop a complete view of the network system. The hybrid intrusion detection system is more effective in comparison to the other intrusion detection system. Prelude is an example of Hybrid IDS.
Benefits of IDS

### Benefits of IDS
* Detects malicious activity: IDS can detect any suspicious activities and alert the system administrator before any significant damage is done.
* Improves network performance: IDS can identify any performance issues on the network, which can be addressed to improve network performance.
* Compliance requirements: IDS can help in meeting compliance requirements by monitoring network activity and generating reports.
* Provides insights: IDS generates valuable insights into network traffic, which can be used to identify any weaknesses and improve network security.

### Detection Method of IDS
1. Signature-based Method: 
Signature-based IDS detects the attacks on the basis of the specific patterns such as the number of bytes or a number of 1s or the number of 0s in the network traffic. It also detects on the basis of the already known malicious instruction sequence that is used by the malware. The detected patterns in the IDS are known as signatures. Signature-based IDS can easily detect the attacks whose pattern (signature) already exists in the system but it is quite difficult to detect new malware attacks as their pattern (signature) is not known.

2. Anomaly-based Method:
 Anomaly-based IDS was introduced to detect unknown malware attacks as new malware is developed rapidly. In anomaly-based IDS there is the use of machine learning to create a trustful activity model and anything coming is compared with that model and it is declared suspicious if it is not found in the model. The machine learning-based method has a better-generalized property in comparison to signature-based IDS as these models can be trained according to the applications and hardware configurations.

 ### Comparison of IDS with Firewalls
 IDS and firewall both are related to network security but an IDS differs from a firewall as a firewall looks outwardly for intrusions in order to stop them from happening. Firewalls restrict access between networks to prevent intrusion and if an attack is from inside the network it doesn’t signal. An IDS describes a suspected intrusion once it has happened and then signals an alarm.

 Intrusion Detection System (IDS) is a powerful tool that can help businesses in detecting and prevent unauthorized access to their network. By analyzing network traffic patterns, IDS can identify any suspicious activities and alert the system administrator. IDS can be a valuable addition to any organization’s security infrastructure, providing insights and improving network performance.


 ### Intrusion Prevention System(IPS)
 Intrusion Prevention System is also known as Intrusion Detection and Prevention System. It is a network security application that monitors network or system activities for malicious activity. Major functions of intrusion prevention systems are to identify malicious activity, collect information about this activity, report it and attempt to block or stop it. 

Intrusion prevention systems are contemplated as augmentation of Intrusion Detection Systems (IDS) because both IPS and IDS operate network traffic and system activities for malicious activity. 

IPS typically record information related to observed events, notify security administrators of important observed events and produce reports. Many IPS can also respond to a detected threat by attempting to prevent it from succeeding. They use various response techniques, which involve the IPS stopping the attack itself, changing the security environment or changing the attack’s content. 

### working process of IPS:
An IPS works by analyzing network traffic in real-time and comparing it against known attack patterns and signatures. When the system detects suspicious traffic, it blocks it from entering the network.

### Types of IPS
1. Network-Based IPS: A Network-Based IPS is installed at the network perimeter and monitors all traffic that enters and exits the network.

2. Host-Based IPS: A Host-Based IPS is installed on individual hosts and monitors the traffic that goes in and out of that host.

### Importance of IPS:
An IPS is an essential tool for network security. Here are some reasons:

* Protection Against Known and Unknown Threats: 
An IPS can block known threats and also detect and block unknown threats that haven’t been seen before.

* Real-Time Protection: An IPS can detect and block malicious traffic in real-time, preventing attacks from doing any damage.

* Compliance Requirements: Many industries have regulations that require the use of an IPS to protect sensitive information and prevent data breaches.

* Cost-Effective: An IPS is a cost-effective way to protect your network compared to the cost of dealing with the aftermath of a security breach.

* Increased Network Visibility: An IPS provides increased network visibility, allowing you to see what’s happening on your network and identify potential security risks.

### Classification of Intrusion Prevention System (IPS): 
Intrusion Prevention System (IPS) is classified into 4 types: 
 
1. Network-based intrusion prevention system (NIPS): 
It monitors the entire network for suspicious traffic by analyzing protocol activity. 
 
2. Wireless intrusion prevention system (WIPS): 
It monitors a wireless network for suspicious traffic by analyzing wireless networking protocols. 
 
3. Network behavior analysis (NBA): 
It examines network traffic to identify threats that generate unusual traffic flows, such as distributed denial of service attacks, specific forms of malware and policy violations. 
 
4. Host-based intrusion prevention system (HIPS): 
It is an inbuilt software package which operates a single host for doubtful activity by scanning events that occur within that host. 

### Detection Method of Intrusion Prevention System (IPS):  

* Signature-based detection: 
Signature-based IDS operates packets in the network and compares with pre-built and preordained attack patterns known as signatures. 
 
* Statistical anomaly-based detection: 
Anomaly based IDS monitors network traffic and compares it against an established baseline. The baseline will identify what is normal for that network and what protocols are used. However, It may raise a false alarm if the baselines are not intelligently configured. 
 
* Stateful protocol analysis detection: 
This IDS method recognizes divergence of protocols stated by comparing observed events with pre-built profiles of generally accepted definitions of not harmful activity. 


An Intrusion Prevention System (IPS) is a crucial component of any network security strategy. It monitors network traffic in real-time, compares it against known attack patterns and signatures, and blocks any malicious activity or traffic that violates network policies. An IPS is an essential tool for protecting against known and unknown threats, complying with industry regulations, and increasing network visibility. Consider implementing an IPS to protect your network and prevent security breaches.

### Comparision between IPS and IDS
The main difference between Intrusion Prevention System (IPS) with Intrusion Detection Systems (IDS) are: 

1. Intrusion prevention systems are placed in-line and are able to actively prevent or block intrusions that are detected. 
2. IPS can take such actions as sending an alarm, dropping detected malicious packets, resetting a connection or blocking traffic from the offending IP address. 
3. IPS also can correct cyclic redundancy check (CRC) errors, defragment packet streams, mitigate TCP sequencing issues and clean up unwanted transport and network layer options. 


# Day 13

## High availability and High availability Clusters
 Today I learned about high availability in information tehnology,how it works as well as how it  can be achieved through clustering, its measurement process, High available cluster's concept and its working process.

### High availability:
High availability (HA) is the ability of a system to operate continuously without failing for a designated period of time. HA works to ensure a system meets an agreed-upon operational performance level. In information technology (IT), a widely held but difficult-to-achieve standard of availability is known as five-nines availability, which means the system or product is available 99.999% of the time.
HA systems are used in situations and industries where it is critical the system remains operational. Real-world high-availability systems include military control, autonomous vehicle, industrial and healthcare systems. People's lives depend on these systems being available and functioning at all times. For example, if the system operating an autonomous vehicle fails to function when the vehicle is in operation, it could cause an accident, endangering its passengers, other drivers and vehicles, pedestrians and property.

Highly available systems must be well-designed and thoroughly tested before they are used. Planning for one of these systems requires all components meet the desired availability standard. Data backup and failover capabilities play important roles in ensuring HA systems meet their availability goals. System designers must also pay close attention to the data storage and access technology they use.

### Working process of High Availability(HA)
It is impossible for systems to be available 100% of the time, so true high-availability systems generally strive for five nines as the standard of operational performance.

The following three principles are used when designing HA systems to ensure high availability:

* Single points of failure:
 A single point of failure is a component that would cause the whole system to fail if it fails. If a business has one server running an application, that server is a single point of failure. Should that server fail, the application will be unavailable.

* Reliable crossover:
 Building redundancy into these systems is also important. Redundancy enables a backup component to take over for a failed one. When this happens, it's necessary to ensure reliable crossover or failover, which is the act of switching from component X to component Y without losing data or affecting performance.

 * Failure detectability:
 Failures must be visible and ideally, systems have built-in automation to handle the failure on their own. There should also be built-in mechanisms for avoiding common cause failures, where two or more systems or components fail simultaneously, likely from the same cause.

To ensure high availability when many users access a system, load balancing becomes necessary. Load balancing automatically distributes workloads to system resources, such as sending different requests for data to different services hosted in a hybrid cloud architecture. The load balancer decides which system resource is most capable of efficiently handling which workload. The use of multiple load balancers to do this ensures no one resource is overwhelmed.

The servers in an HA system are in clusters and organized in a tiered architecture to respond to requests from load balancers. If one server in the cluster fails, a replicated server in another cluster can handle the workload designated for the failed server. This sort of redundancy enables failover where a secondary component takes over a primary component's job when the first component fails, with minimal performance impact.

The more complex a system is, the more difficult it is to ensure high availability because there are simply more points of failure in a complex system.

Host intrusion detection systems (HIDS) run on independent hosts or devices on the network. A HIDS monitors the incoming and outgoing packets from the device only and will alert the administrator if suspicious or malicious activity is detected. It takes a snapshot of existing system files and compares it with the previous snapshot. If the analytical system files were edited or deleted, an alert is sent to the administrator to investigate. An example of HIDS usage can be seen on mission-critical machines, which are not expected to change their layout.


![Information flow between highly availability severs and end user](https://cdn.ttgtmedia.com/rms/onlineimages/data_center-information_flow-f.png)


#### Measurement of High availability:

Availability can be measured relative to a system being 100% operational or never failing; meaning it has no outages. Typically, an availability percentage is calculated as follows:

Availability = (minutes in a month - minutes of downtime)/(Minutes in a month)*100

Three metrics used to measure availability include the following:

* Mean time between failures (MTBF) is the expected time between two failures for the given system.
* Mean downtime (MDT) is the average time that a system is nonoperational.
* Recovery time objective (RTO), also known as estimated time of repair, is the total time a planned outage or recovery from an unplanned outage will take.

These metrics can be used for in-house systems or by service providers to promise customers a certain level of service as stipulated in a service-level agreement (SLA). SLAs are contracts that specify the availability percentage customers can expect from a system or service.
Availability metrics are subject to interpretation as to what constitutes the availability of the system or service to the end user. Even if systems continue to partially function, users may deem it unusable based on performance problems. Despite this level of subjectivity, availability metrics are formalized concretely in SLAs, which the service provider or system is responsible for satisfying.
If a system or SLA provides 99.999% availability, the end user can expect the service to be unavailable for the following amounts of time:

* Daily= 0.9 seconds
* Weekly= 6.0 seconds
* Monthly=26.3 seconds
* Yearly= 5 minutes and 15.6 seconds

### High Availability Cluster
High availability clusters are groups of hosts (physical machines) that act as a single system and provide continuous availability. High availability clusters are used for mission critical applications like databases, eCommerce websites, and transaction processing systems.High availability clusters are typically used for load balancing, backup, and failover purposes. To successfully configure a high availability (HA) cluster, all hosts in the cluster must have access to the same shared storage. In any case of failure, a virtual machine (VM) on one host can failover to another host, without any downtime.The number of nodes in a high availability cluster can vary between two to dozens of nodes, but storage administrators should be aware that adding too many virtual machines and hosts to one HA cluster can make load balancing difficult.This article is a conceptual overview of high availability architectures, presented as part of our series of articles on AWS high availability.

#### Working of Highly availability clustering
High availability server clusters are groups of servers that support applications or services, which need to run reliably with minimal downtime.High availability architectures use redundant software performing a similar function, installed on multiple machines, so each of them can be used as a backup when another component fails. Without this clustering, if an application or website fails, the service will not be available until it is repaired.

A highly available architecture prevents this situation using the following process:
1. Detecting failure
2. Performing failover of the application to another redundant host
3. Restarting or repairing the failed server without requiring manual intervention

#### The heartbeat technique
High availability cluster servers typically use a replication method known as heartbeat. The purpose of this technique is to monitor cluster node health via a dedicated network connection. Each node in the cluster constantly advertises its availability to the other nodes by sending a “heartbeat” over the dedicated network link.One of the critical conditions that must be prevented in a high availability cluster is a “split brain”. Split brain happens when all private internal links are cut off at the same time, but the cluster nodes are still functioning.In this case, all nodes of the cluster may mistakenly assume that all other nodes are down, and try to start services that other nodes are already running. With multiple versions of the same service, all of which may be exposed to users, and can result in data corruption.

#### High Availability Cluster Concepts
1. Active/Active Cluster:
A failover ensures that when a node loss occurs within a service group, it is quickly offset by other nodes in that location. This way, when a node fails, its IP address automatically moves to a standby node. You can use a network routing tool (for example, a load balancer) to redirect traffic from a failed node.In an active/passive model, initially, only one node serves customers, and continues working alone until it fails for some reason. At that point, both new and existing sessions are transferred to a backup or inactive node. Always add one more redundant component for each type of resource (n + 1 redundancy) to ensure you have sufficient resources for existing demand, while covering potential failure.

2. Active/Active Cluster
In a cluster with an active/active design, there are two or more nodes with the same configuration, each of which is directly accessed by clients.If one node fails, clients automatically connect to the other node and start working with it, as long as it has enough resources (because one node is now handling the load for two nodes). After restoring or replacing the first node, clients are again split between the two original nodes.The main benefit to running an active/active cluster is that you can effectively achieve node-network balance. A load balancer sends all client requests to available servers and monitors node-network activity. The load balancer moves traffic to nodes that can better handle that traffic, using predefined algorithms.The routing strategy can follow a round robin model, in which customers are distributed arbitrarily between the available nodes, or it may follow a weighing scheme, in which one node takes precedence over another by a certain percentage.In a cluster configuration combining active/active and active/passive, redundancy can be greatly improved by adding a passive node, alongside the active nodes. If a service cannot tolerate downtime, you should aim to combine active and passive high availability models.




# Day 14

## Introduction to Database and Database Management System
 Today I learned about database and its types, able to  differentiate between database and spreadsheet, challenges of database, database software as well as Database Management system and use of database to improve business performance and decision making.

### Database:
A database is an organized collection of structured information, or data, typically stored electronically in a computer system. A database is usually controlled by a database management system (DBMS). Together, the data and the DBMS, along with the applications that are associated with them, are referred to as a database system, often shortened to just database.

Data within the most common types of databases in operation today is typically modeled in rows and columns in a series of tables to make processing and data querying efficient. The data can then be easily accessed, managed, modified, updated, controlled, and organized. Most databases use structured query language (SQL) for writing and querying data.

### Types of Database:
There are many different types of databases. The best database for a specific organization depends on how the organization intends to use the data.

#### Relational databases
Relational databases became dominant in the 1980s. Items in a relational database are organized as a set of tables with columns and rows. Relational database technology provides the most efficient and flexible way to access structured information.

#### Object-oriented databases
Information in an object-oriented database is represented in the form of objects, as in object-oriented programming.

#### Distributed databases
A distributed database consists of two or more files located in different sites. The database may be stored on multiple computers, located in the same physical location, or scattered over different networks.

#### Data warehouses
A central repository for data, a data warehouse is a type of database specifically designed for fast query and analysis.

#### NoSQL databases
A NoSQL, or nonrelational database, allows unstructured and semistructured data to be stored and manipulated (in contrast to a relational database, which defines how all data inserted into the database must be composed). NoSQL databases grew popular as web applications became more common and more complex.

#### Graph databases
* A graph database stores data in terms of entities and the relationships between entities.
* OLTP databases: An OLTP database is a speedy, analytic database designed for large numbers of transactions performed by multiple users.

#### Open source databases
An open source database system is one whose source code is open source; such databases could be SQL or NoSQL databases.

#### Cloud databases
A cloud database is a collection of data, either structured or unstructured, that resides on a private, public, or hybrid cloud computing platform. There are two types of cloud database models: traditional and database as a service (DBaaS). With DBaaS, administrative tasks and maintenance are performed by a service provider.

#### Multimodel database
Multimodel databases combine different types of database models into a single, integrated back end. This means they can accommodate various data types.

#### Document/JSON database
Designed for storing, retrieving, and managing document-oriented information, document databases are a modern way to store data in JSON format rather than rows and columns.

#### Self-driving databases
The newest and most groundbreaking type of database, self-driving databases (also known as autonomous databases) are cloud-based and use machine learning to automate database tuning, security, backups, updates, and other routine management tasks traditionally performed by database administrators.

### Difference between database and spreadsheet:
Databases and spreadsheets (such as Microsoft Excel) are both convenient ways to store information. The primary differences between the two are:

* How the data is stored and manipulated
* Who can access the data
* How much data can be stored

Spreadsheets were originally designed for one user, and their characteristics reflect that. They’re great for a single user or small number of users who don’t need to do a lot of incredibly complicated data manipulation. Databases, on the other hand, are designed to hold much larger collections of organized information—massive amounts, sometimes. Databases allow multiple users at the same time to quickly and securely access and query the data using highly complex logic and language.

### Challanges of Database:
Today’s large enterprise databases often support very complex queries and are expected to deliver nearly instant responses to those queries. As a result, database administrators are constantly called upon to employ a wide variety of methods to help improve performance. Some common challenges that they face include:

* Absorbing significant increases in data volume.The explosion of data coming in from sensors, connected machines, and dozens of other sources keeps database administrators scrambling to manage and organize their companies’ data efficiently.

 * Ensuring data security. Data breaches are happening everywhere these days, and hackers are getting more inventive. It’s more important than ever to ensure that data is secure but also easily accessible to users.

* Keeping up with demand. In today’s fast-moving business environment, companies need real-time access to their data to support timely decision-making and to take advantage of new opportunities.

* Managing and maintaining the database and infrastructure. Database administrators must continually watch the database for problems and perform preventative maintenance, as well as apply software upgrades and patches. As databases become more complex and data volumes grow, companies are faced with the expense of hiring additional talent to monitor and tune their databases.

* Removing limits on scalability. A business needs to grow if it’s going to survive, and its data management must grow along with it. But it’s very difficult for database administrators to predict how much capacity the company will need, particularly with on-premises databases.

* Ensuring data residency, data sovereignty, or latency requirements. Some organizations have use cases that are better suited to run on-premises. In those cases, engineered systems that are pre-configured and pre-optimized for running the database are ideal.

Addressing all of these challenges can be time-consuming and can prevent database administrators from performing more strategic functions.

### Database software
Database software is used to create, edit, and maintain database files and records, enabling easier file and record creation, data entry, data editing, updating, and reporting. The software also handles data storage, backup and reporting, multi-access control, and security. Strong database security is especially important today, as data theft becomes more frequent. Database software is sometimes also referred to as a “database management system” (DBMS).

Database software makes data management simpler by enabling users to store data in a structured form and then access it. It typically has a graphical interface to help create and manage the data and, in some cases, users can construct their own databases by using database software.

### Database Management System:
A database typically requires a comprehensive database software program known as a database management system (DBMS). A DBMS serves as an interface between the database and its end users or programs, allowing users to retrieve, update, and manage how the information is organized and optimized. A DBMS also facilitates oversight and control of databases, enabling a variety of administrative operations such as performance monitoring, tuning, and backup and recovery.

Some examples of popular database software or DBMSs include MySQL, Microsoft Access, Microsoft SQL Server, FileMaker Pro, Oracle Database, and dBASE.

### Use of  databases to improve business performance and decision-making

With massive data collection from the Internet of Things transforming life and industry across the globe, businesses today have access to more data than ever before. Forward-thinking organizations can now use databases to go beyond basic data storage and transactions to analyze vast quantities of data from multiple systems. Using database and other computing and business intelligence tools, organizations can now leverage the data they collect to run more efficiently, enable better decision-making, and become more agile and scalable. Optimizing access and throughput to data is critical to businesses today because there is more data volume to track. It’s critical to have a platform that can deliver the performance, scale, and agility that businesses need as they grow over time.

The self-driving database is poised to provide a significant boost to these capabilities. Because self-driving databases automate expensive, time-consuming manual processes, they free up business users to become more proactive with their data. By having direct control over the ability to create and use databases, users gain control and autonomy while still maintaining important security standards.










 














