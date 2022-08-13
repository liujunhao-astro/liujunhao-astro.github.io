---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Magnetic fields are important in the diffuse interstellar medium and dense molecular clouds. Its role in regulating star formation, how it's affected by protostellar feedbacks, and its interplay with gravity and turbulence have been the key topics in the study of star formation. Dust polarization observations have been the most common way to trace the plane-of-sky (POS) component of the magnetic field orientations. Other ways tracing the POS field orientations in star-forming regions include the Goldreich-Kylafis (GK) effect ([Goldreich and Kylafis, 1981]( https://ui.adsabs.harvard.edu/abs/1981ApJ...243L..75G/abstract)) and the Velocity Gradient Technique ([Gonza´lez-Casanova \& Lazarian, 2017]( https://ui.adsabs.harvard.edu/abs/2017ApJ...835...41G/abstract)). Many analysis techniques have been developed to infer the properties of magnetic fields based on the statistics of their orientations. For instance, the Davis-Chandrasekhar-Fermi (DCF) method ([Davis \& Greenstein, 1951]( https://ui.adsabs.harvard.edu/abs/1951PhRv...81..890D/abstract), [Chandrasekhar \& Fermi, 1953]( https://ui.adsabs.harvard.edu/abs/1953ApJ...118..113C/abstract) ), the polarization-intensity gradient (KTH) method ([Koch et al., 2012]( https://ui.adsabs.harvard.edu/abs/2012ApJ...747...79K/abstract)), and the Histogram of Relative Orientations (HRO) analysis ([Soler et al., 2013]( https://ui.adsabs.harvard.edu/abs/2013ApJ...774..128S/abstract)). 

### Calibrating the Davis-Chandrasekhar-Fermi method with numerical simulations ([Liu et al. 2021]( https://ui.adsabs.harvard.edu/abs/2021ApJ...919...79L/abstract))

The improvement of instrumental sensitivity has let to an increasing number of magnetic field studies within dense molecular clouds. The DCF method, which was initially proposed to study the ISM magnetic field in the spiral arm, has been the most widely used method to estimate the B strength within star-forming molecular clouds. However, the validity of the assumptions of this method in high-density self-gravitating regions is unclear. 

