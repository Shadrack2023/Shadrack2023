# Hi, I'm Shadrack Otieno

### Penetration Tester · Offensive Security Analyst

I break into things ethically and write the report that helps you fix them. I specialize in **Active Directory exploitation, API security, web and mobile penetration testing, network security and full-scope VAPT** for financial institutions, healthcare providers, SaaS platforms, insurers and SACCOs, pairing an attacker's mindset with clear, business-focused reporting that turns exploit chains into prioritized remediation.

*Currently pursuing the OSCP/OSEP path and going deeper on Active Directory and cloud attack surfaces.*

---

## Security Tools I've Built

Field-tested tooling from real internal engagements. Each one exists because the off-the-shelf option was too noisy, too manual, or blind to the thing that actually mattered.

| Tool | What it does |
|------|--------------|
| [**adpwner**](https://github.com/Shadrack2023/adpwner) | Stateful Active Directory relay-chain orchestrator. It carries credential state between steps, so a hash captured by a relay is driven automatically to the next hop, from coercion and poisoning through to NTDS.dit as domain-compromise proof. Hard scope allowlist, live output, and a timestamped evidence log the report is built from. |
| [**authauditor**](https://github.com/Shadrack2023/authauditor) | API access-control auditor that finds broken authentication and broken authorization (BOLA and BFLA) in REST APIs. Two decoupled stages, discover then test, joined by a portable inventory, so a Postman collection and a bare hostname are the same tool with a different loader. |
| [**rootmapper**](https://github.com/Shadrack2023/rootmapper) | Single-file, standard-library Linux post-exploitation enumerator. Strictly read-only. It ranks privilege-escalation findings by real-world exploitability instead of dumping everything, and hands you the exact command to verify each one. |
| [**winprivesc**](https://github.com/Shadrack2023/winprivesc) | The Windows counterpart to rootmapper. Every "you can escalate here" finding is checked against your effective token identity, your SID plus every group SID and your integrity level, so a writable-service claim means *you* can actually write it, not that some unrelated principal theoretically could. |
| [**networktools**](https://github.com/Shadrack2023/networktools) | Network device monitor that resolves MACs for offline or sleeping hosts by combining an nmap ARP scan with `/proc/net/arp` and `ip neigh`, then logs the deltas over time. |

---

## Core Skills

- **Active Directory and Internal:** attack-path analysis, Kerberoasting, NTLM relay, authentication coercion, AD CS abuse, lateral movement, privilege escalation, GPO and share review
- **API and Web:** authn/authz testing, IDOR and BOLA, broken access control, business-logic flaws, endpoint enumeration and fuzzing, OWASP API Top 10
- **Network and Infrastructure:** internal and external VAPT, recon, service enumeration, firewall and NAC review
- **Mobile:** static (MobSF, JADX) and dynamic analysis, hardcoded-secret detection, insecure storage, backend API trust
- **Scripting:** Python, Bash · Frameworks: OWASP, MITRE ATT&CK, NIST, PTES

## Arsenal

```text
[recon]    Nmap · httpx · nuclei · ffuf · dirsearch · whois · Shodan · Censys · fierce
[ad]       Responder · ntlmrelayx · Impacket · NetExec · mitm6 · PetitPotam · Coercer · Certipy
           Rubeus · Kerbrute · BloodHound · bloodyAD · secretsdump · lsassy
[web/api]  Burp Suite · sqlmap · nuclei · ffuf · jwt_tool · Nikto · mitmproxy · Postman
[mobile]   MobSF · JADX · Frida · objection · adb
[creds]    hashcat · John the Ripper · Hydra · Medusa · SecLists
[pivot]    Ligolo-ng · Chisel · proxychains · socat · evil-winrm · SSH
[dfir/db]  Volatility 3 · PowerUpSQL · mssqlclient · gitleaks
```

Core platform: `Kali Linux` · `Docker` · `Wireshark` · `Metasploit`

---

## Writeups and Reports

| Repo | What's inside |
|------|---------------|
| [**htb-walkthroughs**](https://github.com/Shadrack2023/htb-walkthroughs) | Hack The Box machine writeups (retired and seasonal) |
| [**thm-walkthroughs**](https://github.com/Shadrack2023/thm-walkthroughs) | TryHackMe room walkthroughs |
| [**Sec-Research**](https://github.com/Shadrack2023/Sec-Research) | Methodology notes, tooling guides and vuln deep-dives |
| [**pentest-lab-reports**](https://github.com/Shadrack2023/pentest-lab-reports) | Full VAPT-style reports from practice labs |

## Certifications

- API Penetration Testing, **APISec University** (2026)
- **Cisco** Ethical Hacker and Network Defense (2025)
- Cybersecurity Analyst, **Cyber Shujaa** (2024)

B.Sc. Computer Science, Meru University of Science and Technology

---

## Connect

- shageee2023@gmail.com
- [LinkedIn](https://www.linkedin.com/in/shadrack-mwabe-bb7a8a2b1)

> *"The flag, dear Brutus, is not in our stars, but in our skill to find vulnerabilities where others see none."*
