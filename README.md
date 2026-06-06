# Zenitech-AI-Risk-Assessment

# Zenitech AI Risk Assessment — Enterprise GRC Project

**Document Reference:** ZN-AI-RMF-2026-REV1  
**Classification:** Confidential / Internal Use Only  
**Author:** Ike Favour Chinonso — Governance, Risk & Compliance (GRC)  
**Revision:** 2026, Rev 1

---

## Overview

This project is a full enterprise AI Risk Assessment and Governance framework built for **Zenitech Group**, a fictional technology company used as a realistic case study. It demonstrates executive-level GRC thinking applied to the rapidly evolving domain of Generative AI and Large Language Models (LLMs).

The assessment maps active AI tools across Zenitech's engineering and data analytics operations, identifies governance gaps against leading international frameworks, and delivers a practical system hardening and remediation plan.

---

## What This Project Covers

### 1. AI Tool Inventory & Business Use Cases
Documents all Generative AI tools in active use across the organization:

| Tool | Tier | Primary Users |
|------|------|---------------|
| GitHub Copilot | Enterprise | Software Engineers |
| OpenAI ChatGPT | Enterprise + Free Tier | Data Analysts, Project Managers |
| Anthropic Claude | Professional | Solutions Architecture |
| Google Gemini | Advanced + Workspace | R&D Teams |

### 2. Threat Identification & Risk Triage Matrix
Threats are categorized using the **OWASP Top 10 for LLM Applications** across three severity tiers:

- **CRITICAL** — Data leakage and IP exposure via unvetted public AI prompts
- **HIGH** — Insecure output handling; AI-generated code deployed without review
- **MEDIUM** — Supply chain vulnerabilities from unvetted third-party AI plugins

### 3. Governance Gap Analysis & Compliance Crosswalk
Current posture is benchmarked against three frameworks:

- **NIST AI RMF 1.0** — Partial alignment; missing centralized data-masking gateway
- **ISO/IEC 42001** — Gaps in role-based accountability and AI incident response
- **EU AI Act** — Non-compliant; no mechanism to track prompt data transparency

### 4. Practical System Hardening Plan
Three actionable remediation controls are defined:

1. **Technical — API Middleware Proxy Gateways:** Route all outbound AI queries through an internal gateway with PII/credential regex redaction before data reaches external vendors.
2. **Administrative — AI Acceptable Use Policy (AUP):** Ban free-tier consumer AI tools and mandate peer code review + SAST pipelines for all AI-generated code.
3. **Incident Response Integration:** SOC playbook requiring credential rotation and upstream data erasure request within 15 minutes of a confirmed AI data exposure event.

---

## Frameworks Referenced

- [NIST AI Risk Management Framework (AI RMF 1.0)](https://www.nist.gov/system/files/documents/2023/01/26/AI%20RMF%201.0.pdf)
- [ISO/IEC 42001 — AI Management Systems](https://www.iso.org/standard/81230.html)
- [EU Artificial Intelligence Act](https://artificialintelligenceact.eu/)
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

---

## Project Purpose & Portfolio Value

This document is designed to serve as a high-impact GRC portfolio piece demonstrating:

- Advanced **AI Governance** and risk assessment methodology
- Multi-framework **compliance crosswalking** (NIST, ISO, EU AI Act)
- Practical **threat modeling** using OWASP LLM Top 10
- Executive-level **security decision-making** and remediation planning

It is structured to be clearly articulated and defended in technical GRC or cybersecurity interviews, particularly for roles involving AI security, cloud governance, or enterprise risk management.

---

## File Structure

```
ZN-AI-RMF-2026-REV1.docx    # Full assessment report (confidential)
README.md                    # This file — project summary and navigation guide
```

---

## Author

**Ike Favour Chinonso**  
Governance, Risk & Compliance (GRC)  
Zenitech Group — Internal Project

---

*This is a portfolio/educational project built to demonstrate real-world enterprise AI governance skills. "Zenitech Group" is a fictional organization created for case study purposes.*
