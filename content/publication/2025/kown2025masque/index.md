---
title: "MASQUE: Diffusion-Based Localized Adversarial Makeup for Facial Privacy"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Youngjin Kwon
- Xiao Zhang
# Author notes (optional)
# author_notes:
# - "Equal contribution"

date: "2025-04-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication:  ICLR 2025 Workshop on Foundation Models in the Wild
publication_short: ICLR 2025 FM-Wild Workshop

abstract: Facial recognition has been increasingly employed in real-world applications, raising serious privacy concerns over mass surveillance and unauthorized tracking. Existing anti-facial recognition methods perturb face images using generative models to protect privacy but often introduce global artifacts, depend on reference image prompts, or require target identity, compromising both visual quality and anonymity. To address the above limitations, we introduce MASQUE, a diffusion-based framework that generates localized adversarial makeup guided by user-defined text prompts. By leveraging precise null-text inversion, targeted cross-attention fusion with masking, and a novel pairwise adversarial guidance mechanism using images of the same individual, MASQUE achieves robust dodging performance without the need for an external target identity. Extensive evaluations on open-source FR models and commercial APIs show that MASQUE significantly enhances privacy protection over all baselines, achieving average protection success rates of 90% for identification and 87% for verification while preserving high perceptual fidelity.


# Summary. An optional shortened abstract.
summary: We introduce MASQUE, a diffusion-based framework that generates localized adversarial makeup guided by user-defined text prompts.

tags: 
- Anti-Facial Recognition
- Diffusion Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2503.10549'
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=ydTE0tpZ90'

url_pdf: 'https://arxiv.org/pdf/2503.10549'
url_code: 'https://github.com/TrustMLRG/MASQUE'
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
- kwon2025masque

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
