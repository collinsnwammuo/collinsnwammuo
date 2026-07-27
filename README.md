<div align="center">
  <h1>👋 Hi, I'm Collins Nwammuo</h1>
  <h3>Computer Engineer | Technologist | SOC Analyst</h3>

  <p>
    <img src="https://img.shields.io/badge/Cybersecurity-Blue%20Team%20%7C%20SOC-0A66C2?style=for-the-badge&logo=shield&logoColor=white" />
    <img src="https://img.shields.io/badge/Networking-Enterprise%20%7C%20VLANs-2E8B57?style=for-the-badge&logo=cisco&logoColor=white" />
    <img src="https://img.shields.io/badge/IoT-Research%20%26%20Education-8B0000?style=for-the-badge&logo=arduino&logoColor=white" />
  </p>

  <p>
    <a href="https://www.linkedin.com/in/collins-nwammuo-645482248/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0072b1?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://www.credly.com/users/collins-nwammuo" target="_blank">
      <img src="https://img.shields.io/badge/Credly-Verify_Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white" />
    </a>
    <a href="mailto:collinsnwammuo@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://tryhackme.com/p/conwamc" target="_blank">
      <img src="https://img.shields.io/badge/-TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" />
    </a>
  </p>

</div>

---

## 😎 About Me

👋 I'm **Collins**, a Computer Engineering graduate and **Technologist** at [Chukwuemeka Odumegwu Ojukwu University (COOU)](https://coou.edu.ng), currently working to move into a **Security Operations Center (SOC) Analyst** role. My engineering background bridges hardware, embedded systems, and network infrastructure, and I apply that same fundamentals-first approach to detecting and investigating threats.

Over the past several months I've built a complete home SOC lab spanning network forensics, SIEM engineering across three platforms, intrusion detection, vulnerability management, threat intelligence, and endpoint detection and response, documenting every part of it, including what didn't work the first time.

* 🎓 **M.Eng. Electrical/Electronic Engineering** — Chukwuemeka Odumegwu Ojukwu University
* 🎓 **B.Eng. Computer Engineering** — University of Uyo
* 🏫 **Technologist** — COOU (2023–Present)
* 🧑‍🏫 **IEEE Student Advisor** — COOU Student Branch

### 🎯 A Few Results I'm Proud Of

- Measured a live SSH brute-force detection time of **12 minutes 23 seconds in Splunk**, then rebuilt the same detection in Suricata and brought it down to **under 1 second**.
- Found two critical, unauthenticated, publicly-exploitable backdoors (**CVE-2011-2523, CVE-2010-2075**) running OpenVAS against a lab target, then researched both CVEs' real-world exploitability rather than stopping at the CVSS score.
- Investigated a real **NetSupport RAT malware PCAP** down to the packet level, identifying the victim's hostname, IP, MAC, and Windows username from passive traffic analysis alone.
- Connected **Microsoft Defender for Endpoint directly into Microsoft Sentinel**, tracing a single test detection end-to-end: endpoint block → EDR alert → cloud SIEM incident.
- Built the same detection dashboard **three times**, in Splunk, Kibana, and Sentinel, on identical data, to genuinely understand where each platform helps and where it gets in the way.

---

## 🛡️ SOC Lab Portfolio

