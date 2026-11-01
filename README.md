# Denzel Robinson

**AI Solutions Architect and Research Engineer.** I design governed AI systems that enterprises can trust: grounded retrieval, measurable evaluation, auditable decisions, and data pipelines built to scale.

7+ years turning business, operational, and technical problems into working solutions across SaaS, enterprise platforms, data, and AI.

Atlanta, GA · Open to relocation · [Email](mailto:denzel.robinson23@gmail.com)

## Featured: Muse Shopping Index

**Entry for Meta's Global AI Developer Hackathon**

**[Repository](https://github.com/DenzelR12/Muse-Shopping-Index)** · **[Live demo](https://denzelr12.github.io/Muse-Shopping-Index/demo/)** · **[Pitch video (2:59)](https://denzelr12.github.io/Muse-Shopping-Index/muse_demo-video.MP4)**

Muse Shopping Index turns a Reel into a purchase without costing the customer's trust. A viewer taps **Shop this reel**, sees one exact review (seller, item, total, shipping, tax, refund terms), approves once, and the server executes. **The model proposes. A deterministic server authorizes.**

### Hackathon Highlights

- **Working end to end flow:** from Reel to exact review to single approval to server execution, available as a live demo and a 2:59 pitch video.
- **Verified against real Meta infrastructure:** live Meta catalog reads confirmed through the repository client on October 30, 2026. API deployed and auth gated on Render.
- **Trust controls built in:** approvals are consume once and bound to exact terms. Any change in price, tax, shipping, or terms requires reapproval. Uncertain outcomes go to reconciliation, never a blind retry or a second charge.
- **Exactly once execution:** atomic claim per tenant and key, replay returns the original result, and the burst limiter fails closed.
- **Partner ready go live plan:** an "If you are at Meta" section lists the four partner side switches in order (host binding, Reel entry point, signed handoff, platform catalog access) with every verification step and its timeline.
- **Seller aligned business model:** sellers pay only on a verified order. No fees for clicks, drafts, or abandoned carts.
- **Tenant isolation:** Meta catalog (read only, tenant gated), Shopify Storefront, Render API with Postgres, and a host agnostic review panel. Each seller's data is isolated from every other seller.
- **Accessible by default:** keyboard navigation, screen reader support, high contrast, reduced motion, and a plain English explainer for non technical readers.
- **Honest status:** no live sellers, payments, or native Muse window are claimed.

TypeScript monorepo · CI · Node 22 · pnpm

## What I Build

My work targets the part of AI systems a better prompt cannot fix: **whether an output is grounded, current, authorized, measurable, and auditable.**

- **Agentic commerce and partner integrations:** catalog integration, tenant isolation, consent bound approvals, exactly once execution, and go live plans written for the partner's side of the wall.
- **AI evaluation and governance:** human calibrated LLM evaluation, confidence routing, provenance, and human in the loop controls.
- **Retrieval and data platforms:** RAG architecture, security trimmed retrieval, freshness SLAs, metric verification, data contracts, and observability.
- **Incident management and AIOps:** alert noise analysis, Event Orchestration and routing design, on call and escalation as code, proof of value automation, and Opsgenie migration.
- **Applied ML research:** 3D computer vision, volumetric segmentation, temporal tracking, local evaluation harnesses, and evidence driven experimentation.
- **Product analytics:** API ingestion, ETL, quality gates, A/B testing, conversion funnels, and defensible measurement.

## Selected Public Work

| Project | What it demonstrates |
|---|---|
| [Muse Shopping Index](https://github.com/DenzelR12/Muse-Shopping-Index) | Reel to purchase in one exact review and one approval. Read only Meta and Shopify catalog clients, tenant scoped data, consume once approvals bound to exact terms, exactly once execution, and a step by step partner activation plan. Includes a live demo, pitch video, judge brief, and a clear list of what is not live yet. |
| [POV Autopilot for PagerDuty](https://github.com/DenzelR12/pov-autopilot) | Automates the Solutions Architect motion for incident management deals, starting from a prospect's own alert history. **Discovery** turns an alert export into an auditable noise funnel and service ownership map. **Design** emits Terraform for the official PagerDuty provider: teams, schedules, escalation policies, services, and a global Event Orchestration router. **Proof of value** replays the worst historical storm through Events API v2 against measurable success criteria. **Business case** ties every dollar to an editable assumption. **Migration** converts Opsgenie schedules and escalations ahead of its April 2027 end of support. Zero dependencies, tested, with CI validating all generated Terraform. |
| [AdJudge Guardrails](https://github.com/DenzelR12/adjudge-guardrails) | Human calibrated multimodal evaluation and review routing for ad creative quality, built on a public human versus LLM advertising benchmark (no ownership of the source dataset or ad assets is claimed). Combines provenance aware retrieval, freshness controlled metric evidence, tenant safe analytics, event forensics, and human approved remediation. Includes a runnable local demo, automated tests, freshness checks, and a `make report` decision health digest for managers and client partners. |
| [Developer Ecosystem Insights](https://github.com/DenzelR12/developer-ecosystem-insights) | Agentic Python data pipeline for developer platform adoption telemetry: API ingestion, data quality gates, freshness monitoring, and defensible metric definitions. |
| [Credit Risk Research Framework](https://github.com/DenzelR12/credit-risk-research-framework) | Reference architecture for an early warning credit risk research engine spanning eighteen research areas, served through a quality gated FastAPI backend and live dashboard. Architecture and governance are public; calibrated research remains private. Educational only, not investment advice. |

**One engineering spine runs through all of it:** provenance aware inputs, freshness SLAs, fail closed verification, claim gating, and human approval for anything consequential. Muse applies it to commerce, POV Autopilot to incident response, AdJudge to AI evaluation, and the credit framework to financial risk research.

## Applied ML Research

### VoxTree: 3D Cell Lineage Tracking

Independent research for 4D light sheet microscopy. VoxTree processes 80+ GB volumes with a dual 3D U Net ensemble, Zarr streaming, physical unit non max suppression, and two pass Hungarian matching with velocity prediction.

**Result:** improved from a 0.262 baseline to a 0.873 public leaderboard score through measured iteration. The key gain came from diagnosing an ignore mask training failure that suppressed gradients in dense frames. Fixing it cut heatmap saturation from 0.25 to 0.047, raised a high weight movie's node ratio from 0.72 to 0.94, and delivered a +0.033 leaderboard gain that the local evaluation harness predicted to three decimals. A 22 test regression suite covers critical detection and tracking behavior.

Ongoing work; not a claim of final ranking or production validation.

## Experience

- **LTLinx** · Customer Success and Solutions Strategy Manager · Technical discovery and SaaS implementation strategy for healthcare organizations under HIPAA; feedback from 100+ caregivers synthesized into prioritized product requirements.
- **ClutchAgent** · Founder and Lead Product Architect · AI athlete platform unifying performance, biometric, and engagement data with auditable, human reviewed sponsorship recommendations.
- **Bellevue College** · AI Technology Evaluation and Accessibility Analyst · Repeatable pre adoption framework for emerging AI tools balancing WCAG and VPAT requirements with architecture risk.
- **Marriott International** · Enterprise Systems and Solutions Analyst · Enterprise systems for a 1,000 room property supporting $60M+ in annual sales; cut Microsoft licensing spend about 15%.
- **August CPA Group** · Senior Data Analyst · SQL and ETL workflows powering audit, forecasting, and executive reporting across a $17M portfolio.

Private product and client repositories are not public because they contain proprietary product, customer, or operational material.

## Stack

**Languages and data:** Python · TypeScript · SQL · PostgreSQL · API ingestion · ETL · data quality monitoring

**ML and AI:** PyTorch · computer vision · 3D segmentation · multimodal evaluation · RAG · LLM as Judge evaluation · agent orchestration

**Commerce and platform integrations:** Meta Graph and Catalog API · Shopify Storefront · Render · OAuth and per tenant credentials

**Incident response and infrastructure:** PagerDuty (Events API v2, REST API, Event Orchestration) · Terraform · Docker · Opsgenie migration · alert noise reduction

**System design:** tenant isolation · authorization aware retrieval · metric provenance · freshness verification · audit lineage · observability

**Working principle:** a model output is a hypothesis until the supporting data, metric definition, evaluation harness, authorization scope, and limitations are visible.

## Contact

[denzel.robinson23@gmail.com](mailto:denzel.robinson23@gmail.com) · Atlanta, GA · Open to relocation
