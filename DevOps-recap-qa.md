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

- [Shell Scripting](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/5.Shell-Scripting/shell.md): Resources and examples for learning and mastering shell scripting.

# Git

- [Version Control Systems (VCS)](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/2.VCS/VCS.md): Comprehensive guide to Version Control Systems, covering Git, SVN, and other VCS tools commonly used in DevOps workflows.


# CI/CD - Jenkins and GithubActions

- [Jenkins Setup Guide](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/7.CI-CD/Jenkins/jenkins.md): This document provides a comprehensive guide to setting up Jenkins for CI/CD pipelines.

- [GitHub Actions Guide](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/7.CI-CD/Github-Actions/github.md): Comprehensive documentation on GitHub Actions for CI/CD pipelines.

- [GitLab Setup and Usage](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/7.CI-CD/Gitlab/gitlab.md): Guide for setting up GitLab and utilizing it for CI/CD.

# Docker

- [Docker Interview Questions](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/9.Docker/docker-interview-questions.md): Common Docker interview questions and their explanations.

# Kubernetes

- [Kubernetes Guide](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/10.Kubernetes/Kubernetes.md): Comprehensive guide to Kubernetes for container orchestration.

# Ansible

## 1. What is Ansible?

Ansible is an open-source automation tool used for configuration management, application deployment, and task automation. It allows infrastructure as code (IaC) by defining configurations in simple, human-readable YAML files called playbooks.

## 2. What is Agentless in Ansible?

Ansible is agentless, meaning it does not require any software to be installed on the managed hosts. Instead, it connects to hosts via SSH (Secure Shell) and executes tasks using modules written in Python.

## 3. Explain about the architecture of Ansible?

Ansible follows a client-server architecture where:
- Control Node: Machine where Ansible is installed and from which tasks are executed.
- Managed Nodes: Remote hosts managed by Ansible.

## 4. Explain about the structure of Ansible Playbook?

An Ansible playbook is structured using YAML and consists of:
- Hosts: Defines which hosts to target.
- Variables: Allows parameterization of tasks.
- Tasks: List of actions to be executed on the hosts.
- Handlers: Tasks triggered by specific events.
- Roles: Organizational units for playbooks.

## 5. What is the command to run an Ansible playbook?

To run an Ansible playbook:
```bash
ansible-playbook playbook.yml
```
## 6. How do you test an Ansible playbook?

To test an Ansible playbook without making changes, use the `--check` flag:
```bash
ansible-playbook playbook.yml --check
```

## 7. What is a module in an Ansible playbook? List some modules.

In Ansible, a module is a reusable, standalone script that Ansible uses to perform tasks. Modules can be used to interact with system components such as files, packages, services, and more. Some commonly used modules include:
- `yum`: Manages packages on RPM-based systems.
- `apt`: Manages packages on Debian-based systems.
- `copy`: Copies files from the local or remote machine to a target location.
- `file`: Manages filesystem objects like directories, symlinks, and permissions.

## 8. What is SSH?

SSH (Secure Shell) is a cryptographic network protocol that allows secure communication between two computers. In the context of Ansible, SSH is used as the default method for connecting to and executing commands on remote servers.

## 9. What are roles in Ansible?

Roles in Ansible are a way to organize and structure your playbooks. A role is essentially a collection of variables, tasks, files, templates, and handlers that can be easily reused across multiple playbooks. Roles help in maintaining clean and modular Ansible code, promoting reusability and readability.

## 10. What is a Jinja template in Ansible?

Jinja is a modern and designer-friendly templating language for Python, modelled after Django’s templates. It is used within Ansible to dynamically generate and manipulate configuration files and scripts. Jinja templates allow you to include variables and control structures in your files, making your configurations more flexible and dynamic.

## 11. What are handlers in Ansible?

Handlers in Ansible are tasks that are only executed when notified by other tasks. They are typically used to restart services or perform similar actions that should only occur when a change has been made. Handlers are defined separately from tasks and are notified using the `notify` directive within tasks.

```yaml
---
- name: Example playbook with handlers
  hosts: all
  tasks:
    - name: Ensure nginx is installed
      yum:
        name: nginx
        state: present
      notify:
        - Restart nginx

  handlers:
    - name: Restart nginx
      service:
        name: nginx
        state: restarted
```
## 12. What is configuration management?

   Configuration management refers to the process of systematically handling changes to a system in a way that it maintains integrity over time. It typically involves tracking and controlling changes to software, infrastructure, and documentation, ensuring that systems are configured correctly and consistently.

