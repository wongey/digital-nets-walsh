We investigate base $$b$$ Walsh functions for which the variance of the integral estimator based on a scrambled $$(0,m,s)$$-net in base $$b$$ is less than or equal to that of the Monte-Carlo estimator based on the same number of points.  First we compute the Walsh decomposition for the joint probability density function of two distinct points randomly chosen from a scrambled $$(t,m,s)$$-net in base $$b$$ in terms of certain counting numbers and simplify it in the special case $$t$$ is zero. Using this, we obtain an expression for the covariance of the integral estimator in terms of the Walsh coefficients of the function. Finally, we prove that the covariance of the integral estimator is negative when the Walsh coefficients of the function satisfy a certain decay condition. To do this, we use creative telescoping and recurrence solving algorithms from symbolic computation to find a sign equivalent closed form expression for the covariance term.

### Authors

- Jaspar Wiart, RICAM and Johannes Kepler University, [jaspar.wiart@jku.at](mailto:jaspar.wiart@jku.at)

- [Elaine Wong](https://sites.google.com/view/elainewong/home), Austrian Academy of Sciences, RICAM, [elaine.wong@ricam.oeaw.ac.at](mailto:elaine.wong@ricam.oeaw.ac.at)

### Files

- Update (November 10, 2020): This paper has been accepted to [Mathematics and Computers in Simulation](https://www.sciencedirect.com/journal/mathematics-and-computers-in-simulation) and is online with [DOI:10.1016/j.matcom.2020.10.026](https://doi.org/10.1016/j.matcom.2020.10.026). The preprint is available here: [arXiv:2006.06225](https://arxiv.org/abs/2006.06225). The Mathematica code can be downloaded from here: [MCSFiles.zip (1MB)](https://drive.google.com/file/d/1w-F5NX9YxLZzEc1YWa0xfoU2PQ_dqu89/view?usp=sharing).

  - (PDF Version) [computations.pdf](https://wongey.github.io/digital-nets-walsh/computations.pdf)
  - To run this notebook properly, the following Mathematica packages must be installed: [Guess](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/Guess.html), [HolonomicFunctions](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/HolonomicFunctions.html), [Sigma](https://www3.risc.jku.at/research/combinat/software/Sigma/index.php).
  
### <a id="casc2020">CASC 2020</a>

- Elaine gave a talk at [CASC 2020](http://www.casc-conference.org/2020/schedule.html) discussing the symbolic computation aspects of this paper:

  - [Static Slides](https://wongey.github.io/digital-nets-walsh/talkslides_noanimation.pdf)
  - [Extended Abstract](https://wongey.github.io/digital-nets-walsh/extendedabstract.pdf)

- <a id="cascpp">[Christoph Koutschan](http://koutschan.de/index.php) and Elaine wrote a sequel to this paper for the post proceedings of CASC, highlighting some of the technical details that were not mentioned in the original and showing different ways to speed up computations.

- Update (May 4, 2021): This sequel has been accepted to the CASC 2020 Special Issue of Springer [Mathematics in Computer Science](https://www.springer.com/journal/11786/) and is online with [DOI:10.1007/s11786-021-00514-3](https://doi.org/10.1007/s11786-021-00514-3). The preprint is available here [arXiv:2010.08889](https://arxiv.org/abs/2010.08889). The Mathematica code can be downloaded from here: [CASC2020Files.zip (3MB)](https://drive.google.com/file/d/1Q8g8ECuq0OKMWI2L-lawZ31f2EKVrK0n/view?usp=sharing).

  - (PDF Version) [CTsums.pdf](https://wongey.github.io/digital-nets-walsh/CTsums.pdf)
  - Required packages can be downloaded from [here](https://www3.risc.jku.at/research/combinat/software/ergosum/packages.html).
  
### Links to References

1. G. Andrews, P. Paule, and C. Schneider. [Plane partitions VI: Stem-bridge’s TSPP theorem.](https://www.sciencedirect.com/science/article/pii/S0196885804001356)   Advances in Applied Mathematics 34 (2005).

2. A. Bostan, P. Lairez, and B. Salvy [Multiple binomial sums.](https://doi.org/10.1016/j.jsc.2016.04.002) Journal of Symbolic Computation 80, 351–386 (2017). 

3. F. Chyzak, [Groebner  bases, symbolic summation and symbolic integration.](https://www.cambridge.org/core/books/grobner-bases-and-applications/grobner-bases-symbolic-summation-and-symbolic-integration/762AE2D70338CB5DD0D75E39D3DDF0B0) Groebner Bases and Applications UK: Cambridge University Press, pp. 32–60 (1997).

4. F. Chyzak, A. Mahboubi, T. Sibut-Pinote, and E. Tassi. [A computer-algebra-based formal proof of the irrationality of ζ(3).](https://doi.org/10.1007/978-3-319-08970-611) In: G. Klein, and R. Gamboa (eds.) Springer. ITP 2014: Interactive Theorem Proving 8558, 160–176 (2014). 

5. J. Dick  and  F. Pillichshammer. [Digital  Nets  and  Sequences:  Discrepancy  Theory  and  Quasi-Monte Carlo integration.](https://www.cambridge.org/core/books/digital-nets-and-sequences/8EB7ECB56318388BF9FA3504801D2A59#) UK: Cambridge University Press, 2010.

6. [DLMF.](http://dlmf.nist.gov/) NIST Digital Library of Mathematical Functions, 2019. F. W. J. Olver, A. B. Olde
Daalhuis, D. W. Lozier, B. I. Schneider, R. F. Boisvert, C. W. Clark, B. R. Miller and B. V. Saunders, eds.

7. M. Kauers, [Guessing Handbook.](http://www.risc.jku.at/research/combinat/software/Guess/) Technical Report 09-07, RISC Report Series, Johannes Kepler University, Linz, Austria, 2009.

8. M. Kauers, M. Jaroschek, and F. Johansson. [Ore Polynomials in Sage.](https://doi.org/10.1007/978-3-319-15081-96) Lecture Notes in Computer Science 8942, 105–125 (2015).

9. C. Koutschan, [Advanced Applications of the Holonomic Systems Approach.](http://koutschan.de/publ/Koutschan09/thesisKoutschan.pdf) Ph.D. Thesis, Johannes Kepler University, Linz, Austria (2009).

10. C. Koutschan, [HolonomicFunctions User’s Guide.](http://www.risc.jku.at/publications/download/risc_3934/hf.pdf) Technical Report 10-01, RISC Report Series, Johannes Kepler University, Linz, Austria, 2010.

11. R. Lyons, P. Paule, and A. Riese. [A computer proof of a series evaluation in termsof harmonic numbers.](https://link.springer.com/article/10.1007/s00200-002-0107-z) Applicable Algebra in Engineering, Communication  and Computing 13, 327–333 (2002)

12. H. Prodinger. [Descendants  in  heap  ordered  trees  or  a  triumph  of  computer algebra.](https://doi.org/10.37236/1253) The Electronic Journal of Combinatorics 3, R29 (1996).

13. C. Lemieux, [Negative Dependence, Scrambled Nets, and Variance Bounds.](https://pubsonline.informs.org/doi/10.1287/moor.2017.0861) Mathematics of Operations Research 43, 228–251 (2017).

14. H. Niederreiter, [Low-Discrepancy Point Sets Obtained by Digital Constructions over Finite Fields.](https://dml.cz/handle/10338.dmlcz/128322) Czechoslovakia Mathematics Journal 42, 143–166 (1992).

15. H. Niederreiter, [Random Number Generation and Quasi-Monte Carlo Methods.](https://www.ricam.oeaw.ac.at/files/people/siambook_nied.pdf) Vol. 63, SIAM CBMS-NSF Regional Conference Series in Applied Mathematics, 1992.

16. A. B. Owen, [Scrambled Net Variance for Integrals of Smooth Functions.](https://projecteuclid.org/euclid.aos/1031594731) The Annals of Statistics 25, No. 4, 1541–1562 (1997).

17. A. B. Owen, [Randomly Permuted $$(t, m, s)$$-nets and $$(t, s)$$-sequences.](https://link.springer.com/chapter/10.1007%2F978-1-4612-2552-2_19) Monte Carlo and Quasi-Monte Carlo Methods in Scientific Computing, 299–317 (1995).

18. A. B. Owen, [Variance and Discrepancy with Alternative Scramblings.](https://dl.acm.org/doi/10.1145/945511.945518) ACM Transactions on Modeling and Computer Simulation 13, 363–378 (2003).

19. C. Schneider, [Symbolic Summation Assists Combinatorics.](http://www.risc.jku.at/research/combinat/software/Sigma/) Séminaire Lotharingien de Combinatoire 56, 1–36, Article B56b (2007).

20. J. L. Walsh, [A Closed Set of Normal Orthogonal Functions.](https://www.semanticscholar.org/paper/A-Closed-Set-of-Normal-Orthogonal-Functions-Walsh/ad391e1110899d902f912d649fb05bd83f12781e) American Journal of Mathematics 45(1), 5-24 (1923).

21. K. Wegschaider. [Computer generated proofs of binomial multi-sum identities.](https://www3.risc.jku.at/publications/download/risc_2245/diplom.ps) Ph.D. Thesis, Johannes Kepler University, Linz, Austria (1997).

22. J. Wiart, C. Lemieux, and G. Dong, [On the Dependence Structure of Scrambled $$(t, m, s)$$-nets.](https://doi.org/10.1515/mcma-2020-2079) Monte Carlo Methods and Applications 27(1), 1-26 (2021).

23. D. Zeilberger, [A Holonomic Systems Approach to Special Functions Identities.](https://www.sciencedirect.com/science/article/pii/037704279090042X) Journal of Computational and Applied Mathematics 32, 321–368 (1990).

24. D. Zeilberger, [The Method of Creative Telescoping.](https://www.sciencedirect.com/science/article/pii/S0747717108800442) Journal of Symbolic Computation 11, 195-204 (1991).

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
