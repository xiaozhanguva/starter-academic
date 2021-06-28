---
title: "A Unified Computational and Statistical Framework for Nonconvex Low-Rank Matrix Estimation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lingxiao Wang
- Xiao Zhang
- Quanquan Gu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2017-08-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication:  Thirty-Fourth International Conference on Machine Learning
publication_short: ICML 2017

abstract: We propose a generic framework based on a new stochastic variance-reduced gradient descent algorithm for accelerating nonconvex low-rank matrix recovery. Starting from an appropriate initial estimator, our proposed algorithm performs projected gradient descent based on a novel semi-stochastic gradient specifically designed for low-rank matrix recovery. Based upon the mild restricted strong convexity and smoothness conditions, we derive a projected notion of the restricted Lipschitz continuous gradient property, and prove that our algorithm enjoys linear convergence rate to the unknown low-rank matrix with an improved computational complexity. Moreover, our algorithm can be employed to both noiseless and noisy observations, where the (near) optimal sample complexity and statistical rate can be attained respectively. We further illustrate the superiority of our generic framework through several specific examples, both theoretically and experimentally.

# Summary. An optional shortened abstract.
summary: A generic framework based on a new stochastic variance-reduced gradient descent algorithm for accelerating nonconvex low-rank matrix recovery

tags: 
- Low-Rank Matrix Recovery
- Variance Reduction
- Algorithm
- Nonconvex Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1701.02301'
  
- name: Link
  url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'http://proceedings.mlr.press/v70/wang17n/wang17n.pdf'
url_code: 'https://github.com/xiaozhanguva/LR-SVRG'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://vimeo.com/240662546'

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
- wang2017unified-1

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
