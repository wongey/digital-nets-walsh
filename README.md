## An Application of Symbolic Computation to Quasi-Monte Carlo Integration

We compute the base $b$ Walsh coefficients of the joint pdf of two distinct points randomly chosen from a scrambled $(0,m,s)$-net in base $b$ and use them to obtain a reasonable expression for $\cov(f(\BFU_I), f(\BFU_J))$ in terms of the Walsh coefficients of the function $f$ over the unit hypercube. From there, we illustrate that algorithms from symbolic computation have a good chance of simplifying the sum to certain closed forms for analysis. In this way, we were able to further show that under a reasonable assumption on the decay of the Walsh coefficients of $f$ that $\cov(f(\BFU_I),f(\BFU_J))\leq 0$. Thus, the randomized Quasi-Monte Carlo (RQMC) estimator for the integral of such functions based on scrambled $(0,m,s)$-nets in base $b$ will do no worse than the Monte-Carlo (MC) estimator based on the same number of points. One of the features of this paper is to reveal how symbolic computation methods can be conducive to the computations that arise in the area of Quasi-Monte Carlo integration.

Authors:

Jaspar Wiart, Austrian Academy of Sciences, RICAM and Johannes Kepler University, jaspar.wiart@jku.at

Elaine Wong, Austrian Academy of Sciences, RICAM, elaine.wong@ricam.oeaw.ac.at

### Files

digital-nets-walsh files

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

12. M. Petkovsek, H. S. Wilf, and D. Zeilberger, [A=B.](https://www.math.upenn.edu/~wilf/AeqB.html) A K Peters/CRC Press, 1996.

13. C. Schneider, [Symbolic summation assists combinatorics.](http://www.risc.jku.at/research/combinat/software/Sigma/) Séminaire Lotharingien de Combinatoire 56 (2007), 1–36. Article B56b.

14. J. L. Walsh, [A closed set of normal orthogonal functions.](https://www.semanticscholar.org/paper/A-Closed-Set-of-Normal-Orthogonal-Functions-Walsh/ad391e1110899d902f912d649fb05bd83f12781e) Amer. J. Math. 45 (192211).

15. J. Wiart, C. Lemieux, and G. Dong, [On the dependence structure of scrambled (t, m, s)-nets.](https://arxiv.org/abs/1903.09877) arXiv e-prints (2019), submitted for publication (arXiv:1903.09877).

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
