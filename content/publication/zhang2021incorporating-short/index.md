---
title: "Incorporating Label Uncertainty in Intrinsic Robustness Measures"

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

date: "2021-05-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Security and Safety in Machine Learning Systems Workshop at ICLR 2021
publication_short: ICLR 2021 aisecure workshop

abstract: Starting with Gilmer et al. (2018), a line of theoretical works have focused on studying the concentration of measure phenomenon which is fundamentally connected to adversarial robustness. In this work, we argue that the standard concentration is not sufficient to characterize the intrinsic robustness limit for an adversarially robust classification problem since it does not take data labels into account. Built upon on a novel definition of label uncertainty, we empirically demonstrate that error regions induced by various state-of-the-art classification models tend to have much higher label uncertainty than randomly selected subsets. This observation implies that in order to obtain a more accurate intrinsic robustness limit for a particular data distribution, it is important to understand the concentration of measure regarding the input regions with high label uncertainty. In this paper, we adapt the standard concentration problem to produce a more accurate estimate of intrinsic robustness that incorporates label uncertainty and study the error region characteristics of the state-of-the-art machine learning classifiers.

# Summary. An optional shortened abstract.
summary: Advocate to understand the concentration of measure phenomenon regarding inputs regions with high label uncertainty

tags: 
- Adversarial Examples
- Intrinsic Robustness
- Concentration of Measure
- Label Uncertainty

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: ArXiv
#   url: 'https://arxiv.org/abs/2107.03250'
  
- name: Link
  url: 'https://iclr.cc/virtual/2021/workshop/2127'

# - name: Post
#   url: 'https://uvasrg.github.io/robustrepresentations/'

url_pdf: 'https://aisecure-workshop.github.io/aml-iclr2021/papers/37.pdf'
url_code: 'https://github.com/xiaozhanguva/intrinsic_rob_lu'
# url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1W51ReWumAZ7wC7AG-KUW80Y6maSTomLO/view?usp=sharing'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
- zhang2021incorporating-short

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
