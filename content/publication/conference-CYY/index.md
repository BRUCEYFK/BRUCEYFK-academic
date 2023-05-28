---
title: 'Deep Reinforcement Learning in Maximum Entropy Framework with Automatic Adjustment of Mixed Temperature Parameters for Path Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yingying Chen
  - Admin
  - Xiangjian Li
  - Huashan Liu

# Author notes (optional)
author_notes:
  # - ''
  # - ''

date: '2023-01-05T00:00:00Z'
doi: '10.1109/ICRCA57894.2023.10087467'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 7th International Conference on Robotics, Control and Automation (ICRCA)*
# publication_short: In *ICRCA*

abstract: Deep reinforcement learning in maximum entropy framework is sample-efficient and has a strong exploration capacity, making it effective and favorable to solve problems like path planning. Properly tuning the temperature parameters can improve the performance of policy learning, but manual tuning is inefficient. In this paper, we propose a mixed algorithm named SAC-M which is inspired by adaptive soft actor-critic (A-SAC) and soft actor-critic with automatic entropy (SAC-A). The proposed method achieves automatic adjustment of temperature parameters so that the entropy can vary among different states to control the degree of exploration, reducing the possibility of learning suboptimal policies to some extent. The experimental results illustrate that the proposed SAC-M outperforms A-SAC and SAC-A in path planning tasks in different scenes, especially when A-SAC and SAC-A are mixed in a proper ratio.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Academic
  - Deep Reinforcement Learning
  - Robotics
  - Motion Planning

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10087467'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

