<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0720hr/0720hr/main/header-dark.gif">
  <img src="https://raw.githubusercontent.com/0720hr/0720hr/main/header-light.gif" alt="Hajra Ramzan. Active role seeker. SOC Analyst, Detection Engineering, Blue Team." width="100%">
</picture>

<a href="https://www.linkedin.com/in/hajra-ramzan-hry/"><img src="https://raw.githubusercontent.com/0720hr/0720hr/main/btn-get-in-touch.png" alt="Get in touch on LinkedIn" height="44"></a>
&nbsp;&nbsp;
<a href="https://tryhackme.com/p/EHR"><img src="https://raw.githubusercontent.com/0720hr/0720hr/main/btn-tryhackme.png" alt="TryHackMe profile" height="44"></a>

</div>

---

## 👩‍💻 About Me

I am a Cyber Security and Networks student at the University of East London, graduating in 2027.

Security made sense to me the moment I stopped reading about attacks and started running them. I built a lab on a single laptop, attacked it myself, and watched what the defences actually caught. A good half of it did not work, and that turned out to be the half worth having. A rule I was certain was broken had been fine all along. A workflow that passed every test I wrote was completely broken. Working out why taught me more than any course had.

That is how I learn now. I build something, break it, and write up what happened, including the parts that were embarrassing, because a write-up where everything worked first time is not telling anyone very much.

My plan is deliberate. I want to start in a SOC and get properly good at detection, triage and incident response, because that is where you see what attacks look like at volume rather than one at a time. After that I want to move into offensive security. I think the best red teamers understand defence from the inside.

---

## 🚀 Featured Projects

| Project | What it does | Tools |
|---|---|---|
| **[Wazuh SIEM Detection Lab](https://github.com/0720hr/hr_range/tree/main/01-wazuh-siem-lab)** | Detects a full SSH attack chain, from password guessing through to an attacker becoming root. Each stage is mapped to MITRE ATT&CK, and the attacker is blocked automatically by a firewall rule that expires after 180 seconds. | Wazuh, Docker, iptables, MITRE ATT&CK |
| **[SOC Automation](https://github.com/0720hr/hr_range/tree/main/02-soc-automation)** | Picks up serious alerts without a human, enriches the attacker's address against threat intelligence, emails an analyst either way, and contains confirmed account takeovers through the Wazuh API. | Shuffle, VirusTotal API, Wazuh API, SMTP |

Every detection was triggered by a real attack inside the lab and verified afterwards in the alert data. None of it was tested only in a rule simulator and left there.

---

## 🛡️ Skills

- Writing and tuning custom detection rules, and diagnosing why one is not firing
- Mapping detections to MITRE ATT&CK techniques
- Deploying and operating a SIEM across manager, indexer and dashboard, and enrolling agents
- Building automation playbooks with conditional branching and API driven response
- Reconstructing an attack chain from raw logs and verifying that containment actually happened
- Simulating attacks to validate detections against live traffic rather than a simulator
- Credential rotation, secrets management, and keeping configuration out of version control

---

## 🧰 Tools

| Area | What I use |
|---|---|
| 🔍 **SIEM and detection** | Wazuh 4.14.5, Active Response, MITRE ATT&CK |
| ⚙️ **Automation and response** | Shuffle, webhooks, REST APIs, VirusTotal API, SMTP |
| 🐧 **Platforms** | Docker, Docker Compose, Linux, Ubuntu, WSL2, Bash |
| 🖥️ **Windows and infrastructure** | Windows Server 2022, Active Directory, DNS, DHCP, PowerShell, VMware |
| 🌐 **Networking and defence** | iptables, TCP/IP, SSH hardening |
| 📦 **Other** | Git, OpenSearch |

---

## 💼 Experience

**SecurityHQ**, a managed security services provider that runs security monitoring on behalf of other companies. I was selected as one of two candidates from over 200 applicants through their Diversity of Thought programme. I rotated across the business, and the SOC is where it clicked: real tickets, live log analysis, and clients being walked through what went wrong and how to fix it. Seeing alerts arrive at volume rather than one at a time is what pointed me towards detection engineering.

**University of East London**, Junior IT Technician. Three months standing up Windows Server 2022 with Active Directory, DNS and DHCP, and running Windows and Ubuntu machines in VMware. Knowing how infrastructure is actually put together is what lets me reason about what an attacker is doing to it, because half of detection is knowing what normal looks like.

---

## 📚 Hands-On Training

| | |
|---|---|
| 🎯 **Platform** | [TryHackMe](https://tryhackme.com/p/EHR) |
| 🏆 **Global rank** | Top 2% |
| 🚪 **Rooms completed** | 180 |
| 🎖️ **Badges** | 35 |
| 📈 **Level** | 60 |
| 🧭 **Current path** | SOC Level 1 |
