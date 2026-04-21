# Hi, I'm Aseel 👋

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=500&lines=Cybersecurity+Student+%40+Gannon+University;Penetration+Testing+Enthusiast;AI+Security+Automation+Builder;GRC+%26+Compliance+Explorer;Graduating+May+2026)](https://git.io/typing-svg)

</div>

<p align="center">
  <a href="mailto:Alqoud001@gannon.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/aseel-yg"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/hpppm"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://revclear.tech"><img src="https://img.shields.io/badge/Project-revclear.tech-2E9EF7?style=for-the-badge&logo=firefox-browser&logoColor=white" /></a>
</p>

-----

## 🎓 About Me

I'm a cybersecurity student at **Gannon University** (graduating May 2026), passionate about breaking things to understand how to protect them better. My interests lie at the intersection of **penetration testing**, **governance, risk, and compliance (GRC)**, and **AI-powered security automation**.

When I'm not in class, you'll find me:

- 🔍 Testing web apps for vulnerabilities and doing bug bounty hunting
- 🤖 Building AI agents to automate security tasks
- ☁️ Exploring cloud security in Azure and AWS environments
- 🐧 Running Kali Linux for CTFs and hands-on pentesting practice
- 📚 Learning about compliance frameworks and risk management

-----

## 🔨 What I'm Currently Building

> *Active projects as of early 2026*

| Project | Status | Stack |
|---------|--------|-------|
| 🏥 [RevClear — AI Medical Billing System](https://revclear.tech) | 🟡 Active Development | Next.js, TypeScript, Express, PostgreSQL, Docker, AWS, Railway |
| 🤖 [AI Agent Skills Design Lab](https://github.com/hpppm/lab-agent-skills-design) | 🟢 Active | Python, Claude API |
| 🖥️ Self-Hosted AI Stack | 🟢 Active | Ollama, Open WebUI, DigitalOcean, Telegram |
| ☁️ [Azure Network Security Lab](https://github.com/hpppm/lab-azure-network-security) | ✅ Completed | Azure |

-----

## 🚀 Projects

### 🏥 [RevClear — AI Medical Billing System](https://revclear.tech) *(Senior Capstone)*

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![HIPAA](https://img.shields.io/badge/HIPAA-Compliant-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)

My senior capstone project at Gannon University — a **HIPAA-compliant AI-powered medical transcription and billing automation system**. Combines healthcare compliance, intelligent data processing, and workflow automation. I serve as **team lead**, responsible for infrastructure, AWS integration, and security architecture.

**Key Features:**

- ⚛️ **Next.js 16 + TypeScript** frontend for the medical billing interface
- 🔌 **Express.js API** (TypeScript) handling core application logic and routing
- 🗄️ **PostgreSQL** (AWS RDS, encrypted, deletion protection enabled) as the primary database
- 🎙️ **Whisper AI** transcription microservice (Python, faster-whisper, deployed as separate Railway service)
- 🔍 **Pinecone** vector search for intelligent CPT/ICD medical code matching
- 🔐 **AWS Cognito** authentication with TOTP MFA, token rotation on refresh, 1-hour access token expiry
- 🏥 EDI claims formatting and billing workflow automation
- 🔒 HIPAA compliance: audit logging, httpOnly cookies, security error handling, OWASP + Semgrep static analysis
- 🧪 Playwright E2E test suite + Jest backend security tests
- 🐳 **Dockerized** services, deployed across 3 Railway services (frontend, backend, Whisper)

**AWS Production Controls (verified):**

- 🔑 KMS customer-managed key with annual auto-rotation (`mrk-8c57ed...`)
- 🪣 S3: public access blocked, versioning enabled, KMS-only upload policy, access logging active
- 🛤️ CloudTrail multi-region trail (`RevClearTrail`) with KMS encryption + log file validation
- 📊 CloudWatch: 7-year log retention (2557 days)
- 🌐 VPC flow logs active
- 🗄️ RDS: encrypted at rest, deletion protection enabled

> *Repository is private. Live project: [revclear.tech](https://revclear.tech)*

-----

### 🤖 [AI Agent Skills Design Lab](https://github.com/hpppm/lab-agent-skills-design)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic-Claude%20API-4B275F?style=flat-square&logo=anthropic&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

A modular **Claude AI agent** built with a skills architecture, persistent memory, and security-first principles. Demonstrates production-grade AI patterns: progressive context loading, structured prompts, PowerShell skill integration, and audit logging.

**Key Features:**

- 🧩 Modular skills system (self-contained Python modules)
- 🧠 Short-term memory with automatic pruning
- 🔒 Security-first design: input validation, least privilege, no sensitive data logging
- ⚡ PowerShell skill with command allowlist and output sanitization

-----

### 🖥️ Self-Hosted AI Stack

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

A personal self-hosted AI infrastructure stack for running and routing LLM models with zero recurring cost.

**What I Built:**

- 🦙 Ollama on local Windows PC (RTX 3050) for on-device model inference
- 🌐 Open WebUI hosted on a DigitalOcean droplet as the primary interface
- ☁️ On-demand AWS EC2 GPU instances for heavier workloads
- 🤖 Telegram bot interface via OpenClaw for remote model access from anywhere
- 💸 Free cloud-routed models as fallback to minimize compute costs

-----

### ☁️ [Azure Network Security Lab](https://github.com/hpppm/lab-azure-network-security)

![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

Hands-on Azure security lab implementing enterprise-grade network controls from scratch.

**What I Built:**

- 🏗️ Virtual networks and subnet segmentation
- 🔥 Azure Firewall with custom policy rules
- 🛣️ User-defined routes (UDR) for traffic control
- ✅ Verified allowed/blocked outbound traffic behavior
- 📊 RBAC vs. ABAC comparison using Azure Key Vault (from CYSEC_308 Cloud Security coursework)
- 📄 Full documentation with screenshots and evidence

-----

## 🏆 Certifications

<div align="center">

### ✅ Earned

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)
![eJPT](https://img.shields.io/badge/INE-eJPT-4B275F?style=for-the-badge&logo=hackaday&logoColor=white)

### 🎯 In Progress

![AWS](https://img.shields.io/badge/AWS-AI%20Solution%20Architect-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

-----

## 🛠️ Skills & Technologies

<details open>
<summary><b>🔐 Security & Pentesting</b></summary>
<br>

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burp-suite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0078D4?style=flat-square&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

- Web application penetration testing (SQL injection, XSS, CSRF, auth bypass)
- Bug bounty hunting and vulnerability research
- Static analysis with Semgrep and CodeQL (CI/CD integrated)
- Google dorking and OSINT reconnaissance techniques
- Network enumeration and vulnerability assessment
- Traffic analysis and packet inspection
- Exploit development fundamentals
- Pentesting lab environments: Docker-based Kali, WSL2, VirtualBox VMs

</details>

<details open>
<summary><b>☁️ Cloud & Infrastructure</b></summary>
<br>

![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)

- AWS KMS key management with auto-rotation policies
- CloudTrail multi-region audit logging and log file validation
- RDS encryption, deletion protection, and secure configuration
- Cognito MFA configuration (TOTP) with token rotation on refresh
- S3 security hardening (public access policies, KMS upload enforcement, access logging)
- Multi-service Railway deployments (frontend, backend, AI microservices)
- Cloudflare Tunnel configuration and domain routing
- Azure & AWS security services and cloud infrastructure
- Docker container management and WSL2 environments
- Linux/Windows system administration and hardening
- Network security architecture and segmentation
- RBAC vs. ABAC identity and access management
- Self-hosted AI infrastructure (Ollama, Open WebUI, EC2 GPU instances)

</details>

<details open>
<summary><b>💻 Programming & Automation</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

- Security automation and scripting
- REST API development (Express/TypeScript, Flask)
- Frontend development with Next.js + TypeScript
- AI agent design and workflow engineering
- Git workflow management, branching strategies, and PR review
- GitHub Actions CI/CD (secret scanning, dependency auditing, Semgrep SAST)
- E2E testing with Playwright, backend security testing with Jest

</details>

<details open>
<summary><b>📋 GRC & Compliance</b></summary>
<br>

- HIPAA Security Rule implementation with AWS evidence (CloudTrail, KMS rotation, RDS encryption, Cognito MFA)
- Compliance frameworks: NIST, ISO 27001, HIPAA
- Risk assessment and security policy fundamentals
- Security monitoring and incident response basics
- Cloud compliance and identity governance

</details>

-----

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hpppm&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cache_seconds=86400" alt="GitHub Stats" width="495">
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=hpppm&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="495">
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hpppm&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph" width="800">
</div>

<p align="center"><i>📝 Note: Much of my work is in private repositories (including RevClear senior design), so stats don't reflect full activity.</i></p>

-----

## 🎯 What I'm Currently Learning

```python
current_focus = {
    "penetration_testing": ["Web app security", "CTF challenges", "OWASP Top 10", "Bug bounty hunting"],
    "grc": ["Risk assessment", "Compliance frameworks", "HIPAA Security Rule / AWS evidence collection"],
    "automation": ["AI agent workflows", "Security orchestration", "Python scripting"],
    "cloud_security": ["AWS KMS & CloudTrail", "Cognito MFA", "RDS encryption", "Railway deployments"],
}
```

-----

## 📫 Let's Connect!

I'm always open to connecting with fellow security enthusiasts, discussing projects, or just chatting about cybersecurity!

<p align="center">
  <a href="mailto:Alqoud001@gannon.edu">📧 Email Me</a> •
  <a href="https://www.linkedin.com/in/aseel-yg">💼 LinkedIn</a> •
  <a href="https://github.com/hpppm">🐙 GitHub</a> •
  <a href="https://revclear.tech">🏥 RevClear Project</a>
</p>

-----

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=hpppm&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views" />
</div>

<div align="center">
  <i>"Security is not a product, but a process." — Bruce Schneier</i>
</div>
