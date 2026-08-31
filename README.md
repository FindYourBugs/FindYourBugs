<div align="center">

# Shrikant Shinde
### [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2F6FED&center=true&vCenter=true&width=600&lines=Offensive+Security)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-findyourbugs.github.io-2F6FED?style=flat-square)](https://findyourbugs.github.io/shrikant-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shrikant--shinde-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrikant-shinde-194890202)
[![Medium](https://img.shields.io/badge/Medium-@findyourbugs-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@findyourbugs)
[![Email](https://img.shields.io/badge/Email-shinde.shrikant1604-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:shinde.shrikant1604@gmail.com)

</div>

---

## About

Penetration tester focused on **Web Application VAPT**, **Android Application VAPT**, and **Active Directory / network penetration testing**, with a background in **SIEM log analysis** and **digital forensics**. I test the way an attacker actually chains failures together — not one CVE at a time — and I write reports the way I'd want to receive one: reproducible, scoped, and with a fix that actually closes the hole.

Currently building toward freelance VAPT work and bug bounty, on top of hands-on lab work that goes well past "ran a scanner."

## Recent engagements

**HackTheBox "Odyssey" (Insane)** — full external-to-Domain-Admin kill chain: NoSQL aggregation-pipeline injection → forged WebAuthn credential + `userHandle` confusion → prototype pollution into a LaTeX file-read oracle → jsonpath-plus RCE → password reuse to root → MSSQL NTLM coercion → GodPotato to SYSTEM → Shadow Credentials chained through a 4-level nested AD group into a **BadSuccessor dMSA** identity-theft abuse → reverse-engineered a custom .NET named-pipe service (decompiled with ilspycmd) into a **DPAPI decryption-oracle** bug and a **YamlDotNet `ObjectDataProvider` deserialization RCE** → Rubeus `tgtdeleg` → DCSync → Domain Admin.

**HackTheBox "Silentium" (Insane)** — Flowise 3.0.5 unauthenticated password-reset token leak (CVE-2025-58434) → admin takeover → `Function()`-constructor RCE via a Custom MCP node (CVE-2025-59528) → container escape via leaked env credentials → internal Gogs instance compromised via a symlink-based `PutContents` arbitrary file write (CVE-2025-8110) → overwrote `root`'s `authorized_keys` → root.

*(Full writeups follow the same format as [danglingtree-writeup](https://github.com/FindYourBugs/danglingtree-writeup) below.)*

## What I test

| | |
|---|---|
| **Web Application VAPT** | Auth/session logic flaws, injection (SQL/NoSQL/SSTI), IDOR, deserialization, SSRF, business-logic abuse |
| **API Security Testing** | BOLA/IDOR, broken function-level auth, mass assignment, rate-limit/abuse flaws, GraphQL introspection & injection |
| **Android Application VAPT** | Insecure storage, weak transport security, broken auth, exported-component abuse, static + dynamic (Frida) analysis |
| **Network / Infrastructure Pentesting** | External & internal network assessments, service enumeration, firewall/segmentation testing, pivoting |
| **Active Directory & Red Teaming** | Kerberos abuse (Shadow Credentials, dMSA/BadSuccessor, delegation), lateral movement, credential coercion, C2 tradecraft, adversary emulation |
| **SIEM & Forensics** | Log correlation, detection-rule authoring (Wazuh), incident triage, timeline reconstruction |

## Projects

- **[VAPT.ai](https://github.com/FindYourBugs/VAPT.ai)** — local AI-assisted VAPT workspace: FastAPI backend, scope enforcement, Kali tool orchestration, controlled browser capture, local LLM-assisted analysis, and audit-logged reporting.
- **[AI-Pentesting-Playground](https://github.com/FindYourBugs/AI-Pentesting-Playground)** — practical test cases for the OWASP Top 10 for LLM applications.
- **[sophos-wazuh-decoder](https://github.com/FindYourBugs/sophos-wazuh-decoder)** / **[sophos-wazuh-rule](https://github.com/FindYourBugs/sophos-wazuh-rule)** — custom Wazuh SIEM decoders and detection rules for Sophos firewall logs.

## Writeups

<!-- WRITEUPS:START -->
| Writeup | Description | ★ |
|---|---|---|
| [paperwork-writeup](https://github.com/FindYourBugs/paperwork-writeup) | HackTheBox "Paperwork" — Easy Difficulty — Legacy Protocol Exploitation & Privilege Escalation Writeup | 0 |
| [odyssey-writeup](https://github.com/FindYourBugs/odyssey-writeup) | HackTheBox "Odyssey" — Insane Difficulty — Web Chain to Active Directory Domain Compromise Writeup | 0 |
| [nimbus-writeup](https://github.com/FindYourBugs/nimbus-writeup) | HackTheBox "Nimbus" — Hard Difficulty — Cloud-Native / AWS Service Abuse Pentest Writeup | 0 |
| [ghostlink-writeup](https://github.com/FindYourBugs/ghostlink-writeup) | HackTheBox "Ghostlink" — Insane Difficulty — Active Directory / ADCS Pentest Writeup | 0 |
| [darkzeroreturns-writeup](https://github.com/FindYourBugs/darkzeroreturns-writeup) | HackTheBox "DarkZeroReturns" — Hard Difficulty — Pro Lab Entry Chain: AD Forest Trust & CI/CD Abuse Writeup | 0 |
| [cobblestone-writeup](https://github.com/FindYourBugs/cobblestone-writeup) | HackTheBox "Cobblestone" — Insane Difficulty — Second-Order SQLi to Twig SSTI to Cobbler RCE Writeup | 0 |
| [bedside-writeup](https://github.com/FindYourBugs/bedside-writeup) | HackTheBox "Bedside" — Medium Difficulty — Web Exploitation, Container Pivoting & ML Deserialization Writeup | 0 |
| [abducted-writeup](https://github.com/FindYourBugs/abducted-writeup) | HackTheBox "Abducted" — Medium Difficulty — Samba Print-Spooler RCE & Privilege Escalation Writeup | 0 |
| [danglingtree-writeup](https://github.com/FindYourBugs/danglingtree-writeup) | Full technical writeup, HTB "DanglingTree" (Medium) — AD forest with an Enterprise CA in the chain. | 0 |
| [Puppet---HTB-writeup](https://github.com/FindYourBugs/Puppet---HTB-writeup) | Hack The Box Pro Lab: Puppet - Writeup | 0 |
| [checkpoint---writeup](https://github.com/FindYourBugs/checkpoint---writeup) | Checkpoint — Hack The Box Writeup — Medium — Active Directory, SMB, VMware Memory Forensics, Kerberos, BadSuccessor/dMSA | 0 |
<!-- WRITEUPS:END -->

*(Auto-updated — every new public repo with "writeup" in its name shows up here automatically.)*

## GitHub stats

<div align="center">
<img src="https://raw.githubusercontent.com/FindYourBugs/FindYourBugs/master/github-metrics.svg" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=FindYourBugs&hide_border=true#gh-light-mode-only" />
</div>

## Toolset

### 🌐 Reconnaissance & OSINT
![Maltego](https://img.shields.io/badge/Maltego-0EA5E9?style=for-the-badge) ![Shodan](https://img.shields.io/badge/Shodan-0EA5E9?style=for-the-badge) ![Censys](https://img.shields.io/badge/Censys-0EA5E9?style=for-the-badge) ![FOFA](https://img.shields.io/badge/FOFA-0EA5E9?style=for-the-badge) ![ZoomEye](https://img.shields.io/badge/ZoomEye-0EA5E9?style=for-the-badge) ![Recon-ng](https://img.shields.io/badge/Recon--ng-0EA5E9?style=for-the-badge) ![SpiderFoot](https://img.shields.io/badge/SpiderFoot-0EA5E9?style=for-the-badge) ![theHarvester](https://img.shields.io/badge/theHarvester-0EA5E9?style=for-the-badge) ![Sherlock](https://img.shields.io/badge/Sherlock-0EA5E9?style=for-the-badge) ![Holehe](https://img.shields.io/badge/Holehe-0EA5E9?style=for-the-badge) ![Photon](https://img.shields.io/badge/Photon-0EA5E9?style=for-the-badge) ![Dmitry](https://img.shields.io/badge/Dmitry-0EA5E9?style=for-the-badge) ![Amass](https://img.shields.io/badge/Amass-0EA5E9?style=for-the-badge) ![Subfinder](https://img.shields.io/badge/Subfinder-0EA5E9?style=for-the-badge) ![AssetFinder](https://img.shields.io/badge/AssetFinder-0EA5E9?style=for-the-badge) ![httpx](https://img.shields.io/badge/httpx-0EA5E9?style=for-the-badge) ![waybackurls](https://img.shields.io/badge/waybackurls-0EA5E9?style=for-the-badge) ![gau](https://img.shields.io/badge/gau-0EA5E9?style=for-the-badge) ![Osmedeus](https://img.shields.io/badge/Osmedeus-0EA5E9?style=for-the-badge) ![IntelX](https://img.shields.io/badge/IntelX-0EA5E9?style=for-the-badge)

### 🎯 Web Application & API Security Testing
![Burp Suite](https://img.shields.io/badge/Burp+Suite-F97316?style=for-the-badge) ![OWASP ZAP](https://img.shields.io/badge/OWASP+ZAP-F97316?style=for-the-badge) ![Nuclei](https://img.shields.io/badge/Nuclei-F97316?style=for-the-badge) ![FFUF](https://img.shields.io/badge/FFUF-F97316?style=for-the-badge) ![feroxbuster](https://img.shields.io/badge/feroxbuster-F97316?style=for-the-badge) ![Gobuster](https://img.shields.io/badge/Gobuster-F97316?style=for-the-badge) ![dirsearch](https://img.shields.io/badge/dirsearch-F97316?style=for-the-badge) ![WPScan](https://img.shields.io/badge/WPScan-F97316?style=for-the-badge) ![Nikto](https://img.shields.io/badge/Nikto-F97316?style=for-the-badge) ![SQLmap](https://img.shields.io/badge/SQLmap-F97316?style=for-the-badge) ![Arjun](https://img.shields.io/badge/Arjun-F97316?style=for-the-badge) ![ParamSpider](https://img.shields.io/badge/ParamSpider-F97316?style=for-the-badge) ![Dalfox](https://img.shields.io/badge/Dalfox-F97316?style=for-the-badge) ![XSStrike](https://img.shields.io/badge/XSStrike-F97316?style=for-the-badge) ![Corsy](https://img.shields.io/badge/Corsy-F97316?style=for-the-badge) ![jwt_tool](https://img.shields.io/badge/jwt_tool-F97316?style=for-the-badge) ![GraphQLmap](https://img.shields.io/badge/GraphQLmap-F97316?style=for-the-badge) ![Caido](https://img.shields.io/badge/Caido-F97316?style=for-the-badge)

### 📱 Mobile & Android Security
![Frida](https://img.shields.io/badge/Frida-0D9488?style=for-the-badge) ![jadx](https://img.shields.io/badge/jadx-0D9488?style=for-the-badge) ![apktool](https://img.shields.io/badge/apktool-0D9488?style=for-the-badge) ![MobSF](https://img.shields.io/badge/MobSF-0D9488?style=for-the-badge) ![Objection](https://img.shields.io/badge/Objection-0D9488?style=for-the-badge)

### 🌍 Network & Infrastructure Scanning
![Nmap](https://img.shields.io/badge/Nmap-16A34A?style=for-the-badge) ![Masscan](https://img.shields.io/badge/Masscan-16A34A?style=for-the-badge) ![RustScan](https://img.shields.io/badge/RustScan-16A34A?style=for-the-badge) ![Netcat](https://img.shields.io/badge/Netcat-16A34A?style=for-the-badge) ![Nessus](https://img.shields.io/badge/Nessus-16A34A?style=for-the-badge) ![OpenVAS](https://img.shields.io/badge/OpenVAS-16A34A?style=for-the-badge) ![Zmap](https://img.shields.io/badge/Zmap-16A34A?style=for-the-badge) ![DNSx](https://img.shields.io/badge/DNSx-16A34A?style=for-the-badge) ![Shodan CLI](https://img.shields.io/badge/Shodan+CLI-16A34A?style=for-the-badge)

### 🏰 Active Directory Attacks
![BloodHound](https://img.shields.io/badge/BloodHound-78350F?style=for-the-badge) ![bloodyAD](https://img.shields.io/badge/bloodyAD-78350F?style=for-the-badge) ![Impacket](https://img.shields.io/badge/Impacket-78350F?style=for-the-badge) ![NetExec](https://img.shields.io/badge/NetExec-78350F?style=for-the-badge) ![Responder](https://img.shields.io/badge/Responder-78350F?style=for-the-badge) ![Rubeus](https://img.shields.io/badge/Rubeus-78350F?style=for-the-badge) ![evil-winrm](https://img.shields.io/badge/evil--winrm-78350F?style=for-the-badge) ![Certipy-ad](https://img.shields.io/badge/Certipy--ad-78350F?style=for-the-badge) ![ligolo-ng](https://img.shields.io/badge/ligolo--ng-78350F?style=for-the-badge) ![Chisel](https://img.shields.io/badge/Chisel-78350F?style=for-the-badge) ![GodPotato](https://img.shields.io/badge/GodPotato-78350F?style=for-the-badge) ![Coercer](https://img.shields.io/badge/Coercer-78350F?style=for-the-badge) ![PetitPotam](https://img.shields.io/badge/PetitPotam-78350F?style=for-the-badge) ![pywhisker](https://img.shields.io/badge/pywhisker-78350F?style=for-the-badge) ![rpcclient](https://img.shields.io/badge/rpcclient-78350F?style=for-the-badge) ![ilspycmd](https://img.shields.io/badge/ilspycmd-78350F?style=for-the-badge)

### ⚡ Exploitation & Post-Exploitation Frameworks
![Metasploit](https://img.shields.io/badge/Metasploit-DC2626?style=for-the-badge) ![Empire](https://img.shields.io/badge/Empire-DC2626?style=for-the-badge) ![Covenant](https://img.shields.io/badge/Covenant-DC2626?style=for-the-badge) ![Sliver](https://img.shields.io/badge/Sliver-DC2626?style=for-the-badge) ![Cobalt Strike](https://img.shields.io/badge/Cobalt+Strike-DC2626?style=for-the-badge) ![BeEF](https://img.shields.io/badge/BeEF-DC2626?style=for-the-badge) ![Villain](https://img.shields.io/badge/Villain-DC2626?style=for-the-badge) ![pwncat](https://img.shields.io/badge/pwncat-DC2626?style=for-the-badge)

### 🔑 Password Cracking, Fuzzing & Credential Attacks
![John the Ripper](https://img.shields.io/badge/John+the+Ripper-9333EA?style=for-the-badge) ![Hashcat](https://img.shields.io/badge/Hashcat-9333EA?style=for-the-badge) ![Hydra](https://img.shields.io/badge/Hydra-9333EA?style=for-the-badge) ![Medusa](https://img.shields.io/badge/Medusa-9333EA?style=for-the-badge) ![Spray](https://img.shields.io/badge/Spray-9333EA?style=for-the-badge) ![CeWL](https://img.shields.io/badge/CeWL-9333EA?style=for-the-badge) ![Mentalist](https://img.shields.io/badge/Mentalist-9333EA?style=for-the-badge)

### 📡 Wireless, RF & IoT Security
![Aircrack-ng](https://img.shields.io/badge/Aircrack--ng-CA8A04?style=for-the-badge) ![Kismet](https://img.shields.io/badge/Kismet-CA8A04?style=for-the-badge) ![Wifite](https://img.shields.io/badge/Wifite-CA8A04?style=for-the-badge) ![Bettercap](https://img.shields.io/badge/Bettercap-CA8A04?style=for-the-badge) ![Flipper Zero](https://img.shields.io/badge/Flipper+Zero-CA8A04?style=for-the-badge) ![HackRF](https://img.shields.io/badge/HackRF-CA8A04?style=for-the-badge)

### ☁️ Cloud & Container Security
![ScoutSuite](https://img.shields.io/badge/ScoutSuite-4F46E5?style=for-the-badge) ![Prowler](https://img.shields.io/badge/Prowler-4F46E5?style=for-the-badge) ![Trivy](https://img.shields.io/badge/Trivy-4F46E5?style=for-the-badge) ![CloudSploit](https://img.shields.io/badge/CloudSploit-4F46E5?style=for-the-badge) ![Pacu](https://img.shields.io/badge/Pacu-4F46E5?style=for-the-badge) ![Checkov](https://img.shields.io/badge/Checkov-4F46E5?style=for-the-badge) ![Grype](https://img.shields.io/badge/Grype-4F46E5?style=for-the-badge) ![Falco](https://img.shields.io/badge/Falco-4F46E5?style=for-the-badge) ![kube-hunter](https://img.shields.io/badge/kube--hunter-4F46E5?style=for-the-badge) ![Trufflehog](https://img.shields.io/badge/Trufflehog-4F46E5?style=for-the-badge) ![GitLeaks](https://img.shields.io/badge/GitLeaks-4F46E5?style=for-the-badge)

### 🕵️ Digital Forensics & Traffic Analysis
![Wireshark](https://img.shields.io/badge/Wireshark-475569?style=for-the-badge) ![tcpdump](https://img.shields.io/badge/tcpdump-475569?style=for-the-badge) ![Autopsy](https://img.shields.io/badge/Autopsy-475569?style=for-the-badge) ![Volatility3](https://img.shields.io/badge/Volatility3-475569?style=for-the-badge) ![Zeek](https://img.shields.io/badge/Zeek-475569?style=for-the-badge) ![Suricata](https://img.shields.io/badge/Suricata-475569?style=for-the-badge) ![NetworkMiner](https://img.shields.io/badge/NetworkMiner-475569?style=for-the-badge) ![Velociraptor](https://img.shields.io/badge/Velociraptor-475569?style=for-the-badge) ![YARA](https://img.shields.io/badge/YARA-475569?style=for-the-badge) ![Wazuh](https://img.shields.io/badge/Wazuh-475569?style=for-the-badge)

### 🤖 AI & LLM Security Tooling
![Ollama](https://img.shields.io/badge/Ollama-DB2777?style=for-the-badge) ![LangChain](https://img.shields.io/badge/LangChain-DB2777?style=for-the-badge) ![OpenAI API](https://img.shields.io/badge/OpenAI+API-DB2777?style=for-the-badge) ![Garak](https://img.shields.io/badge/Garak-DB2777?style=for-the-badge) ![PyRIT](https://img.shields.io/badge/PyRIT-DB2777?style=for-the-badge) ![PromptBench](https://img.shields.io/badge/PromptBench-DB2777?style=for-the-badge)

---

<div align="center">
<sub>Open to freelance Web & Android VAPT engagements — reach out via <a href="https://linkedin.com/in/shrikant-shinde-194890202">LinkedIn</a> or <a href="mailto:shinde.shrikant1604@gmail.com">email</a>.</sub>
</div>
