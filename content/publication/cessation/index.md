---
title: "Machine learning and synthetic outcome estimation for individualised antimicrobial cessation"

authors:
  - William Bolton
  - Timothy Rawson
  - Bernard Hernandez
  - Richard Wilson
  - David Antcliffe
  - Pantelis Georgiou
  - Alison Holmes

date: "2022-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Digital Health"
publication_short: ""

abstract: The decision on when it is appropriate to stop antimicrobial treatment in an individual patient is complex and under-researched. Ceasing too early can drive treatment failure, while excessive treatment risks adverse events. Under- and over-treatment can promote the development of antimicrobial resistance (AMR). We extracted routinely collected electronic health record data from the MIMIC-IV database for 18,988 patients (22,845 unique stays) who received intravenous antibiotic treatment during an intensive care unit (ICU) admission. A model was developed that utilises a recurrent neural network autoencoder and a synthetic control-based approach to estimate patients’ ICU length of stay (LOS) and mortality outcomes for any given day, under the alternative scenarios of if they were to stop vs. continue antibiotic treatment. Control days where our model should reproduce labels demonstrated minimal difference for both stopping and continuing scenarios indicating estimations are reliable (LOS results of 0.24 and 0.42 days mean delta, 1.93 and 3.76 root mean squared error, respectively). Meanwhile, impact days where we assess the potential effect of the unobserved scenario showed that stopping antibiotic therapy earlier had a statistically significant shorter LOS (mean reduction 2.71 days, p-value <0.01). No impact on mortality was observed. In summary, we have developed a model to reliably estimate patient outcomes under the contrasting scenarios of stopping or continuing antibiotic treatment. Retrospective results are in line with previous clinical studies that demonstrate shorter antibiotic treatment durations are often non-inferior. With additional development into a clinical decision support system, this could be used to support individualised antimicrobial cessation decision-making, reduce the excessive use of antibiotics, and address the problem of AMR.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - AI
  - Deep Learning
  - Antibiotic Optimisation
  - Clinical Decision Support

featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 'publication/cessation/Bolton.pdf'
#url_code: 'https://github.com/WilliamBolton/iv_to_oral'
#url_dataset: ''
#url_poster: 'Poster.pdf'
#url_project: ''
#url_slides: 'Slides.pdf'
url_source: 'https://www.frontiersin.org/journals/digital-health/articles/10.3389/fdgth.2022.997219/full'
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
