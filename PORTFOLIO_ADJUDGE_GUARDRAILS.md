# AdJudge Guardrails

## Enterprise AI Evaluation and Decision Operations

[AdJudge Guardrails](https://github.com/DenzelR12/adjudge-guardrails) is an enterprise reference implementation for auditing, governing, and operationalizing AI-assisted creative-quality review.

It addresses a practical deployment problem: a multimodal LLM can accelerate creative review, but a confident rating or rationale is not proof that it agrees with expert human judgment. AdJudge measures human–LLM disagreement and positivity bias, applies evidence and freshness controls, routes high-risk cases to people, and provides the operational context needed to investigate and resolve failures.

## Core capabilities

- Provenance-aware RAG that separates retrieved context from verified metric evidence.
- Versioned metric definitions, source snapshots, input hashes, freshness SLAs, and fail-closed verification states.
- Human-in-the-loop review routing based on confidence, disagreement risk, and metric trust status.
- Event lineage, source/data-contract checks, root-cause investigation, and blast-radius analysis.
- Human-approved remediation plans with explicit owners, risk, rollback, and success criteria.
- Tenant-scoped semantic analytics designed for parameterized, read-only SQL and fast dashboard/report generation.
- Enterprise control-plane concepts: data classification, access policy, auditability, experimentation, and cost awareness.

## Architecture

AdJudge is organized around five focused intelligence layers:

1. Knowledge Brain — grounded policy and documentation retrieval.
2. Metric Evidence Brain — freshness- and provenance-verified measurements.
3. Operations Forensics Brain — event timelines, evidence bundles, and hypotheses.
4. Remediation Planner Brain — constrained, human-approved action plans.
5. Customer Analytics Brain — tenant-safe search, dashboards, and reports.

Data-quality contracts, access governance, experiment evaluation, entity lineage, observability, and FinOps act as deterministic cross-cutting controls rather than autonomous agents.

## Source attribution

The initial benchmark uses a public evaluation dataset released by AdControlCenter and distributed through Hugging Face. AdJudge does not claim to have collected the source ads or produced the original annotations. Its original contribution is the enterprise operating layer: independent evaluation, provenance, governance, analytics, forensics, and remediation workflow design.

## Why it matters

The project demonstrates a solution-architect approach to enterprise AI: define the decision, make evidence and data lineage explicit, limit automated authority, preserve human accountability, measure outcomes, and build for safe operation across customers and data sources.
