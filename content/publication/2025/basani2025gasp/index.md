---
title: "GASP: Efficient Black-Box Generation of Adversarial Suffixes for Jailbreaking LLMs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Advik Raj Basani
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
publication:  ICLR 2025 Workshop on Building Trust in Language Models and Applications (Oral)
publication_short: ICLR 2025 BuildingTrust Workshop (Oral)

abstract: Large Language Models (LLMs) have shown impressive proficiency across a range of natural language processing tasks yet remain vulnerable to adversarial prompts, known as jailbreak attacks, carefully designed to elicit harmful responses from LLMs. Traditional methods rely on manual heuristics, which suffer from limited generalizability. While being automatic, optimization-based attacks often produce unnatural jailbreak prompts that are easy to detect by safety filters or require high computational overhead due to discrete token optimization. Witnessing the limitations of existing jailbreak methods, we introduce Generative Adversarial Suffix Prompter (GASP), a novel framework that combines human-readable prompt generation with Latent Bayesian Optimization (LBO) to improve adversarial suffix creation in a fully black-box setting. GASP leverages LBO to craft adversarial suffixes by efficiently exploring continuous embedding spaces, gradually optimizing the model to improve attack efficacy while balancing prompt coherence through a targeted iterative refinement procedure. Our experiments show that GASP can generate natural jailbreak prompts, significantly improving attack success rates, reducing training times, and accelerating inference speed, thus making it an efficient and scalable solution for red-teaming LLMs.


# Summary. An optional shortened abstract.
summary: We introduce Generative Adversarial Suffix Prompter (GASP), a novel framework that combines human-readable prompt generation with Latent Bayesian Optimization (LBO) to improve adversarial suffix creation in a fully black-box setting.

tags: 
- Large Language Model (LLM)
- Jailbreak Attack
- Latent Bayesian Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2411.14133'
  
- name: OpenReview
  url: 'https://openreview.net/forum?id=Gonca78Bwq&noteId=uCKiVEXZCS'

url_pdf: 'https://arxiv.org/pdf/2411.14133'
url_code: 'https://github.com/TrustMLRG/GASP'
# url_dataset: ''
# url_poster: ''
url_project: 'https://gasp-llm.vercel.app/'
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
- basani2025gasp

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
