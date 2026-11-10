# 🔐 NetworkWalks — Week 2 Cybersecurity Project

<div align="center">

**Footprinting, Reconnaissance & Network Scanning**

![Kali Linux](https://img.shields.io/badge/Platform-Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Tool-Nmap%20%7C%20Zenmap-4682B4?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Cybersecurity-orange?style=for-the-badge)
![Training](https://img.shields.io/badge/Program-NetworkWalks-success?style=for-the-badge)

</div>

---

## 📌 Project Overview

This repository documents my Week 2 practical work as part of the **Cybersecurity Training Program at [NetworkWalks](https://networkwalks.com)**.

The project focuses on two key areas of cybersecurity:

1. **W2-PM1 — Footprinting & Reconnaissance:** Gathering publicly available information about `networkwalks.com` using six Kali Linux tools.
2. **W2-PM5 — Network Scanning:** Performing local network host discovery and viewing network topology using Zenmap (Nmap GUI).

The purpose of these exercises was to develop practical experience in information gathering, DNS analysis, website technology identification and network discovery.

## 🎯 Project Objectives

- Understand the purpose of footprinting and reconnaissance.
- Collect publicly available domain registration information.
- Identify website technologies and services.
- Perform DNS resolution and record enumeration.
- Inspect HTTP response headers.
- Check for Web Application Firewall detection.
- Discover active hosts on a local network using Zenmap.
- Document practical activities and results in a technical report.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| **Kali Linux** | Operating system used for cybersecurity practical activities |
| **WHOIS** | Retrieves domain registration information |
| **WhatWeb** | Identifies website technologies and CMS details |
| **Nslookup** | Resolves domain names to IP addresses |
| **cURL** | Inspects HTTP response headers |
| **WAFW00F** | Checks for Web Application Firewall detection |
| **DNSRecon** | Enumerates publicly available DNS records |
| **Zenmap (Nmap GUI)** | Performs network host discovery and displays topology |

---

## 🎯 Practical Execution

### 1. PM1 — Footprinting & Reconnaissance

The following six tools were used to collect and examine publicly available information about the target domain.

| No. | Tool | Command |
|---|---|---|
| 01 | WHOIS | `whois networkwalks.com` |
| 02 | WhatWeb | `whatweb networkwalks.com` |
| 03 | Nslookup | `nslookup networkwalks.com` |
| 04 | cURL | `curl -I https://networkwalks.com` |
| 05 | WAFW00F | `wafw00f networkwalks.com` |
| 06 | DNSRecon | `dnsrecon -d networkwalks.com` |

**Activities performed:**

- Retrieved publicly available domain registration information.
- Identified website technologies using WhatWeb.
- Resolved the domain using DNS queries.
- Examined HTTP response headers using cURL.
- Checked for Web Application Firewall detection.
- Enumerated available DNS records using DNSRecon.

### 2. PM5 — Network Scanning Using Zenmap

Zenmap was used to perform host discovery on the local virtual network.

**Network configuration:**

| Parameter | Value |
|---|---|
| Network Interface | `eth0` |
| Network Range | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2` |
| Default Gateway | `10.0.0.1` |
| Scan Type | Ping Scan |

**Scan command:**

```bash
nmap -sn 10.0.0.0/24
```

**Observed results:**

- Two live hosts were identified.
- `10.0.0.1` — Gateway.
- `10.0.0.2` — Kali Linux machine.
- The Zenmap Topology view was used to visualize the discovered network hosts.

**Note:** This exercise focused on host discovery. It was not a port scan or vulnerability assessment.

---

## 📊 Project Outcomes

The practical exercises provided experience in:

- Domain information gathering using WHOIS.
- Website technology fingerprinting using WhatWeb.
- DNS resolution and enumeration.
- HTTP response header inspection.
- Web Application Firewall detection.
- Local network host discovery using Zenmap.
- Network topology visualization and technical documentation.

The observations are documented in the accompanying report and practical screenshots.

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `W2 -final Report.pdf` | Complete Week 2 technical report |
| `01_WHOIS_Domain_Information.png` | WHOIS practical evidence |
| `02_WhatWeb_Technology_Fingerprint.png` | WhatWeb practical evidence |
| `03_NSLookup_IP_Resolution.png` | DNS resolution evidence |
| `04_CURL_HTTP_Headers.png` | HTTP header inspection evidence |
| `05_WAFW00F_Detection.png` | WAF detection evidence |
| `06_DNSRecon_DNS_Records.png` | DNS enumeration evidence |
| `Zenmap.jpg` | Zenmap scanning/topology evidence |

---

## 📸 Practical Evidence

The screenshots included in this repository document the execution of the tools and the results observed during the exercises.

> If the screenshot filenames in your repository differ from the names above, update the references to match the actual uploaded filenames.

---

## 🐞 Challenges & Learning Experience

During these practical exercises, I developed familiarity with:

1. Using command-line tools in Kali Linux.
2. Understanding domain and DNS information.
3. Interpreting HTTP response headers.
4. Understanding the purpose of WAF detection.
5. Configuring and running a Zenmap host-discovery scan.
6. Exporting and documenting network topology evidence.

---

## 🔐 Security & Ethical Considerations

All activities were undertaken as part of educational cybersecurity training and within the intended exercise scope.

- Reconnaissance findings should be handled responsibly.
- Network scanning should only be performed on systems and networks for which permission has been granted.
- No exploitation was performed as part of the documented activities.
- Observations should not be treated as confirmed vulnerabilities without further authorized validation.

---

## 📚 References & Resources

- [NetworkWalks Official Website](https://networkwalks.com)
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [Nmap Official Documentation](https://nmap.org/book/man.html)
- [Zenmap Documentation](https://nmap.org/book/zenmap.html)

---

## 👨‍💻 Author

**Gaurav Ravindra Chalke**

Cybersecurity Trainee | NetworkWalks

**Areas of Interest:**
- Cybersecurity
- Ethical Hacking
- Footprinting & Reconnaissance
- Network Security
- Web Application Security

**LinkedIn Profile:** [Connect with Gaurav Chalke](https://www.linkedin.com/in/gaurav-chalke-a55060290/)

---

<div align="center">

**Week 2 — Cybersecurity Practical Project**

*Learning • Practicing • Building • Improving*

</div>
