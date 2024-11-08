## Project Overview

This project focuses on system administration and covers essential networking concepts related to IP addresses and network devices.

---

192.168.130.63

### 1. What is an IP?

- Define Internet Protocol Address (IP).
- Explain the two important parts: Network ID and Host ID.

  -> Internet Protocol Address (IP) :
  - An Internet Protocol (IP) address is a unique identifier assigned to devices on a network,
    such as computers, servers, or other connected devices. It allows them to communicate with each other over the internet or local networks.
    IP addresses are essential for identifying the location of a device and enabling data to be routed correctly between different devices.

## - NOTE :
  - ISP service : Internet Service Providers.

### 2. What are the types of an IP address?

- **Static IP address**: Permanent and used for critical equipment (e.g., servers).
- **Dynamic IP address**: Changes occasionally and used for consumer devices (e.g., laptops, smartphones).
- Types of IP Addresses 
1. Static IP Address
  Permanent: It never changes once assigned.
  Used for: Servers, routers, or any device that needs to be easily found, like web or email servers.
  Pros: Reliable for hosting and remote access.
  Cons: Can be more expensive and more prone to attacks since the IP doesn’t change. 
  2. Dynamic IP Address
  Temporary: Assigned automatically by the network (via DHCP), and can change over time.
  Used for: Consumer devices like laptops, smartphones, and home networks.
  Pros: Easy to manage, more secure, and cost-effective.
  Cons: Not reliable for services that need constant access, like hosting. 
  ## - NOTE : 
    - DHCP : Dynamic Host Configuration Protocol (DHCP) server.

### 3. What is the purpose of IP addresses?

  - Discuss how IP addresses facilitate communication between devices.
  - Explain their role in uniquely identifying devices on the internet.
  1. Communication Between Devices
    IP addresses act like mailing addresses. They help devices send and receive information over the internet.
    For example, when you visit a website, your device sends a request to the website’s IP address, and the website sends the page back to your IP address. 
  2. Uniquely Identifying Devices
    Each device on the internet has a unique IP address, like a home address.
    This ensures data reaches the right device, preventing confusion when multiple devices are connected.
    In short, IP addresses allow devices to communicate and make sure data gets to the correct destination.

