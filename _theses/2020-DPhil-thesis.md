---
title: 'Variance reduction techniques for chemical reaction network simulation'
collection: Theses
permalink: /theses/2020-06-01-DPhil-thesis
excerpt: ''
type: 'DPhil thesis'
date: 2020-06-01
paper_authors: '<b>Casper Beentjes</b>'
preprinturl: 'https://cbeentjes.github.io/files/Ramblings/DPhilBeentjes.pdf'
citation: ' <b>Casper Beentjes</b>, &quot;Variance reduction techniques for chemical reaction network simulation.&quot; PhD thesis, University of Oxford (2020).'
---
Abstract:
In recent decades stochastic models have become an indispensable tool when analysing quantitative biological data, which are often subject to noise, both from intrinsic and extrinsic sources. Though such models generate richer, and perhaps more realistic, behaviour than their counterpart deterministic models, they are also inherently more difficult to study. Since exact solutions describing the dynamics of stochastic models are scarce, one is often forced to resort to simulation of these models using Monte Carlo methods, which are generally easy to implement. However, the output of such computational methods is itself subject to statistical error, and consequently it is often computationally demanding to get numerical predictions from stochastic models to a satisfactory degree of accuracy.

In this thesis we therefore consider methods that improve the efficiency of stochastic simulation algorithms, specifically in the context of well-mixed chemical reaction network models. We primarily achieve this by utilising variance reduction techniques to reduce statistical error in the outputs of simulation algorithms without incurring extra computational costs. In particular, as our key contribution, we study three different ideas leading to more efficient simulation approaches.

Firstly, we derive an efficient implementation of the uniformisation technique for continuous-time Markov chain models. Using stratified sampling we can leverage the extra structure in a uniformised chemical reaction network to subsequently produce a more efficient simulation method. In addition we show how to use the uniformisation technique to reduce statistical error via what is effectively a low-pass filter. 

Secondly, we study the synthesis of quasi-Monte Carlo methodology with simulation methods for chemical reaction network models. Whilst such methods can significantly improve efficiency, we show that, due to the problem structure of chemical reaction network models, care must be taken in the specific implementation choices, both regarding the quasi-Monte Carlo techniques and simulation methods. 

Lastly, we provide a significantly improved method for generating unit-rate Poisson processes via Poisson bridge constructions in combination with antithetic sampling. This method is subsequently used to improve the efficiency of standard simulation algorithms for chemical reaction networks.
