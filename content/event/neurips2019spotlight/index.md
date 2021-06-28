---
title: "Empirically Measuring Concentration: Fundamental Limits to Intrinsic Robustness"

event: Neurips 2019 Spotlight Presentation
event_url: https://nips.cc/Conferences/2019/Schedule?showEvent=15792

location: Vancouver Convention Center
address:
  street: 1055 Canada Pl
  city: Vancouver
  region: BC
  postcode: V6C 0C3
  country: Canada

summary: We propose a novel method to measure the concentration of any distributions using empirical samples and show that concentration of measure does not prohibit the existence of adversarially robust classifiers for several image benchmarks.

abstract: Many recent works have shown that adversarial examples that fool classifiers can be found by minimally perturbing a normal input. Recent theoretical results, starting with Gilmer et al. (2018b), show that if the inputs are drawn from a concentrated metric probability space, then adversarial examples with small perturbation are inevitable. A concentrated space has the property that any subset with Ω(1) (e.g., 1/100) measure, according to the imposed distribution, has small distance to almost all (e.g., 99/100) of the points in the space. It is not clear, however, whether these theoretical results apply to actual distributions such as images. This paper presents a method for empirically measuring and bounding the concentration of a concrete dataset which is proven to converge to the actual concentration. We use it to empirically estimate the intrinsic robustness to l∞ and l2 perturbations of several image classification benchmarks. Code for our experiments is available at https://github.com/xiaozhanguva/Measure-Concentration.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-12-10T10:35:00Z"
date_end: "2019-12-10T10:40:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: "2017-01-01T00:00:00Z"

authors: 
- Saeed Mahloujifar
- Xiao Zhang
- Mohammad Mahmoody
- David Evans

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

tags: 
- Adversarial Examples
- Concentration of Measure
- Intrinsic Robustness

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: Sicheng Zhu'
  focal_point: Right

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: 
url_code: "https://github.com/xiaozhanguva/Measure-Concentration"
url_pdf: "https://papers.nips.cc/paper/8763-empirically-measuring-concentration-fundamental-limits-on-intrinsic-robustness.pdf"
url_slides: "https://drive.google.com/file/d/1UIzRxpAT2fWsreTcMM1YGWRV0EyCaY50/view"
url_video: "https://slideslive.com/38923202/track-2-session-1-spotlights"

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
{{% callout note %}}
To view my presentation, click the **Video** button and drag the progress bar to 13:36.
{{% /callout %}}

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
