---
layout: page
title: Laser Capture Microdissection RNA-seq in <i>Pocillopora acuta</i>
description: Chapter two of my dissertation, now published in <i>PLOS One</i> (2026).
img: assets/img/publication_preview/Dellaert_2026.png
importance: 2
category: research
related_publications: false
github: https://github.com/zdellaert/LaserCoral
---

We used Laser Capture Microdissection to isolate distinct tissue regions of the reef-building coral *Pocillopora acuta*, then performed RNA-seq to identify location-specific gene expression.

## Publication

Dellaert, Z. and Putnam, H. M. (2026). Spatially resolved gene expression analysis illuminates location-specific functions in the reef-building coral *Pocillopora acuta*. *PLOS One* 21, e0358454. [Open Access!](https://dx.plos.org/10.1371/journal.pone.0358454)

<img src="https://raw.githubusercontent.com/zdellaert/LaserCoral/main/references/Figure2.png" alt="Figure 2" style="max-width: 500px; width: 100%;">

## Data and code

All analysis code is on [GitHub](https://github.com/zdellaert/LaserCoral). Raw sequencing data is available on [SRA under BioProject PRJNA1209584](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1209584).

Key analysis pipelines:
- [Bioinformatics pipeline (raw reads to gene counts)](https://github.com/zdellaert/LaserCoral/blob/main/code/RNA-seq-bioinf.md)
- [Differential expression (DESeq2)](https://github.com/zdellaert/LaserCoral/blob/main/code/02-DE.md)
- [GO enrichment with Viseago/topGO](https://github.com/zdellaert/LaserCoral/blob/main/code/06-Semantic-Enrichment.Rmd)
- [Code for plotting the published figures](https://github.com/zdellaert/LaserCoral/blob/main/code/Final_Figures.md)
- [Supplementary tables](https://github.com/zdellaert/LaserCoral/blob/main/Supplementary_Tables.xlsx)

Expression in the dissected tissues was compared to the published coral "biomineralization toolkit" (Scucchia et al., [2021a](https://doi.org/10.1111/gcb.15812); [2021b](https://doi.org/10.1098/rspb.2021.0328)) and the *Stylophora pistillata* single-cell atlas ([Levy et al., 2021](https://doi.org/10.1016/j.cell.2021.04.005)).

[![LaserCoral repo](https://github-stats-extended.vercel.app/api/pin/?username=zdellaert&repo=LaserCoral&theme=shadow_green)](https://github.com/zdellaert/LaserCoral)