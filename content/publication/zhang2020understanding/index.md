---
title: "Understanding the intrinsic robustness of image distributions using conditional generative models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Jinghui Chen
- Quanquan Gu
- David Evans

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-08-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Twenty-Third International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2020

abstract: Starting with Gilmer et al. (2018), several works have demonstrated the inevitability of adversarial examples based on different assumptions about the underlying input probability space. It remains unclear, however, whether these results apply to natural image distributions. In this work, we assume the underlying data distribution is captured by some conditional generative model, and prove intrinsic robustness bounds for a general class of classifiers, which solves an open problem in Fawzi et al. (2018). Building upon the state-of-the-art conditional generative models, we study the intrinsic robustness of two common image benchmarks under L2 perturbations, and show the existence of a large gap between the robustness limits implied by our theory and the adversarial robustness achieved by current state- of-the-art robust models. Code for all our experiments is available at https://github.com/xiaozhanguva/Intrinsic- Rob.

# Summary. An optional shortened abstract.
summary: We propose a way to characterize the intrinsic robustness of image distributions under L2 perturbations using conditional generative models.

tags: 
- Adversarial Examples
- Intrinsic Robustness
- Generative Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2003.00378'
  
- name: Link
  url: 'http://proceedings.mlr.press/v108/zhang20h.html'

url_pdf: 'http://proceedings.mlr.press/v108/zhang20h/zhang20h.pdf'
url_code: 'https://github.com/xiaozhanguva/Intrinsic-Rob'
# url_dataset: ''
# url_poster: ''
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
