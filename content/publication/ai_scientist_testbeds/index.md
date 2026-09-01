---
title: 'Adversarial Fast-Moving Real-World Domains as Test Beds for Benchmarking AI Scientist Capabilities'

authors:
  - William Bolton
  - Philip Torr

date: '2026-07-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type (CSL standard).
publication_types: ['paper-conference']

publication: In *ICML 2026 Workshop on AI for Science*
publication_short: In *ICML 2026 AI for Science Workshop*

abstract: "Benchmarking the ability of AI scientists to generate novel ideas is notoriously difficult. Existing benchmarks in this field have made progress in evaluating scientific reasoning and research replication, but often rely on synthetic tasks or retrospective targets, which may be confounded by prior exposure. We hypothesize that complex, adversarial, fast-moving real-world domains where expert practitioners independently generate observable outputs can provide a practical solution to fill this gap and evaluate the capabilities needed for AI scientists, including reasoning, novelty, and hypothesis formulation. We instantiate this framework in two structurally different domains, Formula 1 (F1), where models ideate around car design concepts for the 2026 season, and real pre-season innovations provide a ground truth, and Magic: The Gathering (MTG), where models propose decks from a recently updated card pool and are evaluated against 19 Pro Tour (PT) decklists. Across both domains, models produce plausible outputs, but few align with real-world expert solutions. In F1, the best model, GPT-5.2 matched 10 of 40 real innovations with 166 ideas proposed across runs. In MTG, the best deck from Gemini 3 Flash recovered 5 of 7 new-set cards from the third-place PT deck, and across all 108 decks, the cards models selected most often were also the cards most widely adopted by PT decks (Spearman ρ = 0.74, p = 0.0003). These results suggest that a key capability gap for AI scientists is not idea generation, but filtering, prioritization, and coherent novelty."

# Summary. An optional shortened abstract.
summary: "A framework for benchmarking AI scientist capabilities using adversarial, fast-moving real-world domains, where expert practitioners independently produce observable ground truth after an information cutoff. Instantiated in Formula 1 car design for the 2026 regulations and Magic: The Gathering deck building, with frontier models ideating from pre-cutoff information only and their outputs scored against real innovations and Pro Tour decklists."

tags:
  - AI
  - Agents
  - AI Scientists
  - Large Language Models

# Display this page in the Featured widget?
featured: true

#url_code: ''
url_pdf: 'publication/ai_scientist_testbeds/ai_scientist_testbeds.pdf'
links:
  - name: Code (F1)
    url: 'https://github.com/WilliamBolton/f1-ai-scientist-paper'
  - name: Code (MTG)
    url: 'https://github.com/WilliamBolton/mtg-AI-scientist-paper'
url_poster: 'poster.pdf'
url_source: 'https://arxiv.org/abs/2608.03569'

image:
  focal_point: ''
  preview_only: false
---
