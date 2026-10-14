# Mithun Das

Senior backend and platform architect in Kolkata, India (UTC+5:30). Building software since 2006; delivering projects through **Jumacro Software Services Pvt. Ltd., established December 2014**.

I build production backends for accounting, payments, document processing and EV charging: systems that need reliable integrations, explicit permissions and evidence that they work.

**Portfolio:** [mithundas79.github.io](https://mithundas79.github.io/) · **CV:** [PDF](https://mithundas79.github.io/Mithun-Das-CV.pdf) · **Contact:** mithun.das@jumacro.com · [Book a call](https://calendly.com/mithun-das/intro-call)

**Availability:** Core working hours **1–11 PM IST (UTC+5:30)**. Client-specific overlap arranged for US and European teams.

## Selected work

- **[Paynthr](https://paynthr.com/)** — AI bookkeeping automation, **2025–2026; engagement completed**, delivered through Jumacro. Built the product, backend and AWS infrastructure; in production during the engagement from June 2026. Dropbox/email intake, OCR, Claude on AWS Bedrock with tool use, prompt caching and streaming, pgvector/Titan entity resolution, per-client accounting rules and review thresholds, QuickBooks Online and Stripe. 20+ Go services on ECS, Aurora PostgreSQL with row-level security and Terraform. A four-day staging certification reconciled 267 of 275 invoices to the cent; a separate release audit documented 210 findings.
- **Electroop** — EV charge-point management, **2022–present**, within my **Localghost engagement (2018–present)**. Backend architecture for live chargers: OCPP 1.6/2.0.1 over WebSockets, OCPI roaming, payments, tenant APIs and mobile backends. TypeScript on AWS with C# and Python components. Localghost is the underlying engagement; Electroop is the project name.
- **AVEA** — shipping and logistics project through Jumacro, **2025–2026**. AWS shipping-label OCR using Textract, S3, SQS, Lambda and SNS; Laravel vendor-portal fixes and a major-version upgrade; Python/FastAPI work on a direct-carrier gateway whose production launch is not claimed.
- **AWS infrastructure and cost review** — Terraform codification and a **24% monthly cost reduction**, from $2,039 to about $1,550, with budget alarms.

**Upwork history:** 47 completed engagements, 2,400+ hours and 44 rated 5.0, **2015–2020**.

## Public engineering demos

| Repository | What it demonstrates |
|---|---|
| [filing-agent](https://github.com/mithundas79/filing-agent) | A local LLM tool loop using Ollama, application-side evidence checks, bounded retries and run receipts. [Recorded session](https://mithundas79.github.io/filing-agent/). |
| [doc-intake](https://github.com/mithundas79/doc-intake) | TypeScript, local OCR and deterministic accounting rules. [Browser demo](https://mithundas79.github.io/doc-intake/). |
| [doc-intake-service](https://github.com/mithundas79/doc-intake-service) | Python/FastAPI, React, Tesseract and a scikit-learn document classifier trained and evaluated on synthetic data. |

## How I work

Written scope and acceptance criteria, small reviewable pull requests, staging checks and a rollback plan. I distinguish code implemented, changes deployed and behavior verified in production. I use AI coding tools openly within a review-and-verify process that I own.

**Stack:** Go · TypeScript/Node.js · Python/FastAPI · PHP/Laravel · C# · React · AWS (ECS/Fargate, Lambda, Aurora, S3/SQS/SNS, CloudFront, Bedrock, Textract, CodeBuild) · Terraform · Docker · PostgreSQL/RLS · pgvector/Titan embeddings · MongoDB · Neo4j · GCP · QuickBooks Online · Stripe · Dropbox · OCPP/OCPI.

My focus is backend architecture and AI application engineering. The public classifier uses synthetic data; I do not present it as production ML evaluation. Yodlee integration work was sandbox-only.
