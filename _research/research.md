---
layout: archive
permalink: /research/
title: "Projects"
---

## Current Research – Higgs Physics (ATLAS Collaboration, CERN)

My research focuses on precision Higgs-boson measurements and rare decay searches within the ATLAS experiment, combining advanced statistical modelling, multivariate machine learning, and large-scale data analysis.

---

### Higgs Boson Pair Production (HH → bbγγ)  
**Run 2 + Run 3 (2015–2024), 308 fb⁻¹**  
Accepted for publication – arXiv:2507.03495

I contributed to the ATLAS search for non-resonant Higgs boson pair production in the **HH → bbγγ** final state, using the full Run 2 dataset and partial Run 3 data.

My responsibilities included:

- Development and optimisation of **multivariate classifiers (BDT)** for background rejection and signal extraction.
- Validation and calibration of ML models (stability checks, bootstrap studies, feature-dependence analysis).
- Detailed performance studies of **neural-network-based photon identification**.
- Optimisation of event categorisation separately for Run 2 and Run 3.
- Evaluation of systematic uncertainties and contributions to the statistical interpretation.

This analysis set the **most stringent ATLAS limits on the Higgs self-coupling (κλ) to date**, significantly improving constraints on Higgs boson self-interaction and non-resonant HH production.

This analysis set the **most stringent ATLAS limits on the Higgs self-coupling (κλ) to date**, significantly improving constraints on Higgs boson self-interaction and non-resonant HH production.