## 13. What type of Architecture is ansible?

   Ansible follows a client-server architecture or a master-slave architecture. It uses a push mechanism where the control node (Ansible master) pushes configurations and tasks to remote nodes (Ansible clients) using SSH.

## 14. What are tasks in ansible?

   In Ansible, tasks refer to the individual units of work that perform actions on remote hosts. Tasks are defined within playbooks and are executed sequentially. They can include a wide range of actions such as installing packages, managing files, running commands, and more.

## 15. What is Active-Passive Deployment strategy with Ansible?

Active-Passive deployment strategy with Ansible involves configuring redundant servers where one (active) serves production traffic while the other (passive) remains on standby. This setup ensures high availability by quickly switching to the passive server if the active one fails.

#### Examples of Deployment Strategies:

1. **Single server:**
   - Only one server is active at a time, with others on standby.
   
2. **Multi-server:**
   - **Deploy on all servers:** Ansible deploys updates to all servers simultaneously.
   - **Deploy on selected servers:** Ansible targets specific servers for updates using tags or group names.
   - **Blue / Green strategy:** Involves maintaining two identical production environments, where one (blue) is active while the other (green) remains inactive but ready to take over.

#### Blue / Green Deployments:

Blue / Green deployments involve maintaining two identical production environments (blue and green). Here’s how Ansible flags --limit blue and --limit green are used:

- `--limit blue`: Limits the deployment to servers in the blue environment.
- `--limit green`: Limits the deployment to servers in the green environment.

This concept allows for seamless updates and rollback capabilities without downtime, ensuring continuous availability and reducing risk during deployment.
example:
ansible-playbook deploy.yml --limit blue
ansible-playbook deploy.yml --limit green

## 16. What is Ansible Vault? Give commands to use Ansible Vault.

   Ansible Vault is a feature of Ansible that allows you to encrypt sensitive data within your Ansible projects. It provides a way to securely store and manage secrets, such as passwords, API keys, and certificates.

   #### Commands to use Ansible Vault:
   
   - **Create a new encrypted file:**
     ```
     ansible-vault create secrets.yml
     ```
     This command will create a new encrypted file named `secrets.yml` and prompt you to set a password.
   
   - **Edit an existing encrypted file:**
     ```
     ansible-vault edit secrets.yml
     ```
     This command allows you to edit an existing encrypted file `secrets.yml`.
   
   - **Encrypt an existing file:**
     ```
     ansible-vault encrypt secrets.yml
     ```
     Encrypts an existing plaintext file `secrets.yml`.
   
   - **Decrypt an encrypted file:**
     ```
     ansible-vault decrypt secrets.yml
     ```
     Decrypts an encrypted file `secrets.yml` back to plaintext.

## 17. What are Ansible Ad-Hoc commands? Give some example commands.

   Ansible Ad-Hoc commands are one-liners that allow you to perform quick tasks without creating a playbook. They are useful for tasks like running ad-hoc commands, copying files, managing packages, etc.

   #### Examples of Ansible Ad-Hoc commands:
   
   - **Ping all servers:**
     ```
     ansible all -m ping
     ```
     Checks connectivity to all servers.
   
   - **Install a package:**
     ```
     ansible webserver -m yum -a "name=httpd state=installed"
     ```
     Installs Apache (`httpd`) on servers in the `webserver` group.
   
   - **Copy a file:**
     ```
     ansible webserver -m copy -a "src=file.txt dest=/etc/file.txt"
     ```
     Copies `file.txt` to `/etc/file.txt` on servers in the `webserver` group.

## 18. What is inventory and hosts in Ansible? What is the first precedence for ansible.cfg and what is the order of precedence locations?

   **Inventory and Hosts:**
   - **Inventory:** An inventory in Ansible is a file or directory where you define your managed hosts (servers). It can be a simple text file (`hosts`) or a directory (`inventory/`) containing multiple inventory files.

   - **Hosts:** Hosts are individual machines or servers managed by Ansible. They are defined within the inventory file(s) and grouped based on roles or environments.

   **Precedence for ansible.cfg:**
   - The first precedence for `ansible.cfg` is the current working directory (`./ansible.cfg`).
   - Ansible then looks for `/etc/ansible/ansible.cfg`.
   - If none of the above are found, it uses the default settings built into Ansible.

   **Order of Precedence Locations:**
   1. Current working directory (`./ansible.cfg`).
   2. `/etc/ansible/ansible.cfg`.
   3. Default settings within Ansible.

