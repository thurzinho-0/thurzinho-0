# Hi, I'm Arthur Marques 👋 🛡️

<div align="center">
  <img height="300" src="https://github.com/thurzinho-0/thurzinho-0/blob/main/imagem_2025-11-15_152703901-removebg-preview.png?raw=true" alt="Banner"/>
</div>

<p align="center">
  <b>Cybersecurity Analyst | Blue Team | AppSec | Full-Stack Developer</b>
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
  education: "B.Tech Software Development @ FATEC São Paulo (2024–2027)",
  focus: ["Cybersecurity", "Blue Team", "AppSec", "Vulnerability Research"],
  
  highlight: "Disclosed a CVSS 9.3 critical vulnerability in a live production e-commerce",
  
  frameworks: ["OWASP Top 10", "MITRE ATT&CK", "ISO/IEC 27001:2022"],
  certifications: ["Google Cybersecurity Certificate (in progress)", "ISO 27001 Lead Implementer (in progress)"],
  
  devStack: ["PHP", "JavaScript", "Go", "React", "MySQL", "HTML5/CSS3"],
  
  languages: {
    portuguese: "Native",
    english: "Intermediate (B1/B2)",
    spanish: "Intermediate (B1)"
  },
  
  openTo: ["Cybersecurity Analyst", "SOC Analyst", "AppSec", "Blue Team", "GRC"]
};
```

---

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

### Security
<div align="center">

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

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
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=thurzinho-0&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&cache_seconds=1775141446"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thurzinho-0&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&cache_seconds=1775141446"/>
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

## 🎓 Education & Certifications

| | |
|--|--|
| 🎓 | **B.Tech Software Development** — FATEC São Paulo (2024–2027) |
| 📜 | **Google Cybersecurity Certificate** — Coursera (in progress) |
| 📜 | **ISO/IEC 27001:2022 Lead Implementer** — GRC Lab / Udemy (in progress) |
| 🎯 | **CompTIA Security+** — Studying |
| 🏹 | **TryHackMe / HackTheBox** — In progress |

---

## 📚 Currently Learning

- 🔴 Penetration Testing & Ethical Hacking (Udemy — TCM Security)
- 🔵 SOC Analyst operations & SIEM
- 🟣 Digital Forensics (CyberDefenders)
- ☁️ Cloud Security (AWS / Azure)
- 🌍 English fluency (B1 → B2)

---

> *"Security is not a product, but a process."* — Bruce Schneier
