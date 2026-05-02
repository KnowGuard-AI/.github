<img src="KGAI - Logo - HighRes - 4K.png" alt="KnowGuard AI" width="1000">

# KnowGuard AI

**The Enterprise Memory OS.**

We prevent financial leakage before money leaves the building.

---

## What we do

Enterprises lose 0.8–2% of annual spend through duplicate payments, rate drift, missed credits, and contract non-compliance. For a $400M-spend company that's $4–8M out the door every year. Existing tools (recovery audit firms, AP detectors) are exact-match rule engines that miss everything contextual.

KnowGuard ingests invoices, contracts, rate cards, PO data, and historical AP records, then reasons over them semantically with full provenance. Every flag links back to the exact contract clause and invoice line that triggered it.

Our v0.5 production kernel found **$8M of recoverable leakage on $401M of invoice data in 24 hours** during an MVP audit.

---

## How we're different

The category sits on a stateless detection layer. We sit on a memory substrate.

Every transaction analysed enriches a queryable knowledge graph. Every future detection runs against accumulated context. The architecture is designed around how biological memory actually works — fast episodic capture and slow semantic consolidation operating on different timescales — rather than around static rules and per-document scoring.

Financial leakage prevention is the wedge. The platform is the cognitive infrastructure layer for the autonomous enterprise.

---

## What lives in this org

Most of our codebase is private. The repos here are sidecar tools, integration SDKs, and developer-facing utilities we choose to open-source.

- **[HotMem](https://github.com/KnowGuard-AI/HotMem)** — Local-first memory sidecar for agent applications. One SQLite DB, one HTTP port, zero config. Any directory becomes portable agent memory.

More to come as we open-source pieces of the platform that have value beyond our specific deployments.

---

## Stack

NVIDIA NIM microservices for self-hosted LLM inference. Python, FastAPI, PostgreSQL on the application layer. Hybrid vector + graph store for the memory substrate. Containerised, deployable to VPC, on-prem, or air-gapped environments. Confidential compute on roadmap.

We are an [NVIDIA Inception](https://www.nvidia.com/en-us/startups/) member. Backed by AWS Activate and Google Cloud.

---

## Built by

A small founding team across Belgium and Germany. We work with enterprises that take their AP, procurement, and compliance data seriously, and with engineers who want to build infrastructure that compounds rather than commoditises.

If either of those describes you, we'd like to hear from you: **hello@knowguardai.com** · [knowguardai.com](https://knowguardai.com)
