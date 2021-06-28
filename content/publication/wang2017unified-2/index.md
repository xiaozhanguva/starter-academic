---
title: "A Unified Computational and Statistical Framework for Nonconvex Low-rank Matrix Estimation"

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

date: "2017-04-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Twentyth International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2017

abstract: "We propose a unified framework for estimating low-rank matrices through nonconvex optimization based on gradient descent algorithm. Our framework is quite general and can be applied to both noisy and noiseless observations. In the general case with noisy observations, we show that our algorithm is guaranteed to linearly converge to the unknown low-rank matrix up to a minimax optimal statistical error, provided an appropriate initial estimator. While in the generic noiseless setting, our algorithm converges to the unknown low-rank matrix at a linear rate and enables exact recovery with optimal sample complexity. In addition, we develop a new initialization algorithm to provide the desired initial estimator, which outperforms existing initialization algorithms for nonconvex low-rank matrix estimation. We illustrate the superiority of our framework through three examples: matrix regression, matrix completion, and one-bit matrix completion. We also corroborate our theory through extensive experiments on synthetic data."

# Summary. An optional shortened abstract.
summary: A unified framework for estimating low-rank matrices through nonconvex optimization based on gradient descent

tags: 
- Low-Rank Matrix Recovery
- Algorithm
- Nonconvex Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1610.05275'
  
- name: Link
  url: 'http://proceedings.mlr.press/v54/wang17b'

url_pdf: 'http://proceedings.mlr.press/v54/wang17b/wang17b.pdf'
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
- wang2017unified-2

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
