---
layout: paper
title: "What’s Best for My Mesh? Convex or Non-Convex Regularisation for Mesh Optimisation."
year: "2021"
shortref: "IROS 2021"
nickname: smoothing-2022
journal: "IROS"
volume: 3
issue: 
pages: 
authors: 
image: /assets/images/papers/default-paper.svg
redirect_from: 
fulltext:
pdflink: 
github: 
pmid: 
pmcid: 
f1000: 
doi: 
dryad_doi:
figshare_doi: 
altmetric_id: 
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: []
---
{% include JB/setup %}

# Abstract 

A 3D mesh offers a rich yet lightweight representation of geometry and topology for the metric and semantic understanding of a robot’s scene. Noisy features are often used to generate the mesh which furthers the need for accurate regularisation. Current approaches tightly couple front-end optimisation with regularisation making it difficult to evaluate the choice of discretisation and regularisation on mesh accuracy. In this work, we aim to explicitly query the performance of a set of well-known convex and non-convex regularisers on the mesh optimisation problem. We then apply these norms to dense depth estimation from a mesh representation and evaluate their performance in indoor and outdoor environments.While we show that the use of exotic, non-convex regularisers such as logTV and logTGV can result in more faithful structural reconstruction under noise, this comes at the cost of stronger outlier persistence...