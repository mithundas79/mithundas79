# Mithun Das

Senior backend and platform architect, Kolkata (UTC+5:30). Nineteen years in software; contracting independently through Jumacro Software Services.

I build and run backends where a wrong answer costs money - accounting, payments, banking data, hardware in the field - so I design for the times a system is wrong, not only for the times it is right.

**Site:** [mithundas79.github.io](https://mithundas79.github.io/) - production work, three stories from production, how I work, limits stated. · **CV:** [PDF](https://mithundas79.github.io/Mithun-Das-CV.pdf) · **Contact:** mithun.das@jumacro.com · [Book a call](https://calendly.com/mithun-das/intro-call)

## In production

- **[Paynthr](https://paynthr.com/)** (2025-present) - AI bookkeeping automation for a US accounting firm, live since June 2026. Documents from Dropbox and email; OCR + Claude on AWS Bedrock (tool-use, prompt caching, streaming) under each client's explicit accounting rules; entity resolution with pgvector; a per-client trust dial decides what posts to QuickBooks Online unattended. 20+ Go services on ECS, Aurora PostgreSQL with row-level security, Terraform. Built end to end. Certified over four days on a fresh firm before release: 267 of 275 real invoices reconciled to the cent, 210 findings filed openly.
- **Electroop** (2022-present) - backend architect of a live EV charging network: OCPP 1.6/2.0.1 WebSocket server talking to real chargers, OCPI roaming, payments, multi-tenant APIs, mobile backend. TypeScript on AWS. Its customers are not mine to name.

## Public code - the working method in the open

The model proposes, deterministic code decides. Tests, CI, live demos, limits labelled.

| Repository | What it shows |
|---|---|
| [filing-agent](https://github.com/mithundas79/filing-agent) | A tool-calling LLM agent that cannot mark its own work done: hand-written tool loop on a fully local model, fabricated evidence refused, bounded retries, a receipt for every run. [Recorded session, replayed](https://mithundas79.github.io/filing-agent/). |
| [doc-intake](https://github.com/mithundas79/doc-intake) | Documents in, order out - local OCR + deterministic accounting rules. No cloud, no key, no model. [Live demo](https://mithundas79.github.io/doc-intake/). |
| [doc-intake-service](https://github.com/mithundas79/doc-intake-service) | The full-stack sibling: Python/FastAPI + React, Tesseract OCR, a trained document-type classifier with its honest metrics committed. |

## How I work

Scope and acceptance criteria written down before I build. Nothing is done until I have driven it on a deployed environment and shown the evidence. Small reviewable pull requests, staging before production, a rollback path in every release. Prompts are versioned code with tests. I use AI coding tools heavily and openly, inside a review-and-verify process I run.

**Stack:** Go · TypeScript/Node · Python/FastAPI · PHP/Laravel · React · AWS (ECS, Lambda, Aurora, S3/SQS/SNS, Bedrock, Textract) · Terraform · PostgreSQL + RLS · pgvector · MongoDB · QuickBooks Online · Stripe · OCPP/OCPI

**Not:** a data scientist, a fine-tuner, or a design-led front-end specialist. Said here so nobody finds out later.
