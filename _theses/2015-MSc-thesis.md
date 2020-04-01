---
title: 'Computing bifurcation diagrams with deflation'
collection: Theses
permalink: /theses/2015-09-01-MSc-thesis
excerpt: ''
type: 'MSc thesis'
date: 2015-09-01
paper_authors: '<b>Casper Beentjes</b>'
preprinturl: 'https://cbeentjes.github.io/files/Ramblings/MScBeentjes.pdf'
bitbucket_url: 'https://bitbucket.org/CasperBeentjes/files-msc-dissertation'
citation: ' <b>Casper Beentjes</b>, &quot;Computing bifurcation diagrams with deflation.&quot; MSc thesis, University of Oxford (2015).'
---
Abstract:
One of the main deficiencies of current methods in numerical bifurcation analysis is their inability to detect solution branches without first locating a bifurcation point. As a result these methods cannot compute disconnected bifurcation branches, or branches that connect outside of the parameter domain of study. Furthermore, the detection techniques for bifurcation points are not problem-scale invariant. As a result the cost of computing bifurcation points in large-scale systems is often a prohibiting factor in the computation of bifurcation diagrams. In this thesis we propose a method to overcome these two issues. 

We study the use of deflation techniques combined with Newton's method to generate multiple solution branches starting from a single initial solution. A theoretical framework for root-convergence and deflation of functions in Banach spaces is set up. In this framework we derive the first sufficient conditions for convergence towards multiple solutions if Newton's method and deflation are combined. 

Deflation can be made a scalable technique and as a result could be used in tracing out bifurcation diagrams for large-scale systems. We compare arclength continuation augmented with deflation as a method to compute bifurcation diagrams with AUTO-07P, one of the most used and reliable numerical bifurcation software packages available. We find that for a range of illustrative problems AUTO-07P fails to compute complete bifurcation diagrams, whereas deflation and continuation combined yield an accurate result.
