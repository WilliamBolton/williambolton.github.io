---
title: Prescription Agent Demo
summary: 'Demo of an automated way to manage and respond to patients queries and messages.'
tags:
  - Demo
  - AI
  - Entrepreneurship

authors:
  - William Bolton

date: "2024-04-01T00:00:00Z"

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
url_code: 'https://github.com/WilliamBolton/prescription_app'
#url_pdf: 'project/readmission/readmission_prediction.pdf'
#url_slides: ''
#url_video: 'https://youtu.be/Qc0sKRBOwfU'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

A Django REST API that acts as a message-handling agent for patient communications. Each sentence of an incoming patient message is classified into a request type, such as appointment scheduling, prescription renewal or lab-test interpretation, using regular-expression patterns first and falling back to an LLM when the pattern match is uncertain. Where a recognised request type is found, the agent drafts a suggested response for a clinician to review, and every request and response is logged for record-keeping.

The API accepts a patient name, an optional recipient and a list of message strings, and returns the detected request types, the method used to classify them and an example drafted reply. Built with Django REST Framework, NLTK and the OpenAI API.
