---
title: "CosmosPapers -- AI Research Discovery Platform"
excerpt: >-
  A full-stack AI research discovery platform indexing 54K+ papers from 15+
  top-tier conferences with semantic search, pgvector retrieval, AI Copilot Q&A,
  summarization, BibTeX generation, recommendations, and topic-trend analytics.
collection: portfolio
permalink: /portfolio/cosmospapers/
order: 1
---

CosmosPapers was the Microsoft x TD SYNNEX AI Agents winning project at
CUHackit 2026. It is a full-stack AI research discovery platform for finding,
summarizing, and reasoning over papers from major AI, ML, computer vision,
security, HCI, and visualization conferences.

<p>
  <a class="btn btn--primary" href="https://cosmospapers.com/">Live Demo</a>
  <a class="btn" href="https://github.com/RunWang123/cosmospaper">GitHub</a>
  <a class="btn" href="#architecture">Architecture</a>
</p>

## Problem

Researchers waste time searching across fragmented conference proceedings,
PDFs, and publication pages. The work is repetitive, hard to personalize, and
often disconnected from semantic search, summarization, citation management, and
trend analysis.

## My Contributions

- Built backend retrieval and ingestion components for semantic paper search.
- Implemented PostgreSQL/pgvector-based vector similarity search.
- Engineered multithreaded scraping and ingestion pipelines.
- Integrated AI Copilot workflows for summarization, Q&A, BibTeX generation,
  and recommendations.
- Helped deploy a full-stack system using FastAPI, Next.js,
  PostgreSQL/pgvector, Docker, and cloud infrastructure.

## Architecture

CosmosPapers ingests conference paper metadata and PDFs through scraping and
normalization pipelines, generates embeddings, stores vectors in
PostgreSQL/pgvector, and serves semantic search and Copilot workflows through a
FastAPI backend. The Next.js frontend exposes paper search, recommendations,
topic trends, Q&A, summaries, and BibTeX generation.

## Technical Highlights

- 54K+ papers
- 15+ conferences
- PostgreSQL + pgvector
- FastAPI backend
- Next.js frontend
- BERTopic trend analytics
- LiteLLM provider routing for NVIDIA NIM and Microsoft AI Foundry
- Dockerized deployment

## Results / Scale

- Indexed a production-scale academic corpus spanning 54K+ papers from 15+
  top-tier conferences.
- Combined semantic retrieval, AI Copilot workflows, paper recommendations, and
  topic-trend analytics in one recruiter-demoable product.
- Built a practical GenAI/RAG system that connects ingestion, vector retrieval,
  backend APIs, frontend UX, and cloud deployment.

## Links

<p>
  <a class="btn btn--primary" href="https://cosmospapers.com/">Live Demo</a>
  <a class="btn" href="https://github.com/RunWang123/cosmospaper">GitHub</a>
  <a class="btn" href="#architecture">Architecture</a>
</p>

<!--
TODO: Add static screenshots under /images/projects/, then embed them here.
Suggested files:
- /images/projects/cosmospapers-search.png
- /images/projects/cosmospapers-copilot.png
- /images/projects/cosmospapers-trends.png

Screenshots should show the indexed production dataset and Copilot workflows so
the portfolio remains strong if the live demo temporarily shows 0 papers because
of API or loading issues.
-->
