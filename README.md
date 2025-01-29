# PyPPSinflation and PPS_orders Notebooks

**PyPPSinflation** is a Python package designed to numerically and analytically compute the scalar and tensor primordial power spectra (PPS) for single-field slow-roll inflationary models, up to the third order. 

The package is structured into Jupyter Notebooks and Wolfram Mathematica notebooks, organized as follows:

### Notebook Overview

1. **Notebook 1 - Numerical PPS**: This notebook solves the dynamical equations for the scalar field $\phi$. By specifying an inflationary model with the potential $V(\phi)$, it then solves the Mukhanov-Sasaki equations for scalar and tensor perturbations $\delta \phi$, yielding the scalar and tensor PPS. From these, we numerically compute the spectral indices, their runnings, and the runnings of the runnings.

2. **Notebook 2 - Quantities with respect to the number of $e$-folds $N$**: This Wolfram Mathematica notebook analytically computes all necessary quantities for deriving the PPS analytically.

3. **Notebook 3 - Analytical PPS**: This notebook computes the analytical PPS at first, second, and third orders in $\ln\left(\frac{k}{k_*}\right)$. It includes analytical calculations of the spectral indices, their runnings, and the runnings of the runnings.

4. **Notebook 4 - Analytical vs. Numerical PPS**: Here, we compare the analytical PPS up to the third order with the numerical PPS obtained in Notebook 1. We also compare the spectral indices, their runnings, and the runnings of the runnings.

5. **Notebook 5 - Plots**: This notebook provides a streamlined version of Notebook 4, focusing on generating the key plots needed for comparison.

### Model Used

In this generic script, we use the Kachru-Kallosh-Linde-Trivedi (KKLT) model of inflation. For details, refer to: 
- S. Kachru, R. Kallosh, A. Linde, and S.P. Trivedi, "de Sitter vacua in string theory," *Phys. Rev. D* 68 (2003) 046005 [hep-th/0301240].

### Additional Resources: PPS_orders Folder

The repository includes a folder named **PPS_orders**, which contains two sub-folders: **Notebooks_2nd_order** and **Notebooks_3rd_order**. These folders house Wolfram Mathematica notebooks that detail the computations leading to the analytical forms of the PPS presented in the PyPPSinflation reference paper. This includes tabulated integrals, their results, and their super-Hubble limits. Please refer to the reference paper for guidance on these notebooks.

### License and Contribution

PyPPSinflation and the PPS_orders notebooks are free to use. If you have any questions or are interested in contributing, please do not hesitate to contact the authors.

### Reference paper and citations

If you use this code in your research, please cite the following associated reference paper published on Physics of the Dark Universe:

M. Ballardini, A. Davoli, S.S. Sirletti - Third-order corrections to the slow-roll expansion: calculation and constraints with Planck, ACT, SPT, and BICEP/Keck:

@article{BALLARDINI2025101813,
title = {Third-order corrections to the slow-roll expansion: Calculation and constraints with Planck, ACT, SPT, and BICEP/Keck},
journal = {Physics of the Dark Universe},
volume = {47},
pages = {101813},
year = {2025},
issn = {2212-6864},
doi = {https://doi.org/10.1016/j.dark.2025.101813},
url = {https://www.sciencedirect.com/science/article/pii/S2212686425000081},
author = {Mario Ballardini and Alessandro Davoli and Salvatore Samuele Sirletti},
keywords = {Keyword one, Keyword two},
abstract = {We investigate the primordial power spectra (PPS) of scalar and tensor perturbations, derived through the slow-roll approximation. By solving the Mukhanov-Sasaki equation and the tensor perturbation equation with Green’s function techniques, we extend the PPS calculations to third-order corrections, providing a comprehensive expansion in terms of slow-roll parameters with an independent approach to the solution of the integrals compared to the one previously presented in the literature. We investigate the accuracy of the analytic predictions starting from first-order corrections up to third-order ones with the numerical solutions of the perturbation equations for a selection of single-field slow-roll inflationary models. We derive the constraints on the Hubble flow functions ϵi from Planck, ACT, SPT, and BICEP/Keck data. We find an upper bound ϵ1≲0.002 at 95% CL dominated by BICEP/Keck data and robust to all the different combination of datasets. We derive the constraint ϵ2≃0.031±0.004 at 68% confidence level (CL) from the combination of Planck data and late-time probes such as baryon acoustic oscillations, redshift space distortions, and supernovae data at first order in the slow-roll expansion. The uncertainty on ϵ2 gets larger including second- and third-order corrections, allowing for a non-vanishing running and running of the running respectively, leading to ϵ2≃0.034±0.007 at 68% CL. We find ϵ3≃0.1±0.4 at 95% CL both at second and at third order in the slow-roll expansion of the spectra. ϵ4 remains always unconstrained. The combination of Planck and SPT data, compatible among each others, leads to slightly tighter constraints on ϵ2 and ϵ3. On the contrary, the combination of Planck data with ACT measurements, which point to higher values of the scalar spectral index compared to Planck findings, leads to shifts in the means and maximum likelihood values for ϵ2 and ϵ3. We discuss the results obtained for different dataset combinations and different multipole cuts.}
}

