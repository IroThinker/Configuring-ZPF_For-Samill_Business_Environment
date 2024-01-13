This repository encompasses a comprehensive network configuration and security project, consisting of three distinct tasks aimed at establishing a robust and secure networking environment.

**Configure Basic Device Settings**
The initial task focuses on foundational network configuration. It involves cabling the network according to a provided diagram, ensuring each network has at least one connected PC. Basic settings for all routers, including names, IP addresses, and routing configurations (static or RIP), are established. Additionally, PC host IP settings are configured to ensure seamless end-to-end connectivity across the network.

**Configure Secure Router Administrative Access**
Task 2 is dedicated to enhancing router administrative access security. Encrypted passwords and login banners are configured for added security. The EXEC timeout value is set on console and VTY lines, and a local database administrative user is established. Secure Shell (SSH) access is implemented, with Telnet being disabled.

**Configure a Zone-Based Policy Firewall**
The third task focuses on designing and implementing a Zone-Based Policy Firewall for a robust security posture. Specific requirements include allowing internal users access to internal and DMZ servers, permitting returning Internet traffic, and restricting incoming traffic from the Internet into internal networks. Furthermore, only specified protocols (HTTP, HTTPS, DNS, and ICMP) are allowed between the Internet and DMZ servers, with all traffic between internal servers and DMZ servers being prohibited. The tasks involve creating security zones, inspecting class-maps to match traffic, policy-maps for defining actions, creating necessary zone pairs, and applying security policies to respective interfaces.

The completed Packet Tracer file is included in the repository, offering a visual representation of the configured network and security settings. For detailed configuration files and documentation, explore the repository. This project ensures a well-organized, operational network with heightened security measures.
