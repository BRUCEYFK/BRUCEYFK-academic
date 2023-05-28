---
title: "Trajectory Generation for Multiprocess Robotic Tasks Based on Nested Dual-Memory Deep Deterministic Policy Gradient"
authors:
- admin
- Huashan Liu
- Rongxin Jiang
- Xin Yin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-04-13T00:00:00Z"
doi: "10.1109/TMECH.2022.3160605"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ASME Transactions on Mechatronics, 27(6):4643-4653, 2022"
publication_short: ""

abstract: Though there are extensive works on deep reinforcement learning (DRL) for robotics, sequential trajectory generation for multiprocess robotic tasks based on DRL is yet to be explored. In this article, the multiprocess task is formulated as a Markov decision process, and a nested dual-memory deep deterministic policy gradient algorithm with dynamic criteria is proposed, to generalize the traditional trajectory planning with predefined target point into a trajectory exploration problem aiming at a target area without solving inverse kinematics. First, a dual-memory architecture with local-to-global strategy is introduced to enhance the performance. Second, a novel nested architecture is proposed to generate sequential trajectory segments successively and asynchronously for the multiprocess task. Third, a compound reward system is designed and a weight coefficient matrix is adopted to balance the position control and the orientation control based on Tait–Bryan angles. In addition, a virtual twin system is established to promote the training efficiency, where the trajectory generated in simulation can be directly applied to the real physical platform. Finally, experimental results on both simulated and real-world applications have verified the performance of the proposed approach.

# Summary. An optional shortened abstract.
summary: This work implemented an IK-free trajectory planning scheme based on DRL. A nested architecture and a compound reward system were proposed to generate sequential trajectory segments for multiprocess robotic tasks. A dual-memory architecture with local-to-global strategy was introduced for efficient policy learning.

tags:
  - Academic
  - Deep Reinforcement Learning
  - Robotics
  - Motion Planning
  - Reward Design
  - Efficient Policy Learning

featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9756549
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://ieeexplore.ieee.org/document/9756549/media#media

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: ""
---


