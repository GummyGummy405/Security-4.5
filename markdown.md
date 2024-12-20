# Given a scenario, modify enterprise capabilities to enhance security
Ports 
Logical communication endpoints on a computer or server


Port 21 # H1
FTP(File transfer protocol) - TCP


Port 22
SSH, SCP, SFTP - TCP


Port 23
Telnet - TCP


Port 25
SMTP (Simple Mail Transfer Protocol) - TCP


Port 53
DNS (Domain Name System) - TCP/UDP


Port 69
TFTP (Trivial File Transfer Protocol) - UDP


Port 80
HTTP. - TCP


Port 88
Kerberos - UDP


Port 110
POP3 (Post Office Protocol) - TCP


Port 119
NNTP (Network News Transfer Protocol) - TCP


Port 135
RPC(Remote Procedure Call) - TCP/UDP


Port 137/138/139
NetBIOS
(TCP / UDP)


Port 143
IMAP (Internet Message Access Protocol) - TCP


Port 161
SNMP (Simple Network Management Protocol) - UDP


Port 162
SNMP Trap - UDP


Port 389
LDAP (Lightweight Directory Access Protocol) - TCP


Port 443
HTTPS (HTTP SECURE) - TCP


Port 445
SMB (Server Message Block) - TCP


Port 465, 587
SMTPS (SMTP SECURE) - TCP


Port 514
Syslog - UDP


Port 636
LDAPS (LDAP SECURE) - TCP


Port 993
IMAPS (IMAP over SSL/TLS) - TCP


Port 995
POP3S (POP3 over SSL/TLS) - TCP


Port 1433
Microsoft SQL - TCP


Port 1645, 1646
RADIUS (Remote Authentication) - TCP


Port 1812, 1813
RADIUS UDP - UDP


Port 3389
RDP (Remote Desktop Protocol) - TCP


Port 6514
Syslog TLS - TCP


Firewall
Network security device or software that monitors and controls network traffic based on security rules


Screened Subnet
Acts as a security barrier between external untrusted networks and internal trusted networks using a protected host with security measures like a packer-filtering firewall


Access Control Lists - Firewalls
Consist of permit and deny statements - often based on port numbers - control the flow of traffic into and out of networks


Configuring ACLs
Place most specific rules at the top with general rules at the bottom - executes top down and stops when a statement fits


ACL Rules
Consist of: Type of traffic - source of traffic - destination of traffic - action to be taken against the traffic


Intrusion Detection System
Logs or alerts that it found something suspicious or malicious


Signature Based IDS
Analyzes traffic based on defined signatures and can only recognize attacks based on previously identified attacks in its database


Anomaly-Based IDS
Analyzes traffic and compares it to a normal baseline of traffic to determine whether a thread is occurring


Intrusion Prevention Systems
Logs, alerts, and takes action when it finds something suspicious or malicious


Group Policy
A set of rules and policies that can be applied to users or computer accounts within an operating system


Baselining
The process of measuring changes in networking, hardware, software environment


SELinux (Security Enhanced Linux)
A security mechanism that provides an additional layer of security for linux distributions - enforces Mandatory Access Control


Mandatory Access Controls (MAC)
Restricts access to system resources based on subject clearance and object labels


Contexts in SELinux
User Context, Role Context, Type Context


User Context
Defines which users can access an object


Role Context
Determines which roles can access an object


Type Context
Essential for fine-grained access control, grouping objects with similar security characteristics


Network Access Control (NAC)
Used to protect networks from both known and unknown devices by scanning devices to assess their security status before granting network access


Web Filter
Web filtering or content filtering is used to control or restrict the content users can access on the internet


Agent-based Web Filtering
Involves installing an agent on each device - monitors and enforces web usage policies - effective for remote and mobile workers


Centralized Proxy
Uses a proxy server as an intermediary between an organization's end users and the internet - evaluates and controls web requests based on policies


URL Scanning
Analyzes websites URLs to check for matches in a database of known malicious websites


Content Categorization
Classifies websites into categories and blocks or allows categories based on policies


Block Rules
Specific guidelines set by organizations to prevent access to certain websites or categories, often used to address security threats


Reputation-Based Filtering
Blocks or allows websites based on a reputation score determined by third-party services


DNS Filtering
blocks access to specific websites by preventing the translation of domain names to their IP addresses - If requested domain is on block list the ip address is withheld


Email Security
Encompasses techniques and protocols to protect email content, accounts, and infrastructure from unauthorized access, loss, or compromise


Domain Keys Identified Mail (DKIM)
Allows the receiver to verify the source and integrity of an email by adding a digital signature to the email headers


Sender Policy Framework (SPF)
Prevents sender address forgery by verifying the sender's IP against authorized IPs listed in the sender's domain DNS records


Domain-based Message Authentication, Reporting and Conformance (DMARC)
Detects and prevent email spoofing by setting policies for email sending and handling failures - can work with DKIM, SPF, or both


Email Gateway Protocol Config
Serve as entry/exit point for emails, facilitating secure and efficient email transmission - SMTP utilized for sending/receiving emails - handles email routing, security, policy enforcement, and encryption


Endpoint Detection and Response (EDR)
Category of security tools that monitor endpoint and network events and record the information in a central database - collects data from endpoints, sends data to a centralized security solution, analyzes data for threats and responds as necessary - focuses on endpoints


File Integrity Monitoring
Validates the integrity of operating system and application software files by comparing their current state with a known, good baseline


Extended Detection and Response (XDR)
Security strategy that integrates multiple protection technologies into a single platform to improve detection accuracy and simplify the incident response process - more comprehensive solution and expands beyond endpoints


User Behavior Analytics
Advanced cybersecurity strategy that uses big data and machine learning to analyze user behaviors for detecting security threats - focus on understanding user behavior to identify patterns


Secure Protocols
Choose secure protocols to protect data in transit - example: HTTP vs HTTPS, FTP vs SFTP, Telnet vs SSH


Port Selection
Ports are logical constructs used to identify processes or services on a system


Transport Methods
TCP - connection-oriented ensuring data delivery without errors - UDP: best effort but is connectionless so no guarantee
