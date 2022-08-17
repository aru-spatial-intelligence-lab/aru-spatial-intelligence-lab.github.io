---
layout: paper
title: "Smoothing Away From The Edge For Mesh Estimation in Urban Outdoor Environments."
year: "2022"
shortref: "ICRA 2022"
nickname: smoothing-2022
journal: "ICRA"
volume: 
issue: 
pages: 
authors: "Jason Pilbrough, Paul Amayo"
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

3D meshes offer a computationally efficient but still quite accurate path to the understanding of a robot's environment. While mesh reconstructions are often employed in indoor regions where regular planar surfaces dominate the scene, their use in urban outdoor environments has been under-explored.  This is as outdoor urban environments produce a significant contrast between preserving discontinuities between different objects and maintaining smoothness in the solution. When coupled with the natural sparse nature of meshes this presents a significant challenge to their optimisation.
    
Motivated by these challenges and leveraging insights from computer graphics, we firstly balance previously introduced real-time definitions of variational smoothing on meshes with their 'canonical' definitions. In doing so we introduce a novel Delaunay-Voronoi formulation for real-time mesh smoothing that allows for the accumulation of information away from the triangular edges. This allows for the use of more powerful non-convex regularisers that are able to more finely balance smoothness and object discontinuities and showcase more faithful reconstructions of the urban outdoor scene. In doing so the benefits of non-convex regularisers promised in the `every-pixel' scenarios can now be inherited by sparse mesh formulations.
