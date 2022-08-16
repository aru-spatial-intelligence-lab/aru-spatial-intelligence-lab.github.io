---
layout: paper
title: "Semantic classification of road markings from geometric primitives"
year: "2018"
shortref: "Amayo 2018"
nickname: smoothing-2022
journal: "ITSC"
volume: 
issue: 
pages: 
authors: "Paul Amayo, Tom Bruls, Paul Newman"
image:
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

The classification of semantically meaningful road markings in images is an important and safety critical task for autonomous and semi-autonomous vehicles. However, beyond simple lane markings, real-time detection and interpretation of road markings is challenging as images are subject to occlusions, partial observations, lighting changes and differing weather conditions. Additionally, there is high variation in the road markings between countries and regions, which makes interpretation difficult. In this work we present a three-fold approach to the semantic classification. Firstly, we employ a weakly supervised neural network to detect pixels belonging to road markings under different conditions. Subsequently, these pixels are classified into geometric primitives, from which we retrieve the semantic classes through a fast and parallel model-fitting algorithm that offers real-time performance. Unlike other methods in …