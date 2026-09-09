<div align="center">

# Hajra Ramzan

### SOC Analyst in training · Detection Engineering · Blue Team

Cyber Security and Networks student at the University of East London, graduating 2027.
I build a security home lab, attack it, and write up what the defences actually caught.

<a href="https://www.linkedin.com/in/hajra-ramzan-hry/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://tryhackme.com/p/EHR">
  <img src="https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe">
</a>
<a href="https://github.com/0720hr/hr_range">
  <img src="https://img.shields.io/badge/Home_Lab_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Home Lab repository">
</a>

</div>

---

## About Me

Security made sense to me the moment I stopped reading about attacks and started running them. I built a lab on a single laptop, attacked it myself, and watched what the defences actually caught. A good half of it did not work, and that turned out to be the half worth having. A rule I was certain was broken had been fine all along. A workflow that passed every test I wrote was completely broken. Working out why taught me more than any course had.

That is how I learn now. I build something, break it, and write up what happened, including the parts that were embarrassing, because a write-up where everything worked first time is not telling anyone very much.

My focus is clear. I want to work inside a security operations centre, defending one organisation, and get properly good at detection, triage and incident response. That is where you see what attacks look like at volume rather than one at a time, and it is the work I have been building this lab to prepare for.

---

## Featured Projects

All four projects live in one repository: [**0720hr/hr_range**](https://github.com/0720hr/hr_range). Each has its own write-up with the problems I hit, how I fixed them, and how I verified it worked.

| Project | What it demonstrates | Tools |
|---|---|---|
| **[01 · Wazuh SIEM Detection Lab](https://github.com/0720hr/hr_range/tree/main/01-wazuh-siem-lab)** | Detects a full SSH attack chain, from password guessing through to an attacker gaining root, with each stage mapped to MITRE ATT&CK and the attacker blocked automatically by a firewall rule that expires after 180 seconds. | Wazuh, Docker, iptables, MITRE ATT&CK |
| **[02 · SOC Automation](https://github.com/0720hr/hr_range/tree/main/02-soc-automation)** | Picks up serious alerts without a human, enriches the attacker's address against threat intelligence, emails an analyst, and contains confirmed account takeovers through the Wazuh API. | Shuffle (SOAR), VirusTotal API, Wazuh API, SMTP |
| **[03 · Endpoint Detection with LimaCharlie](https://github.com/0720hr/hr_range/tree/main/03-limacharlie-edr)** | Runs the same attack past an EDR and a SIEM watching one Windows endpoint, to show what endpoint telemetry catches that log-based detection cannot, and where each tool is blind. | LimaCharlie (EDR), Sysmon, Wazuh |
| **[04 · Adversary Emulation and Detection Coverage](https://github.com/0720hr/hr_range/tree/main/04-adversary-emulation)** | Runs seven ATT&CK techniques against the lab, measures Wazuh against LimaCharlie in a coverage matrix, writes custom rules to close the gaps, and works the confirmed detections as incident cases. | Atomic Red Team, Wazuh, LimaCharlie, DFIR-IRIS |

Every detection was triggered by a real attack inside the lab and verified afterwards in the alert data. None of it was tested only in a rule simulator and left there.

---

## What I Can Do

- Write and tune custom detection rules, and diagnose why one is not firing
- Map detections to MITRE ATT&CK techniques and measure coverage across tools
- Deploy and operate a SIEM across manager, indexer and dashboard, and enrol agents
- Build automation playbooks with conditional branching and API-driven response
- Reconstruct an attack chain from raw logs and verify that containment actually happened
- Run structured adversary emulation to test detections against live activity, not a simulator
- Work confirmed detections as incident cases with assets, indicators and a timeline
- Rotate credentials, manage secrets, and keep configuration out of version control

---

## Tools

<div align="center">

[![My tools](https://skillicons.dev/icons?i=docker,linux,ubuntu,bash,powershell,git,github,windows)](https://skillicons.dev)

</div>

| Area | What I use |
|---|---|
| **SIEM and detection** | Wazuh 4.14.5, Sysmon, custom detection rules, MITRE ATT&CK |
| **Endpoint detection** | LimaCharlie (EDR), detection and response rules |
| **Automation and response** | Shuffle (SOAR), webhooks, REST APIs, VirusTotal, SMTP |
| **Adversary emulation** | Atomic Red Team, coverage matrices |
| **Case management** | DFIR-IRIS |
| **Platforms** | Docker, Docker Compose, Linux, Ubuntu, WSL2, Bash |
| **Windows and infrastructure** | Windows Server 2022, Active Directory, DNS, DHCP, PowerShell, VMware |
| **Networking and defence** | iptables, TCP/IP, SSH hardening |
| **Other** | Git, OpenSearch |

---

## Experience

**SecurityHQ** — a managed security services provider that runs security monitoring for other companies. I was selected as one of two candidates from over 200 applicants through their Diversity of Thought programme. I rotated across the business, and the SOC is where it clicked: real tickets, live log analysis, and clients being walked through what went wrong and how to fix it. Seeing alerts arrive at volume rather than one at a time is what pointed me towards detection engineering.

**University of East London** — Junior IT Technician. Three months standing up Windows Server 2022 with Active Directory, DNS and DHCP, and running Windows and Ubuntu machines in VMware. Knowing how infrastructure is actually put together is what lets me reason about what an attacker is doing to it, because half of detection is knowing what normal looks like.

---

## Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=0720hr&show_icons=true&hide_border=true&count_private=false&theme=midnight-purple" alt="GitHub stats">
<img height="165" src="https://streak-stats.demolab.com/?user=0720hr&hide_border=true&theme=midnight-purple" alt="GitHub streak">

<br>

<a href="https://tryhackme.com/p/EHR">
  <img src="https://tryhackme-badges.s3.amazonaws.com/EHR.png" alt="TryHackMe badge for EHR">
</a>

</div>

---

<div align="center">

Open to SOC placements and internships in the UK.

</div>
