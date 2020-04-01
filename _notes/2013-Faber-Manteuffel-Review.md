---
title: 'On short recurrences in optimal Krylov subspace solvers'
collection: Notes
permalink: /notes/2013-Faber-Manteuffel-Review
excerpt: ''
type: 'Technical report'
date: 2013-09-01
paper_authors: '<b>Casper Beentjes</b>'
preprinturl: 'https://cbeentjes.github.io/files/Ramblings/ShortRecurrenceKrylov.pdf'
bitbucket_url: 'https://bitbucket.org/CasperBeentjes/short-recurrence-optimal-krylov-solvers'
citation: ' <b>Casper Beentjes</b>, &quot;On short recurrences in optimal Krylov subspace solvers.&quot; Technical Report, Leiden University (2013).'
---
Abstract:
To solve large sparse linear systems of equations computational fast methods are preferable above methods such as GMRES. By exploiting structure of the involved matrix one can in certain cases use short-recurrences to create an optimal Krylov subspace method. In this report we explain some of the theory regarding short-recurrence methods for solving linear systems. A central object in this theory is the Faber-Manteuffel theorem of which some extensions are given in this report as well. After the theory two actual algorithms which use these short-recurrences are discussed and tested, SUMR for shifted and scaled unitary matrices and PGMRES for nearly Hermitian matrices. Some theory is given for both methods and they are numerically tested against alternative methods.
