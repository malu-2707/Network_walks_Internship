### Network Scanning with Zenmap

### Objective
To identify active devices connected to a local network using Zenmap and Nmap, determine their IP and MAC addresses, count live hosts, and visualize the network topology.

### Tool Used
- Zenmap (Nmap GUI)
- Nmap
- Windows PC
- Kali Linux Terminal (for command-line verification)

### Background
Zenmap is the official graphical user interface (GUI) for Nmap. It is an open-source network scanning tool used by cybersecurity professionals to discover hosts, identify network devices, and understand network configurations. It provides different scanning profiles and a graphical topology view to visualize discovered network hosts.

### Methodology
1. Downloaded and installed Zenmap on the Windows PC.
2. Identified the local IP address and LAN subnet using network configuration commands.
3. Performed a Ping Scan using Zenmap to discover active devices in the local subnet.
4. Identified the total number of live hosts in the network.
5. Collected the IP addresses of the discovered hosts.
6. Identified the MAC addresses of the live hosts where available.
7. Opened the Topology tab in Zenmap to visualize the discovered network devices.
8. Saved the generated network topology in PDF format.

### Results – Network Scanning

| No. | Task | Result |
|---:|---|---|
| 1 | Zenmap Installation | Successfully installed |
| 2 | Local IP Address | Identified using network configuration |
| 3 | LAN Subnet | Identified |
| 4 | Live Host Discovery | Successfully performed |
| 5 | Total Live Hosts | As displayed in Zenmap scan results |
| 6 | Live Host IP Addresses | Identified from scan results |
| 7 | Live Host MAC Addresses | Collected where available |
| 8 | Network Topology | Successfully generated |
| 9 | Topology PDF | Saved on Desktop |

### Observation
Zenmap successfully identified active devices within the local network subnet. The scan results provided information about live hosts, their IP addresses, and available MAC addresses. The topology visualization helped understand the connections and relationships between the discovered network devices.

### Conclusion
The experiment demonstrated how Zenmap and Nmap can be used for network discovery and host identification. It provided practical knowledge of local network scanning, IP and MAC address identification, and graphical network topology visualization.

### Evidence / Output
- Zenmap scan results screenshot
- Local IP address and subnet details
- Live hosts list
- IP and MAC address details
- Network topology screenshot
- Generated Network_Topology.pdf

**Note:** The number of live hosts and their IP and MAC addresses may vary depending on the local network configuration. MAC addresses may not be available for devices outside the local network segment.
