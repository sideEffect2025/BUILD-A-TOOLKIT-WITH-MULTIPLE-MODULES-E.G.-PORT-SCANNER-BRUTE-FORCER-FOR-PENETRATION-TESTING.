# OVERVIEW:
This Python-based penetration testing toolkit is designed to assist cyber security proffessionals for identifying vulnerabilities in network searching and web applications.It provides multiple modules for security testing, including port scanning, brute-force attacks.
# MODULES:
***1.Port scanner:***
Purpose: Identifies open ports on a target system.

***How it works:***
* Uses the socket library to attempt connections to ports (1–1024 by default).
* If a connection succeeds, the port is marked as open.
* Useful for finding vulnerable services running on a system.

***2.Brute-Force Attack:***
Purpose: Tries multiple username-password combinations to break into an account.
**How it works:**

* Uses a wordlist file containing possible passwords.
* Sends authentication requests with each password.
* If the response indicates success, the correct password is found.

# FUTURE ENHANCEMENTS:
* Add SSH & FTP brute-force modules
* Enhance web vulnerability scanner with more attack vectors
* Implement multi-threading for faster scanning

# DRAWBACKS:
1️.Legal & Ethical Concerns
Unauthorized usage can lead to legal consequences.
Must have explicit permission before testing any system.

2️. Limited Functionality
Port Scanner only scans common ports (1-1024); doesn’t support custom ranges.
Brute-Forcer relies on a dictionary attack, making it ineffective against strong passwords.

3️.Performance Issues
Scanning large networks or huge wordlists can be slow.
No multi-threading support for faster execution.

4️.Detection Risks
Firewall & Intrusion Detection Systems (IDS) may detect and block scans.
IPs might get blacklisted when brute-forcing.

5️.No Advanced Features
Lacks exploit execution, hash cracking, or post-exploitation modules.
No support for multi-protocol brute-forcing (e.g., SSH, FTP, SMTP).
