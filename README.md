
# Devops-Zero-to-Hero

# Introduction - Day 1

Welcome to the #90DaysOfDevOps Challenge with the #TrainWithShubham Community! Today, we begin our journey into the world of DevOps. Here’s what you need to do:

1. **Fork this Repository:**
   - Go to the repository on GitHub and fork it to your own account. This will allow you to track your progress and contribute.

2. **Start with a DevOps Roadmap:**
   - Watch the introductory video on DevOps: [DevOps Roadmap](https://youtu.be/g_QHuGq3E2Y?si=fR9K56-JevZTfrBK)

3. **Write a LinkedIn Post or a Small Article:**
   - Share your understanding of DevOps based on the video and your research. Cover the following points:

4. **Engage with the Community:**
   - Share your LinkedIn post or article link in the community forum or on social media using the hashtags #90DaysOfDevOps and #TrainWithShubham.
   - Read and comment on posts from other participants to foster a collaborative learning environment.
  

**1. Week 1 Tasks**
**2. Submission Post**:
**"Week 1 of #90DaysOfDevOps2025 completed! 🚀**

**✅ Learned OSI & TCP/IP models :- The OSI model: A conceptual blueprint :-**
The OSI model, developed by the International Organization for Standardization (ISO), offers a standardized, 7-layer framework for network communication. It's a theoretical model, useful for teaching and troubleshooting network issues. 

**Here's a breakdown of the 7 layers and their functions:**
**Physical Layer (Layer 1):** Defines the physical connection between devices, including cables, connectors, and electrical signals. Example: Ethernet cables.
**Data Link Layer (Layer 2):** Ensures reliable node-to-node data transfer on the same network segment. Handles physical addressing (MAC addresses), framing, and error checking. Examples: Ethernet, PPP.
**Network Layer (Layer 3)**: Responsible for routing data packets across different networks and assigns logical addresses (IP addresses). Example: IP.
**Transport Layer (Layer 4):** Ensures end-to-end data integrity and reliability, managing flow control, error recovery, and data sequencing. Examples: TCP, UDP.
**Session Layer (Layer 5):** Manages and maintains connections (sessions) between applications, handling synchronization and dialogue control. Examples: NetBIOS, PPTP.
**Presentation Layer (Layer 6):** Translates and formats data for the application layer, handling encryption, decryption, and compression. Examples: SSL/TLS, JPEG.
**Application Layer (Layer 7):** Serves as the interface for network services directly used by user applications. Examples: HTTP, FTP, SMTP. 

**The TCP/IP model:** The backbone of the internet:-The TCP/IP model is a more practical framework, developed by the U.S. Department of Defense in the 1970s and widely used for real-world networking, forming the basis of the internet. It's simpler, with four layers: 

**Network Access Layer (Link Layer):** Combines the Physical and Data Link layers of the OSI model, managing hardware communication and physical transmission. Examples: Ethernet, Wi-Fi.

**Internet Layer:** Equivalent to the Network Layer in OSI, responsible for addressing and routing data packets across networks using IP addresses. Examples: IP, ICMP, ARP.

**Transport Layer:** Similar to the OSI Transport layer, it handles reliable data delivery using protocols like TCP and UDP, providing connection-oriented or connectionless services.

**Application Layer:** Combines the Application, Presentation, and Session layers of the OSI model, supporting high-level protocols for services like web browsing, file transfers, and email. Examples: HTTP, FTP, SMTP, DNS. 


**✅ Explored AWS Security Groups:**-**Exploring AWS Security Groups**
AWS Security Groups act as virtual firewalls for your Amazon Web Services (AWS) resources, primarily designed to filter both inbound and outbound network traffic. They are a fundamental building block of network security within AWS and crucial for protecting your cloud infrastructure from unauthorized access and potential threats. 




**✅ Practiced networking commands**
**ip: This is the modern replacement for ifconfig. It allows viewing and configuring IP addresses, network interfaces, routing tables, and more.

**ip addr:** Displays IP addresses assigned to network interfaces.
**ip link:** Shows link-layer information, such as MAC addresses.
**ip route:** Displays and manipulates routing tables.

**ifconfig:** Displays or configures network interface parameters (though deprecated in favor of ip in some newer distributions).
**ifconfig eth0:** Shows configuration for the eth0 interface.

**hostname**: Displays or sets the system's hostname.

**route:** Views and manipulates the IP routing table.
**route -n:** Displays the routing table numerically. 

**Connectivity testing and troubleshooting**

**ping:** Tests network connectivity to a host and measures round-trip time.
**ping google.com:** Checks connectivity to google.com.
**ping -c 5 google.com:** Sends a specified number of ping requests (e.g., 5).

**traceroute/tracert:** Displays the route packets take to a network host.
**traceroute google.com:** Traces the route to google.com.

**telnet:** Used to establish a connection to a specific host and port (less secure, used with caution, and for debugging purposes).
**telnet google.com 80:** Attempts to connect to google.com on port 80.

**netstat:** Displays network connections, routing tables, interface statistics, and listening ports (superseded by ss in many cases).
**netstat -an:** Displays all active network connections.

**ss:** Inspect active sockets and display network statistics.

**nslookup/dig:** Queries DNS name servers for information about host addresses, mail exchanges, and name servers.
**nslookup google.com**: Queries DNS for google.com.
**dig google.com**: Provides more advanced DNS lookup information. 

**Network data transfer and analysis**
**curl:** Transfers data to or from a server, supporting various protocols (HTTP, HTTPS, FTP, etc.).
**wget:** Downloads files from the internet.

**tcpdump:** Captures, filters, and analyzes network traffic (packets).
**tcpdump -i eth0:** Captures packets on the eth0 interface.

**nmap:** Performs network scanning and security auditing to discover hosts, services, and vulnerabilities.
**nmap -sT google.com:** Scans google.com for open TCP ports.

**netcat (nc)**: A versatile networking tool for reading and writing data across network connections. 
Firewall management

**iptables: A command-line tool to configure Linux firewall rules.**
**iptables -A INPUT -p tcp --dport 22 -j ACCEPT**: Allows SSH connections.

**UFW (Uncomplicated Firewall)**: A user-friendly firewall configuration tool for Ubuntu.

**sudo ufw enable**: Enables UFW.
**sudo ufw allow 22/tcp**: Allows traffic on port 22 (TCP). **



**✅ Set up my first web server**



