---
title: Machine learning based clinical decision support for individualised antibiotic side effect prediction
summary: 'Supervised masters student project'
tags:
  - AI
  - Machine Learning
  - Clinical Decision Support

authors:
  - William Bolton
  - Vasileios Stylianos Sotiropoulos
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
url_pdf: 'project/side_effect/side_effect_prediction.pdf'
#url_slides: ''
#url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

In this study, we present a machine learning-based clinical decision support system for the individualised prediction of Acute Kidney Injury (AKI) following a Vancomycin with Piperacillin-Tazobactam (VPT) ad- ministration. AKI can be a critical side effect associated with the use of antibiotics, particularly in severely ill patients. Consequently, from a clinical perspective, being able to accurately predict the risk of AKI on an individual patient basis can contribute significantly to the decision making process by supporting decisions such as initiation and cessation of treatment as well as frequency of monitoring.

Our work uses a series of machine learning algorithms based on the electronic health records (EHR) of all the patients who were administered VPT in order to develop a predictive model for AKI. Taking into account that their corresponding explicit diagnoses stored are lacking timestamps and therefore cannot be evaluated in terms of reliability, it includes the development of an implicit label generation algorithm that can be used to produce accurate and detailed diagnostic information based on KDIGO AKI guidelines.

After applying a wide range of filters and experimenting with several data configurations, a comprehensive dataset was formed by incorporating patient demographics, medical history, and laboratory values and was used to train and evaluate our selection of algorithms. The final results obtained with our best performing model indicated a high level of effectiveness for our binary classifier in predicting the occurrence of AKI following a VPT administration. Specifically, an AUC estimation of ≈ 0.83 was achieved using a trained logistic regression model and 10-fold cross validation. This demonstrates a balanced trade off between sen- sitivity and specificity and showcases the model’s strong ability in distinguishing between the two classes.

In order to ascertain the validity of our results, a second EHR database was utilised. This indicated a consistency in the performance attained and consequently verified the generalisability of our model. As a result, we can conclude that the use of our suggested model could provide credible information to clinicians regarding potential side effects from antibiotic prescribing, enabling them to make informed decisions and optimise their use.
