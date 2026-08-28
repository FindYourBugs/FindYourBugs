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
| [danglingtree-writeup](https://github.com/FindYourBugs/danglingtree-writeup) | Full technical writeup, HTB "DanglingTree" (Medium) — AD forest with an Enterprise CA in the chain. | 0 |
| [Puppet---HTB-writeup](https://github.com/FindYourBugs/Puppet---HTB-writeup) | — | 0 |
| [checkpoint---writeup](https://github.com/FindYourBugs/checkpoint---writeup) | — | 0 |
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

`Burp Suite` `nmap` `ffuf` / `feroxbuster` `impacket` `BloodHound` / `bloodyAD` `evil-winrm` `Rubeus` `Responder` `ligolo-ng` `hashcat` `Frida` `ilspycmd` `Python` `Bash` `Wazuh`

---

<div align="center">
<sub>Open to freelance Web & Android VAPT engagements — reach out via <a href="https://linkedin.com/in/shrikant-shinde-194890202">LinkedIn</a> or <a href="mailto:shinde.shrikant1604@gmail.com">email</a>.</sub>
</div>
