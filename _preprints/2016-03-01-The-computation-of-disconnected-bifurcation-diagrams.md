---
title: 'The computation of disconnected bifurcation diagrams'
collection: Preprints
permalink: /preprint/2016-03-01-The-computation-of-disconnected-bifurcation-diagrams
excerpt: ''
date: 2016-03-01
paper_authors: 'Patrick Farrell,  <b>Casper Beentjes</b>, &Aacute;sgeir Birkisson'
paperurl: 'http://arxiv.org/abs/1603.00809'
preprinturl: '1603.00809'
citation: ' Patrick Farrell,  <b>Casper Beentjes</b>, &Aacute;sgeir Birkisson, &quot;The computation of disconnected bifurcation diagrams.&quot; arXiv:1603.00809 [math.NA].'
---
Abstract:
Arclength continuation and branch switching are enormously successful algorithms for the computation of bifurcation diagrams. Nevertheless, their combination suffers from three significant disadvantages. The first is that they attempt to compute only the part of the diagram that is continuously connected to the initial data; disconnected branches are overlooked. The second is that the subproblems required (typically determinant calculation and nullspace construction) are expensive and hard to scale to very large discretizations. The third is that they can miss connected branches associated with nonsimple bifurcations, such as when an eigenvalue of even multiplicity crosses the origin. Without expert knowledge or lucky guesses, these techniques alone can paint an incomplete picture of the dynamics of a system. In this paper we propose a new algorithm for computing bifurcation diagrams, called deflated continuation, that is capable of overcoming all three of these disadvantages. The algorithm combines classical continuation with a deflation technique that elegantly eliminates known branches from consideration, allowing the discovery of disconnected branches with Newton&apos;s method. Deflated continuation does not rely on any device for detecting bifurcations and does not involve computing eigendecompositions; all subproblems required in deflated continuation can be solved efficiently if a good preconditioner is available for the underlying nonlinear problem. We prove sufficient conditions for the convergence of Newton&apos;s method to multiple solutions from the same initial guess, providing insight into which unknown branches will be discovered. We illustrate the success of the method on several examples where standard techniques fail.
