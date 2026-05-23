<link rel="stylesheet" type="text/css" href="assets/styles.css" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">


<a href="https://scholar.google.com/citations?hl=en&user=sw4MCXcAAAAJ" target="_blank">
  <i class="ai ai-google-scholar-square ai-3x"></i>
</a>
<a href="https://arxiv.org/search/?searchtype=author&query=Pessoa%2C+P" target="_blank">
  <i class="ai ai-arxiv ai-3x" style="color: red;"></i>
</a>
<a href="https://orcid.org/0000-0002-6258-5679/" target="_blank">
  <i class="ai ai-orcid-square ai-3x" style="color: #006000;"></i>
</a>
<a href="https://github.com/pessoap" target="_blank">
  <i class="fab fa-github fa-3x" style="color: black;"></i>
</a>
<a href="https://www.linkedin.com/in/ppessoa" target="_blank">
  <i class="fab fa-linkedin fa-3x"></i>
</a>
<!-- <a href="https://bsky.app/profile/pedropessoaphd.bsky.social" target="_blank">
  <i class="fab fa-bluesky fa-3x"></i>
</a> -->

[//]: $P^4$

<details>
<summary style="font-family: Arial; font-size: 32px; color: darkblue;"><strong> Blog </strong></summary>
    <details>
    <summary style="font-family: Arial; font-size: 24px;"><strong> Tutorials on Bayesian statistics </strong></summary>
    <ol>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-i-asserting-if-a-coin-is-biased-tutorial/">Why do we need Bayesian statistics? Part I – Asserting if a coin is biased</a> -- <a href="https://github.com/PessoaP/blog/blob/master/Coins/Coins.ipynb">GitHub </a> </li>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-ii-the-lighthouse-problem-tutorial/">Why do we need Bayesian statistics? Part II — The lighthouse problem</a> -- <a href="https://github.com/PessoaP/blog/blob/master/Lighthouse/Lighthouse.ipynb">GitHub </a></li>
        <li>  <a href="https://labpresse.com/why-do-we-need-bayesian-statistics-part-iii-learning-multivariate-distributions-tutorial">Why do we need Bayesian statistics? Part III – Learning multivariate distributions </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Lighthouse/Lighthouse2.ipynb">GitHub </a> </li>
    </ol>
    </details>
    <details>
    <summary style="font-family: Arial; font-size: 24px;"><strong> Other blog posts </strong></summary>
    <ul>
        <li>  <a href="https://labpresse.com/the-monty-hall-or-3-doors-problem/"> The Monty Hall (or 3 doors) problem </a>  -- <a href="https://github.com/PessoaP/blog/blob/master/3doors/3doors.ipynb">GitHub </a> </li>
        <li>  <a href="https://labpresse.com/2053-2/">Bayesian <span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal" style="margin-right: 0.03588em;">π</span> – Calculating <span class="strut" style="height: 0.43056em; vertical-align: 0em;"></span><span class="mord mathnormal" style="margin-right: 0.03588em;">π</span> with Monte Carlo </a> -- <a href="https://github.com/PessoaP/blog/blob/master/Coins/PI.ipynb">GitHub </a> </li>
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
        <summary style="font-family: Arial; font-size: 20px;"><strong> Simulation-based inference captures non-Markovian effects as exemplified in protein production kinetics through cell division  </strong></summary>
        <div class="paper">
            <p>
                <strong>Authors:</strong> 
                Pedro Pessoa, Juan Andres Martinez, Vincent Vandenbroucke, Frank Delvigne, Steve Pressé (2026)
                <a href="https://doi.org/10.1073/pnas.2517309123">  PNAS, 123, e2517309123  </a>
            </p>
            <p>
                <strong>Preprint:</strong> 
                <a href="https://arxiv.org/abs/2210.00905">Available at arXiv</a>
            </p>
            <div class="abstract">
                <h4>Abstract:</h4>
                <p>
                    Inferring protein production kinetics in dividing cells is complicated by protein inheritance from the mother cell. For instance, fluorescence measurements commonly used to assess gene activation may reflect not only newly produced proteins but also those inherited through successive cell divisions. In such cases, observed protein levels in any given cell are shaped by its division history. As a case study, we examine activation of the <em>glc3</em> gene in yeast involved in glycogen synthesis and expressed under nutrient-limiting conditions. We monitor this activity using snapshot fluorescence measurements via flow cytometry, where GFP expression reflects <em>glc3</em> promoter activity. A naïve analysis of flow cytometry data ignoring cell division suggests many cells are active with low expression. Explicitly accounting for the (non-Markovian) effects of cell division and protein inheritance makes it impossible to write down a tractable likelihood -- a key ingredient in physics-inspired inference, defining the probability of observing data given a model. The dependence on a cell's division history breaks the assumptions of standard (Markovian) master equations, rendering traditional likelihood-based approaches inapplicable. Instead, we adapt conditional normalizing flows (a class of neural network models designed to learn probability distributions) to approximate otherwise intractable likelihoods from simulated data. In doing so, we find that <em>glc3</em> is mostly inactive under stress, showing that while cells occasionally activate the gene, expression is brief and transient. 
                </p>
            </div>
        </div>
    </details>
    <details>
        <summary style="font-family: Arial; font-size: 20px;"><strong> REPOP: bacterial population quantification from plate counts   </strong></summary>
        <div class="paper">
            <p>
                <strong>Authors:</strong> 
                Pedro Pessoa, Carol Lu, Stanimir Asenov Tashev, Rory Kruithoff, Douglas P. Shepherd, Steve Pressé (2025)
                <a href="    https://doi.org/10.7554/eLife.107122.1">  eLife  </a>
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
        <summary style="font-family: Arial; font-size: 20px;"><strong> Mamba time series forecasting with uncertainty quantification  </strong></summary>
        <div class="paper">
            <p>
                <strong>Authors:</strong> 
                Pedro Pessoa, Paul Campitelli, Douglas P Shepherd, S Banu Ozkan, Steve Pressé (2025)
                <a href="https://iopscience.iop.org/article/10.1088/2632-2153/adec3b">  Machine Learning: Science and Technology, 6, 035012 </a>
            </p>
            <p>
                <strong>Preprint:</strong> 
                <a href="https://arxiv.org/abs/2503.10873">Available at arXiv</a>
            </p>
            <div class="abstract">
                <h4>Abstract:</h4>
                <p>  State space models, such as Mamba, have recently garnered attention in time-series forecasting due to their ability to capture sequence patterns. However, in electricity-consumption benchmarks, Mamba forecasts exhibit a mean error of approximately 8%. Similarly, in traffic-occupancy benchmarks, the mean error reaches 18%. This discrepancy leaves us to wonder whether the prediction is simply inaccurate or falls within error given the spread in historical data.   To address this limitation, we propose a method to quantify the predictive uncertainty of Mamba forecasts. Here, we introduce a dual-network framework based on the Mamba architecture for probabilistic forecasting, where one network generates point forecasts while the other estimates predictive uncertainty by modeling variance. We abbreviate our tool, Mamba with probabilistic time-series forecasting, as <strong>Mamba-ProbTSF</strong>, and the code for its implementation is available on GitHub.   Evaluating this approach on synthetic and real-world benchmark datasets, we find that the Kullback-Leibler divergence between the learned distributions and the data—which, in the limit of infinite data, should converge to zero if the model correctly captures the underlying probability distribution—is reduced to the order of 10<sup>&minus;3</sup> for synthetic data and 10<sup>&minus;1</sup> for real-world benchmarks, demonstrating its effectiveness.   We find that, in both the electricity-consumption and traffic-occupancy benchmarks, the true trajectory stays within the predicted uncertainty interval at the two-sigma level about 95% of the time. We end by considering potential limitations, adjustments to improve performance, and applications of this framework to processes with purely or largely stochastic dynamics, where stochastic changes accumulate, as observed, for example, in pure Brownian motion or molecular-dynamics trajectories.
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
            <a href="https://doi.org/10.1371/journal.pone.0284212">  PLoS ONE, 18,  e0284212  </a>
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
