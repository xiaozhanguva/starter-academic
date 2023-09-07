---
title: "Provably Robust Cost-Sensitive Learning via Randomized Smoothing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuan Xin
- Michael Backes
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-08-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: The 2nd Workshop on New Frontiers in Adversarial Machine Learning at ICML 2023
publication_short: ICML 2023 AdvML-Frontiers Workshop

abstract: We focus on learning adversarially robust classifiers under cost-sensitive scenarios, where the potential harm of different classwise adversarial transformations is encoded in a cost matrix. Existing methods either are empirical that cannot certify robustness or suffer from inherent scalability issues. In this work, we study whether randomized smoothing, a scalable robustness certification framework, can be leveraged to certify cost-sensitive robustness. We first show how to extend the vanilla certification pipeline to provide rigorous guarantees for cost-sensitive robustness. However, when adapting the standard randomized smoothing method to train for cost-sensitive robustness, we observe that the naive reweighting scheme does not achieve a desirable performance due to the indirect optimization of the base classifier. Inspired by this observation, we propose a more direct training method with fine-grained certified radius optimization schemes designed for different data subgroups. Experiments on image benchmarks demonstrate that our method significantly improves certified cost-sensitive robustness without sacrificing overall accuracy.

# Summary. An optional shortened abstract.
summary: Study how to train for and certify cost-sensitive robustness using randomized smoothing.

tags: 
- Certified Robustness
- Randomized Smoothing
- Cost-sensitive Learning


# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: ArXiv
#   url: 'https://arxiv.org/abs/2307.01073'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://openreview.net/pdf?id=6wDGBAs21z'
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
- xin2023provably

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
