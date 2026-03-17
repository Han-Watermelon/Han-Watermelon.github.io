---
title: "FKD-Med: Privacy-Aware, Communication-Optimized Medical Image Segmentation via Federated Learning and Model Lightweighting through Knowledge Distillation"
authors:
- Han SHU
- Guanqun SUN
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: Advances in deep learning have revolutionized medical image segmentation, facilitating the precise delineation of complex anatomical structures. The scarcity of annotated training samples remains a significant bottleneck. To tackle the data limitation, federated learning (FL) offers the promise of pooling data from multiple healthcare institutions.  However, as models grow larger, the increase in communication costs restricts FL to fewer nodes, which constrains the volume of data. This situation necessitates the simultaneous achievement of model lightweighting. To address this problem, this study proposes FKD-Med, a novel framework that integrates FL for privacy-sensitive data amalgamation across multiple healthcare institutions, and uses knowledge distillation (KD) to enhance communication efficiency. The "Med" in FKD-Med refers to medical application computational problems. Our principal contributions encompass the design of an open-source framework that seamlessly blends FL and KD, rendering it applicable to a broad spectrum of medical informatics tasks. Our approach substantially augments the computational data volume, thereby boosting both communication efficiency and training throughput. Tested on two datasets of medical image segmentation using TransUNet and ResUNet as teacher models, FKD-Med achieves data privacy, lowers communication costs, and increases accuracy. The parameters of the student models were reduced to 1/127 and 1/1027 of those in the teacher models. Additionally, the models subjected to KD exhibited accuracy improvements of 0.25\%, 0.43\%, 1.35\%, and 1.46\% respectively, given the same parameter volume. This positions FKD-Med not only as a pivotal tool for multi-institutional medical research but also as a versatile platform adaptable to a wide array of real-world medical engineering applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Medical Image Segmentation
- Federated Learning
- Knowledge Distillation
- U-Net
featured: false

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

# links:
#   - type: pdf
#     url: http://arxiv.org/pdf/1512.04133v1
#   - type: code
#     url: https://github.com/HugoBlox/kit
#   - type: dataset
#     url: ""
#   - type: poster
#     url: ""
#   - type: project
#     url: ""
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: ""
#   - type: video
#     url: ""

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
slides: ""
---

> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
