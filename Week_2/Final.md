# NETWORKWALKS – WEEK 02
# PENETRATION TESTING & RECONNAISSANCE REPORT

### GHDB-Based Footprinting & Zenmap-Based Network Scanning

**W2-PM-FINAL | Cybersecurity & Ethical Hacking Internship**

---

## 1. Project Information

| Category | Details |
|---|---|
| Internship Program | NetworkWalks Cybersecurity & Ethical Hacking |
| Project | Week 02 – Footprinting & Network Scanning |
| Intern Name | Malini S |
| Batch | [Enter your batch] |
| Assessment Date | [Enter completion date] |
| Modules Completed | W2-PM2, W2-PM5 |
| Module 1 | GHDB-Based Footprinting Attacks |
| Module 2 | Zenmap-Based Network Scanning |
| Operating Systems | Windows and Kali Linux |
| Primary Tools | Google Search, GHDB, Zenmap, Nmap |
| Assessment Type | Educational Security Assessment |
| Repository | [Network_walks_Internship](https://github.com/malu-2707/Network_walks_Internship/tree/main/Week_2) |
| Assessment Status | Completed |

## 2. Executive Summary

This report documents the practical cybersecurity activities completed during Week 02 of the NetworkWalks Cybersecurity & Ethical Hacking Internship.

The assessment focused on two important areas of cybersecurity: **public information discovery through Google Hacking Database (GHDB)** and **local network discovery using Zenmap**.

In the first module, Google search operators were used to identify publicly accessible mathematics textbooks and educational PDF resources. In the second module, Zenmap was used to discover active hosts within the local network, identify available IP and MAC address information, and generate a graphical network topology.

These exercises provided practical experience in reconnaissance, information gathering, network discovery, and security assessment documentation.

## 3. Objectives

The primary objectives of this assessment were:

1. Understand search engine-based information gathering techniques.
2. Explore Google Hacking Database (GHDB) search techniques.
3. Identify publicly accessible PDF documents using Google search operators.
4. Understand how search engines index publicly available information.
5. Install and configure Zenmap on a Windows PC.
6. Identify the local IP address and LAN subnet.
7. Discover active hosts within the authorized local network.
8. Identify live host IP addresses and available MAC addresses.
9. Visualize the discovered network using Zenmap Topology.
10. Generate and save the network topology in PDF format.

## 4. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Google Search | Search for publicly accessible resources |
| Google Hacking Database (GHDB) | Explore advanced Google search techniques |
| Zenmap | Graphical network scanning and visualization |
| Nmap | Network host discovery engine |
| Windows CMD | Identify local network configuration |
| Kali Linux Terminal | Command-line verification and network utilities |

---

# 5. Detailed Module Implementation

## 5.1 W2-PM2 – GHDB-Based Footprinting Attacks

### Objective

To use Google Dorking techniques to identify publicly accessible mathematics textbooks and educational resources available in PDF format.

### Background

Google Dorking is an information-gathering technique that uses advanced search operators to locate specific information indexed by search engines.

Google Hacking Database (GHDB), maintained by Exploit Database, provides examples of search queries that demonstrate how search engines can reveal publicly indexed information.

Search operators such as `filetype:`, `site:`, `intitle:`, and `inurl:` help narrow search results and identify specific types of publicly accessible resources.

### Tool Used

- Google Search
- Google Hacking Database (GHDB)
- Web Browser

### Methodology

1. Opened Google Search.
2. Explored Google Hacking Database search techniques.
3. Used the `filetype:pdf` operator to locate PDF documents.
4. Applied keywords such as `mathematics`, `textbook`, and `educational resources`.
5. Used the `site:` operator to narrow results to selected educational websites.
6. Reviewed the search results to identify relevant mathematics textbooks.
7. Verified the accessibility and relevance of the identified educational resources.
8. Documented the search queries and corresponding resource links.

### Google Dorking Techniques Used

| Search Operator | Purpose | Example |
|---|---|---|
| `filetype:` | Find files of a specific format | `filetype:pdf mathematics` |
| `site:` | Restrict search to a particular website | `site:openstax.org mathematics` |
| `intitle:` | Search for specific words in page titles | `intitle:mathematics textbook` |
| `inurl:` | Search for keywords in URLs | `inurl:textbook mathematics` |

### Results – Mathematics PDF Resources

| No. | Resource / Book | Link | Relevant Google Dork |
|---:|---|---|---|
| 1 | NCERT Mathematics Class X | [PDF](https://ncert.nic.in/textbook/pdf/jemh1ps.pdf) | `filetype:pdf mathematics textbook` |
| 2 | OpenStax Calculus Volume 1 | [PDF](https://assets.openstax.org/oscms-prodcms/media/documents/calculus-volume-1_-_WEB.pdf) | `site:openstax.org mathematics filetype:pdf textbook` |
| 3 | LibreTexts Mathematics | [PDF](https://batch.libretexts.org/print/Letter/Finished/math-130898/Full.pdf) | `site:libretexts.org mathematics textbook filetype:pdf` |
| 4 | Fundamentals of Mathematics | [Archive](https://archive.org/details/cnx-org-col10615) | `site:archive.org mathematics textbook pdf` |
| 5 | OpenStax Precalculus 2e | [Book](https://openstax.org/details/books/precalculus-2e) | `site:openstax.org/details/books/precalculus-2e` |
| 6 | OpenStax College Algebra 2e | [Book](https://openstax.org/details/books/college-algebra-2e) | `site:openstax.org/details/books/college-algebra-2e` |
| 7 | OpenStax Introductory Statistics | [Book](https://openstax.org/details/books/statistics) | `site:openstax.org/details/books/statistics` |
| 8 | OpenStax Elementary Algebra 2e | [Book](https://openstax.org/details/books/elementary-algebra-2e) | `site:openstax.org/details/books/elementary-algebra-2e` |
| 9 | OpenStax Calculus Volume 2 | [PDF](https://assets.openstax.org/oscms-prodcms/media/documents/calculus-volume-2_-_WEB.pdf) | `site:openstax.org mathematics calculus filetype:pdf` |
| 10 | OpenStax Calculus Volume 3 | [Book](https://openstax.org/details/books/calculus-volume-3) | `site:openstax.org/details/books/calculus-volume-3` |

**Credentials:** No usernames or passwords were collected.

### Observation

Google Dorking successfully demonstrated how advanced search operators can identify publicly accessible educational documents.

The search results included direct PDF resources and educational book pages containing downloadable materials.

The exercise also demonstrated the importance of understanding how search engines index publicly accessible information.

### Security Relevance

- Search engines can expose information that website owners may not intend to highlight.
- Publicly indexed documents should be reviewed for accidental disclosure of confidential information.
- Organizations should monitor their indexed digital footprint.
- Sensitive documents should be protected through appropriate authentication and access controls.

### Conclusion

The GHDB-based footprinting exercise demonstrated the practical use of Google search operators for targeted information discovery. It improved understanding of search engine indexing, publicly accessible information, and the importance of controlling information exposure.

---

## 5.2 W2-PM5 – Zenmap-Based Network Scanning

### Objective

To discover active devices within a local network using Zenmap, identify their IP and MAC addresses, calculate the number of live hosts, and visualize the network topology.

### Background

Zenmap is the official graphical user interface (GUI) for Nmap. It is a free and open-source network scanning application used by cybersecurity professionals for network discovery and security assessment.

Zenmap simplifies network scanning by providing predefined scanning profiles, graphical scan results, and network topology visualization.

It allows users to identify active hosts and understand the structure of an authorized network environment.

### Tool Used

- Zenmap
- Nmap
- Windows PC
- Windows Command Prompt
- Kali Linux Terminal

### Methodology

**Task 1 – Download and Install Zenmap**

- Visited the official Nmap download website.
- Downloaded the Windows installer.
- Installed Zenmap and its required Npcap component.
- Successfully launched Zenmap.

Official website: https://nmap.org/download.html

**Task 2 – Identify Local IP Address and LAN Subnet**

Executed the following command in Windows Command Prompt:

```cmd
ipconfig
```

Identified the following network details:

| Parameter | Result |
|---|---|
| IPv4 Address | [Enter your IP address] |
| Subnet Mask | [Enter your subnet mask] |
| Default Gateway | [Enter your gateway] |
| Network Subnet | [Enter your LAN subnet in CIDR notation] |

**Task 3 – Discover Live Hosts**

Selected the Ping Scan profile in Zenmap and scanned the identified local subnet.

Equivalent Nmap command:

```bash
nmap -sn <YOUR_LOCAL_SUBNET>
```

This scan was used to identify active hosts without performing a port scan.

**Task 4 – Identify the Total Number of Live Hosts**

Reviewed the scan output and counted the hosts reported as up.

Total live hosts discovered: **[Enter actual number]**

**Task 5 – Identify IP Addresses**

Reviewed the Nmap scan report to identify the IP addresses of the discovered live hosts.

**Task 6 – Identify MAC Addresses**

Reviewed the MAC address information displayed in the scan results.

MAC addresses were recorded wherever available. MAC address discovery is generally available for hosts on the same local Ethernet segment and may require appropriate privileges.

### Results – Network Scanning

| No. | Host Information | Result |
|---:|---|---|
| 1 | Local IP Address | [Enter actual IP] |
| 2 | LAN Subnet | [Enter actual subnet] |
| 3 | Total Live Hosts | [Enter actual count] |
| 4 | Live Host IP Addresses | Identified through Zenmap |
| 5 | MAC Addresses | Identified where available |
| 6 | Network Topology | Successfully generated |
| 7 | Topology PDF | Saved on Desktop |

### Network Topology Visualization

After completing the network scan:

1. Opened the scan results in Zenmap.
2. Selected the Topology tab.
3. Viewed the graphical representation of discovered hosts.
4. Examined the connections and relationships displayed in the topology.
5. Saved the generated topology in PDF format on the Desktop.

**Output File:** `Network_Topology.pdf`

### Observation

Zenmap successfully performed host discovery within the selected local network subnet.

The scan provided information about active devices, their IP addresses, and available MAC addresses. The Topology feature presented the discovered network devices in a graphical format, making network structure easier to understand.

### Security Relevance

- Network scanning helps identify active devices within an organization.
- Unknown devices can be investigated for unauthorized network access.
- Network topology documentation supports asset management.
- Regular network discovery helps administrators maintain visibility over connected devices.

### Conclusion

The Zenmap practical demonstrated how Nmap-based network scanning can identify live hosts within an authorized local network. It provided practical knowledge of IP address discovery, MAC address identification, host counting, and graphical network topology generation.

---

# 6. Combined Findings and Analysis

The two completed modules demonstrate different but complementary reconnaissance techniques.

| Assessment Area | W2-PM2 – Google Dorking | W2-PM5 – Zenmap |
|---|---|---|
| Reconnaissance Type | Search engine-based information discovery | Active network discovery |
| Primary Target | Publicly indexed educational resources | Authorized local LAN |
| Main Tool | Google Search / GHDB | Zenmap / Nmap |
| Information Identified | Public PDF resources and book pages | Live hosts, IPs and MACs |
| Main Technique | Search operators | Ping Scan |
| Output | Resource links and search queries | Scan results and topology PDF |
| Security Focus | Information exposure | Network visibility |

### Key Findings

1. Search engine operators can efficiently locate publicly accessible documents.
2. Search engine indexing can create unintended information exposure when sensitive documents are not properly protected.
3. Zenmap provides an effective graphical interface for local network discovery.
4. Live host discovery helps identify devices connected to a network.
5. Network topology visualization improves understanding of network structure.
6. Combining passive information gathering and active host discovery provides a broader understanding of reconnaissance.

**Important:** The educational PDF resources identified in PM2 are not automatically security vulnerabilities. Their accessibility is not evidence of unauthorized disclosure.

---

# 7. Risk Analysis

| No. | Observation | Potential Security Impact | Risk Assessment |
|---:|---|---|---|
| 1 | Public documents indexed by search engines | Confidential information could be exposed if improperly published | Context-dependent |
| 2 | Search engines reveal publicly accessible resources | Unintended information discovery | Low |
| 3 | Active devices identified through network scanning | Unknown devices may indicate unauthorized connections | Requires investigation |
| 4 | Network IP and MAC information identified | Network asset information becomes available to authorized administrators | Informational |
| 5 | Network topology generated | Provides visibility into network structure | Informational |

No exploitation or unauthorized access was performed as part of these two practical modules.

---

# 8. Security Recommendations

### Recommendations for Information Exposure

1. Avoid publishing confidential documents on publicly accessible directories.
2. Implement appropriate authentication and authorization controls.
3. Regularly review documents indexed by search engines.
4. Remove sensitive information from public-facing resources.
5. Use appropriate indexing restrictions where required.

### Recommendations for Network Security

1. Perform periodic network discovery scans.
2. Maintain an updated inventory of connected devices.
3. Investigate unknown IP and MAC addresses.
4. Restrict network access to authorized devices.
5. Maintain updated network topology documentation.
6. Monitor network activity for unexpected devices and connections.

---

# 9. Learning Outcomes

Through the completion of W2-PM2 and W2-PM5, the following skills were developed:

- Understanding Google Dorking and GHDB search techniques.
- Using advanced Google search operators.
- Identifying publicly accessible PDF resources.
- Understanding search engine information exposure.
- Installing and configuring Zenmap.
- Identifying local IP addresses and LAN subnets.
- Performing network host discovery using Nmap.
- Identifying live hosts and available MAC addresses.
- Generating graphical network topology.
- Understanding the importance of ethical reconnaissance and authorization.
- Preparing technical documentation and security assessment reports.

---

# 10. Evidence and Documentation

The following evidence should be maintained in the GitHub repository.

| Module | Evidence | Description |
|---|---|---|
| W2-PM2 | Google Search Screenshot | Google Dorking search results |
| W2-PM2 | GHDB Screenshot | Search techniques and operators |
| W2-PM2 | Mathematics PDF Resources | Identified educational documents |
| W2-PM5 | Zenmap Installation Screenshot | Installation process |
| W2-PM5 | IP Configuration Screenshot | Local IP and subnet |
| W2-PM5 | Zenmap Scan Screenshot | Live host discovery |
| W2-PM5 | Host Details Screenshot | IP and MAC address information |
| W2-PM5 | Topology Screenshot | Graphical network topology |
| W2-PM5 | Network_Topology.pdf | Exported topology output |

---

# 11. Ethical Considerations and Disclaimer

All activities documented in this report were conducted for educational purposes as part of the NetworkWalks Cybersecurity & Ethical Hacking Internship.

The Google Dorking exercise focused on publicly accessible educational resources. The Zenmap scanning exercise was restricted to the authorized local network environment.

No unauthorized access, exploitation, credential collection, or modification of external systems was performed.

Network scanning should only be conducted on networks and devices owned by the tester or for which explicit authorization has been obtained.

The information in this report is intended for cybersecurity education, awareness, and defensive security purposes.

---

# 12. Final Conclusion

The Week 02 practical assessment provided hands-on experience in two important stages of cybersecurity reconnaissance: information discovery and network discovery.

Through W2-PM2, Google Dorking techniques were used to locate publicly accessible mathematics textbooks and educational PDF resources. This demonstrated how advanced search operators can help identify information indexed by search engines and highlighted the importance of managing publicly exposed information.

Through W2-PM5, Zenmap was used to scan an authorized local network, identify active hosts, collect available IP and MAC address information, and generate a graphical network topology in PDF format.

Overall, these exercises strengthened practical knowledge of reconnaissance, information gathering, network scanning, and security documentation.

**Both selected elective modules, W2-PM2 and W2-PM5, were completed as part of the Week 02 internship activities.**

---

## 13. References

1. Google Search – https://www.google.com/
2. Google Hacking Database – https://www.exploit-db.com/google-hacking-database
3. Nmap Official Website – https://nmap.org/
4. Zenmap Documentation – https://nmap.org/zenmap/
5. NCERT – https://ncert.nic.in/
6. OpenStax – https://openstax.org/
7. LibreTexts – https://libretexts.org/

---

## Author

**Malini S**

Cybersecurity & Ethical Hacking Intern  
NetworkWalks Internship Program

GitHub: https://github.com/malu-2707/Network_walks_Internship

**Project:** Week 02 – Footprinting & Network Scanning

**Completed Modules:** W2-PM2 and W2-PM5

**Final Deliverable:** W2-PM-FINAL – Consolidated Technical Report
