---
title: "Learning One-hidden-layer ReLU Networks via Gradient Descent"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Zhang
- Yaodong Yu
- Lingxiao Wang
- Quanquan Gu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2019-04-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Twenty-Second International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2019

abstract: We study the problem of learning one-hidden-layer neural networks with Rectified Linear Unit (ReLU) activation function, where the inputs are sampled from standard Gaussian distribution and the outputs are generated from a noisy teacher network. We analyze the performance of gradient descent for training such kind of neural networks based on empirical risk minimization, and provide algorithm-dependent guarantees. In particular, we prove that tensor initialization followed by gradient descent can converge to the ground-truth parameters at a linear rate up to some statistical error. To the best of our knowledge, this is the first work characterizing the recovery guarantee for practical learning of one-hidden-layer ReLU networks with multiple neurons. Numerical experiments verify our theoretical findings.

# Summary. An optional shortened abstract.
summary: We prove theoretical guarantees of learning one-hidden-layer neural networks with ReLU activations.

tags: 
- Deep Learning
- ReLU Activation
- Nonconvex Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1806.07808'
  
- name: Link
  url: 'http://proceedings.mlr.press/v89/zhang19g'

url_pdf: 'http://proceedings.mlr.press/v89/zhang19g/zhang19g.pdf'
# url_code: 'https://github.com/xiaozhanguva/Intrinsic-Rob'
# url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1DLCskW0xPldoM6an0Mh4uszgT1Fc_5cj/view?usp=sharing'
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
- zhang2019learning

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
