# Palo Alto Firewall Labs

## Objective
This section showcases practical skills in configuring and managing Palo Alto firewalls, focusing on advanced network security, VPN setup, and traffic monitoring.

## Skills Learned
- Configuring security and NAT policies.
- Implementing VPNs for secure communication.
- Managing and tuning intrusion prevention systems (IPS).
- Analyzing and monitoring real-time network traffic.
- Performing advanced troubleshooting and SSL decryption.

## Tools Used
- Palo Alto Firewall (GUI and CLI)
- VPN Configuration Tools
- Syslog Servers
- Wireshark
- Virtualized Network Environments

## Tasks
Below are the key tasks performed in this section:

### 1. Interface and Zone Configuration
![3](https://github.com/user-attachments/assets/e1db371e-c2f0-4660-969c-8e4a1404c278)
- Configured interfaces with appropriate IP addresses, zones, and security profiles.
- Assigned virtual routers and security zones to segregate network traffic effectively.
- Managed Layer 3 interfaces for enterprise network deployment and SD-WAN setup.
  
### 2. Application Filter Configuration
![Screenshot 2024-07-05 205032](https://github.com/user-attachments/assets/581bebeb-1478-4c16-ac3f-4036fa6e7252)
![Screenshot 2024-07-05 205335](https://github.com/user-attachments/assets/d2ddeb55-ecd0-4a0c-bb68-203b1f08d671)
- Configured application filters to allow or restrict access based on application characteristics.
- Categorized applications by risk level, tags, and characteristics (e.g., SaaS, low-risk).
- Enhanced security by applying application filters to policies for granular traffic control.

### 3. Security Profiles Configuration
![Screenshot 2024-07-17 185316](https://github.com/user-attachments/assets/26670167-4d72-48bc-b681-669572f59156)
![Screenshot 2024-07-17 191222](https://github.com/user-attachments/assets/573c4379-24f3-40dd-ad24-54f104286c30)
![Screenshot 2024-07-17 191528](https://github.com/user-attachments/assets/33f8416f-408f-4a11-ace6-d709e83bc1ec)
- Configured Antivirus Profiles to detect and block malicious payloads over various protocols (HTTP, SMTP, FTP, etc.).
- Created File Blocking Profiles to restrict high-risk file types and enforce organization-wide file access policies.
- Tested security profiles using scenarios with encrypted and non-encrypted files to ensure compliance with rules.
- Applied custom WildFire machine learning settings to enhance threat detection and prevention capabilities.

### 4. GlobalProtect VPN Configuration
![Screenshot 2024-07-19 140331](https://github.com/user-attachments/assets/2088b07f-31f5-4139-9e82-c5b963455ecd)
- Configured GlobalProtect Portal for secure remote access.
- Assigned SSL/TLS and authentication profiles to ensure encrypted and authenticated VPN connections.
- Configured interfaces and IP allocations for user connectivity through the GlobalProtect Portal.

### 5. Data Patterns and Filtering Configuration
![Screenshot 2024-07-24 180436](https://github.com/user-attachments/assets/67e91189-7dd1-4b36-bebf-4b602bc4bbeb)
![Screenshot 2024-07-24 181747](https://github.com/user-attachments/assets/0c6f7123-b7ef-404b-b45c-b6f3e3bfa727)
![Screenshot 2024-07-24 182125](https://github.com/user-attachments/assets/a660abf5-ad98-45f2-a1dd-f027045da5f1)
- Configured custom data patterns to detect sensitive data, including credit card numbers, proprietary information, and confidential files.  
- Applied data filtering profiles with alert/block thresholds to prevent unauthorized data transfers.  
- Integrated data filtering and patterns with security policies for multi-layered data protection.

  ### 6. Log Forwarding and Monitoring
  ![10](https://github.com/user-attachments/assets/df36fbec-4e2f-4c7a-88b0-06c959486b17)
  ![sc3](https://github.com/user-attachments/assets/937a8b65-b2a1-40d1-a1f4-ca6a6fb1571e)
  ![sc1](https://github.com/user-attachments/assets/399f9729-43a8-4cf1-a9a1-7bfe70d631c9)
- Configured log forwarding to a centralized syslog server for enhanced monitoring and analysis.
- Monitored traffic and events using PRTG sensors, focusing on uptime, packet loss, and performance metrics.
- Ensured accurate DNS settings and IP configurations for network devices, enabling seamless connectivity and centralized monitoring.
  
### 7. Security Policy Configuration
![Screenshot 2024-06-21 154510](https://github.com/user-attachments/assets/44c7b835-a65d-48d5-bd3c-8a86a09c2874)
![image](https://github.com/user-attachments/assets/77508909-218e-4f86-89f9-2e7318b4e983)
![image](https://github.com/user-attachments/assets/9f528512-7462-45af-b340-cc76631ff757)
![image](https://github.com/user-attachments/assets/bb463ce0-e150-484f-bc28-1c216d09ead0)
- Created and managed security policies to regulate access and protect sensitive data.
- Configured application-based and user-based policies to enhance control.

### 8. NAT Configuration
![image](https://github.com/user-attachments/assets/76b88512-95b7-42f2-8380-5918874fd072)
- Set up Source NAT (SNAT) and Destination NAT (DNAT) for seamless traffic flow.
- Configured port forwarding for application accessibility.

### 9. Traffic Monitoring and Analysis
![image](https://github.com/user-attachments/assets/ebcaeeda-5286-411b-ab3b-e1c36cc3e05c)
![image](https://github.com/user-attachments/assets/11add58a-282e-4d4e-a46d-c466e1c151bd)
![image](https://github.com/user-attachments/assets/fbde1f2a-e776-40da-be29-1024c8338700)
![image](https://github.com/user-attachments/assets/ffd36108-0274-4a80-af6d-5647f414b8a2)
- Monitored traffic using dashboards and traffic logs.
- Analyzed logs to troubleshoot and optimize network performance.

### 10. SSL Decryption
- Set up SSL decryption policies to inspect encrypted traffic.

### 11. SNMP Configuration
![image](https://github.com/user-attachments/assets/44c66c26-454d-4059-8a60-17603638cf41)
- Configured SNMP settings for network monitoring and integration with management systems.
- Set up SNMP community strings and configured SNMPv3 for enhanced security.

### 12. Configuration Auditing
![image](https://github.com/user-attachments/assets/8cb88003-3ff0-4340-9786-cf19d8352286)
![image](https://github.com/user-attachments/assets/9d67a2ca-1270-4681-b887-e58179e92f1c)
- Performed configuration audits to track and review changes to firewall settings.
- Identified added, modified, and deleted configuration entries to ensure compliance and accuracy.

### 13. Log and SYN Flood Management
![image](https://github.com/user-attachments/assets/8285faaa-cc2f-4b6d-9bb2-2813f80585b5)
![image](https://github.com/user-attachments/assets/c121cd26-4194-4a6b-bc5b-6760ba8e4d72)
- Used scripts to manage and clear traffic, threat, and URL logs for maintenance and performance optimization.
- Conducted SYN flood tests to measure handshake performance and validate flood protection mechanisms.
- Utilized API calls and testing tools to enhance firewall log management and attack response capabilities.

### 14. Security Policy Testing
![image](https://github.com/user-attachments/assets/f6909dfa-c870-4d18-8805-32f302faedc0)
![image](https://github.com/user-attachments/assets/0fae6216-fe96-4b7e-84f8-44250699018a)
![image](https://github.com/user-attachments/assets/3e98913a-66d7-4ccf-9386-9614447506d9)
- Tested security policies by verifying their impact on traffic flow and connectivity.
- Used `nslookup` to confirm DNS queries were allowed or blocked based on policies.
- Conducted ping tests to validate policy behavior, ensuring intended traffic was permitted or denied.
- Analyzed policy hit counts and logs to confirm correct implementation.

### 15. External Dynamic List (EDL) Configuration
![image](https://github.com/user-attachments/assets/5ce14d92-d86d-45ff-8cab-75beeb17f19e)
- Configured External Dynamic Lists to dynamically manage malicious domains and IPs.
- Set up source URLs for automatic updates and ensured lists were fetched periodically.
- Utilized EDLs to enforce security policies against high-risk or known malicious resources.

### 16. URL Filtering and Monitoring
![image](https://github.com/user-attachments/assets/f0321ae1-1007-47fb-97cc-87af90223392)
- Monitored URL filtering logs to ensure malicious and blocked sites were being correctly identified.
- Verified the enforcement of security policies based on dynamic URL categories and blocklists.
- Analyzed logs to review user activity and ensure compliance with organizational policies.
---

Return to the [Main Repository](https://github.com/darpanne/Firewall-Management) for other firewall and network monitoring configurations.

