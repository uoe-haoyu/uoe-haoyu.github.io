---
title: High-resolution conductivity reconstruction by electrical impedance tomography using structure-aware hybrid-fusion learning
authors:
- admin
- Haoyu Liu, Zhe Liu, Zeyu Wang, and Jiabin Jia.

date: "2024-01-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.cmpb.2023.107861"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types:
- "Article"

# Publication name and optional abbreviated publication name.
publication: "Elsevier"
publication_short: "CMPB"

abstract:  Electrical impedance tomography (EIT) has gained considerable attention in the medical field for the diagnosis of lung-related diseases, owing to its non-invasive and real-time characteristics. However, due to the ill-posedness and underdetermined nature of the inverse problem in EIT, suboptimal reconstruction performance and reduced robustness against the measurement noise and modeling errors are common issues. This study aims to mine the deep feature information from measurement voltages, acquired from the EIT sensor, to reconstruct the high-resolution conductivity distribution and enhance the robustness against the measurement noise and modeling errors using the deep learning method. A novel data-driven method named the structure-aware hybrid-fusion learning (SA-HFL) is proposed. SA-HFL is composed of three main components, a segmentation branch, a conductivity reconstruction branch, and a feature fusion module. These branches work in tandem to extract different feature information from the measurement voltage, which is then fused to reconstruct the conductivity distribution. The unique aspect of this network is its ability to utilize different features extracted from various branches to accomplish reconstruction objectives. To supervise the training of the network, we generated regular-shaped and lung-shaped EIT datasets through numerical calculations. The simulations and three experiments demonstrate that the proposed SA-HFL exhibits superior performance in qualitative and quantitative analyses, compared with five cutting-edge deep learning networks and the optical image-guided group sparsity (IGGS) method. The evaluation metrics, relative error (RE), mean structural similarity index (MSSIM), and peak signal-to-noise ratio (PSNR), are improved by implementing the SA-HFL method. For the regular-shaped dataset, the values are 0.119 (RE), 0.9882 (MSSIM), and 31.03 (PSNR). For the lung-shaped dataset, the values are 0.257 (RE), 0.9151 (MSSIM), and 18.67 (PSNR). Furthermore, the proposed network can be executed with appropriate parameters and efficient floating-point operations per second (FLOPs), concerning network complexity and inference speed. The reconstruction results indicate that fusing feature information from different branches enhances the accuracy of conductivity reconstruction in the EIT inverse problem. Moreover, the study shows that fusing different modalities of information to reconstruct the EIT conductivity distribution may be a future development direction.






# Summary. An optional shortened abstract.
summary: This study proposes a novel deep learning method, SA-HFL, that fuses multi-branch features to improve the accuracy and robustness of EIT conductivity reconstruction against noise and modeling errors.


tags:
- Source Themes
featured: true


url_pdf: https://www.sciencedirect.com/science/article/pii/S0169260723005278


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---


