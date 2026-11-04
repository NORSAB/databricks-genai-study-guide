# GenAI Engineering with Databricks: Study Guide (Modules 0 to 6)

[![Databricks](https://img.shields.io/badge/Databricks-GenAI%20Engineering-FF3621?logo=databricks&logoColor=white)](https://www.databricks.com/)
[![Qualtop Brand Ambassador](https://img.shields.io/badge/Qualtop-Brand%20Ambassador-E83808)](https://qualtop.com/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

A practical architecture manual and exam-preparation guide covering Foundation Model APIs, Medallion RAG pipelines, Vector Search, Mosaic AI Agents, LangGraph orchestration, RAG Triad evaluation, and AI Gateway governance.

Developed as part of the **Qualtop Brand Ambassadors Program (Q4 2026)** by **Norman Sabillón**.

---

## 📥 Direct Downloads

| Format | File | Best for |
|---|---|---|
| **EPUB** | [📥 Download `guide.epub`](https://github.com/NORSAB/databricks-genai-study-guide/releases/download/v1.0.0/guide.epub) | Kindle, iPad, Apple Books, Kobo, Android e-readers |
| **PDF** | [📥 Download `guide.pdf`](https://github.com/NORSAB/databricks-genai-study-guide/releases/download/v1.0.0/guide.pdf) | PC, Desktop reading, High-resolution print (49 pages) |

---

## 📖 Architecture & Modules Overview

```
├── Module 0: Foundations & the Exam Blueprint
├── Module 1: Prompt Engineering & Model APIs
├── Module 2: RAG Architecture & Ingestion (Medallion Pipeline)
├── Module 3: Building Agents with Mosaic AI (ReAct Loop)
├── Module 4: Orchestration, Memory & Multi-Agent State
├── Module 5: Evaluating GenAI Applications (RAG Triad & LLM Judges)
├── Module 6: Security, Guardrails & Governance (4 Defense Layers)
└── Reference: Exam Cheat Sheet, Glossary & Self-Check Solutions
```

### Key Technical Architecture Highlights:
- **Medallion Ingestion for RAG:** Ingestion pipeline pattern from raw files (Bronze) to clean layout-aware parsed documents (Silver) and tokenized chunks with Delta Change Data Feed (Gold) syncing Mosaic AI Vector Search automatically.
- **Unified Unity Catalog Perimeter:** Single security boundary governing model serving endpoints, external model providers, Vector Search indexes, and Python/SQL callable tools.
- **Mosaic AI Agent Execution:** ReAct execution loops with strict recursion guardrails and MLflow tracing hierarchies.
- **Diagnostic RAG Evaluation Triad:** Decoupling retriever evaluation (*Context Relevance*) from generator hallucination (*Groundedness*) and intent satisfaction (*Answer Relevance*).
- **Four-Layer Defense-in-Depth:** Input validation, tool authorization via Unity Catalog, PII egress filtering, and Delta Lake inference tables.

---

## 👨‍💻 About the Author

**Norman Sabillón** is an Enterprise Data Architect and Artificial Intelligence specialist with a background spanning electrical engineering, applied mathematics, and machine learning systems. He holds an M.Sc. in Mathematics and Statistics from UNAH, an M.Sc. in Big Data from UNIR, and is currently completing his Ph.D. in Artificial Intelligence at UNADE.

His enterprise practice focuses on visual analytics, modern Lakehouse systems, and executive decision intelligence in multilateral banking architectures. Approaching his first full year as a **Qualtop Brand Ambassador**, Norman is committed to sharing production-tested engineering resources to elevate regional engineering talent.

Beyond engineering, Norman has practiced traditional Kung-Fu and Wushu for over **21 years**, serving on the coaching staff supporting the **Honduras National Wushu Kung-Fu Team** in traditional **Hung Gar (洪家拳)**.

---

## 📄 License & Attribution

Authored by **Norman Sabillón** for the **Qualtop Brand Ambassadors Program**.  
Distributed under Creative Commons [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
