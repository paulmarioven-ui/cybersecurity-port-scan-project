Cybersecurity Port Scan & Security Analysis (AWS EC2)
Overview
This project demonstrates a basic security assessment of a cloud-based server hosted on AWS EC2. Using Nmap, I analysed open ports and running services to identify potential security risks.
Tools Used
- AWS EC2 (Ubuntu)
- Nmap
- Linux Terminal
Methodology
1. Launched an EC2 instance on AWS
2. Installed Nmap using the terminal
3. Performed a basic scan using: nmap localhost
4. Performed a service version scan using: nmap -sV localhost
5. Analysed open ports and services
Findings
The scan identified the following open ports:
- Port 22 (SSH): Used for remote access
- Port 80 (HTTP): Used for hosting the web server
These ports are expected for a web server but can pose security risks if not properly managed.
SECURITY ANALYSIS
Open ports increase the attack surface of a system. Port 22 (SSH) is sensitive and should be restricted to trusted IP addresses.
Port 80 (HTTP) allows web traffic but should be secured using HTTPS in real-world environments.
Conclusion
This project highlights the importance of monitoring open ports and understanding active services in a cloud environment.
Screenshots
Website (Screenshot_20260416_004959)
Nmap Scan (Screenshot_20260416_005502)
Terminal (Screenshot_20260416_010218)
