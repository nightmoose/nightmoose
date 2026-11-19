# NightMoose

Software and data engineering from Orange City, Florida. We build data pipelines and AI features where code checks the output before anyone relies on it.

[nightmoose.com](https://nightmoose.com)

## Products

- **[DataContractGate](https://github.com/nightmoose/contractgate)**: checks data against a contract at every pipeline boundary (ingest, between stages, egress). Open-source Rust gateway, MIT. [datacontractgate.com](https://datacontractgate.com)
- **AISchemaGate**: the same idea for LLM output. Structured responses are checked against a contract, then repaired or quarantined. [aischemagate.com](https://aischemagate.com)

## Hackathon work

- **[SchemaSmith](https://github.com/nightmoose/schemasmith)** (Lexsi AI Safety & Alignment Hackathon, selected for the final stage as one of 20 teams): Tiny Aya fine-tuned with LoRA SFT and DPO for contract-valid ticket extraction in eight languages. Made-up values fell from 32.9% to 0% on held-out tickets; the README also lists what still fails.
- **[LineageGate](https://github.com/nightmoose/lineagegate)** (FalkorDB Graph Hacks): an agent over a lineage and data-contracts graph that answers "what breaks if this column changes?". [Live demo](https://lineagegate.fly.dev)
- **[Pipeline Medic](https://github.com/nightmoose/pipeline-medic)** (Meta Global AI Developer Hackathon): diagnoses a failing dbt job on Airflow, verifies a fix in a sandbox, and drafts a PR.
- **[vultr-csv-fixer](https://github.com/nightmoose/vultr-csv-fixer)** (Vultr Agent Rush): model-written CSV repairs run in a no-network Docker sandbox, and output ships only after DataContractGate validators pass.
- **[MorningDrop](https://github.com/nightmoose/morningdrop)** (DEV Hacktoberfest AI, week 3): overnight local data checks with a Gemma summary that AISchemaGate checks.
- **[Ghostlog](https://github.com/nightmoose/ghostlog)** (DEV Hacktoberfest AI, week 4): offline sqlglot lineage for dead pipelines, with a local Gemma model.
- **[TasteProof](https://github.com/nightmoose/tasteproof)** (Qloo Agentic Hackathon): a planner that has to cite Qloo evidence for every recommendation.
- **[dbt Shepherd](https://gitlab.com/gitlab-ai-hackathon/transcend-october-2026/43776816/showcase)** (GitLab Transcend, on GitLab): GitLab Duo agents turn a one-line data request into a tested dbt model.

## Other open source

- **[ClankerSpanker](https://github.com/nightmoose/ClankerSpanker)**: a local-first control plane for coding agents.
- **[Markus](https://github.com/nightmoose/Markus)**, **[Keyline](https://github.com/nightmoose/Keyline)**, **[Whistler](https://github.com/nightmoose/Whistler)**: small native apps.
