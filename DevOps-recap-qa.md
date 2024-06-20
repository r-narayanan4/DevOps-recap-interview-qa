# Interview Questions

### 1. Tell me about yourself

Hello, it's nice to meet you. I'm Lakshmi Narayanan, and I'm excited to discuss how my skills and experience can benefit your company.

**Skills:**

To start with, I’m skilled at using tools like Jenkins for continuous integration and delivery (CI/CD). I can manage containers with Kubernetes and Docker, and I also have good experience with configuration management tools like Ansible. I also have hands-on experience with AWS and Terraform to set up and manage infrastructure.

**Experience/Education:**

In 2021, I earned my degree in Electronic and Communication Engineering. After that, I worked for Buildbot Technologies for more than a year as a DevOps engineer. Throughout my employment, I specialized in automating and optimizing development workflows, particularly through scalable CI/CD pipelines and configuration management.

**Type of Person:**

I am always eager to learn new technologies and actively seeking opportunities to apply my skills.

### 2. Why did you leave your previous company?

I left my old job to grow in my career and take on new challenges. While I enjoyed my time there, I felt ready for something new. Plus, I wanted to be closer to my hometown.

or 

I quit my previous work to advance in my profession and take on new challenges. Even though I had a great time there, I was ready for something different. I also desired to live nearer to my hometown.

### 3. What is your expected salary?

I'm aiming for a salary that reflects my experience and the responsibilities of the role, ensuring a win-win situation for both of us.

### 4. How soon can you join?

I can join immediately as I am currently not employed and do not have any notice period to fulfill. I am ready to start at your earliest convenience.

### 5. What are your day-to-day tasks as a DevOps engineer?

On a typical day, I design and maintain CI/CD pipelines, manage infrastructure with Ansible, and collaborate with development and QA teams. I focus on automating tasks to improve efficiency and troubleshoot issues in various environments.

### 6. Can you explain the projects you have worked on?

I worked on a project for a pharmaceutical client where I automated Kubernetes cluster provisioning using Ansible. I also set up GitHub Actions to automate updates to running pods and created Jenkins pipelines to enhance deployment efficiency.

### 7. What would you do if a pipeline breaks at the time of deployment?

If a pipeline breaks during deployment, I would first halt the deployment to prevent further issues. I would then review logs to identify where the failure occurred and determine the cause. Informing the relevant team members is crucial, so I would quickly communicate the issue and our plan.

Next, I would either apply a quick fix or rollback to the previous stable state, ensuring thorough testing before re-deploying. After resolving the immediate problem, I would conduct a root cause analysis to prevent future occurrences and update our processes and documentation accordingly.

### 8. What is DevOps?

DevOps is a methodology focused on enhancing application delivery through automation, maintaining code quality, and ensuring continuous monitoring and testing.

### 9. Why DevOps?

Before DevOps:

- Developers would develop the code.
- System Administrators would create a server.
- Build and Release Engineers would install required tools onto the server.
- Server Administrators would deploy the application.

This process often took 10 days to deliver an application due to its manual and sequential nature, lacking effectiveness and agility.


### 10. What is Software Development Life Cycle (SDLC)

1. **Planning:**
   - Involves gathering requirements, defining the scope of the project, and planning the timeline and resources needed.
   - Sets the foundation for what the software will achieve and how it will be developed.

2. **Design:**
   - Focuses on creating a blueprint or design for the software based on the requirements gathered.
   - Architects outline the software's structure, user interface, and technical specifications.

3. **Development:**
   - Coding and implementation based on design specifications.
   - Developers build features and integrate components to create the application.

4. **Testing:**
   - Verifying that the software works as intended and meets requirements.
   - Includes unit testing, integration testing, system testing, and acceptance testing.

5. **Deployment:**
   - Releasing and deploying the software into the production environment.
   - Involves installation, configuration, and ensuring readiness for end-users.

### Example: E-commerce Company

- **Planning:** Defining requirements and functionalities for the e-commerce platform.
- **Designing:** Creating wireframes, database schemas, and architectural designs.
- **Building:** Developing front-end and back-end components of the website/application.
- **Testing:** Ensuring functionality and reliability of features like shopping carts and payment gateways.
- **Deployment:** Releasing updates and new features for customer use.

### DevOps Engineer Focus

- **Build:** Automating compilation, packaging, and artifact preparation.
- **Testing:** Implementing automated tests for code quality and reliability.
- **Deployment:** Automating release pipelines for efficient updates to production.

