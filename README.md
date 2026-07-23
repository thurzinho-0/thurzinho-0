# Hi, I'm Arthur Marques 👋 🛡️

<div align="center">
  <img height="300" src="https://github.com/thurzinho-0/thurzinho-0/blob/main/imagem_2025-11-15_152703901-removebg-preview.png?raw=true" alt="Banner"/>
</div>

<p align="center">
  <b>ITOps Intern @ 180 Seguros | Cybersecurity Analyst | AppSec | Full-Stack Developer</b>
  <br/>
  🇧🇷 São Paulo, Brazil — Open to relocation & remote opportunities
</p>

<p align="center">
  <a href="mailto:arthurdearaujomarques@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/arthur-marques-2bb47322a/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://instagram.com/arthurm_1">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>
  <a href="https://discord.gg/8kc8HqXVw2">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
  </a>
  <a href="https://portfolio-arthur-marques.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white"/>
  </a>
</p>

---

## 🎯 About Me

```typescript
const arthur = {
  location: "São Paulo, Brazil",
  currentRole: "ITOps Intern @ 180 Seguros",
  background: "Self-taught professional focused on practical experience & certifications",
  focus: ["Cybersecurity", "Blue Team", "AppSec", "IT Infrastructure", "IAM"],
  
  highlight: "Built a sub-500ms AI translation app & disclosed a CVSS 9.3 vulnerability in production",
  
  frameworks: ["OWASP Top 10", "MITRE ATT&CK", "ISO/IEC 27001:2022", "LGPD"],
  
  devStack: ["TypeScript", "Python/FastAPI", "React", "Electron", "Go", "PHP"],
  infraStack: ["Okta", "Mosyle MDM", "Snipe-IT", "Linux/macOS", "Cisco Packet Tracer"],
  
  languages: {
    portuguese: "Native",
    english: "Intermediate (B1/B2)",
    spanish: "Intermediate (B1)"
  },
  
  openTo: ["ITOps", "Cybersecurity Analyst", "SOC Analyst", "AppSec", "GRC"]
};
```

---

## Professional Experience
🛡️ ITOps Intern — 180 Seguros (Jul 2026 – Present)
Managing corporate IT infrastructure, identity lifecycles, and asset ecosystems in a fast-paced environment.

Identity & Access Management (IAM): Managing user lifecycles and secure authentication via Okta.

Device Management (MDM): Administering macOS fleets via Mosyle and maintaining hardware tracking via Snipe-IT.

Tech Support: Delivering N1/N2 technical support and executing secure onboarding/offboarding workflows.

## 🔐 Security Research

### 🔴 Critical — .git Directory Exposure (CVSS 9.3)
> Identified and disclosed a publicly accessible `.git` repository on a live e-commerce platform in production.
- **Impact:** Full source code reconstruction possible, including payment integrations (PagSeguro / MercadoPago)
- **Tool:** GitDumper — responsible disclosure process followed
- **Remediation:** Nginx/Apache block rules, secure CI/CD pipeline, commit history audit
- **ISO 27001 Mapping:** A.8.9 Configuration Management, A.8.25 Secure Development

### 🟠 High — Outdated Nginx Server (CVSS 7.5)
> Identified nginx/1.19.6 (Dec 2020) via HTTP header fingerprinting — publicly known CVEs applicable.
- **CVEs:** CVE-2021-23017 (CVSS 9.4), CVE-2020-29363
- **Impact:** RCE, DoS, information disclosure via server banner
- **Remediation:** Upgrade to nginx 1.26+, disable server_tokens, patch management policy

