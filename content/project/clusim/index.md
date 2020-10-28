---
title: CluSim
summary: "CluSim: a package for calculating clustering similarity."
tags:
- Code
- Clustering
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Comparing clusters.
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  link: "https://github.com/Hoosier-Clusters/clusim"
- icon: book
  icon_pack: fa
  link: "https://hoosier-clusters.github.io/clusim/html/clusim.html"
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

Clustering reveals the coarse-grained structure of data. However, to understand, evaluate, and leverage data clusterings, we need to quantitatively compare them. Clustering comparison forms the backbone of many tasks, including method evaluations, consensus clustering, and tracking the temporal evolution of clusters.

Take, for example, the evaluation of a clustering or community detection method.  To determine if the method is recovering a known feature of the data, it is necessary to compare the method’s result to a planted reference (a.k.a. ground truth) clustering, assuming that the more similar the method’s solution is to the reference clustering, the better the method.

Despite the importance of clustering comparison, no consensus has been reached for a standardized assessment; many, many clustering similarity methods exist, and each similarity measure rewards and penalizes different criteria, sometimes producing contradictory conclusions.  The situtation is even worse for generalized definitions of clusterings that include overlaps or hierarchy.

**CluSim** is a python package providing a unified library of over 20 clustering similarity measures for partitions, dendrograms, and overlapping clusterings.

Read More:
---------------
{{< cite page="/publication/randomcluster" view="1" >}}

{{< cite page="/publication/elementcentric" view="1" >}}

{{< cite page="/publication/clusim" view="1" >}}