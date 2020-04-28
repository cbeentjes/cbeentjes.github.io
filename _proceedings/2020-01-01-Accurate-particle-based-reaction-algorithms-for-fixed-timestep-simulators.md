---
title: 'Accurate particle-based reaction algorithms for fixed timestep simulators'
collection: Proceedings
permalink: /proceeding/2020-01-01-Accurate-particle-based-reaction-algorithms-for-fixed-timestep-simulators
excerpt: ''
date: 2020-01-01
venue: '2018 MATRIX Annals'
paper_authors: 'Stuart Johnston,  Christopher Angstmann,  Satya Arjunan,  <b>Casper Beentjes</b>,  Adrien Coulier,  Samuel Isaacson,  Ash Khan,  Karen Lipkow,  Steven Andrews'
paperurl: 'http://link.springer.com/10.1007/978-3-030-38230-8_11'
preprinturl: 'https://cbeentjes.github.io/files/Preprints/MATRIX_Annals_2018.pdf'
citation: ' Stuart Johnston,  Christopher Angstmann,  Satya Arjunan,  <b>Casper Beentjes</b>,  Adrien Coulier,  Samuel Isaacson,  Ash Khan,  Karen Lipkow,  Steven Andrews, &quot;Accurate particle-based reaction algorithms for fixed timestep simulators.&quot; 2018 MATRIX Annals (2020).'
---
Abstract:
Particle-based simulators are widely used to study biochemical systems involving spatial transport and chemical reactions on sub-cellular length scales. Fixed time step methods can often offer good performance even when simulating complex many-particle systems. However, current reaction algorithms approximate more detailed molecular dynamics models either inaccurately or slowly. Here, we present new reaction algorithms that better approximate microscopic molecular dynamics models while maintaining good computational efficiency. A “Brownian bridge” algorithm samples reactions using reactant positions both before and after each diffusive step; its simulated dynamics exactly match those of appropriate underlying idealised models. Simpler but less accurate “RDF-matching” algorithms sample reactions by only using reactant positions after diffusive steps; they accurately reproduce the steady-state radial distribution function of the underlying idealised model. These algorithms can accurately approximate both commonly used reaction models and more realistic models that account for intermolecular potentials.
