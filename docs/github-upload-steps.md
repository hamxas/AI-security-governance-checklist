# GitHub Upload Steps

## Option 1: GitHub Website

1. Go to https://github.com/new
2. Repository name: `enterprise-ai-security-governance-checklist`
3. Description: `Excel-based AI security and governance checklist for organisations adopting generative AI, LLMs, copilots, and agentic AI workflows.`
4. Choose Public or Private.
5. Do not initialize with README if uploading this package.
6. Create repository.
7. Upload all files from this folder.
8. Commit with message: `Initial release of AI security governance checklist`

## Option 2: Git CLI

```bash
git init
git add .
git commit -m "Initial release of AI security governance checklist"
git branch -M main
git remote add origin https://github.com/<your-username>/enterprise-ai-security-governance-checklist.git
git push -u origin main
```

## Recommended Repository Settings

- Add topics:
  - `ai-security`
  - `ai-governance`
  - `llm-security`
  - `genai-security`
  - `risk-management`
  - `nist-ai-rmf`
  - `owasp-llm-top-10`
  - `shadow-ai`
  - `ai-detection-response`

- Add repository description:

```text
Practical Excel-based checklist for AI security, governance, Shadow AI detection, LLM guardrails, and enterprise GenAI risk management.
```

## Suggested First Release

Create a GitHub release:

- Tag: `v1.0.0`
- Title: `Enterprise AI Security & Governance Checklist v1.0`
- Attach the Excel workbook from `tool/`.
- Add a short summary of included tabs and control domains.
