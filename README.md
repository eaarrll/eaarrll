# Earl Martin Sioson

**Senior DevOps Engineer** · AWS · Azure · Kubernetes · Terraform · Metro Manila, Philippines

I have 8+ years of experience building CI/CD, cloud infrastructure and operational automation on AWS and Azure, at Accenture, Home Credit, Safeway Philtech (Albertsons), Asurion, 3Cloud and now ConnectOS. At ConnectOS I support two enterprise clients in parallel, owning production releases, incident investigation, security hardening and cost work. Highlights include cutting AWS spend \~30% (\~$180K a year), cutting release cycle time \~40%, and migrating 150+ apps to AKS with zero downtime.

Lately I build AI agents that take over manual ops work: an incident-triage agent for a ServiceNow TechOps queue, an Azure AI Foundry tagging agent, and Claude Code + MCP automation for releases and code reviews.

**Open to Senior DevOps, Platform and SRE roles from January 2027**, remote, hybrid or with relocation.

## Projects

- **[abiso](https://github.com/eaarrll/abiso)**: last-mile disaster-alert relay for Philippine barangays. It narrows PAGASA's province-wide warnings down to the exposed barangays, sends plain-language SMS that fit in one segment, tracks replies, and escalates to the municipal DRRMO when nobody answers. Python, Docker, Terraform on Azure, and a GitHub Actions pipeline.
- **[ci-triage-agent](https://github.com/eaarrll/ci-triage-agent)**: a GitHub Action in which an AI agent investigates failed CI runs and posts the root cause, the log lines that prove it, and the fix on the pull request. It reads cloud and platform failures too (Terraform state locks, AWS IAM, Azure OIDC, OOM kills, ImagePullBackOff), redacts secrets before anything reaches the model, treats logs as untrusted input, and is scored against 17 recorded failures. TypeScript, Claude API with read-only tools. [Live demo PRs](https://github.com/eaarrll/ci-triage-agent-demo/pulls)
- **[infra-status-dashboard](https://github.com/eaarrll/infra-status-dashboard)**: answers "is it us or them?" during an incident. It shows 13 vendor status pages (AWS, Cloudflare, GitHub, Datadog and more) on one screen and counts only incidents that are still open. [Live demo](https://infra-status-dashboard.vercel.app)
- **[manila-outages](https://github.com/eaarrll/manila-outages)**: tracks scheduled power and water interruptions in Metro Manila. An Android app with a GitHub Actions pipeline that builds and signs the release bundle, with the Play Store upload step ready to switch on.

## Toolbox

| | |
|---|---|
| **AI & agentic ops** | Claude Code, Claude API (tool use, evals), MCP, Azure AI Foundry Agents, FastAPI, agentic workflows |
| **CI/CD** | GitHub Actions, Azure DevOps Pipelines (Classic and YAML), Jenkins, GitLab CI |
| **Containers & IaC** | Docker, Kubernetes (AKS, EKS), Helm, Terraform, Bicep, ARM, Ansible |
| **AWS** | Lambda, API Gateway, DynamoDB, S3, EC2, EKS, CloudFront, Route 53, IAM |
| **Azure** | AKS, App Services, Key Vault, VNets, Landing Zones, Azure Monitor, Log Analytics |
| **Security** | GitHub OIDC, least-privilege IAM/RBAC, Key Vault, AWS Secrets Manager, AWS and Cloudflare WAF |
| **Observability** | Datadog, Prometheus, Grafana, Loki, CloudWatch, Azure Monitor, ELK |
| **Scripting** | PowerShell, Python, Bash, Azure CLI, AWS CLI |
| **Delivery** | ServiceNow, Jira, Confluence, CAB/change management, RCAs and runbooks |

## Certifications

Microsoft AZ-400 (DevOps Engineer Expert) · AZ-104 · AZ-900 · AWS SAA-C03 in progress

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/earl-martin-sioson/) · [Portfolio](https://earl-sioson-devops-engineer.vercel.app)