## 19. Difference between import and include in Ansible playbook?

   - **Import:** Imports another playbook into the current playbook at the location where the `import` statement is used. The imported playbook is run independently of the current playbook.

   - **Include:** Includes another playbook into the current playbook at the location where the `include` statement is used. The included playbook is integrated into the tasks of the current playbook.

   **Example:**
   ```yaml
   - name: Include another playbook
     include: tasks.yml

   - name: Import another playbook
     import_playbook: tasks.yml
```
## ### Ansible Interview Question and Answer

20. What is Error handling in Ansible playbook? Give examples.

Error handling in Ansible playbook allows you to manage and respond to errors that may occur during playbook execution. This ensures graceful handling of failures and enhances playbook robustness.


#### Examples of Error Handling:

- **Ignore errors for a specific task:**
  ```yaml
  - name: Attempt to restart a service (may fail)
    service:
      name: myservice
      state: restarted
    ignore_errors: yes
   #This task attempts to restart myservice but ignores any errors that occur.

  #Fail the playbook on error

  - name: Ensure package is installed
  package:
    name: mypackage
    state: present
  failed_when: false
  ```
This task ensures mypackage is installed and explicitly specifies not to fail even if the package is already present.

- [Ansible remaining questions](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/8.Ansible/ansible.md): Documentation and tutorials for Ansible configuration management tool.

# AWS

