---
title: "Personalising intravenous to oral antibiotic switch decision making through fair interpretable machine learning"
authors:
  - William Bolton
  - Richard Wilson
  - Mark Gilchrist
  - Pantelis Georgiou
  - Alison Holmes
  - Timothy Rawson

date: "2024-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nature Communications"
publication_short: ""

abstract: Antimicrobial resistance (AMR) and healthcare associated infections pose a significant threat globally. One key prevention strategy is to follow antimicrobial stewardship practices, in particular, to maximise targeted oral therapy and reduce the use of indwelling vascular devices for intravenous (IV)administration. Appreciating when an individual patient can switch from IV to oral antibiotic treatment is often non-trivial and not standardised. To tackle this problem we created a machine learning model to predict when a patient could switch based on routinely collected clinical parameters. 10,362 unique intensive care unit stays were extracted and two informative feature sets identified. Our best model achieved a mean AUROC of 0.80 (SD 0.01) on the hold-out set while not being biased to individuals protected characteristics. Interpretability methodologies were employed to create clinically useful visual explanations. In summary, our model provides individualised, fair, and interpretable predictions for when a patient could switch from IV-to-oral antibiotic treatment. Prospectively evaluation of safety and efficacy is needed before such technology can be applied clinically.

# Summary. An optional shortened abstract.
summary: Fair and interpretable machine learning models for individualised antimicrobial stewardship decision-making.

tags:
  - AI
  - Machine Learning
  - Antibiotic Optimisation
  - Clinical Decision Support
  - Interpretability
  - Ethics

featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 'publication/ivos/Bolton.pdf'
url_code: 'https://github.com/WilliamBolton/iv_to_oral'
#url_dataset: ''
url_poster: 'Poster.pdf'
#url_project: ''
url_slides: 'Slides.pdf'
url_source: 'https://www.nature.com/articles/s41467-024-44740-2'
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