| Repo | Focus | Highlight |
|---|---|---|
| [Wireshark-projects](https://github.com/collinsnwammuo/Wireshark-projects) | Network forensics, 10 projects | Full investigation of a real NetSupport RAT malware PCAP, IOCs mapped to MITRE ATT&CK |
| [SIEM-Splunk](https://github.com/collinsnwammuo/SIEM-Splunk) | SIEM engineering, 14 projects | Live SSH brute-force detection (12 min 23 sec MTTD) + Splunk BOTS v1 real-world investigation |
| [SIEM-ELK-Stack](https://github.com/collinsnwammuo/SIEM-ELK-Stack) | Elastic Stack SIEM | Clean install, real ingestion/config failures resolved, direct Splunk vs Kibana comparison |
| [Suricata-IDS-Lab](https://github.com/collinsnwammuo/Suricata-IDS-Lab) | IDS deployment & custom rules | Live detection brought down to ~0.87 seconds; documented a real detection gap (FIN/connect scans) |
| [nmap-recon-lab](https://github.com/collinsnwammuo/nmap-recon-lab) | Network reconnaissance | Diagnosed a false-negative host discovery caused by ICMP filtering on my own target |
| [openvas-vuln-management](https://github.com/collinsnwammuo/openvas-vuln-management) | Vulnerability scanning | Found 2 critical unauthenticated backdoors (vsftpd, UnrealIRCd), triaged 38 findings by CVSS |
| [threat-intel-lab](https://github.com/collinsnwammuo/threat-intel-lab) | CVE & IOC research | Corroborated a malware C2 indicator against 3 independent public sources |
| [edr-xdr-lab](https://github.com/collinsnwammuo/edr-xdr-lab) | EDR/XDR & cloud SIEM | Connected Microsoft Defender for Endpoint into Microsoft Sentinel; CrowdStrike Falcon in progress |

---

## 🛠️ Core Skills

| **Security Operations** | **Networking & Development** | **Tools & Platforms** |
| :--- | :--- | :--- |
| SIEM Engineering (Splunk, ELK, Sentinel) | Network Segmentation (VLANs) | Wireshark & tcpdump |
| Intrusion Detection (Suricata) | Python & Bash Scripting | Suricata, Zeek |
| Vulnerability Management (OpenVAS) | Embedded C / Arduino | Microsoft Defender for Endpoint |
| Endpoint Detection & Response | VANET Simulation (SUMO/NS3) | Cisco Packet Tracer |
| Threat Intelligence & CVE Research | HTML/CSS/JavaScript | Linux (Kali/Ubuntu), Windows |
| MITRE ATT&CK Framework | | KQL / SPL Query Development |

---

## 🧪 Other Engineering & Research Work

### 🔹 [Enterprise Network Segmentation (Cisco Packet Tracer)](https://github.com/collinsnwammuo/Cisco-Packet-Tracer-Projects)
*Designed a secure enterprise LAN with departmental isolation.*
- **Tech:** VLANs, Trunking, Router-on-a-Stick, Inter-VLAN Routing
- **Outcome:** Segregated HR and Sales traffic to improve security and performance

### 🔹 Digital Heart Rate Monitor (Embedded Systems)
*Design and implementation of a fingertip-based biometric sensor.*
- **Tech:** Arduino Uno, LCD Display, Pulse Sensor
- **Outcome:** Created a low-cost medical diagnostic tool for resource-constrained environments

### 🔹 VANET Routing Protocol Evaluation
*Comparative analysis of AODV, DSR, and OLSR protocols.*
- **Tech:** SUMO, OMNET++, VEINS
- **Focus:** Optimizing Vehicle-to-Vehicle (V2V) communication latency

---

## 🧾 Certifications
*Verified via [Credly](https://www.credly.com/users/collins-nwammuo)*

| Issuer | Certification | Year |
| :--- | :--- | :--- |
| **ISC2** | Certified in Cybersecurity (CC) | 2025 |
| **Cisco** | Junior Cybersecurity Analyst | 2025 |
| **CompTIA** | Security+ | 2025 |
| **Microsoft** | Azure Fundamentals (AZ-900) | 2025 |
| **Huawei** | HCIA Security | 2024 |

---

## 📄 Publications

1. **Nwammuo, C. T.**, et al. (2024). *"Evaluation of AODV, DSR, and OLSR VANET Routing Protocols for V2V Implementation: A Solution for Developing Economies."*
2. Iloh, J.I & **Nwammuo, C.T** (2024). *"IoT-based instrumentation systems for enhancing entrepreneurial skills of engineering students."*
3. Nzeife, I.D., **Nwammuo, C.T**, et al. (2025). *"Load Optimization of a Single-Sided Electromagnetic Elevator."*

---

## 🐱 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=collinsnwammuo&show_icons=true&theme=tokyonight&hide_border=true" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=collinsnwammuo&layout=compact&theme=tokyonight&hide_border=true" />
</div>

---

## 🕹️ TryHackMe Progress

<p align="center">
  <a href="https://tryhackme.com/p/conwamc">
    <img src="https://tryhackme-badges.vercel.app/api/badges?username=conwamc&theme=dark" alt="TryHackMe Stats" />
  </a>
</p>

---

<div align="center">
  <sub>Last Updated: July 2026 • 📍 Nigeria (WAT)</sub>
</div>
