---
title: Deep Learning for Individualised Antibiotic Readmission Prediction
summary: 'Supervised masters student project'
tags:
  - AI
  - Deep Learning
  - Clinical Decision Support

authors:
  - William Bolton
  - Boon Liang Wong
  - Pantelis Georgiou

date: '2023-06-21T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
#url_code: ''
url_pdf: 'project/readmission/readmission_prediction.pdf'
#url_slides: ''
#url_video: ''

# Is this a featured project? (true/false)
featured: False

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Antimicrobial resistance (AMR) is one of the leading causes of death worldwide. In 2019, bacterial AMR was found to be associated with approximately 4.95 million of deaths across 204 countries with 1.2 million of them directly attributed to it. Misuse and overuse of antibiotics are significant drivers in the development of AMR. To deal with AMR, a multi-modal approach is needed including antimicrobial stewardship to preserve the ef- fectiveness of currently available agents. Recent research has focused on using electronic health records (EHRs) for infection diagnoses and antibiotic therapy selection through machine learning (ML), but little work has focused on antimicrobial stewardship. Inade- quate, ineffective or incomplete antibiotic treatment often leads to antibiotic retreatment (antibiotic readmission), causing unnecessary and excessive use of antibiotics.

This project applied electronic health records of 2,189 intensive care unit (ICU) patients from the MIMIC-IV database to develop ML-based decision support models using deep learning approach to reliably predict whether ICU patients will be retreated with antibiotic if current antibiotic treatment is discontinued. This project is formulated and addressed as both classification and regression tasks. Accurately predicting antibiotic readmission (antibiotic retreatment) for ICU patients could be extremely helpful in optimising antibiotic treatment to combat AMR by providing individualised predictions to support the decision on continuation or cessation of antibiotic treatment.
