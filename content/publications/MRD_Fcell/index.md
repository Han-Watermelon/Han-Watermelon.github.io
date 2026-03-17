---
title: "Morphology-Aware Distillation for Lightweight Retinal Vessel Segmentation Across Fundus Photography and OCT Angiography"
authors:
- Han SHU
- Guanqun SUN
- Yizhi PAN
- Qi YUAN
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2026-04-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
# publishDate: '2026-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Frontiers in Cell adnd Development Biology"
publication_short: "Fcell"

abstract: Retinal vessel segmentation is critical for diagnosing ophthalmic and systemic diseases, yet deploying high-performance models in resource-constrained clinical settings remains a challenge. While Knowledge Distillation (KD) offers a solution for model compression, conventional KD methods often treat the U-Net as a generic feature extractor, neglecting the unique topological nature of vascular networks. This oversight frequently leads to "fractured" segmentation maps in student models, where fine capillaries and continuous vessel branches are lost. In this paper, we advocate a task-specific, morphology-aware distillation strategy for lightweight retinal vessel segmentation. We introduce Morphology-Aware Reconstruction Distillation (MRD), a novel framework designed to transfer the teacher's capability to reconstruct coherent vascular graphs rather than merely mimicking pixel statistics. Central to MRD is the Hierarchical Structure Fusion (HSF) module, a purpose-built unit that adaptively integrates multi-scale features using a tailored residual gating mechanism. By focusing on the decoder's role as a topological reconstruction engine, HSF guides the student to learn how to synthesize continuous vessel structures from compressed representations. We validate our approach across two distinct modalities Fundus Photography (Fives dataset) and OCT Angiography (Rose dataset). Extensive experiments demonstrate that our method significantly outperforms existing KD techniques. Notably, our distilled student model achieves diagnostic-level segmentation fidelity that surpasses massive teacher architectures like TransUNet, all while operating with a radically reduced parameter footprint. By robustly preserving delicate vascular morphology across diverse datasets, these results highlight the strong translational potential of our approach, providing a structurally reliable and highly efficient solution tailored for point-of-care clinical deployment.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Retinal Vessel Segmentation
- Knowledge Distillation
- U-Net
featured: true

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
