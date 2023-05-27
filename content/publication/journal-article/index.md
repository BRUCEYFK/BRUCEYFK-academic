---
title: "Extensively Explored and Evaluated Actor-Critic With Expert-Guided Policy Learning and Fuzzy Feedback Reward for Robotic Trajectory Generation"
authors:
- admin
- Huashan Liu
- Rongxin Jiang
- Menghua Dong
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-01-18T00:00:00Z"
doi: "10.1109/TII.2022.3143611"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Industrial Informatics, 18(11):7749–7760"
publication_short: ""

abstract: Trajectory generation for redundant manipulators based on inverse kinematics (IK) still faces some restraints, as it lacks universal IK calculation or specific trajectory generation methods that are suitable for robots with arbitrary degrees of freedom. In this article, the IK-free trajectory generation for robot manipulators is formulated as a Markov decision process and implemented by a general method based on deep reinforcement learning. First, an extensively explored and evaluated actor-critic (E3AC) algorithm that can make diverse action explorations and comprehensive evaluations is designed to solve the trajectory generation problem. Second, a dual-memory structure with expert-guided policy learning strategy is proposed to further enhance the performance of the algorithm in the early training period by additional successful experiences and performing an increasingly unbiased data sampling. Third, a fuzzy feedback reward mechanism that can directly establish a mapping from the abundant state variables to the self-tuning reward is constructed, instead of puzzling out an explicit function to feature the complex relations among the control objects. Finally, the comparative experimental results show that, the proposed approach is more efficient in algorithm convergence and reward calculation, and is more qualified for complex tasks with strong randomness.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