DevOps Engineers enhance software delivery by integrating automation and continuous integration/continuous delivery (CI/CD) practices, ensuring frequent and high-quality releases.

## 11. What is the Agile methodology?

Agile methodology is a project management framework that breaks projects down into several dynamic phases, commonly known as sprints.

The Agile framework is an iterative methodology. After every sprint, teams reflect and look back to see if there was anything that could be improved so they can adjust their strategy for the next sprint.


# Networking Concepts

## 1. What is a Network?
When two or more computers and computing devices are connected together through communication channels, such as cables or wireless media, and share files, it is called a Network.

### A network is used to:
- Allow the connected devices to communicate with each other.
- Enable multiple users to share devices over the network, such as music and video servers, printers, and scanners.

The Internet is the largest network in the world and can be called "the network of networks".

## 2. What are Types of Networks?
There are different types of networks. But the main two are LAN and WAN:

- **LAN (Local Area Network)**: Interconnects computers within a limited area, such as residences or schools. Examples: Wi-Fi, Ethernet.
- **MAN (Metropolitan Area Network)**: Used in metropolitan areas (cities).
- **WAN (Wide Area Network)**: Extends LAN over a large geographic area. Example: Optical fiber cable.
- **SONET (Synchronous Optical Network)**: Used in submarine communications.

## 3. List the Network Components
1. **Switch**: A device that connects two or more computers.
   - Creates a MAC address table to manage data transfer.
   - Types:
     - **Unmanaged switch**: Simple device, data sent to one device reaches all devices.
     - **Managed switch**: Supports VLAN, used in companies.

2. **Router**: Connects one network to another.
   - Often combined with modem and switches in home devices (ADSL).

3. **Modem**: Used for modulation and demodulation.
   - Converts analog signals to digital and vice-versa.

4. **Hub**: Broadcasts signals to all connected computers.
   - Replaced by switches due to inefficiency in data handling.

5. **NIC (Network Interface Card)**: Connects a computer to the internet.
   - Has a MAC (Media Access Control) address.

6. **Bridge**: Connects multiple LANs to form a larger LAN.
   - Reduces broadcasting, stores MAC addresses, replaced by switches.

## 4. What is a Protocol?
A network protocol is a set of rules that determine how data is transmitted between different devices in the same network. Examples: HTTP, TCP, IP, FTP, SMTP.

## 5. List the IP Address and its Types and Classes
Every device on the internet must have at least one unique network address identifier known as the IP (Internet Protocol) address.

### Types of IP addresses:
- **IPv4**: 32-bit address, divided into 4 groups or Octets.
  - Example: 123.89.46.72 (dotted decimal notation).

- **IPv6**: 128-bit address, represented by hexadecimal values.

### Classes of IP address (mainly for IPv4):
- **Class A**: 0.0.0.0 to 127.255.255.255
- **Class B**: 128.0.0.0 to 191.255.255.255
- **Class C**: 192.0.0.0 to 223.255.255.255
- **Class D**: 224.0.0.0 to 239.255.255.255 (reserved for multicast groups)
- **Class E**: 240.0.0.0 to 255.255.255.255 (reserved for future use)

### Special Addresses:
- **Loopback**: 127.0.0.0 to 127.255.255.255 (used for diagnostics).

### Example IP Address:
- **192.168.1.10** (Class C)
  - **Subnet Mask**: 255.255.255.0
  - **Network Part**: 192.168.1
  - **Host Part**: 10

### Explanation:
- **Network Part (192.168.1)**: First three octets define the network segment.
- **Host Part (10)**: Last octet identifies the specific device within the network segment.

### Network ID and Host ID:
- **Class A**: First octet is Network ID, remaining three are Host ID.
- **Class B**: First two octets are Network ID, remaining two are Host ID.
- **Class C**: First three octets are Network ID, last octet is Host ID.

## 6. What are the Network Topologies?
A Network Topology is the shape or arrangement of a network with which computer systems or network devices are connected to each other. Topologies may define both physical and logical aspects of the network.

## 7. List the Different Types of Network Topologies?
1. **Bus Topology**:
   - **Definition**: All devices are connected to a single central cable (bus).
   - **Advantages**: Easy to install, requires less cable.
   - **Disadvantages**: Main cable failure can bring down the entire network.

2. **Ring Topology**:
   - **Definition**: Each device is connected to two others, forming a circular data path.
   - **Advantages**: Fast data packets, fewer collisions.
   - **Disadvantages**: A failure in any cable or device can disrupt the network.

