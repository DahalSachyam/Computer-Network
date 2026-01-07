# Lab 2: Network Diagnostic and Troubleshooting Commands

## Aim
To study and apply commonly used network commands for checking connectivity, identifying network paths, and troubleshooting basic network-related problems.

---

## Tools and Requirements
- A computer system with access to a command-line interface
- Active network connection (wired or wireless)

---

## Overview of Network Commands Used
The following commands were used during the lab session to observe network configuration, test connectivity, and analyze routing and address resolution:
- ping
- ipconfig / ifconfig
- tracert / traceroute
- netstat (-a, -n)
- nslookup
- arp
- telnet
- pathping
- route print
- getmac
- nbtstat
- whois

---

## Description and Usage of Network Commands

### 1. ping
- **Syntax:** `ping <hostname or IP address>`
- **Purpose:** Checks whether a remote host is reachable and measures the time taken for packets to travel to and from the destination.

---

### 2. ipconfig (Windows) / ifconfig (Linux)
- **Syntax:** `ipconfig` or `ifconfig`
- **Purpose:** Displays the current network configuration including IP address, subnet mask, default gateway, and DNS information.

---

### 3. tracert (Windows) / traceroute (Linux)
- **Syntax:** `tracert <hostname or IP>` or `traceroute <hostname or IP>`
- **Purpose:** Shows the path followed by packets as they move through different routers to reach the destination.

---

### 4. netstat
- **Syntax:**  
  - `netstat -a`  
  - `netstat -n`
- **Purpose:** Lists active network connections, listening ports, and network statistics.

---

### 5. nslookup
- **Syntax:** `nslookup <hostname>`
- **Purpose:** Retrieves DNS information such as IP addresses associated with a domain name.

---

### 6. arp
- **Syntax:** `arp -a`
- **Purpose:** Displays the ARP table showing the mapping between IP addresses and MAC addresses.

---

### 7. telnet
- **Syntax:** `telnet <hostname or IP> <port>`
- **Purpose:** Tests connectivity to a specific port on a remote host.

---

### 8. pathping (dosent work in linux and mac)
- **Syntax:** `pathping <hostname or IP>`
- **Purpose:** Combines features of ping and tracert to analyze packet loss and latency across network hops.

---

### 9. route print
- **Syntax:** `route print`
- **Purpose:** Displays the routing table currently used by the system.

---

### 10. getmac
- **Syntax:** `getmac`
- **Purpose:** Shows the MAC addresses of network interfaces present on the machine.

---

### 11. nbtstat
- **Syntax:** `nbtstat -a <hostname>`
- **Purpose:** Displays NetBIOS-related statistics and name tables for systems using NetBIOS over TCP/IP.

---

### 12. whois
- **Syntax:** `whois <domain name>`
- **Purpose:** Fetches domain registration details from the WHOIS database.

---

## Procedure Followed
1. The command-line interface was opened on the system.
2. The network configuration was checked using `ipconfig` or `ifconfig`.
3. The listed network commands were executed as required.
4. Command outputs were observed and saved for reference.

---

## Observations and Output
- Each command produced expected results based on its function.
- some of the commnad were found to not work or be os specific
- Outputs for all executed commands were saved in separate files.
- All result files were organized and stored in the designated **output** directory.

---

## Conclusion
This lab helped develop practical understanding of essential network diagnostic commands. The commands used are fundamental tools for identifying connectivity issues, analyzing routing paths, and verifying network configurations, making them vital for effective network troubleshooting.
