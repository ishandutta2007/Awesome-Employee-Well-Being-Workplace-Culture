# Awesome Employee Well-being & Workplace Culture [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of leading SaaS platforms, open-source software, developer tools, and frameworks for employee well-being, burnout detection, workplace mental health, mood tracking, and organizational culture analytics.

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Employee-Well-Being-Workplace-Culture?style=flat-square)](https://github.com/ishandutta2007/Awesome-Employee-Well-Being-Workplace-Culture/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ishandutta2007/Awesome-Employee-Well-Being-Workplace-Culture?style=flat-square)](https://github.com/ishandutta2007/Awesome-Employee-Well-Being-Workplace-Culture/network/members)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)](https://github.com/ishandutta2007/Awesome-Employee-Well-Being-Workplace-Culture/pulls)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)

---

## Overview

Modern organizations and distributed remote teams require scalable, privacy-first tooling to monitor employee sentiment, avoid burnout, support psychological safety, and foster high-trust work cultures.

This repository catalogs **top SaaS platforms** and **active open-source GitHub projects** powering the employee well-being ecosystem. Whether you are an HR leader evaluating enterprise platforms, an engineering manager implementing team mood check-ins, or an architect building self-hosted culture analytics systems to maintain data privacy compliance (HIPAA, GDPR, CCPA), this guide covers the landscape.

---

## Table of Contents

- [Key Focus Areas & Keywords](#key-focus-areas--keywords)
- [SaaS Platforms & Enterprise Solutions](#saas-platforms--enterprise-solutions)
- [Open-Source Projects & Self-Hosted Tools](#open-source-projects--self-hosted-tools)
- [Comparative Framework Guide](#comparative-framework-guide)
- [Privacy, Anonymity & Compliance Considerations](#privacy-anonymity--compliance-considerations)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Key Focus Areas & Keywords

- **Burnout Detection & Early Warning**: Automated pulse algorithms, workload telemetry, and webhook triggers alerting managers before turnover occurs.
- **Anonymous Pulse Surveys & eNPS**: Lightweight periodic check-ins tracking team sentiment and Employee Net Promoter Scores without de-anonymizing respondents.
- **Workplace Mental Health & EAP**: Therapy, coaching, and clinical assistance ecosystems (e.g., Lyra, Modern Health).
- **Culture & People Analytics**: Real-time engagement drivers, 360 feedback, recognition programs, and attrition forecasting.
- **Privacy-Preserving & Self-Hosted Stacks**: Solutions designed with hardcoded minimum cohort thresholds, cryptographic hashing, and local database hosting.

---

## SaaS Platforms & Enterprise Solutions

Commercial tools providing turn-key engagement, validated clinical mental health resources, and enterprise benchmarks:

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Culture Amp](https://www.cultureamp.com/)** | Enterprise engagement and performance platform with validated survey instruments, benchmarks across thousands of organizations, and driver analysis. Ideal for teams of 200+ needing statistical rigor. | Quote-only | No free tier; demo via sales |
| **[Virgin Pulse](https://www.virginpulse.com/)** | Comprehensive corporate health, well-being, and habit tracking platform with gamified challenges and rewards. | Quote-only | No free tier; demo via sales |
| **[Modern Health](https://www.modernhealth.com/)** | Global mental health benefits platform offering 1-on-1 coaching, therapy, and digital self-guided programs across 100+ countries and 60+ languages. | Quote-only | No free tier; demo via sales |
| **[Lyra Health](https://www.lyrahealth.com/)** | Clinical-grade workforce mental health platform providing fast access to therapy, coaching, and specialized medication management. | Quote-only | No free tier; demo via sales |
| **[Spring Health](https://www.springhealth.com/)** | Precision mental healthcare utilizing proprietary machine learning assessments to accurately match employees to optimal care plans. | Quote-only | No free tier; demo via sales |
| **[Limeade](https://www.limeade.com/)** | Employee experience and well-being software integrating employee listening, wellness challenges, and workplace culture analytics. | Quote-only | No free tier; demo via sales |
| **[Wellable](https://www.wellable.co/)** | Modular wellness platform offering wellness challenges, wearable device syncing, and health education targeted at SMBs and mid-market teams. | Quote-only | No free tier; demo via sales |
| **[Workhuman](https://www.workhuman.com/)** | Social recognition and human workplace platform utilizing peer-to-peer micro-bonuses to provide deep culture sentiment and attrition insights. | Quote-only | No free tier; demo via sales |
| **[Zoho People](https://www.zoho.com/people/)** | Cloud HRIS offering built-in pulse surveys, time-off management, and employee sentiment check-ins. Cost-effective for teams already in the Zoho suite. | Basic: **¥105/employee/year** | **Free**: up to 5 employees; **30-day trial** |

---

## Open-Source Projects & Self-Hosted Tools

Self-hosted and developer-friendly platforms for teams prioritizing complete data sovereignty, customized telemetry, and avoiding per-seat SaaS costs:

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[WorkMate](https://github.com/karlis0099/WorkMate)** | [![Stars](https://img.shields.io/github/stars/karlis0099/WorkMate?style=social&color=white)](https://github.com/karlis0099/WorkMate/stargazers) | **Comprehensive open-source employee well-being check-in system.** Features a lightweight local web UI, weekly check-in portal with **7 psychological wellbeing sliders** (mood, energy, motivation, stress, work-life balance, team connection, accomplishment), real-time composite score calculation, and **automated Slack/Teams burnout alert webhooks** on elevated risk levels. Built with SQLite persistence and SHA-256 PIN authentication. |
| **[Farik](https://github.com/SamoTech/Farik)** | [![Stars](https://img.shields.io/github/stars/SamoTech/Farik?style=social&color=white)](https://github.com/SamoTech/Farik/stargazers) | **Open-source HRMS with integrated sentiment & culture analytics.** MIT-licensed core includes People Directory, Leave Tracking, and Analytics. Paid add-ons support AI-inferred **Mood Pulse**, burnout heatmaps, culture scoring, and 90-day attrition forecasting. Deploys easily on Vercel or Node.js. |
| **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)** | [![Stars](https://img.shields.io/github/stars/LimeSurvey/LimeSurvey?style=social&color=white)](https://github.com/LimeSurvey/LimeSurvey/stargazers) | **Mature open-source survey engine with 19+ pre-built employee well-being templates.** Features battle-tested questionnaires for Work-Life Balance, Workplace Stress, Employee Engagement, eNPS, and Health & Safety. Supports 80+ languages, 28+ question formats, and detailed cohort segmentation without per-response costs. |
| **[MindBridge](https://github.com/guopanqi/mindbridge)** | [![Stars](https://img.shields.io/github/stars/guopanqi/mindbridge?style=social&color=white)](https://github.com/guopanqi/mindbridge/stargazers) | **Anonymous employee psychological support system.** Architectural emphasis on zero-knowledge anonymity: employee submissions are encrypted with AES-GCM across isolated Cloudflare D1 databases. Features deterministic rule engines for crisis triage and hardcoded cohort suppression (<10 responses suppressed) to prevent deanonymization. |
| **[WorkWell AI](https://github.com/topics/employee-wellbeing)** | — | **Predictive burnout detection machine learning framework.** Evaluates workload trends, communication patterns, and behavioral telemetry via a REST API and management dashboard to identify burnout risk factors proactively. |
| **[regulatory-first/health-frontend](https://github.com/sumanjangili/regulatory-first)** | — | **Regulatory-compliant daily wellness check-in tool.** Built with React and Material-UI for distributed remote workers. Architected specifically for compliance environments requiring HIPAA, GDPR, CCPA, and DPDPA alignment. Includes aggregated manager views and Dockerized deployment. |
| **[employee-pulse-survey-enps-engine](https://github.com/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63)** | — | **FastAPI-powered eNPS and pulse survey engine.** Modern Python stack utilizing LangChain for response sentiment synthesis and trend extraction. Docker ready. |

---

## Comparative Framework Guide

Selecting the right solution depends on your organizational needs, data security requirements, and technical capabilities:

- **For Clinical & Crisis Support**: Choose specialized SaaS platforms ([Lyra Health](https://www.lyrahealth.com/), [Spring Health](https://www.springhealth.com/), [Modern Health](https://www.modernhealth.com/)) that connect staff directly with licensed therapists and physicians.
- **For Enterprise Benchmarking & Engagement Analytics**: Leverage [Culture Amp](https://www.cultureamp.com/) or [Limeade](https://www.limeade.com/) to measure drivers against global industry standards.
- **For Anonymous Pulse Surveys & eNPS**: Deploy [LimeSurvey](https://github.com/LimeSurvey/LimeSurvey) (self-hosted, zero seat cost) or [employee-pulse-survey-enps-engine](https://github.com/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63).
- **For Self-Hosted Team Mood & Burnout Alerts**: Implement [WorkMate](https://github.com/karlis0099/WorkMate) for internal networks with automated webhook notifications, or [MindBridge](https://github.com/guopanqi/mindbridge) for strict anonymized employee crisis channels.

---

## Privacy, Anonymity & Compliance Considerations

Employee well-being platforms handle highly sensitive psychological, medical, and sentiment data. Implementing these systems requires strict adherence to privacy engineering principles:

1. **Aggregation & K-Anonymity Thresholds**: Enforce strict minimum reporting thresholds (e.g., minimum 5–10 respondents per department/cohort) before revealing any sentiment metrics to HR or managers to avoid reverse-identification.
2. **Data Encryption & Zero-Knowledge Architecture**: Store sensitive feedback using authenticated encryption (e.g., AES-GCM) with segregated identity and response databases.
3. **Regulatory Standards**: Ensure data pipelines respect healthcare and consumer privacy frameworks including **HIPAA** (health data in the US), **GDPR** (EU employee privacy protections), **CCPA/CPRA**, and relevant international standards.

---

## How to Contribute

Contributions to this ecosystem list are welcome!

1. Fork this repository.
2. Add your project or SaaS tool to the appropriate section in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-Employee-Well-Being-Workplace-Culture/README.md).
3. Ensure you include:
   - Tool/Project Name and official link
   - Clear, objective 1–2 sentence description of functionality
   - Starting pricing and free tier/trial details (if SaaS) or license & stars (if open-source)
4. Submit a Pull Request with a descriptive title.

---

## Disclaimer

This repository is a community-curated directory compiled for educational, research, and technical evaluation purposes. Inclusion does not imply endorsement. Organizations evaluating well-being software should conduct their own security, privacy, and clinical efficacy reviews.
