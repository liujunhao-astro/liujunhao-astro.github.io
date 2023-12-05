---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Stars form from molecular cores that are created by the contraction of over-dense regions in molecular clouds. Observational studies of magnetic fields (B fields) in molecular clouds are essential to help us understand how exactly the B field is affecting and affected by star formation at different scales and in different evolutionary stages, which is crucial to provide constraints for different star formation theories. The most common way to trace the plane-of-sky (POS) component of the magnetic field orientations is via dust polarization observations.

## <ins>1.Observational studies of B fields in molecular clouds</ins>

### Multi-scale magnetic properties in evolved high-mass star-forming region NGC 6334 ([Liu et al. 2023a](https://ui.adsabs.harvard.edu/abs/2023ApJ...945..160L/abstract))

Despite the wealth of existing B field studies toward different scales (e.g., $\sim$10 pc clouds, $\sim$1 pc clumps, $\sim$0.1 pc cores, $\sim$0.01 pc condensations...), there is a lack of multi-scale study in the same region. Since the dynamic role of the B field may vary from large to small scales, it is essential to study the multi-scale B field in a single cloud. Using dust polarization data from ALMA, JCMT, and Planck, I comprehensively investigated the multi-scale B field property in the nearby evolved massive star formation region NGC 6334. With an experimental synergistic analysis of relative orientations between B fields, column density gradients, local gravity, and velocity gradients, I find that NGC 6334 is trans-to-sub-Alfvenic (i.e., B fields dominate turbulence) at complex/cloud scale. The B field is dragged by gravity within the cloud and is affected by star formation activities in high-density regions. This work presents a multi-scale B field study across 4 orders of magnitude in an evolved massive star formation region, which is important for the development of massive star formation theories. The synergistic relative orientation analysis improved in this study provides a valuable tool for future similar observational studies.

<p align="center">
  <img src="/images/N6334_gnilc_B_equj.png?raw=true" alt="Photo" style="width: 400px;"/> 
  <img src="/images/jcmt_N6334_B.png?raw=true" alt="Photo" style="width: 400px;"/> 
</p>
<p align="center">
  <img src="/images/N6334In_cb_mk_B.png?raw=true" alt="Photo" style="width: 240px;"/> 
  <img src="/images/N6334I_cb_mk_B.png?raw=true" alt="Photo" style="width: 240px;"/> 
    <img src="/images/N6334IV_cb_mk_B.png?raw=true" alt="Photo" style="width: 240px;"/> 
  <img src="/images/N6334V_cb_mk_B.png?raw=true" alt="Photo" style="width: 240px;"/> 
</p>
Magnetic field orientations (line segments) overlaid on the dust emission map (colorscales) in NGC 6334 from Planck, JCMT, and ALMA observations.


<p align="center">
  <img src="/images/A_N6334_omega_am_planck.png?raw=true" alt="Photo" style="width: 300px;"/> 
  <img src="/images/A_N6334_omega_am_jcmt.png?raw=true" alt="Photo" style="width: 300px;"/> 
  <img src="/images/A_N6334_omega_am_alma.png?raw=true" alt="Photo" style="width: 300px;"/> 
</p>
Relative orientations (characterized by the alignment measure $AM$) between magnetic field (B) and local gravity (LG) as a function of column density for Planck, JCMT, and ALMA observations.


### Initial condition of low-mass and high-mass star formation ([Liu et al. 2019]( https://ui.adsabs.harvard.edu/abs/2019ApJ...877...43L/abstract),[2020]( https://ui.adsabs.harvard.edu/abs/2020ApJ...895..142L/abstract), and submitted)

The role of B fields in the early stages of star formation remains mysterious due to the lack of direct observations. Specifically, determining the magnetic critical state is important to constrain the lifetime of dense cores and to provide insights into the interstellar star formation rate. In Liu et al. 2019 and Liu et al. 2020, I investigated the B field properties in the low-mass starless core Ophiuchus C and in several high-mass dense cores in the infrared dark cloud (IRDC) G28.34, both at early evolutionary stages, using dust polarization observations obtained with the JCMT and ALMA, respectively. In both studies, I estimated the B field strength of these cores with modified statistical methods and found that these cores are magnetically supercritical (gravity dominates B fields). These two studies provide some of the earliest observational evidences for the magnetic critical state in the early stages of both low-mass and high-mass star formation. Moreover, Liu et al. 2020 also presented a quantitative comparison for several statistical methods that have been widely used to estimate the B field strength. In Liu et al. (submitted), I extended the work in Liu et al. 2020 and studied the multi-scale (from cloud to condensation scales) B fields in IRDC G28.34 using dust polarization data from Planck, JCMT, and ALMA. With a comprehensive analysis implementing a wealth of statistical approaches, I found that B fields dominate gravity and turbulence in the environment of G28.34 at large scales, resulting in relatively slow cloud formation and evolution processes. Within the IRDC, gravity overwhelms both B fields and turbulence, allowing local dynamical star formation to happen. The dynamical state in G28.34 is inconsistent with the two major classes of massive star formation models (turbulent core accretion model and competitive accretion model), which provides significant observational evidence for the future refinement of massive star formation theories. The study in Liu et al. (submitted) clearly reveals the role of B fields at different scales in an individual IRDC, which presents a cloud-to-condensation-scale B field study in an early-stage massive star formation region and fills in the gap of such studies.

