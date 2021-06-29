---
title: "Fast and Sample Efficient Inductive Matrix Completion via Multi-Phase Procrustes Flow"

event: ICML 2018
event_url: https://icml.cc/Conferences/2018

location: Stockholmsmässan
address:
  street: Mässvägen 1, Älvsjö
  # city: Stockholm
  region: Stockholm
  postcode: 125 80
  country: Sweden

summary: We present a new gradient-based optimization algorithm for inductive matrix completion, which achieves both linear rate of convengence and sample complexities linearly depending on the feature dimension.

abstract: We revisit the inductive matrix completion problem that aims to recover a rank-r matrix with ambient dimension d given n features as the side prior information. The goal is to make use of the known n features to reduce sample and computational complexities. We present and analyze a new gradient-based non-convex optimization algorithm that converges to the true underlying matrix at a linear rate with sample complexity only linearly depending on n and logarithmically depending on d. To the best of our knowledge, all previous algorithms either have a quadratic dependency on the number of features in sample complexity or a sub-linear computational convergence rate. In addition, we provide experiments on both synthetic and real world data to demonstrate the effectiveness of our proposed algorithm.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2018-07-13T08:20:00Z"
date_end: "2018-07-13T08:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: 
- Xiao Zhang
- Simon Du
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
url_code: 'https://github.com/xiaozhanguva/Inductive-MC'
url_pdf: 'http://proceedings.mlr.press/v80/zhang18b/zhang18b.pdf'
url_slides: 'https://drive.google.com/file/d/1CgbMASa2hKlB-iDlHS4iV2wSvWr4IUch/view?usp=sharing'
url_video: 'https://vimeo.com/287767590'

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
