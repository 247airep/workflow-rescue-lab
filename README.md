# Workflow Rescue Lab

A hands-on automation reliability and troubleshooting portfolio project.

## Purpose

Business automations rarely fail in clean ways. This project demonstrates how failures can be detected, diagnosed, contained, recovered, and documented rather than simply showing a happy-path workflow.

## Pipeline

`Web Form → Validate → Deduplicate → API → Database → AI Classification → Route → Follow-up`

## Incident scenarios

- API timeout → retry/backoff → recovery verification
- Duplicate webhook → idempotency protection
- Malformed AI JSON → schema validation + fallback
- Missing required data → quarantine + human review
- HTTP 429 rate limit → retry window + exponential backoff

## Skills demonstrated

Automation architecture, APIs, webhooks, input validation, idempotency, structured AI output validation, retry logic, fallback design, incident logging, root-cause analysis, QA, and operational thinking.

## Why I built it

I wanted a reproducible environment for demonstrating not only how I build workflows, but how I approach the more important question: what happens when the workflow breaks?

## Roadmap

1. Persist incident history
2. Add JSON event payload inspector
3. Add automated test suite
4. Add webhook/API mock service
5. Add incident severity and SLA tracking
6. Add downloadable incident report
