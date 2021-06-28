---
title: "Empirically Measuring Concentration: Fundamental Limits to Intrinsic Robustness"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Saeed Mahloujifar
- Xiao Zhang
- Mohammad Mahmoody
- David Evans

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-12-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Thirty-third Conference on Neural Information Processing Systems 
publication_short: NeurIPS 2019 (Spotlight)

abstract: Many recent works have shown that adversarial examples that fool classifiers can be found by minimally perturbing a normal input. Recent theoretical results, starting with Gilmer et al. (2018b), show that if the inputs are drawn from a concentrated metric probability space, then adversarial examples with small perturbation are inevitable. A concentrated space has the property that any subset with Ω(1) (e.g., 1/100) measure, according to the imposed distribution, has small distance to almost all (e.g., 99/100) of the points in the space. It is not clear, however, whether these theoretical results apply to actual distributions such as images. This paper presents a method for empirically measuring and bounding the concentration of a concrete dataset which is proven to converge to the actual concentration. We use it to empirically estimate the intrinsic robustness to l∞ and l2 perturbations of several image classification benchmarks. Code for our experiments is available at https://github.com/xiaozhanguva/Measure-Concentration.

# Summary. An optional shortened abstract.
summary: We develop a method to measure the concentration of image benchmarks using empirical samples and show that concentration of measure does not prohibit the existence of adversarially robust classifiers.

tags: 
- Adversarial Examples
- Concentration of Measure
- Intrinsic Robustness

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/1905.12202'
  
- name: Post
  url: 'https://jeffersonswheel.org/neurips-2019-empirically-measuring-concentration/'

url_pdf: 'https://papers.nips.cc/paper/8763-empirically-measuring-concentration-fundamental-limits-on-intrinsic-robustness.pdf'
url_code: 'https://github.com/xiaozhanguva/Measure-Concentration'
# url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1_bQ0AFR7_-GVDpnDWNUirBW3tqGeGJHF/view'
# url_project: ''
url_slides: 'https://drive.google.com/file/d/1UIzRxpAT2fWsreTcMM1YGWRV0EyCaY50/view'
# url_source: ''
url_video: 'https://drive.google.com/file/d/1z-97tgTqB5dH3WzQcE6kBOVJHizo5z7A/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Illustration of our empirical method for measuring concentration'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- mahloujifar2019empirically

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
Preliminary versions of this work were presented at [Safe Machine Learning](https://sites.google.com/view/safeml-iclr2019) and [Debugging ML Models](https://debug-ml-iclr2019.github.io/) at ICLR 2019, as well as [Uncertainty & Robustness in Deep Learning Workshop](https://sites.google.com/view/udlworkshop2019/) at ICML 2019.

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
