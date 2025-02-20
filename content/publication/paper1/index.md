---
title: "Long-Horizon FCS-MPC Trained 1-D Convolution Neural Networks for FPGA-Based Power-Electronic Converter Control With a Si/SiC Hybrid Converter Case Study."
authors:
- Admin
date: "2025-02-14T00:00:00Z"
doi: "10.1109/TIE.2025.3536555"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Conventional long-horizon finite-control-set model predictive control (FCS-MPC) for power electronics has two main real-time implementation problems: 1) calculation burden and latency; and 2) high hardware resource requirements on real-time platforms such as FPGA. To solve these problems, machine learning models have been proposed using model predictive control results as offline training data to train an artificial neural network (ANN), which will be implemented in the real-time controller instead of the original model predictive control model. In this way, the ANN reduces the online calculation burden and the hardware resource requirements. In this article, an FPGA-based 1-D convolution neural network (CNN) for long-horizon FCS-MPC is proposed. To simplify the network model and reduce the hardware resources further, model compression techniques of pruning, fine-tuning, and quantization are implemented. The proposed model is verified using a parallel hybrid converter as a case study converter, with performance and hardware resource requirements compared to conventional FCS-MPC and multilayer perceptron (MLP) models. The results show that the proposed compressed CNN model can reduce FPGA DSP resource requirements by 75% compared to a FCS-MPC model and an MLP models, while also achieving comparable or superior performance.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

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
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