## <ins>2.Numerical study of analysis methods used to interpret B fields</ins>

### Calibrating the DCF method with numerical simulations ([Liu et al. 2021]( https://ui.adsabs.harvard.edu/abs/2021ApJ...919...79L/abstract))

The Davis-Chandrasekhar-Fermi (DCF) method, which was initially proposed to study the interstellar medium (ISM) B field in the spiral arm, has been the most widely used method to estimate the B strength within star-forming molecular clouds with observations of the B field orientations. However, the validity of the assumptions of this method in high-density self-gravitating regions is unclear. To address this issue, we conducted a numerical study using a series of 3D magnetohydrodynamic (MHD) and radiative transfer simulations (made with [RAMSES](https://www.ics.uzh.ch/~teyssier/ramses/RAMSES.html) and [POLARIS](https://portia.astrophysik.uni-kiel.de/polaris/)) of clustered star formation regions with different magnetic and turbulent levels, aiming at investigating the uncertainty of the DCF method at sub-parsec scales (i.e., dense clumps/cores) that are associated with significant self-gravity. Based on the simulation results, I assessed the uncertainties of the DCF assumptions and derived correction factors for different modified forms of the DCF method in different physical conditions. This study presents corrections of the DCF method in small-scale high-density ($<$1 pc and $>$10$^4$ cm$^{-3}$) regions, which is instructive for future high-resolution observational B field studies in molecular clouds.

<p align="center">
  <img src="/images/Simu_LIC.png?raw=true" alt="Photo" style="width: 350px;"/> 
</p>
An example of the synthetic observation of our simulations. Line integral convolution map shows the magnetic field orientation. Colorscales indicate the dust emission. 

## <ins>3.Review of B field studies in the literature</ins>


### A Compilation of All the DCF Estimations ([Liu et al. 2022a]( https://ui.adsabs.harvard.edu/abs/2022ApJ...925...30L/abstract))

Despite the increasing number of observational studies of B fields in molecular clouds, it is hard to infer the general role played by the B field in star formation from individual studies. Thus, I collected all the DCF estimations from polarized dust emission observations in the literature published before June 2021 (230 estimations from 75 papers) and re-estimated the B field strength with the updated correction factors of different modified DCF methods for self-gravitating clumps/cores from my aforementioned numerical study (Liu et al. 2021). The findings are: 1) The B field scales with density as $B \propto n^{0.57}$. The power-law slope is between the values predicted by strong and weak field models. However, the observed spatial $B-n$ relation may not be comparable to the predicted temporal $B-n$ relation of theoretical models. 2) The average state of the clumps/cores is trans-to-super-Alfv\'{e}nic, but individual clumps/cores could still be sub-Alfv\'{e}nic. 3) The DCF compilation reveals a clear increasing trend of normalised mass-to-flux ratio ($\lambda$) with increasing column density among different star formation regions, where the $\lambda$ transits from $\lambda<1$ to $\lambda>1$ at $\sim3.4 \times 10^{21}$ cm$^{-2}$. This suggests magnetically sub-critical molecular clouds gradually form super-critical dense clumps/cores. The trend is in agreement with the B field-controlled star formation model. The findings in this work reveal the general property of B fields in star formation regions, which is instructive for the development of future star formation theories.

<p align="center">
  <img src="/images/lambBtot_Ncol_instru0_method0.png?raw=true" alt="Photo" style="width: 540px;"/> 
</p>
Normalized mass-to-flux ratio as a function of gas column density. 


### A review of statistical methods used to study magnetic field properties ([Liu et al. 2022b]( https://ui.adsabs.harvard.edu/abs/2022FrASS...9.3556L/abstract))

The recent improvement of instrumental sensitivity has led to an increasing number of observations that reveal the POS B field orientations in star-forming molecular clouds. Many analysis techniques have been developed to infer the properties of magnetic fields based on the statistics of their orientations. For instance, the Davis-Chandrasekhar-Fermi (DCF) method ([Davis & Greenstein, 1951]( https://ui.adsabs.harvard.edu/abs/1951PhRv...81..890D/abstract), [Chandrasekhar & Fermi, 1953]( https://ui.adsabs.harvard.edu/abs/1953ApJ...118..113C/abstract) ), the polarization-intensity gradient (KTH) method ([Koch et al., 2012]( https://ui.adsabs.harvard.edu/abs/2012ApJ...747...79K/abstract)), and the Histogram of Relative Orientations (HRO) analysis ([Soler et al., 2013]( https://ui.adsabs.harvard.edu/abs/2013ApJ...774..128S/abstract)). We have recently reviewed the advances and limitations of these methods and summarized their applications to observations. In the review, we suggest that the biggest uncertainty of the DCF method comes from the assumption of energy equipartition, which should be further calibrated with simulations and observations. We propose that the ordered and turbulent magnetic fields of particular observations are local properties of the considered region. Summarizing from observational studies using the DCF, HRO, and KTH methods, we conclude that magnetically trans-to-super-critical and averagely trans-to-super-Alfvenic clumps/cores form in sub-critical and trans-to-sub-Alfvenic clouds. We found that high-mass star-forming regions may be more gravity-dominant than their low-mass counterparts due to higher density. This review presents a state-of-the-art theoretical and observational summary of the three statistical methods used to study B fields, which provides guidance for future theoretical improvements and observational applications of those methods.


