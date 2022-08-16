---
layout: paper
title: "Geometric Multi-Model Fitting with a Convex Relaxation Algorithm"
year: "2018"
shortref: "AmayoCVPR"
nickname: smoothing-2022
journal: "CVPR"
volume: 3
issue: 
pages: 
authors: "Paul Amayo, Pedro Piniés, Lina M Paz, Paul Newman"
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

We propose a novel method for fitting multiple geometric models to multi-structural data via convex relaxation. Unlike greedy methods-which maximise the number of inliers-our approach efficiently searches for a soft assignment of points to geometric models by minimising the energy of the overall assignment. The inherently parallel nature of our approach, as compared to the sequential approach found in state-of-the-art energy minimisation techniques, allows for the elegant treatment of a scaling factor that occurs as the number of features in the data increases. This results in an energy minimisation that, per iteration, is as much as two orders of magnitude faster on comparable architectures thus bringing real-time, robust performance to a wider set of geometric multi-model fitting problems. We demonstrate the versatility of our approach on two canonical problems in estimating structure from images: plane extraction from RGB-D images and homography estimation from pairs of images. Our approach seamlessly adapts to the different metrics brought forth in these distinct problems. In both cases, we report results on publicly available data-sets that in most instances outperform the state-of-the-art while simultaneously presenting run-times that are as much as an order of magnitude faster.