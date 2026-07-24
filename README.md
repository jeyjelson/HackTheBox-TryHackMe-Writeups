# TryHackMe & HackTheBox Write-Ups

My write-ups for the boxes and challenges I've worked through - how I enumerated, what I exploited, and how I got root. Each one walks through the full process with screenshots and an attack-path diagram.

## Offensive Security

| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [Recruit](./THM%20Recruit%20CTF%20Writeup) | TryHackMe | Intermediate | Enumeration, LFI, SQL injection |
| [Validation](./HTB%20Validation%20CTF%20writeup/README.md) | HTB Labs | Easy | SQL injection, web shell, privilege escalation |
| [XSS Phishing](./HTB%20XSS%20Phishing%20CTF%20writeup) | HTB Academy | Intermediate | Cross-site scripting, phishing form injection, credential harvesting |
| [Session Hijacking](./HTB%20Session%20Hijacking%20CTF%20writeup) | HTB Academy | Intermediate | Blind XSS, cookie theft, session hijacking |
| [XSS Skills Assessment](./HTB%20XSS%20Skills%20Assessment%20CTF%20writeup) | HTB Academy | Intermediate | Blind XSS, cookie theft, session hijacking |
| [Headless](./HTB%20Headless%20CTF%20Writeup) | HTB Labs | Easy | Header-based XSS, blind XSS cookie theft, command injection, relative-path privilege escalation
| [Command Injection Skills Assessment](./HTB%20Command%20Injection%20Skills%20Assessment%20Writeup) | HTB Academy | Easy | Command injection, filter bypass, ${IFS} and ${PATH:0:1} obfuscation, path traversal |
| [SSRF Skills Assessment](./HTB%20In-BandSSRF%20Skills%20Assessment%20Writeup/README.md) | HTB Academy | Easy | SSRF, internal port scanning with ffuf, localhost trust abuse |

## Defensive Security

| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [Nessus Vulnerability Assessment](./HTB%20Nessus%20Vulnerability%20Assessment) | HTB Academy | Easy | Authenticated vulnerability scanning |
| [Incident Handling](./HTB%20Incident%20Handling%20Write-up/README.md) | HTB Academy | Easy | TheHive triage, VirusTotal enrichment, MITRE ATT&CK mapping, Base64 PowerShell decoding |

## AI Security

| Box | Platform | Difficulty | Key techniques |
|-----|----------|------------|----------------|
| [ContAInment](./ContAInment%20THM%20CTF%20writeup) | TryHackMe | Intermediate | Phishing analysis, PCAP forensics, prompt injection, LLM exploitation |

More on the way
