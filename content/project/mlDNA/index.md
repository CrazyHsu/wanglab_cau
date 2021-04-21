---
title: mlDNA
summary: mlDNA:Machine Learning-based Differential Network Analysis of Transcriptome Data
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

Machine learning (ML) is an intelligent data mining technique that builds a prediction model based on the learning of prior knowledge to recognize patterns in large-scale data sets. We present an ML-based methodology for transcriptome analysis via comparison of gene coexpression networks, implemented as an R package called machine learning-based differential network analysis ([mlDNA](https://cran.r-project.org/web/packages/mlDNA/index.html)) and apply this method to reanalyze a set of abiotic stress expression data in Arabidopsis thaliana.

The mlDNA first used a ML-based filtering process to remove nonexpressed, constitutively expressed, or non-stress-responsive "noninformative" genes prior to network construction, through learning the patterns of 32 expression characteristics of known stress-related genes. The retained "informative" genes were subsequently analyzed by ML-based network comparison to predict candidate stress-related genes showing expression and network differences between control and stress networks, based on 33 network topological characteristics. Comparative evaluation of the network-centric and gene-centric analytic methods showed that mlDNA substantially outperformed traditional statistical testing-based differential expression analysis at identifying stress-related genes, with markedly improved prediction accuracy.

mlDNA was developed by [Chuang Ma](/authors/chuang-ma/) in 2013.
