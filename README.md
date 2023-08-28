We investigate base $b$ Walsh functions for which the variance of the integral estimator based on a scrambled $(0,m,s)$-net in base $b$ is less than or equal to that of the Monte-Carlo estimator based on the same number of points.  First we compute the Walsh decomposition for the joint probability density function of two distinct points randomly chosen from a scrambled $(t,m,s)$-net in base $b$ in terms of certain counting numbers and simplify it in the special case $t$ is zero. Using this, we obtain an expression for the covariance of the integral estimator in terms of the Walsh coefficients of the function. Finally, we prove that the covariance of the integral estimator is negative when the Walsh coefficients of the function satisfy a certain decay condition. To do this, we use creative telescoping and recurrence solving algorithms from symbolic computation to find a sign equivalent closed form expression for the covariance term.

### Authors

- Jaspar Wiart
  - Previous Affiliation: Johannes Kepler University, Linz, Austria
  - Previous Affiliation: Austrian Academy of Sciences, RICAM

- [Elaine Wong](https://wongey.com), Oak Ridge National Laboratory, USA
  - Contact: [wongey@ornl.gov](wongey@ornl.gov)
  - Previous Affiliation: Austrian Academy of Sciences, RICAM

### Paper and Code

- This paper has been accepted to [Mathematics and Computers in Simulation](https://www.sciencedirect.com/journal/mathematics-and-computers-in-simulation) and is online with [DOI:10.1016/j.matcom.2020.10.026](https://doi.org/10.1016/j.matcom.2020.10.026). The preprint is available here: [arXiv:2006.06225](https://arxiv.org/abs/2006.06225). The Mathematica code can be downloaded from here: [MCSFiles.zip (1MB)](https://drive.google.com/file/d/1w-F5NX9YxLZzEc1YWa0xfoU2PQ_dqu89/view?usp=sharing).

  - (PDF Version) [computations.pdf](https://wongey.github.io/digital-nets-walsh/computations.pdf)
  - To run this notebook properly, the following Mathematica packages must be installed: [Guess](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/Guess.html), [HolonomicFunctions](https://www3.risc.jku.at/research/combinat/software/ergosum/RISC/HolonomicFunctions.html), [Sigma](https://www3.risc.jku.at/research/combinat/software/Sigma/index.php).
  
### <a id="casc2020">CASC 2020</a>

- Elaine gave a talk at [CASC 2020](http://www.casc-conference.org/2020/schedule.html) discussing the symbolic computation aspects of this paper:

  - [Static Slides](https://wongey.github.io/digital-nets-walsh/talkslides_noanimation.pdf)
  - [Extended Abstract](https://wongey.github.io/digital-nets-walsh/extendedabstract.pdf)

- <a id="cascpp">[Christoph Koutschan](http://koutschan.de/index.php) and Elaine wrote a sequel to this paper for the post proceedings of CASC, highlighting some of the technical details that were not mentioned in the original and showing different ways to speed up computations. It has been accepted to the CASC 2020 Special Issue of Springer [Mathematics in Computer Science](https://www.springer.com/journal/11786/) and is online with [DOI:10.1007/s11786-021-00514-3](https://doi.org/10.1007/s11786-021-00514-3). The preprint is available here [arXiv:2010.08889](https://arxiv.org/abs/2010.08889). The Mathematica code can be downloaded from here: [CASC2020Files.zip (3MB)](https://drive.google.com/file/d/1Q8g8ECuq0OKMWI2L-lawZ31f2EKVrK0n/view?usp=sharing).

  - (PDF Version) [CTsums.pdf](https://wongey.github.io/digital-nets-walsh/CTsums.pdf)
  - Required packages can be downloaded from [here](https://www3.risc.jku.at/research/combinat/software/ergosum/packages.html).
  - Errata (July 2021): Section 3.8 - there is a missing negative sign in front of the given rational function. This is just a typo and the written conclusion holds with the typo fixed.

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
