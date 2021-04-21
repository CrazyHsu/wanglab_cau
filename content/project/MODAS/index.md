---
title: MODAS
summary: MODAS (Multi-Omics Data Association Study toolkit) is an efficient software for high-dimensional omics data association analysis
tags:
- Tools
date: "2021-04-21"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

MODAS (Multi-Omics Data Association Study toolkit) is an efficient software for high-dimensional omics data association analysis. A major feature of MODAS is its novel genome-wide association analysis (GWAS) strategy for high-dimensional omics data. Firstly, MODAS generates pseudo-genotype files to reduce the dimensionality of the original SNP-based genotype data; then, it performs block-based GWAS to screen out the significantly associated genomic regions (SAGRs); finally, it performs SNP-based association analysis on the SAGRs to obtain the QTLs for the high-dimensional omics data. Another feature of MODAS is that it introduces Mendelian randomization algorithm to infer the genetic regulation relationship between omics-data related QTLs, which helps biological hypothesis establishment. Moreover, a HTML based web page is implemented in MODAS for the visualization and query of omics-data based GWAS results, which facilitate further gene function mining.

MODAS was developed by [Songyu Liu](/authors/songyu-liu/) in 2021.

Please read the [tutorial](https://modas-bio.github.io/) for details!
