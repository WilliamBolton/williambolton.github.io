---
title: "et al."
summary: "Building the interface for agent-driven science: a personalised discovery feed and self-improving knowledge base for researchers and their agents."
tags:
  - AI
  - Agents
  - AI Scientists
  - Entrepreneurship

authors:
  - William Bolton
  - Thomas Lynch

date: "2026-05-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# Left empty so the project has its own page (with the launch video); the website
# is linked via the button below instead.
external_link: ""

image:
  focal_point: "Smart"

links:
  - icon: link
    icon_pack: fas
    name: Website
    url: 'https://etal.co'
url_video: "https://lnkd.in/p/eRjBtqpc"
---

et al. starts as a personalised discovery feed and self-improving knowledge base for researchers and their agents. Researchers connect their papers, notes and research tools; et al. indexes this knowledge and turns it into working memory for agents. In return, the agents help the researcher reason across papers, generate citations in any journal format, and surface relevant new literature, hypotheses and experimental methods.

Users can import an existing library or save papers, datasets and code repositories as they browse, with a Chrome extension that captures any webpage in one click. They can then read these materials in the app, ask the agent questions about a single paper or their entire library, and receive suggestions of new work based on what they are reading. Every answer is grounded in the user's own sources, so each claim can be traced back to the passage it came from.

Behind this sits a metadata ingestion pipeline that resolves records across multiple sources and extracts equations from LaTeX, with OCR and vision fallbacks for scanned documents. Citations can be inserted directly into Google Docs, Word and Overleaf through the Word add-in and browser extension, and a remote MCP server lets an external coding agent query a researcher's library directly.

I also built a reference checker that verifies whether the citations in a paper are correct and actually support the claims made about them: it parses the bibliography, infers the citation style, resolves each reference and checks every claim against the original source.

By capturing what researchers read, save, ask and eventually test, the platform builds a data flywheel: it improves each user's view of the scientific frontier while gathering the workflow traces needed to train and evaluate scientific agents. Launched in May 2026 and publicly accessible, with around 2,000 people trying the product.