### 4. What is the difference between IPv4 and IPv6?

  - **IPv4**: 32-bit addresses, ~4.3 billion addresses, uses numeric dot-decimal notation.
  - **IPv6**: 128-bit addresses, ~340 undecillion addresses, uses alphanumeric hexadecimal notation.
  1. IPv4 (Internet Protocol Version 4)
     Size: It uses 32 bits to create an address.
     Total Addresses: Can generate about 4.3 billion unique IP addresses.
     Format: Written in dot-decimal notation like 192.168.1.1 (four numbers separated by periods).
     Problem: Due to the growing number of internet devices, IPv4 is running out of addresses.
  2. IPv6 (Internet Protocol Version 6)
     Size: It uses 128 bits to create an address, making it much larger than IPv4.
     Total Addresses: Can create 340 undecillion addresses (that's a number with 36 zeros!).
     Format: Written in hexadecimal format like 2001:0db8:85a3::8a2e:0370:7334 (longer and includes letters and numbers).
     Advantage: IPv6 has way more addresses than IPv4, solving the address shortage.
     What’s Used Now and Why?
     IPv4 is still the most widely used, but it’s running out of available addresses.
     IPv6 is gradually being adopted because it has a lot more addresses, and can handle the increasing number of devices connecting to the internet,
     like phones, smart devices, and cars.
     IPv6 also offers better efficiency and security for the future.
  - In summary:
    IPv4 has been around longer but is running out of space.
    IPv6 is the new solution with plenty of room for growth!

### 5. What is TCP/IP?
  - Define Transmission Control Protocol/Internet Protocol.
  - Explain its role in computer communication on networks.

  1. Transmission Control Protocol/Internet Protocol (TCP/IP)
     TCP/IP is a set of rules (protocols) that allow computers and devices to communicate with each other over the internet or any network.
     It has two main parts:
     TCP (Transmission Control Protocol): Makes sure data is split into smaller pieces (called packets), sent to the correct place, and put back together in the right order.
     IP (Internet Protocol): Finds the best way to send those packets of data to the correct device, just like addressing a letter to reach the right house.
  2. Role in Computer Communication
     IP handles the addressing part: it gives each device an address (IP address) so the data knows where to go.
     TCP makes sure the data arrives correctly: it checks that all parts of the message reach the destination and are assembled in the right order, ensuring nothing is missing or out of place.
     Simple Example:
     Think of it like sending a package:
     IP is like the mailing address on the package, telling the post office where to deliver it.
     TCP is like the delivery service making sure the package arrives safely and completely, and all parts of it are put together if it's split into pieces.
     In Short:
     IP is responsible for finding the right address.
     TCP ensures the data arrives safely and in the right order.
     Without TCP/IP, computers wouldn’t know how to communicate with each other properly over networks.

### 6. What is the difference between TCP and IP?
- Clarify that IP obtains addresses while TCP is responsible for data delivery.

### 7. How does TCP/IP work?
- Outline the four layers of the TCP/IP model:
  - **Datalink Layer**
  - **Internet Layer**
  - **Transport Layer**
  - **Application Layer**

-------------------------------------------------------

### 8. What is a switch?

- Define a switch and its function within a Local Area Network (LAN).

### 9. What is a router?

- Define a router and its role in managing network traffic.

### 10. How does a router work?

- Explain the internal routing table and how routers direct packets to their destination.

### 11. What is the difference between a Modem and a Router?

- Clarify that modems connect to the internet, while routers manage local networks.

### 12. What is a loopback address?

- Define the loopback address and its range (127.0.0.0 to 127.255.255.255).

### 13. What is a subnet?

- Explain the concept of subnetting and its efficiency in networks.

### 14. How to calculate a subnet mask from an IP address (step by step)?

- Provide the detailed steps using the example IP address 10.20.4.13/29, including:
  - Finding the subnet number
  - Calculating the subnet mask
  - Determining subnet size
  - Finding the broadcast address
  - Identifying the IP address subnet
  - Calculating valid hosts

---

## Additional Notes

- Ensure all definitions are clear and concise.
- Include diagrams or tables where necessary for better understanding.
- Provide examples to illustrate each concept.

##  what does mean by network ?
  - "A network is a system where multiple devices are connected to each other using either cables (called a wired connection) 
    or wireless technology (called a wireless connection), allowing them to communicate and share information."

## USE OF Network

1. Sharing Hardware: Devices like printers or scanners can be shared by multiple computers, saving costs since you don’t need separate equipment for each device.
2. Sharing Data: Files, documents, and media can be easily shared and accessed between different devices on the network without needing physical transfer.
3. Data Protection: Networks allow for centralized storage and backups, which help protect data from being lost or corrupted. This also makes it easier to manage security, 
   like setting up firewalls and encryption.

## NETWORK COMPONENTS
1. End Device:
  An end device is any device that connects to the network to communicate or share information. Examples include computers, 
  smartphones, printers, and servers. These devices either send or receive data over the network.
2. Network Media: 
  Network media refers to the way devices are physically or wirelessly connected to the network. 
  There are two main types:
  Physical Connection (Wired): Uses cables to connect devices. 
  There are different types of cables:
  Copper Cables: These are common and include:
  Coaxial Cable: Used for TV and internet connections, with a single core and layers of insulation.
  Twisted Pair Cable: Used in Ethernet networks, it consists of pairs of wires twisted together to reduce interference.
  Fiber Optic Cables: Transmit data using light, allowing for much faster speeds and longer distances than copper cables.
  Wireless Connection: Uses radio waves (e.g., Wi-Fi, Bluetooth) to connect devices without cables, allowing mobility and ease of access.
3. Network Interface:
  A network interface is the hardware or software component that allows a device to connect to a network. It can be a Network Interface Card (NIC), which is a physical card installed in computers, 
  or a wireless adapter that connects via Wi-Fi.
  Example: Ethernet ports (for wired connections) or Wi-Fi adapters (for wireless connections).
  The network interface helps devices communicate by sending and receiving data through the network media.
4. Network Protocols:
  Network protocols are the rules and standards that devices on a network follow to communicate and exchange data. 
  They ensure that information is sent, received, and understood correctly between devices.
  Examples:
  TCP/IP: The foundation of internet communication, ensuring reliable data transfer.
  HTTP/HTTPS: Protocols used for web browsing.
  Wi-Fi Protocols: Standards that govern wireless communication.
  Protocols are like a common language that all devices on the network must speak to ensure smooth communication.

## type of casting
1. Unicast:
  Definition: Unicast is a one-to-one communication method where data is sent from a single source to a single destination.
  Example: Sending an email from one person to another. Only the intended recipient receives the data.
2. Broadcast:
  Definition: Broadcast is a one-to-all communication method where data is sent from a single source to all devices on a network.
  Example: A network message sent to all computers in a local area network (LAN), such as an announcement or a DHCP request.
3. Multicast:
  Definition: Multicast is a one-to-many communication method where data is sent from a single source to a specific group of devices.
  Example: Streaming a live video to multiple subscribers. Only devices that have joined the multicast group receive the data.
4. Anycast:
  Definition: Anycast is a one-to-nearest communication method where data is sent from a single source to the nearest device in a group of potential receivers.
  Example: Routing requests to the closest server in a content delivery network (CDN) to reduce latency and improve load times.
Summary:
  Unicast: One source to one destination.
  Broadcast: One source to all devices on the network.
  Multicast: One source to a specific group of devices.
  Anycast: One source to the nearest device in a group.

## Transmission modes
1. Simplex:
  Definition: In simplex mode, data transmission occurs in only one direction. One device sends data, and the other device only receives it.
  Example: A keyboard sending input to a computer; the keyboard cannot receive data back from the computer.
2. Half-Duplex:
  Definition: In half-duplex mode, data can be transmitted in both directions, but not simultaneously. Devices can send and receive data, 
  but one must wait while the other is transmitting.
  Example: Walkie-talkies; when one person speaks, the other must wait until they finish before responding.
3. Full-Duplex:
  Definition: In full-duplex mode, data transmission occurs in both directions simultaneously. Both devices can send and receive data at the same time.
  Example: A phone call; both parties can speak and listen to each other at the same time.
Summary:
  Simplex: One-way communication (e.g., keyboard to computer).
  Half-Duplex: Two-way communication, but not at the same time (e.g., walkie-talkies).
  Full-Duplex: Two-way communication happening simultaneously (e.g., phone calls).

##  NETWORK Types :
1. Personal Area Network (PAN)
  Range: Typically a few meters.
  Purpose: Connects devices within a person’s reach, often for individual use.
  Examples: Bluetooth connections between a smartphone and a smartwatch, or connecting wireless headphones to a computer.
2. Local Area Network (LAN)
  Range: Covers a small geographic area, like a single building, office, or school.
  Purpose: Connects computers and devices within a limited area, often used for sharing resources such as files, printers, or internet connections.
  Examples: Home Wi-Fi networks, or a company’s internal network in an office.
3. Metropolitan Area Network (MAN)
  Range: Covers a city or a large campus.
  Purpose: Connects multiple LANs within a specific geographic area. MANs are often established by cities or large institutions.
  Examples: Citywide Wi-Fi networks or a university campus network.
4. Wide Area Network (WAN)
  Range: Spans large geographical areas, often a country or continent.
  Purpose: Connects multiple LANs and MANs over long distances. WANs are typically operated by telecommunications companies.
  Examples: The internet is the largest WAN, or a corporate WAN connecting offices in different cities.
5. Campus Area Network (CAN)
  Range: Limited to a specific campus or collection of buildings.
  Purpose: Connects LANs within a campus-like area, usually within universities, hospitals, or large corporate settings.
  Examples: A college network connecting various buildings, or a business park’s network.
6. Virtual Private Network (VPN)
  Range: Virtual, extends across other networks.
  Purpose: Creates a secure connection over the internet, allowing private data to be shared securely across public networks.
  Examples: Corporate VPNs used for remote work, personal VPNs to access region-restricted content.
7. Storage Area Network (SAN)
  Range: Typically within a building or data center.
  Purpose: Connects storage devices to servers in a way that they appear to be locally attached to the operating system.
  Examples: Used in data centers to manage large volumes of storage across multiple servers.

------------------------------------

## OSI model and TCP/IP model :

                                                ![OSI Model image](https://media.geeksforgeeks.org/wp-content/uploads/20210220204638/cn1.png)

- TCP/IP is Practical, OSI is Ideal: The OSI model is theoretical, but TCP/IP was designed for real-world application. 
  TCP/IP lumps some OSI layers together to make a more streamlined, efficient process for internet communications. 
  For example, TCP/IP combines the OSI’s Application, Presentation, and Session layers into one Application layer, which fits the internet’s requirements well.

# Layer 1: Physical Layer

                                                ![Physical Layer Image](https://media.geeksforgeeks.org/wp-content/uploads/20241015103017414021/physical-layer-768.png)

- The Physical Layer is the foundation of the OSI model. 
  It deals with the physical connection between devices and handles the transmission of raw bits over a network medium. It has 3 main fucntion:
1. Transmission Medium:
  - Defines the type of physical connection used to send data, like cables (Ethernet, fiber optic) or wireless (radio waves).
  - Determines how devices are connected (e.g., wired or wireless) and ensures compatibility for data transfer.
2. Signal Encoding:
  - Converts data into signals (electrical, light, or radio) that can travel over the transmission medium.
  - This involves encoding bits into the appropriate form for the medium being used 
    (e.g., converting digital bits into electrical pulses for copper cables or light pulses for fiber optics).
3. Physical Topology:
  - Refers to the layout of connected devices on a network, such as star, bus, or ring configurations.
  - Different topologies can affect the performance and reliability of the network
  **Devices Operating at the Physical Layer**
  - Cables and Connectors: Ethernet cables, fiber optic cables, and connectors enable physical connectivity.
  - Hubs and Repeaters: Basic devices that extend or boost signals on a network.
  - Network Interface Cards (NICs): Provide the physical connection point on a device for network access.
  **Summary**
  - The Physical Layer is responsible for transmitting raw data as electrical, optical, or radio signals across the network medium. 
  - It deals with the physical aspects of the connection, such as cables, signals, and network topology, enabling all other layers to communicate effectively.

# Layer 2: Data Link Layer

                                                ![Data Link Layer image](https://imgs.search.brave.com/RsN1busw9Rg0svn4R3CD3FC4mdF3jqkQnrzVPPUdjjE/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly91cGxv/YWQud2lraW1lZGlh/Lm9yZy93aWtpcGVk/aWEvY29tbW9ucy8z/LzNiL1VEUF9lbmNh/cHN1bGF0aW9uLnN2/Zw)

- The Data Link Layer is responsible for transmitting data between devices on the same network (or local network segment). 
  It packages data into frames and manages error checking to ensure accurate transmission. It has 4 main functions:
1. MAC Addressing:
  - Uses MAC (Media Access Control) addresses to identify devices on the same local network.
  - MAC addresses are unique to each device’s network interface card (NIC), allowing the Data Link Layer to forward data to the correct device on a network.
2. Framing:
  - Breaks down data from the Network Layer into frames (manageable data packets) before sending it over the physical network.
  - Frames are easier to manage and verify for accuracy when data is divided into smaller pieces.
3. Error Detection and Correction:
  - Checks for errors in frames using methods like Cyclic Redundancy Check (CRC).
  - If an error is detected, the Data Link Layer can request retransmission of the frame.
4. Flow Control and Access Control:
  - Flow control manages the speed of data transmission to prevent one device from overwhelming another.
  - Access control determines which devices have permission to transmit data at any given time, preventing collisions on the network.

## Layer 3: Network Layer
- The Network Layer is responsible for logical addressing and routing, which are key functions for moving data between different networks.
1. Logical Addressing (IP Addressing):
  - In Layer 3, IP addresses are used to identify devices on different networks. Unlike MAC addresses (which are used in Layer 2), 
  - IP addresses can be assigned to devices across the world, allowing communication between devices on different networks (LANs or even WANs).
  - IPv4 and IPv6 are the most commonly used protocols for logical addressing at this layer.
  - Subnetting is used to divide larger networks into smaller subnetworks, allowing more efficient routing and IP address management.
2. Routing:
  - Routing is a process of determining the best path for data to travel from one network to another. This happens in Layer 3.
  - Routers operate at this layer. They examine the destination IP address of incoming packets and forward them to the appropriate next-hop router or final destination based on their routing tables.
  - Routers use routing protocols like RIP, OSPF, or BGP to learn and share network routes.
 **Key Concepts in Layer 3:**
  - IP Addressing: Devices are uniquely identified by their IP address, which helps routers forward packets across networks.
  - Routing Protocols: Enable routers to determine the best paths and communicate with other routers to forward packets.
  - Devices in Layer 3:
  - Routers: Forward packets between different networks using IP addresses and routing tables.
  - Layer 3 Switches: These combine features of both Layer 2 (switching) and Layer 3 (routing) and can perform routing within a local network.
  **Conclusion:**
  - Network Layer (Layer 3) is responsible for logical addressing (IP addresses) and routing, 
    enabling communication between devices on different networks by forwarding packets across the internet or across a large network.

## Layer 4: Transport Layer

- The Transport Layer is responsible for getting data safely from one device to another, even if they’re on different networks. It has 4 main functions:
1. Reliable or Fast Delivery:
  Ensures data is delivered accurately and in the right order.
  TCP (Transmission Control Protocol) provides reliable delivery by checking for errors and re-sending lost data.
  UDP (User Datagram Protocol) offers faster but less reliable delivery, ideal for streaming and online gaming.
2. Data Segmentation and Reassembly:
  Breaks large messages into smaller parts, called segments, for easier handling and reassembles them at the destination.
  This makes it easier for data to travel through different networks without getting lost.
3. Flow Control:
  Manages the speed of data transfer so the receiver isn’t overwhelmed with too much data at once.
  Prevents network congestion by adjusting the rate at which data is sent.
4. Port Addressing:
  Uses port numbers to send data to the correct application (e.g., port 80 for web browsing, port 25 for email).
  Port numbers help make sure the data goes to the right place on the receiving device.
**Protocols at the Transport Layer**
  TCP: Reliable, connection-based protocol for error-checked delivery.
  UDP: Fast, connectionless protocol for speedy but less reliable delivery.
Summary
  The Transport Layer’s job is to safely deliver data between applications. It can guarantee reliability (with TCP) or focus on speed (with UDP), 
  controls data flow, segments data for easier handling, and directs it to the right app using port numbers.

## Session Layer (Layer 5)
**The Session Layer has 4 main jobs to help applications communicate smoothly over a network.**
Here’s a breakdown:
1. Transmission Mode (Dialog Control):
  Manages the flow of communication between two devices.
  Decides if communication is one-way (simplex), two-way but one at a time (half-duplex), or two-way at the same time (full-duplex).
2. Session Setup and Close:
  Starts and ends sessions for applications that need a continuous connection (like video calls or remote access).
  This layer makes sure the connection opens when needed and closes properly after the data exchange is complete.
3. Synchronization: 
  Adds checkpoints during long data transfers.
  If there’s a disruption, the session can restart from the last checkpoint rather than from the beginning. This is useful for large file transfers or ongoing tasks.
4. Authentication and Authorization:
  Checks identity (authentication) and access permissions (authorization) before starting a session.
  Helps verify that only approved users can connect to the service, adding a layer of security.
**Summary**
  The Session Layer makes sure that applications can connect, communicate in the right mode, recover if there’s an issue, and stay secure with identity checks. 
  This layer is essential for reliable, organized communication in tasks like video calls, file sharing, and remote connections.

## Layer 6: Presentation Layer
 -  The Presentation Layer makes sure that data sent from one device can be understood by the other device, 
    even if they use different data formats. It has 3 main functions:
1. Data Translation:
  Converts data into a format that the receiving application can understand.
  For example, it may translate between different character encoding formats like ASCII and Unicode.
2. Data Encryption and Decryption:
  Secures data by encrypting it before it’s sent and decrypting it upon receipt.
  Ensures that sensitive information (like passwords) is safe from unauthorized access.
3. Data Compression:
  Reduces the size of data to save bandwidth and speed up transmission.
  Common in tasks like sending images or videos to reduce loading time.
**Summary of Presentation Layer**
  The Presentation Layer is like the "translator" of the OSI model. It formats, encrypts, 
  and compresses data so that devices with different setups can communicate smoothly and securely.

## Layer 7: Application Layer
- The Application Layer is the closest layer to the end-user and is where network applications operate. 
  It provides the interface that allows users to interact with the network. It has 3 main functions:
1. Application Services:
  Provides network services directly to end-user applications, like email, web browsing, and file transfers.
  For example, when you open a website, the Application Layer handles the communication between your browser and the web server.
2. Network Resource Access:
  Helps applications access network resources like files, databases, and printers.
  Manages requests for data or services and ensures they are properly handled.
3. Data Integrity and End-User Protocols:
  Supports protocols that define specific communication rules, like HTTP (for web), FTP (for file transfer), and SMTP (for email).
  Ensures data integrity and proper formatting so applications work as expected.
  **Summary of Application Layer**
- The Application Layer enables users and applications to interact with the network by providing services like email, file transfer, and web browsing. 
- It ensures data is properly formatted for end-users and supports protocols specific to each application.

## Networking devices : 

1. **Hub**
  - A hub is the simplest networking device and operates at the Physical Layer (Layer 1) of the OSI model. 
  - It has limited intelligence and primarily functions as a basic signal repeater.
    **How a Hub Works** :
  - A hub receives data (signals) from one device and broadcasts it to all other devices on the network.
  - It doesn’t have any capability to distinguish which device the data is meant for, so it sends the signal to every connected device.
  - All devices connected to a hub share the same bandwidth and collision domain, which means if two devices send data at the same time, a collision can occur, causing delays.
  **Hub Characteristics** :
  - Broadcasts Data to All Ports: No intelligence to send data only to the intended device.
  - Half-Duplex: Data can only go in one direction at a time, limiting efficiency.
  - Collision-Prone: Especially in larger networks, hubs can slow down performance due to frequent data collisions.
    **Use Cases** :
  - Suitable for small or simple networks where speed and security are not crucial.
  - Rarely used today because switches offer better performance.

2. **switch**
  - A switch is a more advanced device and operates at the Data Link Layer (Layer 2) of the OSI model. 
  - Unlike hubs, switches learn which devices are connected to each of its ports using MAC addresses.
  **How a Switch Works** :
  - When a switch receives a frame, it checks the destination MAC address and forwards the data only to the port connected to that address.
  - Switches create separate collision domains for each connected device, allowing full-duplex communication (data can flow both ways simultaneously).
  - The switch maintains a MAC address table to remember which device is on which port, improving efficiency.
  **switch Characteristics** :
  - Unicast Data Forwarding: Sends data only to the destination device rather than broadcasting to all ports.
  - Full-Duplex Communication: Allows devices to send and receive data at the same time, reducing delays.
  - Isolated Collision Domains: Each port has its own collision domain, so devices can communicate without interference.
  **Use Cases** :
  - Ideal for local area networks (LANs) and modern office environments where performance and network traffic management are important.
  - Switches are widely used for connecting devices in homes, offices, and data centers.

3. **Router** 
  - A router operates at the Network Layer (Layer 3) of the OSI model and is more complex than switches and hubs. 
  - Routers are responsible for connecting different networks and directing data between them.
  **How a Router Works** :
  - Routers analyze the IP addresses in data packets and determine the best path for sending data to its destination, even across different networks (e.g., from a local network to the internet).
  - They maintain routing tables that store information about available paths to different networks, which they update dynamically.
  - Routers can also provide Network Address Translation (NAT), allowing multiple devices on a local network to share a single public IP address when connecting to the internet.
  **Router Characteristics** :
  - Directs Data Between Networks: Connects and manages traffic between different networks (e.g., LAN to WAN).
  - IP-Based Forwarding: Uses IP addresses to decide where to send data.
  - Routing Protocols: Uses protocols like OSPF, BGP, or RIP to communicate with other routers and determine optimal paths.
  **Use Cases** :
  - Essential for connecting a local network to the internet or linking multiple networks (e.g., different branches of a company).
  - Used at home to connect multiple devices to an internet service provider (ISP).

4. **Modem**
  - A modem (short for Modulator-Demodulator) is a device that connects your local network to your Internet Service Provider (ISP) and enables internet access. 
  - It translates the signals from your ISP (over phone lines, coaxial cable, fiber, or satellite) into a digital signal that your devices can understand.
  **How a Modem Works** :
  - Modulation: Converts digital data from your network (like your computer) into analog signals that can travel over various types of lines.
  - Demodulation: Converts analog signals from the ISP into digital data for your devices to use.
  **Types of Modems** :
  - DSL Modem: Connects via phone lines.
  - Cable Modem: Connects via coaxial cable.
  - Fiber Modem (ONT): Connects to fiber-optic lines.
  **Function** :
  The modem connects directly to the ISP and provides a single IP address to the connected device, which is often your router.
  **Use Case** :
  Essential for translating internet signals from an ISP into a form usable by your local network.
  **Modem + Router Combos** :
  - In many modern setups, a modem and router are combined into a single device, especially in home networks provided by ISPs. 
  - This device performs both functions: translating signals for internet access (modem) and managing local network traffic (router).

## What is a Loopback Address?
  - A loopback address is like a special shortcut on your computer. It allows your computer to talk to itself. 
  - This address is mainly used for testing and making sure your computer's network parts are working.

**How Does It Work**?
  - Every device that uses the internet has an IP address to talk to other devices.
  - But when we use a loopback address, we are telling the computer, "Send this data back to yourself."
  - It’s like writing yourself a letter and putting it in your mailbox. The message never leaves your house; it’s just for you!
**What Is the Loopback Address**?
  - In IPv4 (the older IP system), the loopback address is 127.0.0.1.
  - In IPv6 (the newer IP system), the loopback address is ::1.
  - These addresses always mean "this computer" and will never reach out to another device on the network.
**Why Use It**?
  - Testing: We use 127.0.0.1 (or localhost) to check if the computer’s network is working without needing any other device or an internet connection.
  - Developing and Running Programs: If you're testing a program, like a website, on your computer, 
  - you can type 127.0.0.1 or localhost in your browser to open it without needing to be online.

### 13. What is a subnet?

- Explain the concept of subnetting and its efficiency in networks.

### 14. How to calculate a subnet mask from an IP address (step by step)?
  - Provide the detailed steps using the example IP address 10.20.4.13/29, including:
  - Finding the subnet number
  - Calculating the subnet mask
  - Determining subnet size
  - Finding the broadcast address
  - Identifying the IP address subnet
  - Calculating valid hosts
