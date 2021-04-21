---
title: KGBassembler
summary: KGBassembler:A karyotype-based genome assembler for Brassicaceae species
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

[KGBassembler](http://www.cmbb.arizona.edu/KGBassembler/) is a tool used to assemble full chromosomes from scaffolds if a karyotype is provided. The KGBassembler is featured with a user-friendly graphical user interface (GUI), allowing users to use automatic assembling of chromosomes based on CCP-based karyotypes and/or to manually edit the layouts of contigs according to in silico generated karyotypes. KGBassembler runs in three steps (Phases I–III). Phase I (Contigs2Blocks) is to identify the 24 blocks in contigs via analyzing BLAT alignments using two algorithms: local and global search. KGBassembler was implemented in C++ with a GUI built with the open-source QT toolbox.

KGBassembler was developed by [Chuang Ma](/authors/chuang-ma/) in 2011
