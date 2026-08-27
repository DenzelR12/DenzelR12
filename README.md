# Denzel Robinson

AI and data engineer, willing to relocate. I build production data pipelines, agentic AI workflows, and the evaluation infrastructure that makes both trustworthy.

## What I work on

**Data platforms and pipelines.** Python and SQL ingestion from APIs and enterprise systems, with data quality gates, freshness monitoring, and fail-safe behavior designed in from day one. See [developer-ecosystem-insights](https://github.com/DenzelR12/developer-ecosystem-insights) for a working example built around developer platform telemetry.

**Agentic engineering workflows.** I run my own development with multi-agent AI workflows: agents that plan, write code, verify it against tests, and pass adversarial review gates before anything ships. The workflow is documented in the repo above.

**Applied ML research.** My VoxTree pipeline for the CZ Biohub Cell Tracking competition (Kaggle) processes 80+ GB of 4D light-sheet microscopy with a dual 3D U-Net ensemble, Kalman-filtered Hungarian matching, and GPU non-max suppression. Public leaderboard score: 0.873. The part I am proudest of is the local evaluation harness: it predicted a +0.033 leaderboard gain to three decimal places before submission, and a 22-test pytest suite caught a training bug that had silently capped recall for weeks.

**Analytics people can defend.** Metric definitions with explicit caveats, baselines captured before changes ship, and anomalies investigated before they ever reach an executive dashboard.

## Selected work

| Project | What it demonstrates |
|---|---|
| [developer-ecosystem-insights](https://github.com/DenzelR12/developer-ecosystem-insights) | API telemetry ingestion, data quality gates, freshness monitoring, and honest metric definitions for platform adoption analytics |
| clutchagent (private) | Multi-tenant AI and data platform: athlete valuation models on telemetry, gameplay, and social data, plus compliance automation |
| LTLinx automation (private) | AI content and engagement automation for a healthcare compliance SaaS, with A/B tested conversion funnels |

## Stack

Python, SQL, PyTorch, PySpark, Delta Lake, scikit-image, Zarr, Databricks-style workflows, Claude Code and multi-agent tooling

## Contact

denzel.robinson23@gmail.com | Willing to relocate
