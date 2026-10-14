# Denzel Robinson

**AI Research Engineer and Solution Architect** building governed AI systems, trustworthy retrieval, evaluation infrastructure, and large-scale data pipelines.

Seattle, WA · Willing to relocate · [Email](mailto:denzel.robinson23@gmail.com)

## Focus

The work here focuses on the part of AI systems that cannot be solved with a better prompt alone: **whether the output is grounded, current, authorized, measurable, and auditable.**

- **Incident management and AIOps:** alert noise analysis, Event Orchestration and routing design, on call and escalation as code, proof of value automation, and Opsgenie migration
- **AI evaluation and governance** — human-calibrated LLM evaluation, confidence routing, provenance, and human-in-the-loop controls
- **Retrieval and data platforms** — RAG architecture, security-trimmed retrieval, freshness SLAs, metric verification, data contracts, and observability
- **Applied ML research** — 3D computer vision, volumetric segmentation, temporal tracking, local evaluation harnesses, and evidence-driven experimentation
- **Product analytics** — API ingestion, ETL, quality gates, A/B testing, conversion funnels, and defensible measurement

## Selected Public Work

| Project | What it demonstrates |
|---|---|
| [POV Autopilot for PagerDuty](https://github.com/DenzelR12/pov-autopilot) | Automates the Solutions Architect motion for incident management deals, starting from a prospect's own alert history. **Discovery** turns an alert export into an auditable noise funnel (dedup, flap suppression, grouping, severity based urgency), cross service storm detection, and service ownership. **Design** emits Terraform for the official PagerDuty provider: teams, schedules, escalation policies, services, a global Event Orchestration router, and suspend rules for flapping checks. **Proof of value** generates measurable success criteria from the baseline and replays the worst historical storm through the Events API v2. **Business case** ties every dollar to an editable assumption. **Migration** converts Opsgenie schedules, time restrictions, and escalations ahead of its April 2027 end of support, and lists every gap that needs a customer decision. Zero dependencies, tested, CI validates all generated Terraform. |
| [AdJudge Guardrails](https://github.com/DenzelR12/adjudge-guardrails) | An independent, human-calibrated multimodal AI evaluation and review-routing architecture for ad creative quality. It uses a public human-versus-LLM advertising benchmark as an evaluation basis; it does not claim ownership of the source dataset or ad assets. The architecture combines provenance-aware retrieval, freshness-controlled metric evidence, tenant-safe analytics, event forensics, human-approved remediation, and a sixth Advertiser and Campaign Intelligence Brain for scoped account context. **Includes a runnable local demo, automated tests, freshness checks, a metric-verification workflow, and a `make report` decision-health digest that makes metric ownership visible to managers and client partners.** |
| [Developer Ecosystem Insights](https://github.com/DenzelR12/developer-ecosystem-insights) | Agentic Python data pipeline for developer-platform adoption telemetry, API ingestion, data-quality gates, freshness monitoring, and defensible metric definitions. |
| [Credit Risk Research Framework](https://github.com/DenzelR12/credit-risk-research-framework) | Transparent reference architecture for an early-warning credit-risk research engine: eighteen research areas across macro credit, SEC filing forensics, earnings quality, consumer stress, ratings actions, sovereign risk, and cross-market synthesis, served through a quality-gated FastAPI backend and live dashboard. Architecture and governance are public; calibrated research remains private. Educational only; not investment advice or a production risk model. |

All of these share one engineering spine: provenance-aware inputs, freshness SLAs, fail-closed verification, claim gating, and human approval for anything consequential. POV Autopilot applies it to incident response, where every projected reduction is traceable to a rule the customer can audit; AdJudge applies it to AI evaluation; the credit framework applies it to financial-risk research.

## Applied ML Research

### VoxTree — 3D cell lineage tracking

An active independent research project for 4D light-sheet microscopy. VoxTree processes 80+ GB volumes with a dual 3D U-Net ensemble, Zarr streaming, physical-unit non-max suppression, and two-pass Hungarian matching with velocity prediction.

The project progressed from a 0.262 baseline to a 0.873 public leaderboard score through measured iteration. The key improvement was diagnosing an ignore-mask training failure that suppressed gradients in dense frames; correcting the mask and target configuration reduced heatmap saturation from 0.25 to 0.047, raised a high-weight movie's node ratio from 0.72 to 0.94, and delivered a +0.033 leaderboard gain that the local evaluation harness predicted to three decimals. A 22-test regression suite covers critical detection and tracking behavior.

The public score is ongoing work, not a claim of final ranking or a production validation.

## Product and Client Work

- **ClutchAgent** — Private multi-tenant AI and data platform for secure analytics workflows, athlete valuation models using telemetry, gameplay, and social-momentum signals, and compliance automation for sponsorship workflows.
- **LTLinx** — Customer Success and SaaS strategy work for senior-care compliance software: translating user blockers into product updates, technical documentation and webinars, and A/B-tested engagement and conversion analysis.

These repositories remain private because they contain proprietary product, customer, or operational material. Their public descriptions are included here for context only.

## Stack and Practice

**Languages and data:** Python · SQL · API ingestion · ETL/data pipelines · data-quality monitoring

**ML and AI:** PyTorch · computer vision · 3D segmentation · multimodal evaluation · RAG · LLM-as-Judge evaluation · agent orchestration

**Incident response and infrastructure:** PagerDuty (Events API v2, REST API, Event Orchestration) · Terraform · Opsgenie migration · on call and escalation design · alert noise reduction

**System design:** tenant isolation · authorization-aware retrieval · metric provenance · freshness verification · audit lineage · observability

**Working principle:** A model output is a hypothesis until the supporting data, metric definition, evaluation harness, authorization scope, and limitations are visible.

## Contact

[denzel.robinson23@gmail.com](mailto:denzel.robinson23@gmail.com) · Seattle, WA · Willing to relocate
