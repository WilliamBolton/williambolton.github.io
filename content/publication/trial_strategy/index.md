---
title: 'Learning Clinical-Trial Strategy: Offline Policy Training for Decision Agents'

authors:
  - William Bolton
  - Philip Torr

date: '2026-07-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type (CSL standard).
publication_types: ['paper-conference']

publication: In *ICML 2026 Workshop on Generative and Agentic AI for Biology (GenBio)*, spotlight. Also presented as a poster at the *ICML 2026 Workshop on Decision-Making from Offline Datasets to Online Adaptation*.
publication_short: In *ICML 2026 GenBio Workshop* (spotlight)

abstract: "Clinical development is sequential decision-making under uncertainty, where a sponsor must plan a portfolio of experiments from heterogeneous evidence. We study this setting by framing oncology clinical development as an offline decision-making problem in which an agent predicts the next six-month trial portfolio of an oncology drug program from information available at the decision date. To support this, we construct a temporal dataset that combines 31.7k heterogeneous public data records, including trial registries, regulatory reviews, sponsor filings, utilization data, and epidemiology, into 881 offline decision episodes across 45 historical programs. We compare four offline objectives: behavioral cloning, reward-weighted behavioral cloning, learned-reward training, and value-based implicit Q-learning against four frontier LLM agents that share a common date-gated retrieval scaffold across held-out drug, sponsor, drug-class, and temporal splits. Models trained offline outperform the non-fine-tuned baselines, particularly in the post-August 2025 contamination-clean hold-out. Reward-weighted behavioral cloning performs the best, obtaining 46.2% indication F1 and 14.2% strict F1 against 25.0% and 2.1%, respectively, for the best-performing tool agent on each metric. These results suggest that structured offline learning can teach agents to plan clinical experiments."

# Summary. An optional shortened abstract.
summary: "Framing oncology clinical development as an offline decision-making problem, where an agent predicts the next six-month trial portfolio of a drug programme from information available at the decision date. Built on a temporal dataset of 31.7k public records turned into 881 decision episodes across 45 historical programmes, used to train offline policies and compare them against frontier LLM agents on held-out drug, sponsor, drug-class and temporal splits."

tags:
  - AI
  - Agents
  - AI Scientists
  - Large Language Models
  - Clinical Trials

# Display this page in the Featured widget?
featured: true

url_code: 'https://github.com/WilliamBolton/clinical-trial-strategy-agents'
url_dataset: 'https://huggingface.co/datasets/WillBolton/oncology-trial-strategy'
url_pdf: 'publication/trial_strategy/trial_strategy.pdf'
url_poster: 'poster.pdf'
url_source: 'https://arxiv.org/abs/2608.03606'

image:
  focal_point: ''
  preview_only: false
---
