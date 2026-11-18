# Cybersecurity Learning Roadmap

[← Back to repository overview](../README.md)

This roadmap is designed to be followed progressively. You can move at your own pace; focus on understanding and documenting concepts rather than rushing through tools.

## Stage 1 — Foundations

**Learn**
- Confidentiality, integrity, and availability (CIA).
- Threats, vulnerabilities, risks, and security controls.
- Authentication, authorization, and least privilege.
- Common malware, phishing, social engineering, and safe browsing.

**Practice**
- Explain a security incident in plain language.
- Create a simple asset-and-risk register for a fictional small business.
- Review account security settings on your own accounts.

**Ready to move on when:** you can explain the difference between a threat, vulnerability, and risk.

## Stage 2 — Networking and operating systems

**Learn**
- OSI and TCP/IP models.
- IP addresses, subnetting basics, DNS, DHCP, HTTP/HTTPS, ports, and routing.
- Linux file permissions, processes, services, users, and logs.
- Windows basics, event logs, and account permissions.

**Practice**
- Draw the path of a web request from browser to server.
- Read sample network captures and identify common protocols.
- Use a local Linux virtual machine for basic administration.

**Ready to move on when:** you can explain what happens when a browser opens a website.

## Stage 3 — Scripting and data

**Learn**
- Python basics: variables, conditions, loops, functions, files, and exceptions.
- SQL basics: SELECT, filtering, joins, and safe parameterized queries.
- JSON, CSV, regular expressions, and command-line workflows.

**Practice**
- Parse a sample log file and summarize event counts.
- Write a script that validates a list of IP address strings.
- Query a small local database using parameterized statements.

## Stage 4 — Choose a security path

### SOC and Blue Team
- Log sources, event severity, alert triage, and escalation.
- Indicators of compromise (IOCs) and basic threat intelligence.
- SIEM concepts, detection logic, incident response, and reporting.
- Understand the incident lifecycle: preparation, detection, analysis, containment, recovery, and lessons learned.

### Vulnerability Assessment and Penetration Testing
- Scope, written authorization, rules of engagement, and safe testing.
- Asset discovery concepts, vulnerability classes, and validation.
- OWASP Top 10, access control, authentication, input handling, and security misconfiguration.
- Risk rating, evidence quality, remediation advice, and retesting.

Only test intentionally vulnerable labs, your own systems, or systems where you have explicit permission.

### Digital Forensics
- Evidence integrity, chain of custody, and forensic documentation.
- File systems, metadata, timestamps, and timeline concepts.
- Disk and mobile device forensics concepts.
- Hashes, evidence handling, analysis notes, and clear reporting.

## Stage 5 — Build and document projects

Suggested beginner-friendly projects:
1. **Log Analyzer:** parse sample logs and flag unusual patterns.
2. **Network Notes:** explain selected protocols using safe sample captures.
3. **Security Checklist:** create a baseline checklist for a personal lab.
4. **Web Security Notes:** document common web risks and their mitigations.
5. **Forensic Case Notes:** write a fictional case report using supplied training evidence.

For each project, include its purpose, setup, test data, method, results, limitations, and lessons learned. Never publish passwords, tokens, private data, or real incident evidence without permission.

## Stage 6 — Portfolio and career readiness

- Keep project descriptions accurate and explain your own contribution.
- Write concise reports that include impact and practical remediation.
- Practice explaining technical concepts in everyday language.
- Keep a learning log and update your roadmap as your skills develop.
- Review local laws, platform rules, and responsible disclosure expectations.

## Tools reference

| Purpose | Tools to explore |
|---|---|
| Network analysis | Wireshark, Nmap |
| Web application testing | Burp Suite, OWASP ZAP |
| Vulnerability assessment | Nessus |
| Digital forensics | Autopsy, FTK, MOBILedit |
| Scripting and systems | Python, SQL, Linux |

A tool is only as useful as the analyst's understanding. Verify results, record limitations, and avoid treating automated output as confirmed fact.

## Learning links

- [Cybersecurity Learning Lab](https://learning-no.github.io/Cybersecurity-Learning-Lab/)
- [Cyber Sentinel project](https://github.com/IamZer01-ai/IamZer01-Sentinel)
- [IamZer01-ai on GitHub](https://github.com/IamZer01-ai)

---

**Learning principle:** understand the concept → practice in an authorized environment → document the result → review what could be improved.
