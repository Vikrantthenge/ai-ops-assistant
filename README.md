# AI-Powered Operations Intelligence Assistant

A local Generative AI assistant built to explore whether a self-hosted LLM
could help with operational risk analysis and reporting — the kind of work
that's normally done manually by reading incident logs and writing summaries
for leadership.

🔗 **Project showcase:** https://vikrantthenge.github.io/ai-ops-assistant

## What it was

A fully local AI pipeline — no cloud APIs, no external calls. Everything ran
in Docker containers on my own machine:

- **Ollama** — running the LLM locally
- **Open WebUI** — Docker-hosted chat interface to query the model
- **Prompt engineering** — structured prompts for risk analysis, KPI
  assessment, and executive-style summarization, built around aviation
  safety and operational datasets

## Why I built it

20+ years in airline operations means a lot of time spent reading incident
reports, performance data, and audit notes, then turning that into a summary
someone in leadership can actually use. I wanted to see how much of that
first pass an LLM could realistically help with, running entirely on local
hardware with no data leaving the device.

## What happened

It worked — the model could take operational data and produce reasonable
draft summaries and flag recurring patterns when prompted well. But running
a local model alongside Docker and Open WebUI pushed past what my 8GB RAM
laptop could handle at a usable speed, so I decommissioned the setup to free
up the system. I don't have the original session logs or screenshots from
that point — the showcase page describes the approach and architecture
rather than reproducing a specific session.

## Stack

`Ollama` · `Docker` · `Open WebUI` · `Generative AI` · `Prompt Engineering`

## Background

## Background

Built by Vikrant Thenge, drawing on 20+ years in airline operations across All Nippon Airways, Garuda Indonesia, and Uganda Airlines, with a current focus on operations analytics and decision-support systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-View_Projects-24292F?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Vikrantthenge/vikrant-portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/vthenge)
[![Email](https://img.shields.io/badge/Email-Contact_Me-0078D4?style=for-the-badge\&logo=microsoftoutlook\&logoColor=white)](mailto:vikrantthenge@outlook.com)

