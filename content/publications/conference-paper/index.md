---
title: 'Retrospective State Fusion with Query-Guided Weighting for Long-Range Epidemic Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qi YUAN
  - Han SHU

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *HugoBlox Kit Conference*
publication_short: In *ICW*

abstract: Accurate long-term forecasting of influenza-like illness (ILI) is essential for effective public health planning and resource allocation. State-of-the-art Spatio-Temporal Graph Neural Networks (STGNNs), however, often create an information bottleneck by compressing historical time-series into a fixed-size representation or using only the final hidden state of a recurrent neural network (RNN), thereby losing crucial sequential dynamics. In this paper, we propose a novel dual-stream STGNN architecture to address this limitation. Our primary contribution is the Retrospective Attention Module (RAM), which introduces a Query-Guided Weighting mechanism to dynamically aggregate the entire sequence of an RNN's hidden states. This mechanism uses the final hidden state as a query to assign adaptive weights to all previous states, generating a comprehensive temporal representation. This enhanced representation subsequently informs the learning of a dynamic spatial attention graph, facilitating a more robust fusion of spatio-temporal dependencies. Extensive experiments on two public U.S. influenza datasets demonstrate that our model, RAM-GNN, achieves state-of-the-art (SOTA) results. It significantly outperforms strong baselines in long-term forecasting, reducing the Root Mean Squared Error (RMSE) by up to 15.3\% on 10-week-ahead predictions and improving the Pearson Correlation Coefficient (PCC) by up to 21.3\% on 15-week-ahead predictions. Our findings underscore the importance of preserving and adaptively weighting complete sequential information for robust long-range spatio-temporal forecasting.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Epidemic Forecasting

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: https://github.com/HugoBlox/kit
  - type: dataset
    url: https://github.com/HugoBlox/kit
  - type: slides
    url: https://www.slideshare.net/
  - type: source
    url: https://github.com/HugoBlox/kit
  - type: video
    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