3. **Star Topology**:
   - **Definition**: All devices are connected to a central hub or switch.
   - **Advantages**: Easy to install/manage, single device failure does not affect the entire network.
   - **Disadvantages**: Central hub failure brings down the entire network.

4. **Tree Topology**:
   - **Definition**: Hybrid topology combining characteristics of star and bus topologies.
   - **Advantages**: Hierarchical, scalable.
   - **Disadvantages**: Backbone line failure affects the entire segment.

5. **Mesh Topology**:
   - **Definition**: Each device is connected to every other device.
   - **Advantages**: High reliability and redundancy.
   - **Disadvantages**: Expensive and complex to install.

Each topology has its strengths and weaknesses, and the choice depends on the specific needs and constraints of the network being designed.

## 8. List type of Networking Models?

There are mainly two types of network model -

1. OSI Reference Model

2. TCP/IP Model

### OSI Reference Model

The OSI model (or Open Systems Interconnection Model) is a reference model created by ISO (International Organization for Standardization) which describe how different types of systems communicate together. The OSI model consists of seven different layers that each have its own unique purpose and responsibilities. This is an imaginary model.

1. **Physical Layer** - Transmits raw bit stream over the physical medium

   In this layer, data will be converted into digital signal(0 and 1) is called Encoding. Then the signal will travel via cable to another device (receiver). Now, these above 7 processes will also be occurred in the receiver device.

2. **Data Link Layer** - Defines the format of Data on the network

   In this layer, each packet is converted into Frame. In each packet, the source MAC address and the destination MAC address (physical address of the device)is added by this layer. Frame is another abstraction (layer) of Packets which contain both the MAC addresses. Switch works in this layer for selecting which device it has to send that data connected with that Switch

3. **Network Layer** - Decides which physical path the data will take

   In this layer, each data segment is converted into Packets. In each packet's Source IP address (sip) and the destination IP address (dip) is added by this layer. Actually, Packets is the abstraction (layer) of Segments. Router works in this layer for connecting one Host with another Host (different network).

4. **Transport Layer** - Transmits Data using transmission protocols including TCP and UDP

   By this Layer the Data in converted into small segments means this layer divides the data in multiple chunks or parts. This layer is also responsible for sequencing the segment, means it will actually add the serial number on each data segment. Because when the data is travelling from one PC to another PC over the internet, so might be there is a chance that one part/segment of data will be dropped. So when the data will be reached from Host-A to Host-B then B will check oK! I got 1,3,4,5 segments, but I have not received the no. 2 segment. Then B will send request again to A that can you please retransmit again no. 2 segment. This layer use some checksum, and it takes care of congestion control. And this layer is responsible for retransmission also.

   **Protocols:**
   A Protocol is set of rules that defines how data is transmitted and received between devices in a network. It ensures standardized communications allowing different systems to understand  and interact with each other. Ex: TCP/IP, HTTP, and SMTP.
   1. **TCP (transmission control Protocol):**

      **Description:** TCP Operates at the transport layer of the OSI model. It Establishes a connection between two devices before data exchange, ensuring reliable and ordered delivery of information. ex: HTTP - port 80, MongoDB - port 27017, SQL - port 1433 etc.

      **Functionality:** It breaks data into packets assigns sequence numbers and uses acknowledgement messages to guarantee delivery. It' Connection-oriented meaning it sets up maintains, and terminates a connection for data exchange.

   2. **UDP (User Datagram Protocol):**

      **Descripting:** Also operating at Transport layer, UDP is a connectionless protocol that offers minimal services. Its like a fire and forget approach for data transmission.

      **Functionality:** It sends data without establishing a connection providing low latency communication. However, it doesn't guarantee delivery or order, making it suitable for real-time applications like video streaming or online gaming.

5. **Session Layer** - Maintains connections and is responsible for controlling ports and sessions .

   When the data is moving to Session Layer, so session layer is actually create and maintain the sessions with the time frame. Whenever you open any bank website, it has a time limit. If you are away from your keyboard for some time, then that session will automatically log out. If you are not using your keyboard or mouse pointer or anything, then the session will log out automatically by a session layer algorithm written by the developers. This is the responsibility of Session Layer.

6. **Presentation Layer** - Ensures that data is in a usable format and is where data encryption occurs.

   This layer actually tells about the Format of Data(just remember this 🙂) means when you see a webpage like google.com or YouTube.com, there you can see many videos, images, thumbnail of videos, comments and all. So the presentation layer helps to represent the data of any format.