- [AWS Interview Questions](https://github.com/iam-veeramalla/aws-devops-zero-to-hero/tree/main/interview-questions)

- [AWS Cloud Guide](https://github.com/r-narayanan4/Interview-preparation-for-DevOps/blob/main/11.Cloud/AWS/aws.md): Documentation and resources for AWS services and cloud concepts.

- [AWS Interview Questions](https://github.com/r-narayanan4/AWS-Hands-on-and-scenarios/tree/main/21.AWS_Interview_Questions): Collection of AWS interview questions and scenarios for preparation.

# Terraform

- [AWS Terraform Interview Questions](https://github.com/iam-veeramalla/aws-devops-zero-to-hero/blob/main/interview-questions/aws-terraform.md): Interview questions related to AWS and Terraform.

# Monitoring tool

# Prometheus

## 1. What is Observability

**Observability** – The ability to understand and measure the state of a system based on data generated by the system in unexpected scenarios.

Observability allows you to generate actionable outputs from unexpected scenarios in dynamic environments. Observability will help:

1. Give better insight into the internal workings of a system/application.
2. Speed up troubleshooting.
3. Detect hard-to-catch problems.
4. Monitor performance of an application.
5. Improve cross-team collaboration.

The main purpose of observability is to better understand the internals of your system.

**Observability**

When it comes to troubleshooting issues, we need more information than just what is wrong. We need to know why our application entered a specific state, what component is responsible, and how we can avoid it in the future:

- Why are error rates rising?
- Why is there high latency?
- Why are services timing out?

Observability gives you the flexibility to understand unpredictable events.

### 3 Pillars of Observability

How do we accomplish observability?

- **Logging**
- **Metrics**
- **Traces**

## 2. What are Logs?

**Logging**

Logs are records of events that have occurred and encapsulate information about the specific event. Logs are comprised of:

- Timestamp of when the log occurred.
- Message containing information.

Logs are the most common form of observation produced by systems. However, they can be difficult to use due to the verbosity of the logs outputted by systems/applications. Logs of processes are likely to be interwoven with other concurrent processes spread across multiple systems.

## 3. What are Traces?

**Traces**

Traces allow you to follow operations as they traverse through various systems and services. So we can follow an individual request and see it flow through our system hop by hop. Traces help us connect the dots on how processes and services work together.

Each trace has a trace-id that can be used to identify a request as it traverses the system. Individual events forming a trace are called spans. Each span tracks the following:

- Start time.
- Duration.
- Parent-id.

## 4. What are Metrics?

**Metrics**

Metrics provide information about the state of a system using numerical values:

- CPU Load
- Number of open files
- HTTP response times
- Number of errors

The data collected can be aggregated over time and graphed using visualization tools to identify trends over time. Metrics contain 4 pieces of information:

1. Metric name.
2. Value – most recent or current value of the metric.
3. Timestamp for the metric.
4. Dimensions – additional information about the metric.

Example:
node_filesystem_avail_bytes{fstype="vfat", mountpoint="/home"} 5000 4:30AM 12/1/22

here we can look at the table

| Metric Name                     | Dimensions                          | Value | Timestamp         |
|---------------------------------|-------------------------------------|-------|-------------------|
| node_filesystem_avail_bytes     | {fstype="vfat", mountpoint="/home"} | 5000  | 4:30AM 12/1/22    |


## 5. Define SLI/SLO/SLA?

**SLI/SLO/SLA**

When designing a system or applications, it's important for teams to set specific measurable targets/goals to help organizations strike the right balance between product development and operation work. These targets help customers and end users quantify the level of reliability they should come to expect from a service.

Example: “Application should have 97% uptime in a rolling 30-day window”

### Service Level Indicator (SLI)

**Service Level Indicator (SLI)** – quantitative measure of some aspect of the level of service that is provided.

Common SLIs:

- Request Latency
- Error Rate
- Saturation
- Throughput
- Availability

Not all metrics make for good SLIs. You want to find metrics that accurately measure a user’s experience. High-cpu/high-memory make for a poor SLI as a user might not see any impact on their end during these events.

### Service Level Objective (SLO)

**Service Level Objective (SLO)** – target value or range for an SLI.
- SLI - Latency
- SLO – Latency < 100ms
- SLI – Availability
- SLO – 99.9% uptime

SLOs should be directly related to the customer experience. The main purpose of the SLO is to quantify the reliability of a product to a customer. 

It may be tempting to set SLOs to aggressive values like 100% uptime; however, this will come at a higher cost. The goal is not to achieve perfection but instead to make customers happy with the right level of reliability. If a customer is happy with 99% reliability, increasing it any further doesn’t add any other value.

### Service Level Agreement (SLA)

**Service Level Agreement (SLA)** – contract between a vendor and a user that guarantees a certain SLO. The consequences for not meeting any SLO can be financial based but can also be a variety of other things as well.

## 6. What is Prometheus?

Prometheus is a monitoring solution responsible for collecting and aggregating metrics. It is an open-source monitoring tool that collects metrics data and provides tools to visualize the collected data. In addition, Prometheus allows you to generate alerts when metrics reach a user-specified threshold.

Prometheus collects metrics by scraping targets who expose metrics through an HTTP endpoint. Scraped metrics are then stored in a time-series database which can be queried using Prometheus’ built-in query language PromQL.

### What kind of metrics can Prometheus Monitor?

- CPU/Memory Utilization
- Disk space
- Service Uptime
- Application specific data
- Number of exceptions
- Latency
- Pending Requests

Prometheus is designed to monitor time-series data that is numeric. 

### What type of data should Prometheus not monitor?

- Events
- System logs
- Traces

## 7. Explain Prometheus Architecture

Refer to this link: [Prometheus Architecture](https://devopscube.com/prometheus-architecture/)

### Pull-Based Model

Prometheus follows a pull-based model. Prometheus needs to have a list of all targets it should scrape. Other pull-based monitoring solutions include:

- Zabbix
- Nagios

### Push-Based Model

In a push-based model, the targets are configured to push the metric data to the metrics server. Push-based systems include:

- Logstash
- Graphite
- OpenTSDB

### Why Pull?

Some of the benefits of using a pull-based system:

- Easier to tell if a target is down. In a push-based system, we don’t know if it’s down or has been decommissioned.
- Push-based systems could potentially overload the metrics server if too many incoming connections get flooded at the same time.
- Pull-based systems have a definitive list of targets to monitor, creating a central source of truth.

### Why Push?

Push-based monitoring excels in the following areas:

- Event-based systems, where pulling data wouldn’t be a viable option. However, Prometheus is for collecting metrics and not monitoring events.
- Short-lived jobs, as they may end before a pull can occur. Prometheus has a feature called Pushgateway to handle this situation.

# Grafana Basics

## What is Grafana?

Grafana is an open-source platform for monitoring and observability. It allows you to visualize and analyze metrics collected from various sources, create alerts, and share dashboards.

## Basic Questions for Beginners

### 1. What is Grafana used for?

Grafana is used for visualizing time-series data from various sources, creating interactive dashboards, setting up alerts, and providing insights into the performance and state of systems and applications.

### 2. What data sources can Grafana integrate with?

Grafana supports a wide range of data sources, including:

- Prometheus
- Graphite
- InfluxDB
- Elasticsearch
- MySQL
- PostgreSQL
- AWS CloudWatch
- Microsoft SQL Server

### 3. How do you create a dashboard in Grafana?

To create a dashboard in Grafana:

1. Click on the "+" icon in the left sidebar.
2. Select "Dashboard."
3. Click "Add new panel."
4. Choose a data source and configure the query.
5. Customize the visualization and save the panel.
6. Repeat to add more panels to the dashboard.

### 4. What are panels in Grafana?

Panels are the basic building blocks of a Grafana dashboard. Each panel can display data using different types of visualizations such as graphs, tables, heatmaps, and more.

### 5. How do you set up alerts in Grafana?

To set up alerts in Grafana:

1. Open the dashboard containing the panel you want to set an alert for.
2. Click on the panel title and select "Edit."
3. Go to the "Alert" tab.
4. Define the alert conditions and thresholds.
5. Configure notification channels for alert delivery (e.g., email, Slack).
6. Save the changes.

### 6. Can Grafana be used for real-time monitoring?

Yes, Grafana can be used for real-time monitoring. By connecting Grafana to data sources that provide real-time metrics, you can create dashboards that update in real-time to reflect the current state of your systems and applications.

### 7. What are Grafana plugins?

Grafana plugins are add-ons that extend Grafana's functionality. Plugins can provide additional data sources, visualization types, and app integrations. They can be installed from the Grafana plugin repository or developed custom.

### 8. How do you share a Grafana dashboard?

To share a Grafana dashboard:

1. Open the dashboard you want to share.
2. Click on the "Share" icon at the top.
3. Choose how you want to share it: via link, snapshot, or export.
4. For links, you can configure the link settings and copy the link to share it.
5. For snapshots, you can take a snapshot of the current state and share it.
6. For export, you can download the JSON model of the dashboard.

### 9. What are template variables in Grafana?

Template variables allow you to create dynamic and reusable dashboards. Variables can be used to filter and customize the data displayed in your panels. They make it easier to manage and interact with dashboards that need to show data for different time ranges, instances, or environments.

### 10. How can you secure a Grafana instance?

To secure a Grafana instance, you can:

- Enable user authentication and role-based access control.
- Use HTTPS to encrypt data transmission.
- Configure data source permissions.
- Regularly update Grafana to the latest version.
- Monitor and audit access logs for any suspicious activity.

By understanding these basic concepts and functionalities, beginners can start leveraging Grafana for effective monitoring and observability.


## Deepsense Digital Solutions Pvt Ltd

## Overview
Deepsense Digital Solutions Pvt Ltd is a digital and technology agency with over 80 professionals. The company specializes in providing comprehensive digital marketing solutions, leveraging innovation, creativity, and technology to create impactful marketing campaigns.

## Services Offered
Deepsense offers a wide range of services across various digital domains:

- **Digital Marketing**: SEO, social media marketing, content marketing, email marketing, and PPC campaigns.
- **Web Development and Design**: Including UX/UI design and development for websites.
- **Mobile App Development**: Creation and design of mobile applications.
- **Advanced Technologies**: Such as AI, AR/VR development, IoT, and chatbot development.

## Industry and Market Position
Deepsense serves a diverse range of industries including hospitality, education, healthcare, FMCG, and more. They have a notable clientele which includes companies like ITC Group, CavinKare, TTK Group, Nippon Paint, Suguna Foods, and Walkaroo.

## Recent Developments and Achievements
The company prides itself on winning over 25 awards in the digital marketing space. Their approach is centered around innovation and pushing the boundaries of what’s possible in digital marketing.

## Leadership
The company was co-founded by Ashok Shanker, Rakesh R., and Rithesh R. They have steered the company from a small startup to a significant player in the digital solutions market.

## Company Culture and Values
Deepsense emphasizes a culture of curiosity and continuous learning. The team is known for its collaborative spirit and commitment to client success. They prioritize putting clients’ goals first and fostering a work environment that encourages creativity and innovation.


## Final Questions

## 1.How does Deepsense support professional development and continuous learning for its employees?

## 2.What opportunities for professional growth and development does Deepsense offer?

## 3. What are the next steps in the hiring process?


