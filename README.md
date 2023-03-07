
# 30 days of Network security and Database vulnerabilities
I will be learning Network security and Database vulnerabilities for 30 days and I will be updating daily about my progress and understanding.

- [Day 1](#Day-1)
- [Day 2](#Day-2)
- [Day 3](#Day-3)
- [Day 4](#Day-4)
- [Day 5](#Day-5)

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

 ## Address Resolution Protocal(ARP)
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



 














