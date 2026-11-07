<h1 align="center">Aser Ahmed</h1>

<p align="center">
  <b>Security Researcher &amp; Full-Stack Developer</b><br>
  Vulnerability research · Application security · Cloud-native infrastructure
</p>

<p align="center">
  Cairo, Egypt · Remote · Available immediately
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aser-ahmed/"><img src="https://img.shields.io/badge/LinkedIn-24292e?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/0xanubiis"><img src="https://img.shields.io/badge/X-24292e?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="https://medium.com/@0xanubiis"><img src="https://img.shields.io/badge/Medium-24292e?style=flat-square&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="mailto:aserhello@gmail.com"><img src="https://img.shields.io/badge/Email-24292e?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I find and responsibly disclose vulnerabilities in widely used open-source software, and I build and ship full-stack products. My research centers on web and cloud-native security: request forgery, authentication and path-handling flaws, and memory-safety bugs. I've been writing code and breaking things since 2020.

## Selected research

| Project | Finding | Severity |
| --- | --- | --- |
| **Istio** (CNCF) | SSRF in the WasmPlugin HTTP fetcher. Fixed in [#61112](https://github.com/istio/istio/pull/61112), credited in the [release notes](https://github.com/istio/istio/pull/61141). | CVSS 7.5 |
| **Turborepo** (Vercel) | Vercel token exfiltration through a repo-controlled remote-cache URL. | CVSS 8.1 |
| **Backman** | Authentication bypass through empty default credentials. | CVSS 9.8 |
| **TensorFlow Lite Micro** | Integer overflow in `ElementCount()`, confirmed with UBSan and ASan. | CVSS 9.8 |
| **Angular Service Worker** | Novel CSRF vector that bypasses SameSite, Origin/Referer checks, and CSRF tokens. | n/a |
| **pghoard** (Aiven) | Symlink bypass of an existing CVE fix, plus a tablespace-path traversal. | File write / RCE |

All findings were reported through responsible disclosure.

## Featured projects

**[Mizan](https://mezanlawyer.vercel.app)** — Legal practice management SaaS built for Egyptian law offices. Multi-tenant architecture with Supabase Row Level Security, case and client management, session calendar, Kanban board, and an Arabic-first interface. Used by 242+ law offices.
`React` `TypeScript` `Supabase` `Tailwind CSS`

**[Azharii](https://azharii.vercel.app)** — Real-time communication platform for Al-Azhar University. Channels, direct messages, 4-tier role-based access control, and live moderation on a 15+ table PostgreSQL schema.
`React` `TypeScript` `Supabase`

## Toolbox

![Burp Suite](https://img.shields.io/badge/Burp_Suite-24292e?style=flat-square&logo=burpsuite&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-24292e?style=flat-square&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-24292e?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-24292e?style=flat-square&logo=nmap&logoColor=white)
![Python](https://img.shields.io/badge/Python-24292e?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-24292e?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-24292e?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-24292e?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-24292e?style=flat-square&logo=react&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-24292e?style=flat-square&logo=postgresql&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-24292e?style=flat-square&logo=splunk&logoColor=white)

## Recognition

- **Cyber Apocalypse CTF 2026:** 537th of 6,744 teams, 57 of 136 challenges solved
- **Holmes CTF 2025:** 1,264th of 7,085 teams
- **Writing:** technical articles on [Medium](https://medium.com/@0xanubiis), including how I found the Istio SSRF

<details>
<summary><b>Forensics, OSINT, and certifications</b></summary>

<br>

**Digital forensics and incident response** — 40+ investigations covering malware infection-chain reconstruction, APT tracking mapped to MITRE ATT&CK, credential-stuffing and persistence analysis, defense-evasion techniques, Windows Event Log forensics, insider-threat cases, and web-server compromises.

**OSINT** — social-media footprint analysis, person-of-interest identification, geolocation verification, domain and WHOIS tracking, and phishing-campaign analysis.

**Certifications**
- Web Penetration Testing In Practice: Recon to Remediation
- Incident Handling: Malware, Email, Network, and Web Security
- Digital Investigation Techniques: Basics

**Education** — B.A. Sharia and Law, Al-Azhar University (expected 2029)

</details>

---

<p align="center">
  Open to security research, application security, and penetration testing roles · 1-week notice
</p>
