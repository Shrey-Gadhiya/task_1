# task_1
use of nmap and perfrom task throw nmap


| Port    | Service | Risk                                       |
| ------- | ------- | ------------------------------------------ |
| 22      | SSH     | Brute force attacks if weak credentials    |
| 80      | HTTP    | Susceptible to MITM or web vulnerabilities |
| 443     | HTTPS   | Safer, but misconfigurations can exist     |
| 139/445 | SMB     | Vulnerable to exploits like EternalBlue    |

 Recommendations:
Disable unused services

Use strong credentials

Implement firewalls and VPNs

Keep systems updated

Enable port filtering



Interview Questions – Answers
1. What is an open port?
An open port is a network port that actively accepts connections. It indicates a service is listening for incoming communication.

2. How does Nmap perform a TCP SYN scan?
Nmap sends SYN packets to targets; if it receives SYN-ACK, the port is open. If RST is received, it's closed. It doesn’t complete the TCP handshake, so it's stealthy.

3. What risks are associated with open ports?
Open ports expose services that attackers can exploit using vulnerabilities, brute force, or information gathering.

4. Explain the difference between TCP and UDP scanning.
TCP scan: Connection-oriented; gets accurate state of ports.

UDP scan: Connectionless; harder to detect open ports, often slower.

5. How can open ports be secured?
Use firewalls

Close unused ports

Enforce access control

Use secure services (e.g., SSH over Telnet)

6. What is a firewall's role regarding ports?
A firewall filters traffic based on port, protocol, and source/destination IP to block unauthorized access.

7. What is a port scan and why do attackers perform it?
A port scan is probing a system for open ports to identify services. Attackers use it to find vulnerabilities or entry points.

8. How does Wireshark complement port scanning?
Wireshark captures and analyzes packets, showing how the system responds during a scan, which helps in deeper analysis.


---> issues to i have face :
1. my browser was dissconnected.
2. some time txt not created and some time brech data show.
