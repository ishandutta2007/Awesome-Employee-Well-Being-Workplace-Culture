# Awesome-Employee-Well-Being-Workplace-Culture

## Top Employee Well-being & Workplace Culture Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Burnout Detection, Wellbeing Check-ins & Culture Analytics*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Well-being & Workplace Culture**. These tools help organizations measure and improve how people feel at work—covering everything from anonymized weekly check-ins and burnout risk scoring to culture surveys and mental health support platforms.

**Examples** include Culture Amp, Virgin Pulse, Modern Health, Lyra Health, Spring Health, Limeade, Wellable, Workhuman, Zoho People, and open-source alternatives like WorkMate and Farik (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted wellbeing platforms, open-source culture analytics, and community-driven employee support—ideal for organizations seeking data sovereignty and avoiding per-employee pricing that compounds across headcount. The open-source landscape is genuinely emerging: **WorkMate** provides a complete wellbeing platform with burnout webhooks , **Farik** bundles mood pulse and culture scoring into an HRMS , and **LimeSurvey** offers a mature survey engine with 19+ pre-built employee questionnaire templates .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Culture Amp](https://www.cultureamp.com/)** | Engagement and performance platform with validated survey instruments and benchmarks from thousands of companies. Driver analysis tells you which factors actually move engagement in your data. Positioned for companies of 200+ wanting rigorous measurement . | Quote-only | No free tier; demo via sales |
| **[Virgin Pulse](https://www.virginpulse.com/)** | Employee wellbeing and engagement platform combining health tracking, rewards, and challenges. Positioned for large employers wanting a consumer-style wellbeing experience. | Quote-only | No free tier; demo via sales |
| **[Modern Health](https://www.modernhealth.com/)** | Global mental health benefits platform connecting employees to coaching, therapy, and self-guided resources. Claims 100+ countries, 60+ languages, and 130+ cultures served . | Quote-only | No free tier; demo via sales |
| **[Lyra Health](https://www.lyrahealth.com/)** | Workforce mental health platform with therapy, coaching, and medication management. Positioned for employers wanting clinical-grade support . | Quote-only | No free tier; demo via sales |
| **[Spring Health](https://www.springhealth.com/)** | Precision mental healthcare platform for employers. Uses clinical data to match employees to the right care. | Quote-only | No free tier; demo via sales |
| **[Limeade](https://www.limeade.com/)** | Employee wellbeing and engagement platform. Combines wellbeing programs, surveys, and culture analytics. | Quote-only | No free tier; demo via sales |
| **[Wellable](https://www.wellable.co/)** | Wellness platform with challenges, rewards, and tracking. Positioned for SMBs and mid-market employers. | Quote-only | No free tier; demo via sales |
| **[Workhuman](https://www.workhuman.com/)** | Recognition and human workplace platform. Combines peer recognition with culture analytics and wellbeing insights. | Quote-only | No free tier; demo via sales |
| **[Zoho People](https://www.zoho.com/people/)** | HRIS with wellness features including time-off tracking and employee engagement. Positioned for SMBs already in the Zoho ecosystem. | Basic: **¥105/employee/year** | **Free**: up to 5 employees; **30-day trial** |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[WorkMate](https://github.com/karlis0099/WorkMate)** | [![Stars](https://img.shields.io/github/stars/karlis0099/WorkMate?style=social&color=white)](https://github.com/karlis0099/WorkMate/stargazers) | **The most complete open-source employee wellbeing platform.** Java desktop app serving a web UI on the local network. **Employee portal**: weekly check-in with **7 psychological wellbeing sliders** (mood, energy, motivation, stress inverted, work-life balance, team connection, accomplishment) plus open-text reflection. **Real-time composite wellbeing score** updates live as sliders move. **Manager portal**: dashboard with 4 key metrics, 5-dimension weekly bar chart, and **burnout risk alerts**. **Burnout webhook** posts to Slack/Teams on HIGH-risk submission. SQLite persistence, SHA-256+salt PIN authentication, configurable check-in window and webhook URL . **Best for teams wanting a self-hosted, privacy-respecting wellbeing check-in system with automated burnout alerts.** |
| **[Farik](https://github.com/SamoTech/Farik)** | [![Stars](https://img.shields.io/github/stars/SamoTech/Farik?style=social&color=white)](https://github.com/SamoTech/Farik/stargazers) | **Open-source HR platform with wellbeing analytics built in.** MIT licensed, self-hostable. **Free tier includes People Directory, Recruitment Pipeline, Employee Helpdesk, Attendance & Leave, and Dashboard Analytics**. **Pro tier ($29/month)** adds **Mood Pulse** (AI-inferred team sentiment), **burnout heatmaps**, **culture scoring**, and **90-day attrition forecasting**. Deploys in 5 minutes on Vercel; local npm setup available . **Best for growing teams wanting an integrated HRIS with wellbeing analytics as they scale.** |
| **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)** | [![Stars](https://img.shields.io/github/stars/LimeSurvey/LimeSurvey?style=social&color=white)](https://github.com/LimeSurvey/LimeSurvey/stargazers) | **Mature open-source survey engine with 19+ employee wellbeing questionnaire templates.** GPL-licensed, self-hosted. Includes **Work-Life Balance**, **Workplace Stress**, **Employee Engagement**, **eNPS**, and **Health & Safety** questionnaires out of the box. Supports 80+ languages and 28+ question types. Data analysis tools for identifying trends. **Best for organizations wanting a proven survey platform to run their own culture and wellbeing assessments** without per-response fees . |
| **[MindBridge](https://github.com/guopanqi/mindbridge)** | [![Stars](https://img.shields.io/github/stars/guopanqi/mindbridge?style=social&color=white)](https://github.com/guopanqi/mindbridge/stargazers) | **Anonymous employee psychological support system for DingTalk organizations.** Core constraint: **people needing protection stay anonymous; responsible parties are identified**. Three physically separated D1 databases (Identity Relay, Care Domain, Staff). **AES-GCM encryption** for employee confessions; **deterministic rule engine** for crisis triage (models can reword but not override risk level). **HR sees only aggregates with sample size <10 suppressed (hardcoded, not configurable)**. Employee side never sees which rule was hit. Cloudflare Pages deployment . **Best for organizations in the DingTalk ecosystem wanting privacy-preserving mental health support.** |
| **[WorkWell AI](https://github.com/topics/employee-wellbeing)** | — | **AI/ML system predicting employee burnout and productivity risk** from workload and behavioral data. Provides decision-support insights through a REST API and interactive dashboard. Listed on GitHub's employee-wellbeing topic (updated January 2026) . **Best for teams wanting a predictive burnout model** they can integrate into existing HR systems. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[regulatory-first/health-frontend](https://github.com/sumanjangili/regulatory-first)** | — | **Regulatory-first daily wellness check-in app for remote workers.** React/Material-UI frontend with questionnaire, manager dashboard (aggregated responses), and policy viewer. Designed **HIPAA-compatible while respecting GDPR/CCPA/DPDPA** from day one. Docker deployment. **Best for regulated industries needing a compliance-first wellbeing check-in** . |
| **[employee-pulse-survey-enps-engine](https://github.com/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63)** | — | **Automated pulse surveying platform calculating eNPS and identifying burnout trends.** MIT licensed, Python/FastAPI/LangChain. Docker included. **Best for teams wanting a focused eNPS and burnout-tracking backend** with modern Python stack . |

**Frameworks for building custom systems**: Choose **WorkMate** for a complete self-hosted wellbeing platform with burnout webhooks , **Farik** for an HRIS with mood pulse and culture scoring , **LimeSurvey** for proven culture surveys with pre-built wellbeing templates , and **MindBridge** for privacy-preserving anonymous support —all without per-employee pricing that scales with headcount.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Employee wellbeing platforms handle sensitive mental health and sentiment data; enforce strict anonymity guarantees, encryption, and compliance with applicable health data regulations (HIPAA where relevant, GDPR/CCPA). **A breach of wellbeing data destroys trust permanently.**
- **Open-source wellbeing tooling is early-stage but genuinely functional.** **WorkMate** provides a complete check-in system with real-time scoring and burnout webhooks, but is a desktop app serving a local network rather than a hardened enterprise platform . **Farik** bundles wellbeing analytics into an HRMS but its Pro features (Mood Pulse, heatmaps) are **paid tiers** despite the MIT license on the core . **MindBridge** has the strongest privacy architecture with physically separated databases and hardcoded suppression thresholds, but is specific to the DingTalk ecosystem . **LimeSurvey** is the most mature option for pure survey-based measurement, with 19+ wellbeing questionnaire templates ready to deploy . **Commercial mental health platforms (Lyra, Spring Health, Modern Health) are universally quote-only** and provide clinical services that open-source tools cannot replicate. **Choose based on whether you need clinical support (commercial), survey-based measurement (LimeSurvey), or self-hosted check-ins (WorkMate, Farik).**

---

**Made for HR leaders, people operations teams, and managers building healthier workplaces.**  
Let's make employee wellbeing and workplace culture more open, anonymous, and action-oriented.
