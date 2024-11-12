**Bold # 4.5 Given a scenario, modify enterprise capabilities to enhance security**
## 1. Ports 
Logical communication endpoints on a computer or server


## 2.  Port 21 
FTP(File transfer protocol) - TCP


## 3. Port 22
SSH, SCP, SFTP - TCP


## 4. Port 23
Telnet - TCP


## 5.Port 25
SMTP (Simple Mail Transfer Protocol) - TCP


## 6. Port 53
DNS (Domain Name System) - TCP/UDP


## 7. Port 69
TFTP (Trivial File Transfer Protocol) - UDP


## 8. Port 80
HTTP. - TCP


## 9. Port 88
Kerberos - UDP


## 10. Port 110
POP3 (Post Office Protocol) - TCP


## 11. Port 119
NNTP (Network News Transfer Protocol) - TCP


## 12. Port 135
RPC(Remote Procedure Call) - TCP/UDP


## 13. Port 137/138/139
NetBIOS
(TCP / UDP)


## 14. Port 143
IMAP (Internet Message Access Protocol) - TCP


## 15. Port 161
SNMP (Simple Network Management Protocol) - UDP


## 16. Port 162
SNMP Trap - UDP


## 17. Port 389
LDAP (Lightweight Directory Access Protocol) - TCP


## 18. Port 443
HTTPS (HTTP SECURE) - TCP


## 19. Port 445
SMB (Server Message Block) - TCP


## 20. Port 465, 587
SMTPS (SMTP SECURE) - TCP


## 21. Port 514
Syslog - UDP


## 22. Port 636
LDAPS (LDAP SECURE) - TCP


## 23. Port 993
IMAPS (IMAP over SSL/TLS) - TCP


## 24. Port 995
POP3S (POP3 over SSL/TLS) - TCP


## 25. Port 1433
Microsoft SQL - TCP


## 26. Port 1645, 1646
RADIUS (Remote Authentication) - TCP


## 27. Port 1812, 1813
RADIUS UDP - UDP


## 28. Port 3389
RDP (Remote Desktop Protocol) - TCP


## 29. Port 6514
Syslog TLS - TCP


## 30. Firewall
Network security device or software that monitors and controls network traffic based on security rules


## 31. Screened Subnet
Acts as a security barrier between external untrusted networks and internal trusted networks using a protected host with security measures like a packer-filtering firewall


## 32. Access Control Lists - Firewalls
Consist of permit and deny statements - often based on port numbers - control the flow of traffic into and out of networks


## 33. Configuring ACLs
Place most specific rules at the top with general rules at the bottom - executes top down and stops when a statement fits


## 34. ACL Rules
Consist of: Type of traffic - source of traffic - destination of traffic - action to be taken against the traffic


## 35. Intrusion Detection System
Logs or alerts that it found something suspicious or malicious


## 36. Signature Based IDS
Analyzes traffic based on defined signatures and can only recognize attacks based on previously identified attacks in its database


## 37. Anomaly-Based IDS
Analyzes traffic and compares it to a normal baseline of traffic to determine whether a thread is occurring


## 38. Intrusion Prevention Systems
Logs, alerts, and takes action when it finds something suspicious or malicious


## 39. Group Policy
A set of rules and policies that can be applied to users or computer accounts within an operating system


## 40. Baselining
The process of measuring changes in networking, hardware, software environment


## 41. SELinux (Security Enhanced Linux)
A security mechanism that provides an additional layer of security for linux distributions - enforces Mandatory Access Control


## 42. Mandatory Access Controls (MAC)
Restricts access to system resources based on subject clearance and object labels


## 43. Contexts in SELinux
User Context, Role Context, Type Context


## 44. User Context
Defines which users can access an object


## 45. Role Context
Determines which roles can access an object


## 46. Type Context
Essential for fine-grained access control, grouping objects with similar security characteristics


## 47. Network Access Control (NAC)
Used to protect networks from both known and unknown devices by scanning devices to assess their security status before granting network access


## 48. Web Filter
Web filtering or content filtering is used to control or restrict the content users can access on the internet


## 49.Agent-based Web Filtering
Involves installing an agent on each device - monitors and enforces web usage policies - effective for remote and mobile workers


## 50. Centralized Proxy
Uses a proxy server as an intermediary between an organization's end users and the internet - evaluates and controls web requests based on policies


## 51. URL Scanning
Analyzes websites URLs to check for matches in a database of known malicious websites


## 52. Content Categorization
Classifies websites into categories and blocks or allows categories based on policies


## 53. Block Rules
Specific guidelines set by organizations to prevent access to certain websites or categories, often used to address security threats


## 54. Reputation-Based Filtering
Blocks or allows websites based on a reputation score determined by third-party services


## 55. DNS Filtering
blocks access to specific websites by preventing the translation of domain names to their IP addresses - If requested domain is on block list the ip address is withheld


## 56. Email Security
Encompasses techniques and protocols to protect email content, accounts, and infrastructure from unauthorized access, loss, or compromise


## 57. Domain Keys Identified Mail (DKIM)
Allows the receiver to verify the source and integrity of an email by adding a digital signature to the email headers


## 58. Sender Policy Framework (SPF)
Prevents sender address forgery by verifying the sender's IP against authorized IPs listed in the sender's domain DNS records


## 59. Domain-based Message Authentication, Reporting and Conformance (DMARC)
Detects and prevent email spoofing by setting policies for email sending and handling failures - can work with DKIM, SPF, or both


## 60. Email Gateway Protocol Config
Serve as entry/exit point for emails, facilitating secure and efficient email transmission - SMTP utilized for sending/receiving emails - handles email routing, security, policy enforcement, and encryption


## 61. Endpoint Detection and Response (EDR)
Category of security tools that monitor endpoint and network events and record the information in a central database - collects data from endpoints, sends data to a centralized security solution, analyzes data for threats and responds as necessary - focuses on endpoints


## 62. File Integrity Monitoring
Validates the integrity of operating system and application software files by comparing their current state with a known, good baseline


## 63. Extended Detection and Response (XDR)
Security strategy that integrates multiple protection technologies into a single platform to improve detection accuracy and simplify the incident response process - more comprehensive solution and expands beyond endpoints


## 64. User Behavior Analytics
Advanced cybersecurity strategy that uses big data and machine learning to analyze user behaviors for detecting security threats - focus on understanding user behavior to identify patterns


## 65. Secure Protocols
Choose secure protocols to protect data in transit - example: HTTP vs HTTPS, FTP vs SFTP, Telnet vs SSH


## 66. Port Selection
Ports are logical constructs used to identify processes or services on a system


## 67. Transport Methods
TCP - connection-oriented ensuring data delivery without errors - UDP: best effort but is connectionless so no guarantee