With 3D magneto-hydrodynamic (MHD) and radiative transfer simulations (made with [RAMSES](https://www.ics.uzh.ch/~teyssier/ramses/RAMSES.html) and [POLARIS](https://portia.astrophysik.uni-kiel.de/polaris/)) of clustered star formation regions, we performed a numerical study to understand the uncertainty of the DCF method at sub-parsec scales (i.e., dense clumps/cores) with significant self-gravity. The major conclusions are:
- The energy equipartition between the turbulent kinetic and magnetic energies are approximately satisfied in trans-Alfv\'{e}nic ($\mathcal{M}_{A} = 0.7-2.5 $) clumps/cores at 1-0.1 pc scales and $n\sim10^4$-10$^6$ cm$^{-3}$. The turbulent magnetic energy is much smaller than the turbulent kinetic energy in super-Alfv\'{e}nic clumps/cores, which can lead to an overestimation of the field strength using the DCF method.
- The turbulent velocity fields and magnetic fields in self-gravitating clumps/cores are approximately isotropic, which is different from the anisotropic MHD turbulence in large-scale non-self-gravitating media. 
- $\delta \phi$ can significantly underestimate the turbulent-to-underlying field strength ratio when $\delta \phi > 25^{\circ}$.
- The correction factor for the DCF-derived B strength decreases with increasing density and decreasing scale. 
- The magnetic field is dominated by the turbulent component when $\mathcal{M}_{A} \gtsim 1$.
- The Angular Dispersion Function (ADF) method (a modified DCF method, [Hildebrand et al. 2009]( https://ui.adsabs.harvard.edu/abs/2009ApJ...696..567H/abstract), [Houde et al. 2009]( https://ui.adsabs.harvard.edu/abs/2009ApJ...706.1504H/abstract), and [Houde et al. 2016]( https://ui.adsabs.harvard.edu/abs/2016ApJ...820...38H/abstract)) correctly accounts for the ordered field structure, the beam-smoothing effect, and the interferometric filtering effect, but might not work well for the effect of line-of-sight (LOS) signal integration. 

![Simulation map](/images/Simu_LIC.png| width="50%")
An example of the synthetic observation of our simulations. Line integral convolution map shows the magnetic field orientation. Colorscales indicate the dust emission. 

### A Compilation of All the DCF Estimations ([Liu et al. 2022]( https://ui.adsabs.harvard.edu/abs/2022ApJ...925...30L/abstract))

Despite the increasing number of observational studies of magnetic fields in molecular clouds, it is hard to infer the general role played by the magnetic field in star formation from individual studies. Thus, we collected all the DCF estimations from polarized dust emission observations in the literature published before June 2021 (230 estimations from 75 papers) and re-estimated the B field strength with the updated correction factors of different modified DCF methods for self-gravitating clumps/cores from our numerical study. The findings are: 
- The magnetic field scales with density as $B \propto n^{0.57}$. The power-law slope is between the values predicted by strong and weak field models. However, the observed spatial $B-n$ relation may not be comparable to the predicted temporal $B-n$ relation of theoretical models.
- There is a clear trend that the mass-to-flux ratio in units of critical value ($\lambda$) transits from $\lambda<1$ to $\lambda>1$ as the column density increases, which suggests magnetically sub-critical molecular clouds gradually form super-critical dense clumps/cores. The dissipation of magnetic flux at high column densities may be due to effects of ambipolar diffusion, magnetic reconnection, and mass accumulation along magnetic field lines. 
- The average state of the clumps/cores is trans-to-super-Alfv\'{e}nic, which may indicate the gas is accelerated by the gravity. 

![lambda map](/images/lambBtot_Ncol_instru0_method0.png | width="50%")
Mass-to-flux ratio in units of critical value as a function of gas column density. 

### Initial condition of massive star formation: Magnetic fields in 3 massive clumps in IRDC G28.34 ([Liu et al. 2020]( https://ui.adsabs.harvard.edu/abs/2020ApJ...895..142L/abstract))

The two major massive star formation theories have contradictory predictions on the dynamical states of massive clumps/cores: the turbulent core accretion model envisioned that massive stars are formed via the monolithic collapse of massive dense cores in virial equilibrium. Alternatively, the competitive accretion model proposed that a cluster of low-mass protostars compete with one another to accrete from the natal gas reservoir and the protostars near the center of gravitational potential accreting at higher rates can thus form massive stars, where a sub-virial state is required for the competitive accretion. Thus, measuring the dynamical state of massive star formation regions is crucial to distinguish between the two models. 

Infrared Dark Clouds (IRDCs) are believed to harbor the early phase of massive star formation. Previous studies suggests that the turbulence is too weak to provide enough support against gravitational collapse in IRDCs. Thus, observational studies of the magnetic field in IRDCs are critical to address the question: could magnetic fields bring the IRDCs back to equilibrium? I investigated the role of B fields in three massive molecular clumps (~1 pc) MM1, MM4, and MM9 in the IRDC G28.34+0.06 with ALMA dust polarization observations. The total virial parameters (including magnetic support) in two massive dense cores, MM1-Core1 and MM4-Core4, are found to be $\sim$0.76 and $\sim$0.37, respectively, suggesting that massive star formation does not start in equilibrium. Half of the outflows in MM4 and MM9 are found to be aligned within 10$^{circ}$ of the condensation-scale ($<$0.05 pc) magnetic field, indicating that the magnetic field could play an important role from condensation to disk scale in the early stage of massive star formation.

![MM1 B map](/images/MM1B.png | width="50%")
Magnetic field vectors overlaid on ALMA 1.3 mm dust continuum maps for MM1. Red and cyan vectors correspond to data with P/DP>2 and P/DP>3, respectively.

![MM4 B map](/images/MM4B.png | width="50%")
Same but for MM4.

![MM4 outflow map](/images/MM4_B.png | width="50%")
Comparison betwee the outflow axis and the magnetic field orientation in G28 MM4.

### Initial condition of low-mass star formation: Magnetic fields in the low-mass starless core Ophiuchus C ([Liu et al. 2019]( https://ui.adsabs.harvard.edu/abs/2019ApJ...877...43L/abstract))

The role of magnetic fields in early stages of low-mass star formation also remains mysterious due to the lack of direct observations. As part of the JCMT large program B-fields in STar-forming Region Observations ([BISTRO](https://www.eaobservatory.org/jcmt/science/large-programs/gb_bfields/)), I investigated the role of B field in the low-mass starless dense core Oph-C. I estimated the plane-of-sky field strength (Bpos) using modified DCF methods based on [structure function (SF, Hildebrand et al. 2009)]( https://ui.adsabs.harvard.edu/abs/2009ApJ...696..567H/abstract), [autocorrelation function (ACF, Houde et al. 2009)]( https://ui.adsabs.harvard.edu/abs/2009ApJ...706.1504H/abstract), and [unsharp masking (Pattle et al. 2017)]( https://ui.adsabs.harvard.edu/abs/2017ApJ...846..122P/abstract) analyses. The calculations yield Bpos of 0.1~0.2 mG and a mass-to-flux-ratio greater than its critical value, suggesting that a low-mass starless core has already begun to collapse. 

![OphC map](/images/map_gbs_ophc.png | width="50%")
Magnetic field orientations overlaid on JCMT 850 $\mu$m total intensity maps. Yellow and cyan vectors correspond to P/DP>2 and P/DP>3, respectively.

### The driving mechanism of an isothermal massive outflow ([ADS link]( https://ui.adsabs.harvard.edu/abs/2018ApJ...860..106L/abstract ))

Molecular outflows are a common phenomenon associated with young stellar objects (YSOs) of all masses, but their driving mechanism remains unclear. Using CSO, APEX, and SMA observations, I performed a multi-transition CO (J=2-1, 3-2, 6-5, and 7-6 ) analysis of the outflowing gas associated with the massive UC HII region G240.31+0.07. With large velocity gradient (LVG) calculations (using the radiative transfer code [RADEX](https://home.strw.leidenuniv.nl/~moldata/radex.html)), I found that the outflow is approximately isothermal with a gas temperature of ∼50 K and that the CO column density clearly decreases with the outflow velocity, which indicates the massive outflow is being driven by a wide-angle protostellar wind. 

![Low-velocity (LV) and High-velocity (HV) integrations of CO J=2-1, 3-2, 6-5, and 7-6 emissions.](/images/G240_contour.png | width="70%")
    Figure 1. Low-velocity (LV) and High-velocity (HV) integrations of CO J=2-1, 3-2, 6-5, and 7-6 emissions.

;![Temperature-velocity diagram](/images/tv_paper.png | width="50%")
;    Figure 2. Temperature-velocity diagram.

;![CO column density-velocity diagram](/images/Nv_paper.png | width="50%")
;    Figure 3. CO column density-velocity diagram.

