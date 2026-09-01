# Denzel Robinson

**AI Research Engineer and Solution Architect** building governed AI systems, trustworthy retrieval, evaluation infrastructure, and large-scale data pipelines.

Seattle, WA · Willing to relocate · [Hugging Face dataset](https://huggingface.co/datasets/AdControlCenter/ad-creative-quality-human-vs-llm) · [Email](mailto:denzel.robinson23@gmail.com)

## Focus

The work here focuses on the part of AI systems that cannot be solved with a better prompt alone: **whether the output is grounded, current, authorized, measurable, and auditable.**

- **AI evaluation and governance** — human-calibrated LLM evaluation, confidence routing, provenance, and human-in-the-loop controls
- **Retrieval and data platforms** — RAG architecture, security-trimmed retrieval, freshness SLAs, metric verification, data contracts, and observability
- **Applied ML research** — 3D computer vision, volumetric segmentation, temporal tracking, local evaluation harnesses, and evidence-driven experimentation
- **Product analytics** — API ingestion, ETL, quality gates, A/B testing, conversion funnels, and defensible measurement

## Selected Public Work

| Project | What it demonstrates |
|---|---|
| [AdJudge Guardrails](https://github.com/DenzelR12/adjudge-guardrails) | Human-calibrated multimodal AI evaluation and review routing for ad creative quality. The platform combines provenance-aware retrieval, freshness-controlled metric evidence, tenant-safe analytics, event forensics, human-approved remediation, and a sixth Advertiser and Campaign Intelligence Brain for scoped account context. |
| [Second Brain RAG Guardrails](https://github.com/DenzelR12/second-brain-rag-guardrails) | Enterprise reference architecture for provenance-aware RAG: data contracts, freshness SLAs, metric verification, fail-closed policies, and audit-ready observability. |
| [Developer Ecosystem Insights](https://github.com/DenzelR12/developer-ecosystem-insights) | Agentic Python data pipeline for developer-platform adoption telemetry, API ingestion, data-quality gates, freshness monitoring, and defensible metric definitions. |
| [Credit Risk Research Framework](https://github.com/DenzelR12/credit-risk-research-framework) | Transparent reference architecture for quality-gated, explainable financial-risk research alerts. Educational only; not investment advice or a production risk model. |

## Applied ML Research

### VoxTree — 3D cell lineage tracking

An active independent research project for 4D light-sheet microscopy. VoxTree processes 80+ GB volumes with a dual 3D U-Net ensemble, Zarr streaming, physical-unit non-max suppression, and two-pass Hungarian matching with velocity prediction.

The project progressed from a 0.262 baseline to a 0.873 public leaderboard score through measured iteration. The key improvement was diagnosing an ignore-mask training failure that suppressed gradients in dense frames; correcting the mask and target configuration reduced heatmap saturation from 0.25 to 0.047, raised a high-weight movie's node ratio from 0.72 to 0.94, and delivered a +0.033 leaderboard gain that the local evaluation harness predicted to three decimals. A 22-test regression suite covers critical detection and tracking behavior.

The public score is ongoing work, not a claim of final ranking or a production validation.

## Public Dataset

### [Ad Creative Quality: Human Expert vs. Vision-LLM Judgments](https://huggingface.co/datasets/AdControlCenter/ad-creative-quality-human-vs-llm)

A CC-BY-4.0 dataset published through AdControlCenter for evaluating human-versus-vision-LLM creative-quality judgments. It supports the AdJudge evaluation work by making agreement, calibration, and systematic-disagreement analysis falsifiable rather than anecdotal.

The dataset is public; original ad creative assets are not redistributed by AdJudge. Source-reported findings and independently recomputed project metrics are intentionally kept separate.

## Product and Client Work

- **ClutchAgent** — Private multi-tenant AI and data platform for secure analytics workflows, athlete valuation models using telemetry, gameplay, and social-momentum signals, and compliance automation for sponsorship workflows.
- **LTLinx** — Customer Success and SaaS strategy work for senior-care compliance software: translating user blockers into product updates, technical documentation and webinars, and A/B-tested engagement and conversion analysis.

These repositories remain private because they contain proprietary product, customer, or operational material. Their public descriptions are included here for context only.

## Stack and Practice

**Languages and data:** Python · SQL · API ingestion · ETL/data pipelines · data-quality monitoring

**ML and AI:** PyTorch · computer vision · 3D segmentation · multimodal evaluation · RAG · LLM-as-judge evaluation · agent orchestration

**System design:** tenant isolation · authorization-aware retrieval · metric provenance · freshness verification · audit lineage · observability

**Working principle:** A model output is a hypothesis until the supporting data, metric definition, evaluation harness, authorization scope, and limitations are visible.

## Contact

[denzel.robinson23@gmail.com](mailto:denzel.robinson23@gmail.com) · Seattle, WA · Willing to relocate
