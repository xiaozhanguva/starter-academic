---
title: "Learning Adversarially Robust Representations via Worst-Case Mutual Information Maximization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sicheng Zhu
- Xiao Zhang
- David Evans

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-07-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Thirty-seventh International Conference on Machine Learning
publication_short: ICML 2020

abstract: Training machine learning models that are robust against adversarial inputs poses seemingly insurmountable challenges. To better understand adversarial robustness, we consider the underlying problem of learning robust representations. We develop a notion of representation vulnerability that captures the maximum change of mutual information between the input and output distributions, under the worst-case input perturbation. Then, we prove a theorem that establishes a lower bound on the minimum adversarial risk that can be achieved for any downstream classifier based on its representation vulnerability. We propose an unsupervised learning method for obtaining intrinsically robust representations by maximizing the worst-case mutual information between the input and output distributions. Experiments on downstream classification tasks support the robustness of the representations found using unsupervised learning with our training principle.

# Summary. An optional shortened abstract.
summary: We propose an unsupervised learning method for obtaining robust representations based on a notion of representation vulnerability.

tags: 
- Adversarial Examples
- Robust Representation
- Mutal Information

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2002.11798'
  
- name: Link
  url: 'http://proceedings.mlr.press/v119/zhu20e.html'

- name: Post
  url: 'https://uvasrg.github.io/robustrepresentations/'

url_pdf: 'http://proceedings.mlr.press/v119/zhu20e/zhu20e.pdf'
url_code: 'https://github.com/schzhu/learning-adversarially-robust-representations'
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
- zhu2020learning

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
