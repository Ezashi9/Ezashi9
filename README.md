## Hi, I'm Eisa

I'm a Level 3 Computer Science student (BTEC Extended Diploma) in Watford, UK, looking for a **cyber security apprenticeship starting September 2027**.

I build small security tools that actually work, and publish each one with tests, a live demo where possible, and a write-up explaining the decisions behind it.

**Portfolio: [ezashi9.github.io](https://ezashi9.github.io)**

### Home SOC: a security operations centre built piece by piece

| Stage | Project | What it does |
|---|---|---|
| Detect | [Log Hunter](https://github.com/Ezashi9/log-hunter) | Finds SSH brute force, spraying and suspicious logins; mapped to MITRE ATT&CK with Sigma rules; 10/10 on labelled attack scenarios |
| Investigate | [IOC Enricher](https://github.com/Ezashi9/ioc-enricher) | Checks attacker IPs against AbuseIPDB threat intelligence |
| Report | [Home SOC Dashboard](https://github.com/Ezashi9/home-soc-dashboard) · [live](https://ezashi9.github.io/home-soc-dashboard/) | Web dashboard, hardened against log-injection XSS |
| Automate | [Live Threat Feed](https://ezashi9.github.io/home-soc-dashboard/live.html) | Runs itself daily: pulls current attackers from SANS DShield and blocklist.de and checks them |

### Email, cloud, risk and privacy

- [Cloud Config Auditor](https://github.com/Ezashi9/cloud-config-auditor): finds high-impact AWS misconfigurations in Terraform before deployment; 17/17 TerraGoat flaws caught, agrees with Checkov on 49 resources and found a secret it missed.

- [Phish Triage](https://github.com/Ezashi9/phish-triage): analyses suspicious emails like a SOC analyst; caught 59.3% of a held-out sample of real phishing with 0.9% false alarms.
- [Cyber Essentials Risk Assessment](https://github.com/Ezashi9/cyber-essentials-assessment): risk register, Cyber Essentials v3.3 gap analysis and costed action plan for a fictional small business.
- [Breach Check](https://github.com/Ezashi9/breach-check) · [try it](https://ezashi9.github.io/breach-check/): checks if a password has been leaked without it ever leaving your device (k-anonymity).

### How I work

Every project runs its tests automatically on each change, has CodeQL code scanning, Dependabot and secret scanning switched on, keeps API keys out of the code, and pins dependencies to exact commits. I build with an AI coding assistant and make sure I can explain every design decision myself.

[LinkedIn](https://www.linkedin.com/in/eisa-c-667294372/)