### 📋 ISMS Portfolio — ISO/IEC 27001:2022
> Formal ISMS implementation based on real vulnerability disclosure case.
- Risk Assessment, Risk Treatment Plan, Statement of Applicability (SoA)
- Legal Requirements mapping: LGPD, PCI-DSS, Marco Civil da Internet
- Available in [`isms-portfolio`](https://github.com/thurzinho-0/isms-portfolio) repository

---

## 💼 Development Projects

## 🛡️ AI SOC Copilot — Threat Detection & Correlation
A simulated Security Operations Center environment combining detection heuristics and AI to filter noise from real threats.

Stack: Python, FastAPI, Flask, OpenAI API.

Features: Detects real attacks (Brute Force T1110, SQLi T1190, Malicious PowerShell), correlates events, auto-classifies risks, and generates AI-assisted incident response playbooks.

## 🦠 AI Malware Triage Assistant
Automated initial malware triage tool designed to replace the first 30 minutes of manual SOC investigation.

Stack: Python, Flask, VirusTotal API, OpenAI API.

Features: Fetches SHA256 data across 75+ engines and uses strict prompt engineering (low temperature) to prevent LLM hallucinations, generating structured SOC reports with IoCs and MITRE mapping.

## 🎫 HelpDesk AI Triage — IT Ops Automation
High-volume ticket triage system built to automate support classification, reducing N1 classification time from 5 minutes to under 3 seconds per ticket.

Stack: Laravel 11, SQLite, Vanilla JS, OpenAI API.

Features: Enforces strict JSON structured outputs from LLMs to categorize issues, define SLAs, impact, and generate N1 action plans without human intervention.

## 🎙️ MasterVoice BR — Real-Time AI Communication HUD
Always-on-top desktop solution designed to eliminate communication delays for global tech professionals.

Stack: TypeScript, React, Electron, Python, FastAPI, Supabase

Features: Sub-500ms low-latency WebSockets, GPT-4o-mini dynamic contextual AI coaching, and smart NLP data filtering.

### 📋 [Mini Kanban — Veritas](https://github.com/thurzinho-0)
> Full-stack Kanban task management system — technical challenge
- **Stack:** Go (Gin Framework), React 18, Axios, CSS3
- **Features:** Full CRUD, REST API, column drag-and-drop, Neobrutalism UI
- **AppSec relevance:** REST API architecture enables identification of auth flaws and IDOR

### 🛒 [CxStore — FATEC E-commerce](https://github.com/thurzinho-0)
> Full-stack e-commerce for a real client — FATEC Integrator Project (Jun 2025)
- **Stack:** PHP, MySQL/MariaDB, JavaScript (AJAX), HTML5/CSS3
- **Features:** Product catalog, cart, order management, admin panel, WhatsApp checkout
- **AppSec relevance:** Hands-on SQL + AJAX = deep insight into SQLi, XSS, CSRF

### 🐰 [Little Bunny's E-commerce](https://github.com/thurzinho-0/little-bunnys)
> Responsive frontend for a fictional e-commerce
- **Stack:** HTML5, CSS3, JavaScript, Swiper.js
- **Features:** Interactive cart, banner carousel, responsive design

### 👕 Streetwear E-commerce
> Full-stack inventory management system for on-demand streetwear
- **Stack:** PHP, MySQL, JavaScript, CSS3
- **Features:** Real-time inventory, admin panel, role-based access control

---

## 🛠️ Tech Stack

### Security & Infrastructure
<div align="center">
  <img src="https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white" />
  <img src="https://img.shields.io/badge/Mosyle-000000?style=for-the-badge&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Snipe--IT-2196F3?style=for-the-badge&logo=codeigniter&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white" />
  <img src="https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white" />
</div>

### Languages & Frameworks
<div align="center">

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

</div>

### Frontend & Database
<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

</div>

### Tools
<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=thurzinho-0&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&cache_seconds=1784798470"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thurzinho-0&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&cache_seconds=1784798470"/>
</div>

<div align="center">
  <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=thurzinho-0&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=thurzinho-0&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D"/>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=thurzinho-0&style=flat-square&color=0e75b6&label=Profile+Views"/>
</div>

---

## 🎓 Certifications & Professional Achievements

| | |
|--|--|
| 🛡️ | **ISO/IEC 27001:2022 Lead Implementer** — Udemy |
| 🌐 | **Computer Networks & Infrastructure Security** — Udemy |
| 📜 | **Google Cybersecurity Certificate** — Coursera |
| ⚖️ | **LGPD & IT Security Fundamentals** — Fundação Bradesco |
| 📈 | **Six Sigma White Belt** — RL&Associados |
| 🎯 | **CompTIA Security+** — Studying |
| 🏹 | **TryHackMe / HackTheBox** — Active platform labs |

---

## 📚 Currently Learning

- ☁️ **Cloud Identity & Infrastructure:** Automation with Okta & MDM strategies.
- 🤖 **AI for Blue Team:** Applied LLMs for automated triage and SOC operations.
- 🔴 **Offensive Security:** Advanced Penetration Testing & Ethical Hacking (TCM Security).
- 🔵 **SIEM Operations:** Correlation and detection engineering.
- 🟣 **Digital Forensics:** Investigations with CyberDefenders.
- 🌍 **English:** Professional fluency focus (B1 → B2).

---
---

> *"Security is not a product, but a process."* — Bruce Schneier
