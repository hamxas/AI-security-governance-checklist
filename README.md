# Enterprise AI Security & Governance Checklist

**Author:** Hamza Saleem  
**Version:** 1.0  
**Format:** Excel-based assessment and implementation tool  

A practical security and governance checklist for organisations adopting AI, LLMs, copilots, AI coding assistants, RAG applications, and agentic AI workflows.

![Dashboard preview](assets/dashboard-preview.png)

## Quick Download

- Download the workbook from `tool/Enterprise_AI_Security_Governance_Checklist.xlsx`
- Best for Microsoft Excel desktop or Excel 365
- Start with the **How to Use** and **AI Asset Inventory** tabs

## Licensing Note

This repository is public for visibility and evaluation, but it is **not open source**. Reuse, redistribution, resale, and repackaging are restricted under `LICENSE.md`.

## Problem Statement

Organisations are adopting AI quickly, often before security, privacy, governance, and detection controls are mature enough. Employees use tools such as ChatGPT, Claude, Gemini, Copilot, AI coding assistants, document summarisation tools, browser extensions, and agentic workflows in day-to-day operations.

This creates several risks:

- Sensitive data exposure through prompts, file uploads, and AI SaaS tools
- Shadow AI usage outside approved enterprise controls
- Prompt injection and jailbreak attempts against internal AI applications
- Unsafe agent actions through tools, APIs, email, tickets, cloud resources, or code repositories
- Weak logging and limited detection coverage for AI misuse
- Inconsistent governance across business, engineering, legal, privacy, and security teams

This tool helps organisations move from **uncontrolled AI adoption** to **measurable AI risk management**.

## What This Tool Provides

The workbook provides a structured assessment model covering AI governance, security architecture, data protection, detection engineering, vendor risk, and incident response.

It includes:

- AI security maturity dashboard
- Control checklist with scoring
- AI asset inventory
- Approved AI tools register
- Data classification rules
- Guardrails matrix
- Shadow AI detection checklist
- LLM gateway controls
- AI vendor review checklist
- AI incident response playbook
- Reference mapping to recognised frameworks

## Workbook Tabs

The workbook currently contains these tabs:

- **Dashboard** - maturity summary and domain-level scoring
- **How to Use** - instructions for completing and maintaining the workbook
- **Control Checklist** - core controls, owners, evidence, and scoring
- **AI Asset Inventory** - AI systems, tools, use cases, and ownership tracking
- **Guardrails Matrix** - preventive and detective safeguards for AI use
- **Detection Library** - example monitoring and detection use cases
- **Vendor Review** - third-party AI risk review prompts and checks
- **Incident Playbook** - response guidance for AI-related incidents
- **Reference Sources** - source material and framework references
- **Settings** - workbook settings and supporting values

## Frameworks Referenced

This tool is inspired by and mapped to widely recognised AI security, privacy, and governance resources, including:

- NIST AI Risk Management Framework: https://www.nist.gov/itl/ai-risk-management-framework
- NIST Generative AI Profile: https://www.nist.gov/itl/ai-risk-management-framework
- ISO/IEC 42001 AI Management System: https://www.iso.org/standard/81230.html
- ISO/IEC 23894 AI Risk Management: https://www.iso.org/standard/77304.html
- OWASP Top 10 for LLM Applications: https://owasp.org/www-project-top-10-for-large-language-model-applications/
- MITRE ATLAS: https://atlas.mitre.org/
- Cloud Security Alliance AI Controls Matrix: https://cloudsecurityalliance.org/
- EU AI Act concepts: https://artificialintelligenceact.eu/

This is not an official implementation of any one standard. It is an operational checklist designed to help security teams apply those concepts in real organisations.

## Scoring Model

Each control can be scored from 0 to 5:

| Score | Meaning |
|---:|---|
| 0 | Not Started |
| 1 | Planned |
| 2 | Partially Implemented |
| 3 | Implemented |
| 4 | Implemented & Tested |
| 5 | Automated & Monitored |

The dashboard uses these scores to show maturity by domain and overall readiness.

## Example Use Cases

Use this tool to assess whether your organisation has controls for:

- Approved AI tool usage
- Shadow AI discovery and reduction
- DLP for AI prompts and uploads
- Secrets detection before LLM submission
- AI browser extension governance
- OAuth app review for AI SaaS tools
- LLM gateway or proxy enforcement
- RAG and vector database access control
- Agentic AI tool permissions
- AI detection and response use cases
- AI vendor due diligence
- AI incident response

## Suggested Operating Model

A practical enterprise AI security programme should cover:

1. **Discover** AI usage across users, SaaS, endpoints, browsers, cloud, and code repositories.
2. **Approve** enterprise AI tools and define acceptable use cases.
3. **Protect** sensitive data with DLP, redaction, file controls, and access policies.
4. **Control** model access through enterprise workspaces or an LLM gateway.
5. **Detect** risky behaviour through SIEM, CASB, SWG, EDR, identity, OAuth, and code repository logs.
6. **Respond** with playbooks for AI data leakage, prompt injection, risky agents, and Shadow AI incidents.
7. **Govern** AI risk through ownership, exception handling, vendor review, and executive reporting.

## Repository Structure

```text
.
├── README.md
├── tool/
│   └── Enterprise_AI_Security_Governance_Checklist.xlsx
├── assets/
│   └── dashboard-preview.png
├── docs/
│   ├── framework-mapping.md
│   ├── implementation-playbook.md
│   ├── github-upload-steps.md
│   └── marketing-copy.md
├── LICENSE.md
├── SECURITY.md
├── CONTRIBUTING.md
├── CHANGELOG.md
└── CITATION.cff
```

## Getting Started

1. Download the workbook from the `tool/` folder.
2. Start with the **AI Asset Inventory** tab.
3. Complete the **Control Checklist** tab.
4. Score each control from 0 to 5.
5. Use the dashboard to identify weak domains.
6. Use the evidence and owner columns to assign remediation actions.
7. Reassess quarterly or after major AI platform changes.

## Positioning

This tool is built for security leaders, AI security engineers, GRC teams, privacy teams, platform teams, and product security teams who need a practical way to govern AI adoption without blocking innovation.

## Disclaimer

This checklist is provided for educational and advisory purposes. It is not legal advice, certification advice, or a substitute for formal risk assessment, audit, privacy review, or regulatory interpretation.
