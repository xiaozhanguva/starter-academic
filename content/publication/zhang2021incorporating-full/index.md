---
title: "Incorporating Label Uncertainty in Understanding Adversarial Robustness"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- David Evans

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication:  ArXiv
# publication_short: arxiv

abstract: A fundamental question in adversarial machine learning is whether a robust classi- fier exists for a given task. A line of research has made progress towards this goal by studying concentration of measure, but without considering data labels. We argue that the standard concentration fails to fully characterize the intrinsic robust- ness of a classification problem, since it ignores data labels which are essential to any classification task. Building on a novel definition of label uncertainty, we em- pirically demonstrate that error regions induced by state-of-the-art models tend to have much higher label uncertainty compared with randomly-selected subsets. This observation motivates us to adapt a concentration estimation algorithm to account for label uncertainty, resulting in more accurate intrinsic robustness measures for benchmark image classification problems. We further provide empirical evidence showing that adding an abstain option for classifiers based on label uncertainty can help improve both the clean and robust accuracies of models.

# Summary. An optional shortened abstract.
summary: Built upon on a novel definition of label uncertainty, we develop an empirical method to estimate a more realistic intirnsic robustness limit for classification tasks

tags: 
- Adversarial Examples
- Intrinsic Robustness
- Concentration of Measure
- Label Uncertainty

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2107.03250'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/2107.03250.pdf'
# url_code: 'https://github.com/xiaozhanguva/LR-SVRG'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://vimeo.com/240662546'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Convergence curves of the estimated best possible adversarial risk'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- zhang2021incorporating-full

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
A short version of this work was presented at workshop on [Security and Safety in Machine Learning Systems](https://iclr.cc/virtual/2021/workshop/2127) at ICLR 2021.

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

