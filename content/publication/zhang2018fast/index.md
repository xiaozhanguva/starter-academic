---
title: "Fast and Sample Efficient Inductive Matrix Completion via Multi-Phase Procrustes Flow"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Simon Du
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

abstract: We revisit the inductive matrix completion problem that aims to recover a rank-r matrix with ambient dimension d given n features as the side prior information. The goal is to make use of the known n features to reduce sample and computational complexities. We present and analyze a new gradient-based non-convex optimization algorithm that converges to the true underlying matrix at a linear rate with sample complexity only linearly depending on n and logarithmically depending on d. To the best of our knowledge, all previous algorithms either have a quadratic dependency on the number of features in sample complexity or a sub-linear computational convergence rate. In addition, we provide experiments on both synthetic and real world data to demonstrate the effectiveness of our proposed algorithm.

# Summary. An optional shortened abstract.
summary: We present a new gradient-based optimization algorithm for inductive matrix completion, which achieves both linear rate of convengence and sample complexities linearly depending on the feature dimension.

tags: 
- Inductive Matrix Completion
- Low-Rank Matrix Recovery
- Nonconvex Optimization
- Algorithm

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1803.01233'
  
- name: Link
  url: 'http://proceedings.mlr.press/v80/zhang18b.html'

url_pdf: 'http://proceedings.mlr.press/v80/zhang18b/zhang18b.pdf'
url_code: 'https://github.com/xiaozhanguva/Inductive-MC'
# url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1pLDQ27f5jPmhycA3Jc-an8epdQ3zCrLV/view?usp=sharing'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://vimeo.com/287767590'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Convergence curves of the estimated best possible adversarial risk'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- zhang2020understanding

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
