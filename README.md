<div align="center">

# Aser Ahmed (Oxanubis)

**Security Researcher & Full-Stack Developer**
*Vulnerability Research · Application Security · Cloud-Native Infrastructure*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aser-ahmed/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/0xanubiis)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@0xanubiis)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aserhello@gmail.com)

📍 Cairo, Egypt · 🌍 Remote · ⚡ Available immediately
</div>

---

## 👨‍💻 About Me
I am a Security Researcher and Full-Stack Developer focused on finding and responsibly disclosing critical vulnerabilities in widely used open-source software and cloud-native infrastructure. 

My research specializes in deep-dive code auditing, including request forgery (SSRF), cryptographic integrity bypasses, authentication flaws, path-handling escapes, and memory-safety bugs. I have been writing code and breaking things since 2020, and I currently rank in the **Top 0.05% on Hack The Box**.

---

## 🏆 Selected Vulnerability Research

| Year | Project | Vulnerability Finding | Severity |
| :--- | :--- | :--- | :--- |
| **2026** | **Microsoft (Azure Go SDK)** | **Credential Exfiltration (SSRF)** via unsigned resume tokens in LRO polling. | Critical (7.4+) |
| **2026** | **Aiven (MyHoard)** | **Root RCE** via untrusted XtraBackup tablespace map path traversal. | Critical (P1) |
| **2026** | **Aiven (rohmu)** | **Crypto Integrity Bypass** (HMAC fail-open) allowing silent backup tampering. | High (P3) |
| **2026** | **Coinbase (Wallet SDK)** | **Access Control Bypass** allowing blind-signing via `wallet_invokeMethod`. | High |
| **2026** | **TensorFlow Lite Micro** | **Integer Overflow** in `ElementCount()` leading to Heap Buffer Overflow (DoS/RCE). | Critical (9.8) |
| **2026** | **Istio** (CNCF) | **SSRF** in WasmPlugin HTTP fetcher. *(Fixed in [#61112](https://github.com/istio/istio/pull/61112), credited in [release notes](https://github.com/istio/istio/pull/61141))* | High (7.5) |
| **2026** | **Turborepo** (Vercel) | **Token Exfiltration** through repo-controlled remote-cache URLs. | High (8.1) |
| **2026** | **Backman** | **Authentication Bypass** via empty default credentials. | Critical (9.8) |
| **2026** | **Aiven (pghoard)** | **Symlink Bypass** of existing CVE fix + Tablespace Path Traversal (RCE). | High |
| **2026** | **Angular Service Worker** | **Novel CSRF Vector** bypassing SameSite, Origin checks, and CSRF tokens. | Medium |
| **2026** | **LaunchDarkly (Go SDK)** | **Stack Overflow (DoC)** via unbounded JSON recursion in FDv1 parsing. | High (7.5) |

*All findings were reported through responsible disclosure channels (MSRC, Bugcrowd, HackerOne, or direct maintainer contact).*

---

## 🚀 Featured Projects

### [Mizan](https://mezanlawyer.vercel.app)
**Legal Practice Management SaaS for Egyptian law offices.**
- Built a multi-tenant architecture using **Supabase Row Level Security (RLS)**.
- Features case/client management, session calendars, Kanban boards, and an Arabic-first interface.
- **Scale:** Used by **242+ law offices**.
- `React` `TypeScript` `Supabase` `Tailwind CSS`

### [Azharii](https://azharii.vercel.app)
**Real-time communication platform for Al-Azhar University.**
- Architected a 15+ table PostgreSQL schema with full Row Level Security.
- Features channels, direct messages, 4-tier RBAC, and live moderation.
- `React` `TypeScript` `Supabase`

---

## 🛠️ Technical Toolbox

<div align="center">

**Security & Pentesting**<br>
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-214478?style=flat-square&logo=nmap&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Development & Cloud**<br>
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## 🎖️ Recognition & Certifications

- **Hack The Box:** Top **0.05%** globally.
- **Cyber Apocalypse CTF 2026:** Ranked **537th** of 6,744 teams (57/136 challenges solved).
- **Holmes CTF 2025:** Ranked **1,264th** of 7,085 teams.
- **Writing:** Published technical articles on [Medium](https://medium.com/@0xanubiis), including a deep-dive on the Istio SSRF and a 9.8 TensorFlow vulnerability.

<details>
<summary><b>🕵️ Click to expand: DFIR, OSINT & Education</b></summary>
<br>

**Digital Forensics & Incident Response (DFIR)**
- Completed **40+ investigations** covering multi-stage malware infection chains, APT tracking (mapped to MITRE ATT&CK), credential stuffing, SSH persistence, defense evasion, Windows Event Log forensics, insider threats, and web server compromises.

**OSINT**
- Social media footprint analysis, person-of-interest identification, geolocation verification, domain/WHOIS tracking, and phishing campaign analysis.

**Certifications**
- Web Penetration Testing In Practice: Recon to Remediation
- Incident Handling: Malware, Email, Network, and Web Security
- Digital Investigation Techniques: Basics

**Education**
- **B.A. Sharia and Law**, Al-Azhar University *(Expected 2029)*

</details>

---

<div align="center">
  <i>Open to Security Research, Application Security, and Penetration Testing roles.</i><br>
  <b>1-week notice · Remote only</b>
</div>
