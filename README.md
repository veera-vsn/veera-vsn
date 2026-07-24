# Hi, I'm Veera 👋

**AI Engineer — RAG systems, LLM agent security & applied ML** · MSc Artificial Intelligence @ National College of Ireland, Dublin (Sept 2026)

I build AI systems that survive contact with the real world — retrieval pipelines with measured hallucination rates, LLM agents with runtime security gates, and ML models validated on rare-event data. Every project here has an evaluation harness, a guardrail, or a human-in-the-loop checkpoint — usually all three.

🌐 **Portfolio:** [veera-vsn.vercel.app](https://veera-vsn.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/veera-vsn/) · ✉️ nargananani2000@gmail.com

---

## 🔨 What I'm building

### 🛡️ [RA-CapBAC](https://github.com/veera-vsn/ra-capbac) — Risk-Adaptive Security for Agentic AI *(MSc dissertation)*
A runtime risk-scoring gate that evaluates every LLM agent tool call before execution — combining semantic similarity, data-provenance trust and per-tool sensitivity.
**Cut prompt-injection attack success from 43.3% → 4.8%** across 187 adversarial cases on the AgentDojo benchmark, while preserving 63% of benign task completions (McNemar's test, p = 0.00024).

### 🔍 [RAGSentry](https://github.com/veera-vsn/RAGSentry) — Evaluation-Driven RAG Platform *(in active development)*
End-to-end RAG pipeline — ingest → chunk → embed → store → retrieve → generate → cite — benchmarked against the published **RAGBench** dataset, so retrieval failures and generation failures are measured separately, not vibes-checked.
BGE-M3 dense retrieval on PostgreSQL/pgvector (HNSW) · swappable Anthropic/OpenAI generation · grounding-enforced, citation-required prompting.

### 📋 [EvidenceOS](https://github.com/veera-vsn/EvidenceOS) — AI Compliance Copilot *(deployed — [live demo](https://evidenceos-web.vercel.app/))*
Production LLM pipeline extracting structured, confidence-scored fields from vendor contracts. AI inference is separated from compliance decisions: a **42-rule deterministic engine** validates every extraction, and human review is enforced before export.
FastAPI + Next.js + Supabase (RLS) on AWS + Vercel · **77 passing tests** · full LLM observability in Langfuse · GDPR / EU data-residency controls.

### 🌊 [Flood Early-Warning Prediction](https://github.com/veera-vsn/urban_flood_prediction_ML_comparision) — Rare-Event Time-Series ML
252,839-row pipeline from 30 years of sensor data, forecasting floods 6 hours ahead on a 1:19 imbalanced dataset.
LSTM: **0.942 ROC-AUC, 86.6% recall** — tuned for the safety-critical trade-off where a missed flood costs more than a false alarm.

---

## 🧰 Tools I work with

**ML / AI:** Python · PyTorch · scikit-learn · LLMs · RAG · prompt evaluation · guardrails · BGE-M3 · Langfuse
**Data & Infra:** PostgreSQL/pgvector · Supabase · FastAPI · Docker · AWS (IAM) · Next.js/TypeScript · Vercel
**From my enterprise years:** Entra ID · Conditional Access / Zero-Trust · PowerShell automation · Exchange Online at 10,000+ user scale

---

## 📍 Now

- 🎓 Completing my MSc in Artificial Intelligence in Dublin (Sept 2026) — dissertation on defending ReAct LLM agents against indirect prompt injection
- 🔭 Working through RAGSentry's roadmap: RAGAS/EM-F1 evaluation harness, Langfuse observability, hallucination guardrails
- 📄 Peer-reviewed publication: SSD Object Detection (JETIR)
- 🇮🇪 Open to AI/MLOps roles across Ireland — Stamp 1G Graduate Visa from Sept 2026, no sponsorship needed
