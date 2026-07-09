# Implementation Playbook

This playbook explains how an organisation can use the checklist to build a practical AI security programme.

## Step 1: Discover AI Usage

Identify where AI is already used:

- ChatGPT, Claude, Gemini, Copilot, Perplexity
- AI browser extensions
- AI meeting assistants
- AI document summarisation tools
- AI coding assistants such as Claude Code, Codex, Cursor, Copilot, Windsurf
- Internal LLM apps
- RAG applications
- Agentic workflows
- AI features embedded in SaaS platforms

Recommended sources:

- Secure Web Gateway / proxy logs
- CASB logs
- DNS logs
- Firewall logs
- Endpoint telemetry
- Browser extension inventory
- SaaS inventory
- OAuth app consent logs
- GitHub/GitLab audit logs
- DLP alerts

## Step 2: Classify AI Use Cases

For each AI use case, record:

- Business owner
- Technical owner
- Tool or model provider
- Data involved
- User population
- Whether external users interact with it
- Whether files are uploaded
- Whether RAG is used
- Whether the AI can call tools or take actions
- Current controls
- Residual risk

## Step 3: Define Approved AI Routes

Create safe paths for users:

- Enterprise AI workspace for general employees
- Approved AI coding assistant for developers
- Internal AI portal for sensitive business workflows
- LLM gateway or proxy for internal applications
- Exception process for special cases

## Step 4: Implement Guardrails

Guardrails should cover:

- Identity and access
- Data classification
- Secrets detection
- PII detection/redaction
- Prompt injection checks
- File upload policy
- Model allowlists
- Output scanning
- Tool/action restrictions for agents
- Human approval for risky actions

## Step 5: Build Detection and Response

Recommended detections:

- Sensitive data uploaded to public AI tools
- Secrets pasted into prompts
- Unapproved AI SaaS usage
- Risky AI OAuth app consent
- AI browser extensions with broad permissions
- Large uploads to AI domains
- Prompt injection attempts
- RAG access control failures
- Agent tool calls outside expected behaviour
- AI-generated insecure code or secrets in commits

## Step 6: Report Maturity

Use the dashboard to report:

- Overall AI security maturity
- Domain-level maturity
- Top control gaps
- Highest-risk AI tools
- Shadow AI trends
- Incident volume and severity
- Roadmap progress

## Step 7: Reassess Continuously

AI adoption changes quickly. Reassess:

- Quarterly
- Before major AI platform rollout
- After a high-risk AI incident
- After introducing agents/tools/RAG
- After onboarding new AI vendors
