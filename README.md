# GenAI Engineering with Databricks: Study Guide (Modules 0 to 6)

[![Databricks](https://img.shields.io/badge/Databricks-GenAI%20Engineering-FF3621?logo=databricks&logoColor=white)](https://www.databricks.com/)
[![Qualtop Brand Ambassador](https://img.shields.io/badge/Qualtop-Brand%20Ambassador-E83808)](https://qualtop.com/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

I wrote this 49-page practical guide while preparing for the Databricks Generative AI Engineer certification. Most resources online focus on basic prompt tricks or surface-level summaries, but production systems usually break down at data ingestion, tool governance, or evaluation.

This guide walks through the complete architecture across all seven official modules, from raw document ingestion to multi-agent state coordination.

Authored as part of the Qualtop Brand Ambassadors Program (Q4 2026) by Norman Sabillon.

---

## Downloads

Grab the format that fits your reading setup:

- [Download EPUB](https://github.com/NORSAB/databricks-genai-study-guide/releases/download/v1.0.0/guide.epub) for Kindle, iPad, Apple Books, Kobo, and phone readers.
- [Download PDF](https://github.com/NORSAB/databricks-genai-study-guide/releases/download/v1.0.0/guide.pdf) for desktop reading and full-bleed print.

---

## What This Guide Covers

The guide is organized into seven core chapters and a quick-reference section:

1. **Foundations and Exam Blueprint (Module 0):** Token math, cost modeling, and when to fine-tune versus use RAG.
2. **Prompt Engineering and Model APIs (Module 1):** Structured outputs, JSON schemas, chaining strategies, and prompt injection defenses.
3. **Medallion Ingestion for RAG (Module 2):** Document parsing, chunking trade-offs, and streaming Delta tables into Vector Search via Change Data Feed.
4. **Building Agents with Mosaic AI (Module 3):** ReAct loops, governing tool permissions with Unity Catalog, and MLflow trace spans.
5. **Multi-Agent Orchestration and State (Module 4):** Supervisor routing, state store isolation, and checkpoint recovery with Delta Lake.
6. **Evaluating GenAI Applications (Module 5):** The RAG Triad (Context Relevance, Groundedness, Answer Relevance) and building automated judge suites with MLflow Evaluate.
7. **Production Security and Guardrails (Module 6):** Four layers of defense covering input sanitization, least-privilege tool execution, and PII egress filtering.
8. **Reference Material:** An exam cheat sheet, concise glossary, and worked scenario answers.

---

## About the Author

Norman Sabillon is an Enterprise Data Architect and AI specialist working in multilateral banking and enterprise analytics. He holds master's degrees in Mathematics and Statistics (UNAH) and Big Data (UNIR), and is completing doctoral research in Artificial Intelligence at UNADE.

As a Qualtop Brand Ambassador, he focuses on publishing open technical resources that bridge software engineering and mathematical rigor.

Outside tech, Norman has practiced traditional Kung-Fu and Wushu for over 21 years, coaching with the Honduras National Wushu Kung-Fu Team in traditional Hung Gar.

---

## License

Authored by Norman Sabillon for the Qualtop Brand Ambassadors Program.  
Shared under Creative Commons [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
