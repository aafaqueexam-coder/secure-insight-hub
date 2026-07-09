# 🛡️ Secure Insight Hub

> **AI-Powered Security Operations Platform**

Secure Insight Hub is a free and open-source AI-powered Security Operations Platform that helps SOC analysts investigate alerts faster using explainable AI, MITRE ATT&CK mapping, human-in-the-loop approval, incident management, and audit-ready workflows. Built with security, transparency, and community collaboration at its core.

---

## 🎯 Mission

Secure Insight Hub aims to make modern Security Operations accessible to everyone.

Instead of replacing security analysts, the platform empowers them with explainable AI that assists in investigations while ensuring every critical decision remains under human control.

---

# ✨ Features

## 🚨 Alert Management
- Alert dashboard
- Alert filtering & search
- Alert investigation
- Related alerts
- Evidence viewer
- IOC extraction

## 🤖 AI-Powered Investigation
- Explainable AI analysis
- Root cause analysis
- AI reasoning
- MITRE ATT&CK mapping
- Investigation checklist
- False positive prediction
- AI confidence score
- Containment recommendations

## 👨‍💻 Human-in-the-Loop
- Approve AI recommendations
- Reject recommendations
- Modify recommendations
- Review comments
- Review history
- Complete audit trail

## 📂 Incident Management
- Convert alerts into incidents
- Incident timeline
- Investigation notes
- Status tracking
- Resolution workflow

## 📊 Dashboard
- Alert statistics
- Critical alerts
- Open incidents
- AI review metrics
- MTTR
- MITRE statistics

## 📋 Reports
- Executive reports
- Daily reports
- Weekly reports
- Compliance reports

## 🛡 Security First
- Least privilege architecture
- Sensitive data redaction
- Audit logging
- Human approval required
- Explainable AI
- Modular design

---

# 🏗 Platform Workflow

```text
Security Alert
      │
      ▼
Context Builder
      │
      ▼
Sensitive Data Redaction
      │
      ▼
AI Investigation
      │
      ▼
Human Review
      │
      ▼
Approve / Modify / Reject
      │
      ▼
Incident Creation
      │
      ▼
Audit Trail
```

---

# 📁 Project Structure

```
secure-insight-hub/

├── artifacts/
│
├── api-server/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   ├── ai/
│   └── database/
│
├── soc-platform/
│   ├── components/
│   ├── pages/
│   ├── layouts/
│   ├── hooks/
│   └── assets/
│
├── lib/
│   ├── db/
│   ├── api-client/
│   ├── api-spec/
│   └── api-zod/
│
├── docs/
│
└── README.md
```

---

# 📂 Folder Overview

### `api-server`
Backend API responsible for:
- AI analysis
- Alert processing
- Incident management
- Authentication
- Audit logging
- Database communication

### `soc-platform`
Frontend application that contains:
- Dashboard
- Alerts
- Incidents
- MITRE ATT&CK
- Reports
- Rule Tuning
- Compliance
- Settings

### `lib`
Shared modules:
- Database models
- API client
- Shared schemas
- Validation

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/<YOUR_USERNAME>/secure-insight-hub.git

cd secure-insight-hub
```

## Install Dependencies

```bash
npm install
```

## Configure Environment

Create a `.env` file.

Example:

```env
DATABASE_URL=

OPENAI_API_KEY=

JWT_SECRET=

PORT=3000

WAZUH_URL=

WAZUH_USERNAME=

WAZUH_PASSWORD=
```

## Run Development Server

```bash
npm run dev
```

---

# 🎯 Use Cases

### SOC Analyst
- Investigate alerts
- Review AI analysis
- Create incidents
- Document investigations

### SOC Manager
- Track SOC performance
- Review incidents
- Generate reports

### Security Engineer
- Improve detection rules
- Review AI accuracy
- Tune detection logic

### Students
- Learn SOC workflows
- Study MITRE ATT&CK
- Practice alert investigations

---

# 🔒 Security Principles

Secure Insight Hub follows security-by-design principles.

- Human approval before action
- Explainable AI
- AI receives only sanitized context
- Least privilege architecture
- Audit logging
- No autonomous AI actions

---

# 🛣 Roadmap

## Current

- ✅ Dashboard
- ✅ Alert Management
- ✅ AI Investigation
- ✅ Explainable AI
- ✅ Human Approval
- ✅ Incident Management
- ✅ Audit Trail
- ✅ MITRE ATT&CK

## Planned

- Live Wazuh Integration
- Threat Intelligence
- VirusTotal Integration
- AbuseIPDB Integration
- Local LLM Support
- Slack Notifications
- Microsoft Teams Integration
- Email Alerts
- Role-Based Access Control (RBAC)
- Multi-tenancy

---

# 🤝 Contributing

Contributions are welcome!

You can help by:

- Reporting bugs
- Suggesting features
- Improving documentation
- Improving AI prompts
- Creating pull requests

Please open an issue before working on major changes.

---

# ⭐ Support the Project

If you find Secure Insight Hub useful:

⭐ Star this repository

🍴 Fork the project

🐛 Report bugs

💡 Suggest new features

🤝 Contribute to development

---

# 📜 License

Licensed under the **Apache License 2.0**.

---

# ❤️ Built for the Cybersecurity Community

Secure Insight Hub is an open-source initiative dedicated to making AI-assisted Security Operations transparent, explainable, and accessible to everyone.

**Empowering Security Analysts with AI — Never Replacing Them.**
