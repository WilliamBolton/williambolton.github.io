---
title: "AGE-nt: intervention intelligence for aging"
summary: "Berlin Bio × AI Hackathon finalist: an agentic system that retrieves, synthesises and grades scientific evidence on ageing interventions."
tags:
  - AI
  - Agents
  - Demo

authors:
  - William Bolton
  - Jonathan Hedley
  - Anda-Raluca Epure
  - Maryam Ghareghani

date: "2026-02-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: "Smart"

url_code: "https://github.com/WilliamBolton/AGE_nt"
url_slides: "slides.pdf"
url_video: "demo.mp4"
---

AGE-nt aggregates data from 11 sources (PubMed, clinical trials, grants, patents and more), normalises the documents into a unified schema, and exposes reasoning tools for evidence grading, trajectory analysis and gap identification through an MCP server, so any LLM client can connect to it.

AGE-nt was built in 24 hours for the [Berlin Bio × AI Hackathon](https://www.biohack.berlin/) (27–28 February 2026), organised by Nucleate Germany, and was selected for the final pitch showcase.

The core idea is that the data layer is the product: agents can only reason well about ageing interventions if the evidence from papers, trials, grants and patents is retrieved, normalised and graded in a consistent way. AGE-nt provides that layer together with tools for grading evidence, tracking how an intervention's evidence base has evolved over time, and identifying gaps.

Built with Python, FastAPI, FastMCP and a React/TypeScript frontend.
