---
title: "A Unified Computational and Statistical Framework for Nonconvex Low-Rank Matrix Estimation"

event: ICML 2017
event_url: https://icml.cc/Conferences/2017

location: International Convention Centre
address:
  street: 14 Darling Drive
  city: Sydney
  region: NSW 
  postcode: 2000
  country: Australia

summary: A generic framework based on a new stochastic variance-reduced gradient descent algorithm for accelerating nonconvex low-rank matrix recovery

abstract: We propose a generic framework based on a new stochastic variance-reduced gradient descent algorithm for accelerating nonconvex low-rank matrix recovery. Starting from an appropriate initial estimator, our proposed algorithm performs projected gradient descent based on a novel semi-stochastic gradient specifically designed for low-rank matrix recovery. Based upon the mild restricted strong convexity and smoothness conditions, we derive a projected notion of the restricted Lipschitz continuous gradient property, and prove that our algorithm enjoys linear convergence rate to the unknown low-rank matrix with an improved computational complexity. Moreover, our algorithm can be employed to both noiseless and noisy observations, where the (near) optimal sample complexity and statistical rate can be attained respectively. We further illustrate the superiority of our generic framework through several specific examples, both theoretically and experimentally.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2017-08-07T12:51:00Z"
date_end: "2017-08-07T01:09:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: 
- Lingxiao Wang
- Xiao Zhang
- Quanquan Gu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: Sicheng Zhu'
#   focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: 
url_code: 'https://github.com/xiaozhanguva/LR-SVRG'
url_pdf: 'http://proceedings.mlr.press/v70/wang17n/wang17n.pdf'
url_slides: "https://drive.google.com/file/d/1S0yuX2Ts-PCCzD6IOK__qoYMYzXPwfRo/view?usp=sharing"
url_video: 'https://vimeo.com/240662546'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<!-- {{% callout note %}}
To view my presentation, click the **Video** button and drag the progress bar to 13:36.
{{% /callout %}} -->

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
