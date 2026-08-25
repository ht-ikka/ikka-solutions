# IKKA Demo

This folder contains public demo materials for IKKA.

IKKA is a governed AI decision infrastructure initiative for manufacturing and engineering environments.

These videos are hosted as Google Drive links and show the current product thesis, early system behavior, and demo workflows.

---

## Demo Videos

### 1. Founder Notes

A short founder video covering the broader origin story and vision behind IKKA.

[Watch Founder Notes](https://drive.google.com/file/d/1nN3HChjqATKgE-yzWrfFmknbiQqyQd0a/view?usp=sharing)

---

### 2. IKKA Intro — Terminal-Based Overview

A terminal-based walkthrough introducing the IKKA architecture, governed execution concept, and how the system is intended to process manufacturing and engineering questions.

[Watch IKKA Intro](https://drive.google.com/file/d/1kJHAAXhUQ_-OIpbjMvGXcsqDX6UQtupU/view?usp=sharing)

---

### 3. IKKA GPT — Local Evidence Retrieval

A use-case demo showing IKKA operating through a Custom GPT interface using a local evidence pack.

The demo highlights governed responses, evidence-backed reasoning, refusal behavior, and traceable outputs for manufacturing and quality-related workflows.

[Watch IKKA GPT Local Evidence Retrieval](https://drive.google.com/file/d/1eiHmfYaDOdTIPmhKdm_3I2LbRFFmtLwL/view?usp=sharing)

---

### 4. IKKA GPT — RAG Retrieval

A use-case demo showing IKKA operating through a Custom GPT interface with Onyx-backed retrieval activated.

The demo focuses on customer-specific requirement questions and shows how IKKA grounds responses in retrieved source material rather than relying on unrestricted AI generation.

[Watch IKKA GPT RAG Retrieval](https://drive.google.com/file/d/1YvUpKMLAuzdBLOE6JSYzP875bcpoCNg_/view?usp=sharing)

---

### 5. IKKA GPT — Controlled LLM Synthesis

A Custom GPT use-case demo showing IKKA with Onyx-backed retrieval and controlled LLM synthesis enabled.

The demo uses real manufacturing and quality scenarios to show how IKKA can resolve structured enterprise context deterministically, retrieve authoritative requirements when needed, synthesize across relevant evidence, and withhold conclusions when the required source-of-truth evidence is unavailable.

Representative workflows include program handoff, production abnormalities, customer complaints, launch-readiness review, and governed evidence refusal.

[Watch IKKA GPT Controlled LLM Synthesis](https://drive.google.com/file/d/1LbtMUP5tDywzR0YwuZDye-7Fuqnz3TEb/view?usp=sharing)

---

## Demo Snapshot

The current public demo set includes:

* Founder vision / application video
* Terminal-based system overview
* Local Evidence Retrieval / Custom GPT use-case demo
* RAG Retrieval / Onyx-backed retrieval demo
* Controlled LLM Synthesis / Onyx-backed retrieval and synthesis demo

Across the demos, IKKA demonstrates:

* Deterministic resolution from structured enterprise context
* Local evidence-pack retrieval
* Onyx-backed retrieval from standards and customer requirements
* Controlled LLM synthesis over retrieved evidence
* Clarification and governed refusal behavior
* Explicit disclosure when available evidence does not support a conclusion
* Traceable execution paths, sources, confidence, and risk

The broader workflow demonstrated is:

**Know the organization → find the governing evidence → synthesize what matters → refuse what cannot be supported.**

## Demo KPI Snapshot

Current results across the public demos:

- **Public demo baseline questions:** 14 across Local Evidence Retrieval and Onyx RAG Retrieval
- **Evidence modes demonstrated:** Structured enterprise context, local evidence-pack retrieval, and Onyx-backed source-of-truth retrieval
- **Controlled LLM synthesis:** Live and successfully demonstrated with Onyx-backed retrieval
- **Selective LLM use:** Deterministic enterprise-context queries can resolve without invoking LLM synthesis
- **Historical Onyx RAG success rate:** 4 / 4
- **Representative controlled-synthesis confidence:** 0.98–1.00
- **Average historical Onyx RAG confidence:** 0.965
- **Average historical Onyx RAG response time:** 1.13 seconds
- **Average local evidence-backed confidence:** 1.00
- **Average local evidence-backed retrieval time:** 58.5 ms
- **Inspection records surfaced:** 135
- **Local evidence formats represented:** JSON, CSV, Markdown
- **Enterprise evidence demonstrated:** Project context, inspection records, product specifications, launch evidence, APQP guidance, IATF-related requirements, and OEM customer-specific requirements
- **Gate behaviors demonstrated:** Deterministic resolution, clarification, governed refusal, evidence retrieval, and controlled evidence synthesis
- **Governance behaviors demonstrated:** Out-of-domain rejection, clarification, no-evidence refusal, compliance-certification refusal, missing-evidence disclosure, and authoritative-source withholding
- **Governed evidence boundary:** IKKA withheld Toyota-specific requirements when no authoritative Toyota CSR was available in the connected evidence rather than substituting another OEM requirement
- **Work compressed:** Program context lookup, inspection review, statistical review, launch readiness, customer-requirement retrieval, manufacturing-event response, cross-requirement synthesis, and first-pass decision framing
- **Current maturity:** MVP / pilot-development demo; results are functional demonstrations rather than audited production benchmarks
- **Onyx model / provider:** Claude Sonnet 4.6 via Anthropic
- **Latest controlled-synthesis test-day spend:** Approximately $0.89 while exercising multiple governed retrieval and synthesis scenarios across Program Management, Quality, Process Engineering, and Operations use cases
