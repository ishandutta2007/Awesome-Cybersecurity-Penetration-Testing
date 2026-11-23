# Awesome Cybersecurity & Penetration Testing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Tracked Repos](https://img.shields.io/badge/Open--Source-Curated-blue.svg)](https://github.com/ishandutta2007/Awesome-Cybersecurity-Penetration-Testing)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Cybersecurity-Penetration-Testing/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated directory of premier Breach & Attack Simulation (BAS), Adversary Emulation platforms, automated penetration testing tools, and open-source offensive security frameworks.

Welcome to the definitive guide for security professionals, red teams, purple teams, and SecOps engineers seeking to continuously evaluate enterprise defenses against modern cyber threats and advanced persistent threat (APT) tactics.

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS Platforms & Enterprise Solutions](#saas-platforms--enterprise-solutions)
- [Open-Source Projects & Tooling](#open-source-projects--tooling)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & Responsible Use](#disclaimer--responsible-use)

---

## Sector Overview & Market Dynamics

The global Breach and Attack Simulation (BAS) and automated security validation market is estimated at **$800M to $1.3B**, expanding at a rapid **CAGR exceeding 25%** toward multi-billion-dollar scale as organizations shift from periodic manual audits to Continuous Threat Exposure Management (CTEM). The competitive landscape is **moderately fragmented**, contested by high-growth pure-play innovators (Pentera, Horizon3.ai, Cymulate, SafeBreach, AttackIQ) alongside consolidating enterprise cybersecurity platforms, rather than a single winner-take-all monopoly.

---

## SaaS Platforms & Enterprise Solutions

The table below catalogs enterprise SaaS platforms specializing in automated penetration testing, adversary emulation, and continuous control validation. Entries are sorted in descending order by company scale (valuation / funding / ARR).

| Platform | Valuation / Company Scale | Pricing | Free Tier / Trial Limits | Primary Focus & Core Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Horizon3.ai](https://horizon3.ai/)** | **$2B+ Valuation** ($100M+ ARR, $250M+ Series E) | Starts at **$18,600/yr** base subscription (or **$15/asset/test** on Flex on-demand model) | **No perpetual free tier**; offers a **guided 14-day / 30-day single-scope evaluation/PoC** upon request via enterprise sales | Autonomous penetration testing (NodeZero) finding actionable, exploitable internal & external attack paths |
| **[Pentera](https://pentera.io/)** | **$1B+ Valuation** ($100M+ ARR, Unicorn / Centaur status) | Starts at **$35,000/yr** (standard deployments range **$50,000–$120,000+/yr** depending on node & IP scope) | **No perpetual free tier**; provides a **scheduled sales-guided 14-day technical PoC / evaluation** on request | Automated penetration testing validating real-world exploitable vulnerabilities across external, internal, and cloud attack surfaces |
| **[Cymulate](https://cymulate.com/)** | **$500M Valuation** (~$30M–$50M ARR, Series D funded) | Starts at **$1,500/mo** (~**$18,000/yr** baseline modular tier; packaged multi-vector bundles start around **$7,000/mo** or **$91,000/yr**) | **No perpetual free tier**; provides a **guided 14-day enterprise proof-of-concept (PoC)** upon enterprise demo approval | Broad continuous security control validation across endpoint, web gateway, email, and cloud vector stacks |
| **[AttackIQ](https://www.attackiq.com/)** | **$220M–$250M Valuation** (~$36M ARR, $76M+ funded) | Starts at **$30,000/yr** for baseline agent tiers (also available via credit-based consumption with *AttackIQ Flex*) | **No perpetual free tier**; offers a **custom 14-to-30-day guided evaluation / proof-of-concept** through partner sales channels | MITRE ATT&CK-aligned automated breach & attack simulation to measure SIEM/EDR detection and prevention efficacy |
| **[SafeBreach](https://www.safebreach.com/)** | **$120M–$150M Est. Valuation** (~$25M–$35M ARR, $107M funded) | Starts at **$50,000/yr** (standard enterprise deployments range **$50,000–$140,000+/yr** based on simulator agent count) | **No perpetual free tier**; offers an **enterprise-guided 14-to-30-day controlled PoC** via technical sales engagement | Continuous security validation simulating real-world adversary playbooks across network, cloud, and endpoints |
| **[SCYTHE](https://scythe.io/)** | **$50M–$75M Est. Valuation** (~$13M+ funded, Series A/Late) | Starts at **$25,000/yr** for platform base license plus variable deployment engine modules | **No perpetual free tier**; provides a **14-day guided proof-of-concept (PoC)** upon corporate demonstration request | Collaborative purple teaming platform designed to build, execute, and measure custom adversary emulation campaigns |

---

## Open-Source Projects & Tooling

Self-hosted frameworks, open-source breach simulation tools, and exploitation utilities offer transparent, community-driven alternatives without per-asset licensing costs. Repositories are ranked below in descending order by GitHub stargazers.

| Project & Repository | GitHub Stars | Primary Category | Description & Core Use Case |
| :--- | :--- | :--- | :--- |
| **[danielmiessler/SecLists](https://github.com/danielmiessler/SecLists)** | [![GitHub stars](https://img.shields.io/github/stars/danielmiessler/SecLists?style=social&color=white)](https://github.com/danielmiessler/SecLists/stargazers) | Security Wordlists & Payloads | The security tester's companion collection of multiple types of lists used during security assessments: usernames, passwords, URLs, sensitive data patterns, and fuzzing payloads. |
| **[rapid7/metasploit-framework](https://github.com/rapid7/metasploit-framework)** | [![GitHub stars](https://img.shields.io/github/stars/rapid7/metasploit-framework?style=social&color=white)](https://github.com/rapid7/metasploit-framework/stargazers) | Exploitation Framework | The premier open-source exploitation framework. Packs thousands of modular exploits, payloads, and post-exploitation scripts to verify real-world exploitability. |
| **[sqlmapproject/sqlmap](https://github.com/sqlmapproject/sqlmap)** | [![GitHub stars](https://img.shields.io/github/stars/sqlmapproject/sqlmap?style=social&color=white)](https://github.com/sqlmapproject/sqlmap/stargazers) | Automated Vulnerability Exploitation | Automatic SQL injection and database takeover engine supporting fingerprinting, data fetching, accessing underlying file systems, and out-of-band connections. |
| **[vxcontrol/pentagi](https://github.com/vxcontrol/pentagi)** | [![GitHub stars](https://img.shields.io/github/stars/vxcontrol/pentagi?style=social&color=white)](https://github.com/vxcontrol/pentagi/stargazers) | Autonomous AI Pentesting | Fully autonomous AI agent platform orchestrating multi-agent workflows for dynamic task planning, reconnaissance, and penetration testing execution. |
| **[projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei)** | [![GitHub stars](https://img.shields.io/github/stars/projectdiscovery/nuclei?style=social&color=white)](https://github.com/projectdiscovery/nuclei/stargazers) | Fast Vulnerability Scanner | Fast and customizable vulnerability scanner driven by community-authored YAML templates to detect zero-days, misconfigurations, and CVEs across large surfaces. |
| **[peass-ng/PEASS-ng](https://github.com/peass-ng/PEASS-ng)** | [![GitHub stars](https://img.shields.io/github/stars/peass-ng/PEASS-ng?style=social&color=white)](https://github.com/peass-ng/PEASS-ng/stargazers) | Privilege Escalation Suite | Privilege Escalation Awesome Scripts Suite (LinPEAS / WinPEAS), hunting for local privilege escalation vectors on Linux, Windows, and macOS systems. |
| **[ffuf/ffuf](https://github.com/ffuf/ffuf)** | [![GitHub stars](https://img.shields.io/github/stars/ffuf/ffuf?style=social&color=white)](https://github.com/ffuf/ffuf/stargazers) | Web Fuzzing & Recon | Extremely fast web fuzzer written in Go, widely used for directory brute-forcing, vhost discovery, parameter fuzzing, and content discovery. |
| **[zaproxy/zaproxy](https://github.com/zaproxy/zaproxy)** | [![GitHub stars](https://img.shields.io/github/stars/zaproxy/zaproxy?style=social&color=white)](https://github.com/zaproxy/zaproxy/stargazers) | DAST & Web App Scanner | OWASP ZAP, the world's most popular open-source web application security scanner and intercepting proxy, engineered for seamless CI/CD pipeline integration. |
| **[nmap/nmap](https://github.com/nmap/nmap)** | [![GitHub stars](https://img.shields.io/github/stars/nmap/nmap?style=social&color=white)](https://github.com/nmap/nmap/stargazers) | Port Scanning & Reconnaissance | The foundational network discovery and port scanner. Includes the powerful Nmap Scripting Engine (NSE) for vulnerability detection and host fingerprinting. |
| **[BishopFox/sliver](https://github.com/BishopFox/sliver)** | [![GitHub stars](https://img.shields.io/github/stars/BishopFox/sliver?style=social&color=white)](https://github.com/BishopFox/sliver/stargazers) | Red Team C2 Framework | Modern, cross-platform adversary emulation and command-and-control (C2) framework supporting multi-player operations, mTLS, WireGuard, and DNS beacons. |
| **[1N3/Sn1per](https://github.com/1N3/Sn1per)** | [![GitHub stars](https://img.shields.io/github/stars/1N3/Sn1per?style=social&color=white)](https://github.com/1N3/Sn1per/stargazers) | Reconnaissance & Attack Surface Scanner | Automated recon and attack surface discovery engine orchestrating 90+ community security tools into unified multi-mode scanning workflows. |
| **[SpecterOps/BloodHound-Legacy](https://github.com/SpecterOps/BloodHound-Legacy)** | [![GitHub stars](https://img.shields.io/github/stars/SpecterOps/BloodHound-Legacy?style=social&color=white)](https://github.com/SpecterOps/BloodHound-Legacy/stargazers) | Active Directory Attack Path Analysis | Graph-based Active Directory security analysis tool using graph theory to reveal hidden, unintended attack paths and permission escalations in AD domains. |
| **[byt3bl33d3r/CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)** | [![GitHub stars](https://img.shields.io/github/stars/byt3bl33d3r/CrackMapExec?style=social&color=white)](https://github.com/byt3bl33d3r/CrackMapExec/stargazers) | Network Pentesting & Lateral Movement | Swiss army knife for assessing Windows Active Directory network environments, executing credentials, and automating post-exploitation enumeration. |
| **[apache/caldera](https://github.com/apache/caldera)** | [![GitHub stars](https://img.shields.io/github/stars/apache/caldera?style=social&color=white)](https://github.com/apache/caldera/stargazers) | Adversary Emulation Platform | Cyber adversary emulation system built on the MITRE ATT&CK framework, featuring autonomous operations, chained abilities, and cross-platform agents. |
| **[Pennyw0rth/NetExec](https://github.com/Pennyw0rth/NetExec)** | [![GitHub stars](https://img.shields.io/github/stars/Pennyw0rth/NetExec?style=social&color=white)](https://github.com/Pennyw0rth/NetExec/stargazers) | Network Pentesting Tool | The actively maintained community successor to CrackMapExec, automating security assessment and exploitation of large Active Directory networks. |
| **[SpecterOps/BloodHound](https://github.com/SpecterOps/BloodHound)** | [![GitHub stars](https://img.shields.io/github/stars/SpecterOps/BloodHound?style=social&color=white)](https://github.com/SpecterOps/BloodHound/stargazers) | Active Directory & Hybrid Cloud Path Analysis | The next-generation BloodHound Community Edition platform rewritten with a modern microservices architecture to map attack paths across Active Directory and Azure/Entra ID. |
| **[OpenAEV-Platform/openaev](https://github.com/OpenAEV-Platform/openaev)** | [![GitHub stars](https://img.shields.io/github/stars/OpenAEV-Platform/openaev?style=social&color=white)](https://github.com/OpenAEV-Platform/openaev/stargazers) | Open Breach & Attack Simulation | Open Automated Exposure Validation platform (formerly OpenBAS), providing an ISO 22398-compliant environment for crisis exercises and adversary simulations. |
| **[0xprxdhx/rexa](https://github.com/0xprxdhx/rexa)** | [![GitHub stars](https://img.shields.io/github/stars/0xprxdhx/rexa?style=social&color=white)](https://github.com/0xprxdhx/rexa/stargazers) | Recon CLI & Workflow Automation | Interactive terminal tool combining Nmap, Nikto, and Gobuster into a guided reconnaissance workflow with automated JSON/Markdown reporting. |
| **[Ether-Security/leviathan](https://github.com/Ether-Security/leviathan)** | [![GitHub stars](https://img.shields.io/github/stars/Ether-Security/leviathan?style=social&color=white)](https://github.com/Ether-Security/leviathan/stargazers) | Offensive Security Workflow Engine | Reusable security workflow orchestration engine enabling teams to define modular YAML workflows and concurrent offensive assessments. |

---

## Recommended Free Validation Stack

For engineering teams seeking an end-to-end continuous validation pipeline without recurring enterprise per-asset licensing costs, consider combining:
1. **Host & Web Reconnaissance**: [Nmap](https://github.com/nmap/nmap) + [Nuclei](https://github.com/projectdiscovery/nuclei) + [ffuf](https://github.com/ffuf/ffuf)
2. **Active Directory & Identity Analysis**: [BloodHound](https://github.com/SpecterOps/BloodHound) + [NetExec](https://github.com/Pennyw0rth/NetExec)
3. **Application & Exploitation Proof**: [OWASP ZAP](https://github.com/zaproxy/zaproxy) + [sqlmap](https://github.com/sqlmapproject/sqlmap) + [Metasploit Framework](https://github.com/rapid7/metasploit-framework)
4. **Adversary & Threat Simulation**: [Apache Caldera](https://github.com/apache/caldera) + [OpenAEV / OpenBAS](https://github.com/OpenAEV-Platform/openaev)

---

## How to Contribute

We welcome additions, updates, and corrections from the community!

1. Fork this repository.
2. Add your tool, platform, or project under the appropriate section adhering to existing tables.
3. Ensure all links point to authoritative repositories or official domains.
4. Open a clear Pull Request detailing your additions.

---

## Disclaimer & Responsible Use

- This repository is curated for educational, defensive, and authorized audit purposes only.
- Penetration testing and adversary emulation execute active tactics against targets. **Only run these tools on networks, applications, and hosts for which you possess explicit, written authorization.**
- The creators and maintainers of this repository assume no liability for misuse, service interruptions, or damages caused by tools listed within this guide.
