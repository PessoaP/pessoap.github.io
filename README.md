<link rel="stylesheet" type="text/css" href="assets/styles.css" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">


<a href="https://scholar.google.com/citations?hl=en&user=sw4MCXcAAAAJ" target="_blank">
  <i class="ai ai-google-scholar-square ai-3x"></i>
</a>
<a href="https://arxiv.org/search/?searchtype=author&query=Pessoa%2C+P" target="_blank">
  <i class="ai ai-arxiv ai-3x" style="color: red;"></i>
</a>
<!-- <a href="https://orcid.org/0000-0002-6258-5679/" target="_blank">
  <i class="ai ai-orcid-square ai-3x" style="color: #006000;"></i> -->
</a>
<a href="https://github.com/pessoap" target="_blank">
  <i class="fab fa-github fa-3x" style="color: black;"></i>
</a>
<a href="https://www.linkedin.com/in/ppessoa" target="_blank">
  <i class="fab fa-linkedin fa-3x"></i>
</a>
<a href="https://bsky.app/profile/pedropessoaphd.bsky.social" target="_blank">
  <i class="fab fa-bluesky fa-3x"></i>
</a>

[//]: $P^4$

<details>
<summary style="font-family: Arial; font-size: 32px; color: darkblue;"><strong> Blog </strong></summary>
    <details>
    <summary style="font-family: Arial; font-size: 24px;"><strong> Tutorials on Bayesian statistics </strong></summary>
    <ol>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-i-asserting-if-a-coin-is-biased-tutorial/">Why do we need Bayesian statistics? Part I – Asserting if a coin is biased</a> -- <a href="https://github.com/PessoaP/blog/blob/master/Coins/Coins.ipynb">GitHub </a> </li>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-ii-the-lighthouse-problem-tutorial/">Why do we need Bayesian statistics? Part II — The lighthouse problem</a> -- <a href="https://github.com/PessoaP/blog/blob/master/Lighthouse/Lighthouse.ipynb">GitHub </a></li>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-iii-learning-multivariate-distributions-tutorial">Why do we need Bayesian statistics? Part III – Learning multivariate distributions </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Lighthouse/Lighthouse2.ipynb">GitHub </a> </li>
        <li>  <a href="https://labpresse.com/2053-2/">Bayesian <span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal" style="margin-right: 0.03588em;">π</span> – Calculating <span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal" style="margin-right: 0.03588em;">π</span> with Monte Carlo </a> -- <a href="hhttps://github.com/PessoaP/blog/blob/master/Coins/PI.ipynb">GitHub </a> </li>
    </ol>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 24px;"><strong> Other blog posts </strong></summary>
    <ul>
        <li><a href="https://labpresse.com/solving-differential-equations-using-neural-networks/"> Solving differential equations using neural networks </a> -- <a href="https://github.com/PessoaP/blog/blob/master/PINN/PINN_tutorial.ipynb">GitHub </a></li>
        <li><a href="https://labpresse.com/a-primer-on-the-normal-distribution/"> A primer on the normal distribution </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Normal/normal.ipynb">GitHub </a></li>
        <li><a href="https://labpresse.com/which-method-should-i-use-a-guide-to-benchmarking/"> Which method should I use? – A guide to benchmarking </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Time/time_benchmark.ipynb">GitHub </a></li>
        <li><a href="https://labpresse.com/what-is-autograd-automatic-differentiation-and-optimization-with-pytorch/"> What is autograd? – Automatic differentiation and optimization with PyTorch </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Autograd/Autograd.ipynb">GitHub </a></li>
        <li><a href="https://labpresse.com/sparse-matrices-in-numba/"> Sparse Matrices in Numba (blog) </a> -- <a href="https://github.com/PessoaP/smn/blob/main/tutorial.ipynb">GitHub </a></li>
    </ul>
    </details>
</details>

<details>
<summary style="font-family: Arial; font-size: 32px; color: darkblue;"><strong> Selected Publications </strong></summary>
    <details>
        <summary style="font-family: Arial; font-size: 20px;"><strong> REPOP: A Tool for Bacterial Population Reconstruction with Uncertainty Quantification from Plate Counts   </strong></summary>
        <div class="paper">
            <p>
                <strong>Authors:</strong> 
                Pedro Pessoa, Carol Lu, Stanimir Asenov Tashev, Rory Kruithoff, Douglas P. Shepherd, Steve Pressé
            </p>
            <p> 
                <strong>Preprint:</strong> 
                <a href="https://doi.org/10.1101/2025.04.01.644179">Available at bioRxiv</a>
            </p>
            <div class="abstract">
                <h4>Abstract:</h4>
                <p>
                    Bacterial counts from native environments, such as soil or the animal gut, often show substantial variability across replicate samples. This heterogeneity is typically attributed to genetic or environmental factors. A common approach to estimating bacterial populations involves successive dilution and plating, followed by multiplying colony counts by dilution factors. This method, however, overestimates the heterogeneity in bacterial population because it conflates the inherent uncertainty in drawing a subsample from the total population with the uncertainty in the sample arising from biological origins. In other words, this approach may obscure features that may otherwise be present in the data hinting at the presence of genuine subpopulations. For example, in plate counting applied to <em>C. elegans</em> gut microbiota, observed multimodality is often interpreted as large host-to-host variance, while the randomness introduced by measurement is frequently ignored. To explicitly account for the uncertainty introduced by dilution and plating randomness, we introduce <strong>REPOP</strong>, a PyTorch-based library to <strong>RE</strong>construct <strong>PO</strong>ulations from <strong>P</strong>lates within a Bayesian framework. Beyond simple cases, REPOP addresses more complex scenarios, including multimodal populations and correcting the mathematically subtle, but experimentally relevant, bias introduced by excluding plates deemed too crowded to distinguish individual colonies. We demonstrate REPOP’s ability to resolve distinct population peaks otherwise obscured by standard multiplication methods. Applications to both simulated and experimental datasets, including bacterial samples of different concentrations and ones from the gut microbiota of <em>C. elegans</em>, show that REPOP accurately recovers the underlying multimodality by properly accounting for error propagation, where naive multiplication fails. REPOP is available on GitHub: <a href="https://github.com/PessoaP/REPOP" target="_blank">https://github.com/PessoaP/REPOP</a>.
                </p>
            </div>
        </div>
    </details>
    <details>
        <summary style="font-family: Arial; font-size: 20px;"><strong> Avoiding subtraction and division of stochastic signals using normalizing flows: NFdeconvolve </strong></summary>
        <div class="paper">
            <p>
                <strong>Authors:</strong> 
                Pedro Pessoa, Max Schweiger, Lance W.Q. Xu, Tristan Manha, Ayush Saurabh, Julian Antolin Camarena, Steve Pressé
            </p>
            <p> 
                <strong>Preprint:</strong> 
                <a href="https://arxiv.org/abs/2501.08288">Available at arXiv</a>
            </p>
            <div class="abstract">
                <h4>Abstract:</h4>
                <p>
                    Across the scientific realm, we find ourselves subtracting or dividing stochastic signals. For instance, consider a stochastic realization, x, generated from the addition or multiplication of two stochastic signals a and b, namely x = a + b or x = ab. For the x = a + b example, a can be fluorescence background and b the signal of interest whose statistics are to be learned from the measured x. Similarly, when writing x = ab, a can be thought of as the illumination intensity and b the density of fluorescent molecules of interest. Yet dividing or subtracting stochastic signals amplifies noise, and we ask instead whether, using the statistics of a and the measurement of x as input, we can recover the statistics of b. Here, we show how normalizing flows can generate an approximation of the probability distribution over b, thereby avoiding subtraction or division altogether. This method is implemented in our software package, NFdeconvolve, available on GitHub with a tutorial linked in the main text.
                </p>
            </div>
        </div>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> Avoiding matrix exponentials for large transition rate matrices </strong></summary>
    <div class="paper">
        <p>
            <strong>Published:</strong> 
            P Pessoa, M Schweiger, S Pressé (2024)  
            <a href="https://doi.org/10.1063/5.0190527"> Journal of Chemical Physics, 160, 094109 </a>
        </p>
        <p> 
            <strong>Preprint:</strong> 
            <a href="https://arxiv.org/abs/2312.05647">Available at arXiv</a>
        </p>
        <div class="abstract">
            <h4>Abstract:</h4>
            <p>
                Exact methods for exponentiation of matrices of dimension N can be computationally expensive in terms of execution time (N<sup>3</sup>) and memory requirements (N<sup>2</sup>) not to mention numerical precision issues. A type of matrix often exponentiated in the sciences is the rate matrix. Here we explore five methods to exponentiate rate matrices, some of which apply even more broadly to other matrix types. Three of the methods leverage a mathematical analogy between computing matrix elements of a matrix exponential and computing transition probabilities of a dynamical process (technically a Markov jump process, MJP, typically simulated using Gillespie). In doing so, we identify a novel MJP-based method relying on restricting the number of "trajectory" jumps based on the magnitude of the matrix elements with favorable computational scaling. We then discuss this method's downstream implications on mixing properties of Monte Carlo posterior samplers. We also benchmark two other methods of matrix exponentiation valid for any matrix (beyond rate matrices and, more generally, positive definite matrices) related to solving differential equations: Runge-Kutta integrators and Krylov subspace methods. Under conditions where both the largest matrix element and the number of non-vanishing elements scale linearly with N — reasonable conditions for rate matrices often exponentiated — computational time scaling with the most competitive methods (Krylov and one of the MJP-based methods) reduces to N<sup>2</sup> with total memory requirements of N.
            </p>
        </div>
    </div>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> How many submissions are needed to discover friendly suggested reviewers? </strong></summary>
    <div class="paper">
        <p>
            <strong>Published:</strong> 
            P Pessoa, S Pressé (2023) 
            <a href="https://doi.org/10.1371/journal.pone.0284212">  PLoS ONE, 18(4),  e0284212  </a>
        </p>
        <p>
            <strong>Preprint:</strong> 
            <a href="https://arxiv.org/abs/2210.00905">Available at arXiv</a>
        </p>
        <div class="abstract">
            <h4>Abstract:</h4>
            <p>
                It is common in scientific publishing to request from authors reviewer suggestions for their own manuscripts. The question then arises: How many submissions are needed to discover friendly suggested reviewers? To answer this question, as the data we would need is anonymized, we present an agent-based simulation of (single-blinded) peer review to generate synthetic data. We then use a Bayesian framework to classify suggested reviewers. To set a lower bound on the number of submissions possible, we create an optimistically simple model that should allow us to more readily deduce the degree of friendliness of the reviewer. Despite this model’s optimistic conditions, we find that one would need hundreds of submissions to classify even a small reviewer subset. Thus, it is virtually unfeasible under realistic conditions. This ensures that the peer review system is sufficiently robust to allow authors to suggest their own reviewers.
            </p>
        </div>
    </div>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> Bose-Einstein statistics for a finite number of particles </strong></summary>
    <div class="paper">
        <p>
            <strong>Published:</strong> 
            P Pessoa (2021) 
            <a href="https://doi.org/10.1103/PhysRevA.104.043318">  Physical Review A, 104, 043318 </a>
        </p>
        <p>
            <strong>Preprint:</strong> 
            <a href="https://arxiv.org/abs/2110.02890">Available at arXiv</a>
        </p>
        <div class="abstract">
            <h4>Abstract:</h4>
            <p>
                This paper presents a study of the grand canonical Bose-Einstein (BE) statistics for a finite number of particles in an arbitrary quantum system. The thermodynamical quantities that identify BE condensation—namely, the fraction of particles in the ground state and the specific heat—are calculated here exactly in terms of temperature and fugacity. These calculations are complemented by a numerical calculation of fugacity in terms of the number of particles, without taking the thermodynamic limit. The main advantage of this approach is that it does not rely on approximations made in the vicinity of the usually defined critical temperature, rather it makes calculations with arbitrary precision possible, irrespective of temperature. Graphs for the calculated thermodynamical quantities are presented in comparison to the results previously obtained in the thermodynamic limit. In particular, it is observed that for the gas trapped in a three-dimensional box, the derivative of specific heat reaches smaller values than what was expected in the thermodynamic limit—here, this result is also verified with analytical calculations. This is an important result for understanding the role of the thermodynamic limit in phase transitions and makes possible to further study BE statistics without relying neither on the thermodynamic limit nor on approximations near critical temperature.
            </p>
        </div>
    </div>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> Information geometry for Fermi–Dirac and Bose–Einstein quantum statistics </strong></summary>
    <div class="paper">
        <p>
            <strong>Published:</strong> 
            P Pessoa, C Cafaro (2021) 
            <a href="https://doi.org/10.1016/j.physa.2021.126061">  Physica A: Statistical Mechanics and its Applications, 576, 126061 </a>
        </p>
        <p>
            <strong>Preprint:</strong> 
            <a href="https://arxiv.org/abs/2103.00935">Available at arXiv</a>
        </p>
        <div class="abstract">
            <h4>Abstract:</h4>
            <p>
                Information geometry is an emergent branch of probability theory that consists of assigning a Riemannian differential geometry structure to the space of probability distributions. We present an information geometric investigation of gases following the Fermi–Dirac and the Bose–Einstein quantum statistics. For each quantum gas, we study the information geometry of the curved statistical manifolds associated with the grand canonical ensemble. The Fisher–Rao information metric and the scalar curvature are computed for both fermionic and bosonic models of non-interacting particles. In particular, by taking into account the ground state of the ideal bosonic gas in our information geometric analysis, we find that the singular behavior of the scalar curvature in the condensation region disappears. This is a counterexample to a long held conjecture that curvature always diverges in phase transitions.
            </p>
        </div>
    </div>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> Entropic dynamics on Gibbs statistical manifolds </strong></summary>
    <div class="paper">
        <p>
            <strong>Published:</strong> 
            P Pessoa, F Xavier Costa, A Caticha (2021) 
            <a href="https://doi.org/10.3390/e23050494">  Entropy 2021, 23(5), 494 </a>
        </p>
        <p>
            <strong>Preprint:</strong> 
            <a href="https://arxiv.org/abs/2008.04683">Available at arXiv</a>
        </p>
        <div class="abstract">
            <h4>Abstract:</h4>
            <p>
                Entropic dynamics is a framework in which the laws of dynamics are derived as an application of entropic methods of inference. Its successes include the derivation of quantum mechanics and quantum field theory from probabilistic principles. Here, we develop the entropic dynamics of a system, the state of which is described by a probability distribution. Thus, the dynamics unfolds on a statistical manifold that is automatically endowed by a metric structure provided by information geometry. The curvature of the manifold has a significant influence. We focus our dynamics on the statistical manifold of Gibbs distributions (also known as canonical distributions or the exponential family). The model includes an “entropic” notion of time that is tailored to the system under study; the system is its own clock. As one might expect that entropic time is intrinsically directional; there is a natural arrow of time that is led by entropic considerations. As illustrative examples, we discuss dynamics on a space of Gaussians and the discrete three-state system.
            </p>
        </div>
    </div>
    </details>
</details>
  
<details>
<summary style="font-family: Arial; font-size: 32px; color: darkblue;"><strong> Selected Software Packages </strong></summary>
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> <a href="https://github.com/PessoaP/REPOP/"> REPOP </a> </strong></summary>
        <p> Library for REconstructing bacterial POpulations from Plate counts.</p>
    </details>   
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> <a href="https://github.com/PessoaP/NFdeconvolve/"> NFDeconvolve </a> </strong></summary>
        <p> Library for obtaning probability distribution from noisy measurements, basically deconvoluting, using normalizing flows.</p>
    </details>   
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> <a href="https://github.com/PessoaP/smn/"> SMN (Sparse matrices in Numba) </a> </strong></summary>
        <p> Library with a class for sparse matrices that is compatible with the popular <a href="https://numba.pydata.org/">Numba</a> compilation tool for fast machine code in Python.</p>
    </details>    
    <details>
    <summary style="font-family: Arial; font-size: 20px;"><strong> <a href="https://github.com/PessoaP/IGQG">IGQG (Information Geometry of Quantum Gases) </a> </strong></summary>
        <p> Library with functions needed for my work on Bose-Einstein condensation. These tools are based on the <a href="https://mpmath.org/">mpmath</a> library for arbitrary numeric precision. </p>
    </details>
</details>