7. **Application Layer** - Human-computer interaction , where applications can access the network services.

   Any software which interacts directly with one human to another comes under Application Layer. e.g :- WhatsApp, Gmail, Web browser etc. Different types of protocol given below is used in Application Layer

### TCP/IP Model

This model is a real model which actually works in real. This model consist of 4 layers.

- Application Layer = (Application Layer + Presentation Layer + Session Layer) of OSI model
- Transport Layer
- Network Layer
- Network Interface Layer = (Data Link Layer + Physical Layer) of OSI model (remaining all are same like OSI model discussed above.)

## 9.What is DNS?

DNS, or the Domain Name System, translates human-readable domain names (for example, www.amazon.com) to machine-readable IP addresses (for example, 192.0.2.44). It is a phone book of the Internet. Each device connected to the Internet has a unique IP address, which other machines use to find the device. DNS servers eliminate the need for humans to memorize IP addresses such as 192.168.1.1 (in IPv4), or more complex newer alphanumeric IP addresses such as 2400:cb00:2048:1::c629:d7a2 (in IPv6). Root DNS Server stores all the Top level domain e.g :- .io, .com, .org etc.


## 10. What is Subnet mask?

Subnet Mask represents the network bits. Computer needs extra information that computer belongs to which network. Subnet mask is represented by / value.

/8 = 255.0.0.0 means it represents 8 bits of an IP address and if you add all 8 bits like (2^7+2^6+2^5+2^4+2^3+2^2+2^1+2^0 = 255). Each octet can vary from 0-255.

but what will be the value of  /9

/9 = 8+1 = 255.128.0.0 is the subnet mask

If you add 8 bits you will get 255 

2^7+2^6+2^5+2^4+2^3+2^2+2^1+2^0

1 + 0 + 0 + 0 + 0 + 0 + 0 + 0 = 128

### Shortcut Table

If you get extra | Add This
--------------- | --------
1               | 128
2               | 192
3               | 224
4               | 240
5               | 248
6               | 252
7               | 258

Then /12 will be  = 255.240.0.0  is the subnet mask

/30 = 255.255.255.252


## 11. What is Subnetting (CIDR)?

Subnetting is a technique used in computer networking to divide a larger IP network into smaller, more manageable sub-networks or subnets.

CIDR Notation:
Classless Inter-Domain Routing (CIDR) is a system used to express subnetting. It allows specifying the number of significant bits in an IP address that make up the network portion.

For example, the IP address 192.168.0.15 with a subnet mask of 255.255.255.0 can be expressed in CIDR notation as 192.168.0.15/24, indicating that the first 24 bits are dedicated to the network.

## 12. What is Forward Proxy and Reverse Proxy?

#### Forward Proxy

Definition:
A forward proxy, or proxy server, routes traffic between clients and external systems. It regulates traffic, masks client IP addresses, enforces security protocols, and can block unwanted traffic.

Key Features:
- Client-Side Proxy: Manages client access to the internet.
- Anonymity: Hides client IP addresses from destination servers.
- Content Filtering: Blocks access to specific websites or content.
- Caching: Improves performance by caching frequently requested resources.

Example Use Case:
An organization uses a forward proxy to control and monitor employee internet access.

#### Reverse Proxy

Definition:
A reverse proxy protects servers by receiving client requests, forwarding them to backend servers, and returning the server's response to clients. Clients are unaware of the backend servers handling their requests.

Key Features:
- Server-Side Proxy: Manages client requests to backend servers.
- Load Balancing: Distributes client requests across multiple servers.
- Security: Hides backend servers, adding an extra layer of security.
- SSL Termination: Handles SSL encryption/decryption to reduce backend load.

Example Use Case:
A website uses a reverse proxy to distribute incoming traffic across multiple web servers for improved availability and performance.

## 13. What is VPN (Virtual Private Network)?

Definition:
A Virtual Private Network (VPN) is a technology that establishes a secure and encrypted connection over less secure networks, such as the internet. It allows users to securely send and receive data as if their devices were directly connected to a private network.

Key Features:
- Encryption: Secures data transmission to prevent eavesdropping.
- Remote Access: Enables secure access to a private network from remote locations.
- Anonymity: Masks user IP addresses for enhanced privacy.
- Bypass Geographical Restrictions: Access region-restricted content by appearing to be in a different location.

Example Use Case:
An employee uses a VPN to securely connect to their company's internal network while working remotely, accessing resources as if they were in the office.


# Linux Concepts

[Linux For DevOps](https://github.com/r-narayanan4/Linux-For-DevOps.git)

# Shell Scripting 


