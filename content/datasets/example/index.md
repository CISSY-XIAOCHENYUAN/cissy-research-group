---
title: IML-MPU Dataset for Multi-Tamper (Splicing, Copy-Move and Removal)
summary: IML-MPU is a large-scale synthetic forgery dataset generating by **Photoshop scripting (PS-Scripting)**, using a diverse set of samples sourced from VISION, KCMI, and own photographs selected as original images. The dataset comprises three distinct subsets, namely copy-move, splicing, and removal, consisting of **38,000**, **43,000**, and **32,000** images, respectively. It contains uncompressed TIFF images and JPEG images with different compression factors.

tags:
  - Image Forensic
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
  - icon: download
    icon_pack: fas
    name: Download Dataset
    url: 'slides/example'
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

The specific generation flows are shown in Fig. 1 and Fig. 2. First, we manually select the tamper target through Labelme based on the Original Image and generate the corresponding mask. After obtaining the minimum rectangles e and f of the tamper target and resizing them using binary operations, the final copy-move forgery image is generated using the Region of Interest (ROI) selection algorithm in OpenCV. The representation of this workflow is illustrated in Figure 1 (I), while Figure 1 (II) presents the similarity flow for corresponding ground-truth generation.
