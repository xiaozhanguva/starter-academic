---
title: "A Primal-Dual Analysis of Global Optimality in Nonconvex Low-Rank Matrix Recovery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Lingxiao Wang
- Yaodong Yu
- Quanquan Gu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018-07-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Thirty-Fifth International Conference on Machine Learning
publication_short: ICML 2018

abstract: We propose a primal-dual based framework for analyzing the global optimality of nonconvex low-rank matrix recovery. Our analysis are based on the restricted strongly convex and smooth conditions, which can be verified for a broad family of loss functions. In addition, our analytic framework can directly handle the widely-used incoherence constraints through the lens of duality. We illustrate the applicability of the proposed framework to matrix completion and one-bit matrix completion, and prove that all these problems have no spurious local minima. Our results not only improve the sample complexity required for characterizing the global optimality of matrix completion, but also resolve an open problem in Ge et al. (2017) regarding one-bit matrix completion. Numerical experiments show that primal-dual based algorithm can successfully recover the global optimum for various low-rank problems.

# Summary. An optional shortened abstract.
summary: A primal-dual based framework for analyzing the global optimality of nonconvex low-rank matrix recovery.

tags: 
- Low-Rank Matrix Recovery
- Primal-Dual Analysis
- Nonconvex Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: ArXiv
#   url: 'https://arxiv.org/abs/1806.07808'
  
- name: Link
  url: 'http://proceedings.mlr.press/v80/zhang18m.html'

url_pdf: 'http://proceedings.mlr.press/v80/zhang18m/zhang18m.pdf'
# url_code: 'https://github.com/xiaozhanguva/Intrinsic-Rob'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://vimeo.com/287809189'

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
- zhang2018primal

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
