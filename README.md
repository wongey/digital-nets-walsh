We investigate base $$b$$ Walsh functions for which the variance of the integral estimator based on a scrambled $$(0,m,s)$$-net in base $$b$$ is less than or equal to that of the Monte-Carlo estimator based on the same number of points.  First we compute the Walsh decomposition for the joint probability density function of two distinct points randomly chosen from a scrambled $$(t,m,s)$$-net in base $$b$$ in terms of certain counting numbers and simplify it in the special case $$t$$ is zero. Using this, we obtain an expression for the covariance of the integral estimator in terms of the Walsh coefficients of the function. Finally, we prove that the covariance of the integral estimator is negative when the Walsh coefficients of the function satisfy a certain decay condition. To do this, we use creative telescoping and recurrence solving algorithms from symbolic computation to find a sign equivalent closed form expression for the covariance term.

### Authors

- Jaspar Wiart, RICAM and Johannes Kepler University, [jaspar.wiart@jku.at](mailto:jaspar.wiart@jku.at)

- Elaine Wong, Austrian Academy of Sciences, RICAM, [elaine.wong@ricam.oeaw.ac.at](mailto:elaine.wong@ricam.oeaw.ac.at)

### Files

- This paper has been submitted for publication (preprint on [arXiv:2006.06225](https://arxiv.org/abs/2006.06225)). 

- The Mathematica notebook containing all computations for the paper is [available for download](https://wongey.github.io/digital-nets-walsh/computations.nb). To run this notebook properly, the following Mathematica packages must be installed:
  - [Guess](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/Guess.html),
  - [HolonomicFunctions](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/HolonomicFunctions.html),
  - [Sigma](https://www3.risc.jku.at/research/combinat/software/Sigma/index.php).

- Furthermore, some objects took a long time to compute. We include it here for your convenience (must be saved in the same directory as the notebook): 
  - [ctouter2](https://wongey.github.io/digital-nets-walsh/ctouter2.m),
  - [R2](https://wongey.github.io/digital-nets-walsh/R2.m).

- For those without a Mathematica installation, we offer a [pdf version](https://wongey.github.io/digital-nets-walsh/computations.pdf) of the notebook.

### Links to References

1. J. Dick  and  F. Pillichshammer. [Digital  nets  and  sequences:  Discrepancy  theory  and  quasi-monte carlo integration.](https://www.cambridge.org/core/books/digital-nets-and-sequences/8EB7ECB56318388BF9FA3504801D2A59#) UK: Cambridge University Press, 2010.

2. [DLMF](http://dlmf.nist.gov/). NIST digital library of mathematical functions, 2019. F. W. J. Olver, A. B. Olde
Daalhuis, D. W. Lozier, B. I. Schneider, R. F. Boisvert, C. W. Clark, B. R. Miller and B. V.
Saunders, eds.

3. M. Kauers, [Guessing handbook.](http://www.risc.jku.at/research/combinat/software/Guess/) Technical Report 09-07, RISC Report Series, Johannes Kepler University, Linz, Austria, 2009.

4. C. Koutschan, [Advanced applications of the holonomic systems approach.](http://koutschan.de/publ/Koutschan09/thesisKoutschan.pdf), Ph.D. Thesis, Linz, Austria, 2009.

5. C. Koutschan, [HolonomicFunctions user’s guide.](http://www.risc.jku.at/publications/download/risc_3934/hf.pdf) Technical Report 10-01, RISC Report Series, Johannes Kepler University, Linz, Austria, 2010.

6. C. Lemieux, [Negative dependence, scrambled nets, and variance bounds.](https://pubsonline.informs.org/doi/10.1287/moor.2017.0861) Mathematics of Operations Research 43 (2017), 228–251.

7. H. Niederreiter, [Low-discrepancy point sets obtained by digital constructions over finite fields.](https://dml.cz/handle/10338.dmlcz/128322) Czechoslovak Math. J 42 (1992), 143–166.

8. H. Niederreiter, [Random number generation and quasi-monte carlo methods.](https://www.ricam.oeaw.ac.at/files/people/siambook_nied.pdf) Vol. 63, SIAM CBMS-NSF Regional Conference Series in Applied Mathematics, 1992.

9. A. B. Owen, [Scrambled net variance for integrals of smooth functions.](https://projecteuclid.org/euclid.aos/1031594731) The Annals of Statistics 25 (1997), no. 4, 1541–1562.

10. A. B. Owen, [Randomly permuted (t, m, s)-nets and (t, s)-sequences.](https://link.springer.com/chapter/10.1007%2F978-1-4612-2552-2_19) Monte carlo and quasi-monte carlo methods in Scientific Computing, 1995, pp. 299–317.

11. A. B. Owen, [Variance and discrepancy with alternative scramblings.](https://dl.acm.org/doi/10.1145/945511.945518) ACM Transactions on Modeling and Computer Simulation 13 (2003), 363–378.

12. C. Schneider, [Symbolic summation assists combinatorics.](http://www.risc.jku.at/research/combinat/software/Sigma/) Séminaire Lotharingien de Combinatoire 56 (2007), 1–36. Article B56b.

13. J. L. Walsh, [A closed set of normal orthogonal functions.](https://www.semanticscholar.org/paper/A-Closed-Set-of-Normal-Orthogonal-Functions-Walsh/ad391e1110899d902f912d649fb05bd83f12781e) Amer. J. Math. 45 (192211).

14. J. Wiart, C. Lemieux, and G. Dong, [On the dependence structure of scrambled (t, m, s)-nets.](https://arxiv.org/abs/1903.09877) arXiv e-prints (2019), submitted for publication (arXiv:1903.09877).

15. D. Zeilberger, [The method of creative telescoping.](https://www.sciencedirect.com/science/article/pii/S0747717108800442) Journal of Symbolic Computation 11 (1991), 195-204.

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
