---
title: "Context-Predictive Representation Learning with Prototype-to-Semantic Memory Retrieval for Terminology-Constrained Surgical Report Generation"
authors:
- Han SHU
- Guanqun SUN
- Qi Yuan
- Mengya XU
- Yizhi PAN
- Zhikun LIU
- Le-Minh NGUYEN
date: "2026-01-10T00:00:00Z"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: "Surgical report generation aims to translate intra-operative visual observations into clinically valid descriptions for documentation and decision support. Unlike general image captioning, surgical reporting is safety-critical and terminology-sensitive, requiring accurate descriptions of fine-grained tool--tissue interactions under a constrained clinical vocabulary. However, prevailing pipelines often rely on visual encoders pre-trained on natural images, which may under-model interaction-centric surgical semantics, and decode in an unconstrained text space, leading to terminological drift and hallucinations. We propose {CLAMP} ({C}ontext-predictive surgica{L} represent{A}tion learning with prototype-to-se{M}antic memory and {P}rototype retrieval), a clinically grounded framework that couples context-predictive representation learning with evidence-grounded, terminology-constrained composition. CLAMP pre-trains a context-predictive vision extractor via latent target prediction on surgical data, encouraging interaction-aware representations that are robust to occlusion and appearance corruption.  Furthermore, CLAMP employs a coarse-to-fine retrieval strategy: a prototype stage retrieves visually consistent clinical evidence to anchor scene context, followed by a semantic stage that refines terminology through cross-modal matching within the candidate set.  Finally, a memory-conditioned projector fuses visual evidence and retrieved clinical cues into a unified representation to guide the caption decoder toward clinically coherent reports. Extensive experiments on the EndoVis and DAISI benchmarks demonstrate that CLAMP achieves state-of-the-art performance and improves clinical validity. We further provide targeted qualitative and quantitative analyses of terminology-related errors."

# Summary. An optional shortened abstract.
summary: 

tags:
- surgical report generation
- clinical context-aware representation learning
- prototype-to-semantic memory retrieval
- self-supervised surgical vision

featured: true

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

# links:
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
# - type: code
#   url: https://github.com/HugoBlox/kit
# - type: slides
#   url: https://www.slideshare.net/
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs. -->

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
