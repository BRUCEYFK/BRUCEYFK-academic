---
title: 'Dual-strategy Pose Estimation Network Based on Mask-RCNN'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haoyu Han
  - Admin
  - Zuowei Pang
  - Huashan Liu

# Author notes (optional)
author_notes:
  # - ''
  # - ''

date: '2023-04-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 42nd Chinese Control Conference (CCC)*
# publication_short: In *CCC*

abstract: 6D pose estimation from a given input image is a key technology in computer vision and robotics, which has been broadly leveraged in robot operations, autonomous driving, and augmented reality. The current mainstream methods fall into two main categories, either regressing the rotation and translation directly from the image or constructing a 2D-3D correspondence and then solving the poses indirectly via PnP. In this work, we propose a 6D pose estimation method: a Mask-RCNN-based dual-strategy pose estimation network. First, it divides the pose into two parts, rotation and translation, and uses two different strategies of pose estimation networks to solve the translation and rotation of the object separately, so as to improve the estimation's accuracy and robustness. Secondly, a Mask-based loss function is proposed to update the network and make it increasingly accurate in calculating the coordinates, where the coordinate points of the predicted object region are extracted from the local image by the Mask-RCNN prediction on the object mask. Finally, experiments are conducted on the LINEMOD dataset to demonstrate the superiority of our method. The method is highly applicable and accurate to handle pose estimation problems for untextured and occluded objects. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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


