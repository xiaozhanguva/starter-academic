---
title: "A Unified Framework for Nonconvex Low-rank plus Sparse Matrix Recovery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Lingxiao Wang
- Quanquan Gu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018-04-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Twenty-First International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2018

abstract: "We propose a unified framework to solve general low-rank plus sparse matrix recovery problems based on matrix factorization, which covers a broad family of objective functions satisfying the restricted strong convexity and smoothness conditions. Based on projected gradient descent and the double thresholding operator, our proposed generic algorithm is guaranteed to converge to the unknown low-rank and sparse matrices at a locally linear rate, while matching the best-known robustness guarantee (i.e., tolerance for sparsity). At the core of our theory is a novel structural Lipschitz gradient condition for low-rank plus sparse matrices, which is essential for proving the linear convergence rate of our algorithm, and we believe is of independent interest to prove fast rates for general superposition-structured models. We illustrate the application of our framework through two concrete examples: robust matrix sensing and robust PCA. Empirical experiments corroborate our theory."


# Summary. An optional shortened abstract.
summary: A unified framework for solving general low-rank plus sparse matrix recovery problems.

tags: 
- Low-Rank Matrix Recovery
- Algorithm
- Nonconvex Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1702.06525v3'
  
- name: Link
  url: 'http://proceedings.mlr.press/v84/zhang18c.html'

url_pdf: 'http://proceedings.mlr.press/v54/wang17b/wang17b.pdf'
url_code: 'https://github.com/xiaozhanguva/Robust-PCA'
# url_dataset: ''
url_poster: 'https://drive.google.com/file/d/12pn770ttbfJzcd4olU0DQyc6eyq2x6mz/view?usp=sharing'
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
- zhang2018unified

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
