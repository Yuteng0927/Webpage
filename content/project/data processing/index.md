---
title: Single-molecule data processing pipeline 
summary: We developed a computational system designed to analyze raw data obtained from imaging techniques used in biological research, such as fluorescence microscopy.
tags:
- biological data
date: "2018-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: ""
  preview_only: false

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


### Research Summary
The first step in this process is the localization extraction of individual molecules within the image. This is accomplished by using specialized algorithms that detect the signal emitted from fluorescent markers that are attached to molecules of interest. These algorithms identify the precise location of each molecule, which can then be used to construct a high-resolution image of the sample.
The next step is to reconstruct a three-dimensional (3D) image from the data obtained in the previous step. This requires the use of advanced computational methods to analyze the positions of individual molecules in multiple planes and to generate a 3D model of the sample.

