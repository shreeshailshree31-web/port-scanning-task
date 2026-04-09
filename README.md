# port-scanning-task
Network port scanning project using Nmap to identify open ports and services on a system.
# 🔐 Network Port Scanning using Nmap

## Objective
To identify open ports and services on a system using Nmap.

## Tools Used
- Nmap

## Target
- Localhost (127.0.0.1)

## Steps Performed
1. Installed Nmap
2. Ran command:
   nmap localhost
3. Saved output using:
   nmap localhost -oN result.txt

## Results
Open ports found:
- 135 (msrpc)
- 445 (SMB)
- 3306 (MySQL)
- 1521 (Oracle)
- and others

## Risks
Open ports can be exploited by attackers if not secured.

## Conclusion
Successfully performed port scanning and understood basic network security concepts.

## Safety Note
Scan was performed only on my own system.
