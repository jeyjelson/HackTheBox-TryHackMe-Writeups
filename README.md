# TryHackMe & HackTheBox Write-Ups
My write-ups for the boxes and challenges I've worked through - how I enumerated, what I exploited, and how I got root. Each one walks through the full process with screenshots and an attack-path diagram.

## Offensive Security

### Cross-Site Scripting (XSS)
| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [XSS Phishing](./HTB%20XSS%20Phishing%20CTF%20writeup/README.md) | HTB Academy | Intermediate | Cross-site scripting, phishing form injection, credential harvesting |
| [Session Hijacking](./HTB%20Session%20Hijacking%20CTF%20writeup/README.md) | HTB Academy | Intermediate | Blind XSS, cookie theft, session hijacking |
| [XSS Skills Assessment](./HTB%20XSS%20Skills%20Assessment%20CTF%20writeup/README.md) | HTB Academy | Intermediate | Blind XSS, cookie theft, session hijacking |
| [Headless](./HTB%20Headless%20CTF%20Writeup/README.md) | HTB Labs | Easy | Header-based XSS, blind XSS cookie theft, command injection, relative-path privilege escalation |

### Server-Side Request Forgery (SSRF)
| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [In-Band SSRF Skills Assessment](./HTB%20In-Band%20SSRF%20Skills%20Assessment%20Writeup/README.md) | HTB Academy | Easy | SSRF, internal port scanning with ffuf, localhost trust abuse |
| [SSRF Enumeration Skills Assessment](./HTB%20SSRF%20Enumeration%20Skills%20Assessment%20Writeup/README.md) | HTB Academy | Easy | SSRF directory enumeration with ffuf, Apache error filtering, internal admin access |
| [Blind SSRF Enumeration](./HTB%20Blind%20SSRF%20Skills%20Assessment%20Writeup/README.md) | HTB Academy | Easy | Blind SSRF, dateserver parameter abuse, ffuf port fuzzing, internal loopback enumeration |

### Injection
| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [Recruit](./THM%20Recruit%20CTF%20Writeup/README.md) | TryHackMe | Intermediate | Enumeration, LFI, SQL injection |
| [Validation](./HTB%20Validation%20CTF%20writeup/README.md) | HTB Labs | Easy | SQL injection, web shell, privilege escalation |
| [Command Injection Skills Assessment](./HTB%20Command%20Injection%20Skills%20Assessment%20Writeup/README.md) | HTB Academy | Easy | Command injection, filter bypass, ${IFS} and ${PATH:0:1} obfuscation, path traversal |
| [Identifying Template Engine for SSTI](./HTB%20SSTI%20Template%20Engine%20Identification%20Writeup/README.md) | HTB Academy | Easy | SSTI, template engine fingerprinting, decision-tree payload testing, Twig vs Jinja2 identification |
| [SSTI Exploitation Jinja2 Flask](./HTB%20SSTI%20Exploitation%20Jinja2%20Flask%20CTF%20Writeup/README.md) | HTB Academy | Easy | Jinja2 SSTI, config.items disclosure, __builtins__ enumeration, LFI via open, os.popen RCE |
| [SSTI Exploitation Twig](./HTB%20SSTI%20Exploitation%20Twig%20CTF%20Writeup/README.md) | HTB Academy | Easy | Twig SSTI, _self enumeration, Symfony file_excerpt LFI, filter+system RCE, path traversal |
| [Identifying and Exploiting Server-Side Includes Injection](./HTB%20Identifying%20and%20Exploiting%20Server-Side%20Includes%20Injection%20CTF%20Writeup/README.md) | HTB Academy| Easy | SSI injection, .shtml detection, #printenv confirmation, #exec RCE, path traversal |

## Defensive Security
| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [Incident Handling](./HTB%20Incident%20Handling%20Write-up/README.md) | HTB Academy | Easy | TheHive triage, VirusTotal enrichment, MITRE ATT&CK mapping, Base64 PowerShell decoding |
| [Nessus Vulnerability Assessment](./HTB%20Nessus%20Vulnerability%20Assessment/README.md) | HTB Academy | Easy | Authenticated vulnerability scanning |

## AI Security
| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [ContAInment](./ContAInment%20THM%20CTF%20writeup/README.md) | TryHackMe | Intermediate | Phishing analysis, PCAP forensics, prompt injection, LLM exploitation |

More on the way