Further details are available in [the official ATLAS public briefing](https://atlas.cern/Updates/Briefing/Higgs-Self-Interaction-Run-3).

The workflow closely mirrors industry-grade model validation and monitoring practices: robust cross-validation, sensitivity studies to input features, uncertainty propagation, and reproducibility checks.

---

### Rare Higgs Decay Search: H → Za → ℓℓγγ (HLRS, ongoing)

I am currently working on the HLRS **H → Za → ℓℓγγ** analysis, combining Run 2 and Run 3 data (2015–2025/26). This rare channel provides sensitivity to beyond-Standard-Model scenarios, including axion-like particles (ALPs) and extended scalar sectors.

My work includes:

- Development and maintenance of analysis software (EasyJet / FastFrames).
- Production and validation of ntuples.
- Implementation and optimisation of event selection (including ML-driven studies).
- Trigger selection strategy and efficiency validation.
- Photon ID cross-checks.
- Preparation of statistical workspaces in TRExFitter and limit-setting procedures.
- Identification and evaluation of experimental systematic uncertainties.

The goal is to deliver a full statistical interpretation of the combined Run 2 + Run 3 dataset.

---

## Detector Upgrade & Data Infrastructure – HGTD (Run 4 Preparation)

In parallel, I contribute to the High-Granularity Timing Detector (HGTD) upgrade program for HL-LHC.

I design and maintain database solutions supporting detector characterisation and quality assurance workflows, including:

- Schema design and validation pipelines.
- Query interfaces.
- Integration with analysis and monitoring frameworks.

This work directly supports Run 4 commissioning and efficient large-scale data management.

---

## Machine Learning in Medical Imaging

In parallel with my work in high-energy physics, I co-authored a machine-learning-driven study on **PET (Positron Emission Tomography) image reconstruction**, addressing the reconstruction of sparse, noisy, high-dimensional medical imaging data.

PET reconstruction is a fundamentally ill-posed inverse problem. The measured data follow Poisson statistics, are incomplete due to detector geometry and limited angular coverage, and are affected by noise and physical effects such as attenuation and scattering. Classical reconstruction approaches (e.g., filtered back-projection or iterative ML-EM methods) often struggle in low-count or sparse regimes.

In this project, we applied:

- Probabilistic modelling of the forward detection process  
- Maximum-likelihood reconstruction  
- Bayesian inference frameworks  
- PyTorch-based optimisation  
- Markov Chain Monte Carlo (MCMC) sampling  

The approach incorporated prior information and uncertainty quantification directly into the reconstruction procedure, allowing improved stability and robustness in low-statistics scenarios.  

This work strengthened my expertise in:
- Inverse problems  
- Likelihood-based modelling  
- Bayesian uncertainty quantification  
- High-dimensional optimisation  
- Probabilistic machine learning  

The results were published in *Computer Physics Communications* (2025), [DOI: https://doi.org/10.1016/j.cpc.2025.109913](https://doi.org/10.1016/j.cpc.2025.109913).

The project demonstrates how statistical inference and ML techniques can bridge physics-based modelling and real-world medical imaging challenges.

---

## Research Philosophy

Across experimental particle physics, detector development, and medical imaging, my work is driven by:

- Rigorous uncertainty quantification  
- Statistical inference and likelihood-based modelling  
- Multivariate machine learning  
- Model validation and reproducibility  
- Large-scale data systems  

I integrate advanced analytics with fundamental physics questions, contributing both to precision measurements of the Higgs sector and to technically complex data-driven environments.

<!-- ---
layout: archive
permalink: /research/
title: "Research"
---

## Postdoctoral researcher at AGH University of Kraków, Faculty of Physics and Applied Informatics

Since October 2021 I have been involved in the study of relativistic heavy-ion collisions as a member of the AGH Heavy-Ion Collision Physics group from the ATLAS collaboration. 
One of the main tasks was to optimize the reconstruction and identification of photons with low $p_T$ values in ultraperipheral lead-lead collisions (UPC). Events were reconstructed using lower thresholds and looser selection criteria in the reconstruction. It will be important, for instance in measuring light-by-light scattering, where two photons with low $p_T$ are present in the detector without any other activity above noise thresholds. The efficiency of cluster and photon reconstruction has been significantly improved for photon $p_T < 5$ GeV for UPC HI events. For example, for photon $p_T = 1.5$ GeV, the efficiency was 15\% with default photon thresholds and is now about 70\% with optimized requirements. A dedicated working point for the identification of very loose photons has been developed for Pb+Pb collisions at $\sqrt{s_{\mathrm{NN}}} = 5.36$ TeV. It is based on the ``cut-based'' method. As a result, a constant photon identification efficiency of 95% was achieved.

Also, I am taking part in the analysis of measurements of top quark pair production in proton-lead collisions at $\sqrt{s_{\mathrm{NN}}} = 8.16$ TeV in the ATLAS experiment. The data set was recorded in 2016 and corresponds to an integrated luminosity of 165 nb$^{-1}$. Top quarks are reconstructed in the lepton+jet and dilepton decay channels with electrons and muons in the final state. The dilepton channel is being studied in heavy-ion collisions for the first time. My main task was to estimate the background contribution to the signal sample. Using the Matrix Method, the efficiencies of fake leptons and two components of real leptons for proton-lead collisions were measured. These efficiencies are input data for the matrix method to determine distributions for non-prompt and fake lepton background in $t\bar{t}$ production. The method uses regions in the transverse momentum space of leptons enriched with fake and non-prompt leptons from MC simulation. The background from $W$ boson decay, $Z$ boson decay, and $t\bar{t}$ production have been determined and subtracted. The efficiency of fake leptons is measured for electrons and muons for transverse momenta $p_T > 18$ GeV and absolute pseudorapidity $\left\lvert \eta < 2.5 \right\rvert$. 

Last but least, I am working with the inter-experimental group HonexComb as part of the STRONG-2020 project, of which AGH is a member, consisting of experimenters and theorists from LHC. My task aims to average the existing measurements of lepton pair production in ultra-peripheral lead-lead collisions, $ Pb+Pb \rightarrow Pb(\gamma \gamma \rightarrow \tau\tau)Pb $, at $\sqrt{s_{\mathrm{NN}}}=5.02 $ TeV in LHC. I am working on combining results from the [ATLAS](https://arxiv.org/abs/2204.13478) and [CMS](https://arxiv.org/abs/2206.05192) experiments regarding the anomalous magnetic moment of the tau lepton using an extended maximum likelihood method. This analysis is ongoing. 

## PhD studies at Jagiellonian University, Faculty of Physics, Astronomy and Applied Computer Science

In 2021 I finished my doctoral thesis at Jagiellonian University under the supervision of dr hab. Roman Skibi{\'n}ski. My doctoral dissertation deals with the theoretical study of the three-nucleon observables for the nucleon elastic and inelastic scattering on the deuteron. This is also supplemented by the study of other selected quantities in few-nucleon systems using nucleon-nucleon (NN) nuclear potentials for which statistical properties (the expected values and covariance matrix) of parameters are known. For my research work the most important examples of such models are the new generation of the chiral interaction derived up to fifth-order (N$^{4}$LO$^{+}$) of the chiral expansion using the semilocal regularization in momentum space (SMS) by the Bochum-Bonn group and the One-Pion-Exchange-Gaussian (OPE-Gaussian) potential. These models are dictated by the availability of the covariance matrix for the potential parameters. Knowledge of the covariance matrix of NN potential parameters opens possibilities in studies of few-nucleon systems. 

My doctoral dissertation concerns the application of the covariance matrix of the nucleon-nucleon interaction potential parameters in the study of proton scattering reactions on a neutron and, first of all, an elastic neutron scattered by a deuteron. In addition, I showed several results related to the deuteron breakup reaction by the nucleon and the binding energy of the deuteron and triton. In addition, I demonstrated several results related to the deuteron breakup reaction by a nucleon and the binding energy of a deuteron and a triton. I used modern nuclear force potentials, such as the One-Pion-Exchange Gaussian potential, as an example of a semi-phenomenological model of nuclear forces and nucleon-nucleon SMS (semi-local moment space regularized) potential obtained by the chiral approach. The latter model is currently the best model available for theoretical research between two nucleons. The version of the chiral potential I used contains all the elements up to the fifth order of the chiral expansion (N$^4$LO) and is even supplemented by the selected elements of the next order (N$^4$LO$^+$ force). Both of the models used were derived in the recent past (2014 and 2018, respectively) and one of their advantages is the availability of the covariance matrix for free parameters of these forces. The use of this matrix is the main topic of the presented doctoral dissertation for the investigated processes.

The most important scientific result presented in the dissertation on theoretical uncertainties is the estimation of the uncertainty of theoretical predictions, which arises due to the uncertainty of the nucleon-nucleon potential parameters, the source of which is the uncertainty of experimental data used to determine the values of these parameters. In addition to this type of theoretical uncertainty (so-called statistical uncertainty), I compared it with other types, i.e. the truncation error arising from neglecting corrections to the nuclear potential coming from higher orders of the chiral expansion, estimated, among other things, within Bayesian statistics and the cutoff dependence of chiral predictions --- uncertainty resulting from the dependence of theoretical predictions on the value of the chiral potential regularization parameter. It was found that the resulting statistical uncertainty is smaller than the truncation errors for the chiral force at lower orders of the chiral expansion. At the higher orders of the chiral expansion and at low energies the statistical error exceeds the truncation one but at intermediate and higher energies truncation error is more important. 

The second problem examined in the dissertation concerned the study of the correlation among observables in the reactions of elastic proton-neutron or neutron-deuteron scattering. Correlation coefficients were estimated among many observables and investigated their dependence on the scattering angle, reaction energy, and nuclear potential. Thus, it was possible to identify pairs of observables that remain linearly correlated with each other, or for which the correlation coefficient remains close to zero. The results of these studies significantly expanded the knowledge about the correlations that occurred, previously limited to only two or three cases of pairs of observables.  I comprehensively examined all pairs of observables in the elastic neutron-deuteron scattering, obtaining information about their correlation. For example, I showed that the pair of the neutron-vector and the deuteron-tensor analyzing powers maintain a strong mutual correlation even at higher energies ($E$ = 135 MeV). On the other hand, most observables show a linear dependence only at low energies, which is most likely due to the sensitivity of these observables to selected potential parameters only. Knowing if some observables are or are not correlated, will influence future methods of fixing free parameters of the two- and many-body potentials. It is hoped that the results of this study will help to improve the efficiency of the fitting procedure used to determine nucleon-nucleon potential parameters by improving the accuracy of determining potential parameters and our understanding of the three-nucleon Hamiltonian. 

During my summer 2021 fellowship, I had the opportunity to work remotely with the BAND (Bayesian Analysis of Nuclear Dynamics) team, collaborating with members from Northwestern and Michigan State University (USA). The primary focus of our work involved developing an interface that bridged a physics code with the BAND/surmise framework (written in python). 
Our main goal was to address how uncertainty quantification can be integrated into nuclear physics at every level from theoretical modeling and simulations, to experimental analysis and control. In particular, we focused on addressing nucleon-nucleon and nucleon-deuteron scattering problems while constructing this interface. Results were presented at the Quark Matter 2022 conference (Krakow). -->