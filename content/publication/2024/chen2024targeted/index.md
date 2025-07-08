---
title: "Can Targeted Clean-Label Poisoning Attacks Generalize?"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhizhen Chen
- Subrat Kishore Dutta
- Zhengyu Zhao
- Chenhao Lin
- Chao Shen
- Xiao Zhang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-12-05T00:00:00Z"
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

abstract: Targeted poisoning attacks aim to compromise the model's prediction on specific target samples. In a common clean-label setting, they are achieved by slightly perturbing a subset of training samples given access to those specific targets. Despite continuous efforts, it remains unexplored whether such attacks can generalize to unknown variations of those targets. In this paper, we take the first step to systematically study this generalization problem. Observing that the widely adopted, cosine similarity-based attack exhibits limited generalizability, we propose a well-generalizable attack that leverages both the direction and magnitude of model gradients. In particular, we explore diverse target variations, such as an object with varied viewpoints and an animal species with distinct appearances. Extensive experiments across various generalization scenarios demonstrate that our method consistently achieves the best attack effectiveness. For example, our method outperforms the cosine similarity-based attack by 20.95% in attack success rate with similar overall accuracy, averaged over four models on two image benchmark datasets.

# Summary. An optional shortened abstract.
summary: We explore whether targeted clean-label data poisoning attacks can generalize to diverse target variations

tags: 
- Clean-Label Data Poisoning Attacks
- Supopulation Attacks
- Gradient Matching

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ArXiv
  url: 'https://arxiv.org/abs/2412.03908'
  
# - name: Link
#   url: 'http://proceedings.mlr.press/v70/wang17n'

url_pdf: 'https://arxiv.org/pdf/2412.03908.pdf'
url_code: https://github.com/jiaangk/generalizable_tcpa
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
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- chen2024targeted

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
