---
title: "Robust Wirtinger Flow for Phase Retrieval with Arbitrary Corruption"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jinghui Chen
- Lingxiao Wang
- Xiao Zhang
- Quanquan Gu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2017-04-20T00:00:00Z"
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

abstract: We consider the phase retrieval problem of recovering the unknown signal from the magnitude-only measurements, where the measurements can be contaminated by both sparse arbitrary corruption and bounded random noise. We propose a new nonconvex algorithm for robust phase retrieval, namely Robust Wirtinger Flow, to jointly estimate the unknown signal and the sparse corruption. We show that our proposed algorithm is guaranteed to converge linearly to the unknown true signal up to a minimax optimal statistical precision in such a challenging setting. Compared with existing robust phase retrieval methods, we improved the statistical error rate by a factor of (n/m)^(1/2) where n is the dimension of the signal and m is the sample size, provided a refined characterization of the corruption fraction requirement, and relaxed the lower bound condition on the number of corruption. In the noise-free case, our algorithm converges to the unknown signal at a linear rate and achieves optimal sample complexity up to a logarithm factor. Thorough experiments on both synthetic and real datasets corroborate our theory.

# Summary. An optional shortened abstract.
summary: A new nonconvex algorithm for robust phase retrieval, which attains a linear rate of convergence and improved statistical error rate.

tags: 
- Phase Retrieval
- Nonconvex Optimization
- Algorithm

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1704.06256'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/1704.06256.pdf'
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
- chen2017robust

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
