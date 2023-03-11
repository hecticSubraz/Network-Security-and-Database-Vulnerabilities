
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
 Today I continued my study on this topic and learned the features, Advantages and Disadvantages and vulnerabilities of Transmission Control Protocol(TCP) and User Datagram Protocol(UDP).

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






 














