---
title: 1 x 1
summary: Package Re-identification system 
tags:
  - Deep Learning
  - Computer Vision
date: '2021-12-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Diagram of package fingerprint generation
  focal_point: 

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

1x1 is a package re-identification system that allows users to load images of unique packages with a tag into the system and then query with a new image of one of the inserted packages to identify which tag it was linked to. The system generates a fingerprint for each package by first isolating the package via background removal and then generating features through a color histogram, dimensions of the package and a contrastive encoder. These fingerprints can then be used to match images to package, as 2 images of the same package will have a similar fingerprint. In our tests, we are able to acheive above 90% accuracy in re-identifiying boxes for a test sample of 200+ boxes. 
