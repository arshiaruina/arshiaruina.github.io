---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am currently working in ground-based gamma-ray astrophysics but come from a background of space-based cosmic-ray physics and high-energy particle physics. Read on to find out more about these topics and my interest in it!

* [Gamma-ray Astrophysics](#gamma-ray-astrophysics)
  * [LST-1 and CTAO](#lst-1-and-ctao)
    * [Extra-Galactic Astrophysics](#extra-galactic-astrophysics)
    * [CRs with DC Light](#crs-with-dc-light)
  * [MAGIC and LST1+MAGIC](#magic-and-lst1magic)
  * [SWGO](#swgo)
* [Cosmic Rays from Space](#cosmic-rays-from-space)
* [High-Energy Particle Physics](#high-energy-particle-physics)

## Gamma-ray Astrophysics

### LST-1 and CTAO

I started my journey in this field with the [Large-Sized Telescope prototype (LST-1) of the Cherenkov Telescope Array Observatory (CTAO)](https://www.ctao.org). The CTA Observatory is a next-generation observatory for gamma-ray astrophysics designed to detect gamma rays in the energy range 20 GeV to 300 TeV. For the best coverage of the full energy range, three categories of [telescopes](https://www.ctao.org/emission-to-discovery/telescopes/) will be deployed: Large-Sized Telescopes (LSTs), Medium-Sized Telescopes (MSTs) and Small-Sized Telescopes (SSTs). The telescopes use the [imaging air-shower technique](https://www.ctao.org/emission-to-discovery/science/how-ctao-works/), wherein a VHE gamma-ray photon, on interacting with the Earth's atmosphere, generates a cascade of charged particles that emit Cherenkov light. This faint blue-UV light is emitted when particles travel faster than light in a medium (light travels 0.03% slower in air than in vacuum!) and can be detected by a telescope. The larger the telescope, the lower its energy threshold can go. Therefore, the LSTs are designed to measure the low-energy range while the SSTs will be able to detect the highest-energy gamma rays. 

#### Extra-Galactic Astrophysics

The origin of gamma-ray emissions in the jets of Active Galactic Nuclei (AGNs), as well as the location of the emissions along the jets, are important open questions in astrophysics. I'm studying VHE emissions from extra-Galactic blazars, which are a kind of AGN whose jets are closely aligned to our line of sight. As a result, their emissions, strongly modified by relativistic effects, can exhibit strong and rapid variabilities. Studying the variability in the photon fluxes with time can help us understand this better. In particular, I'm analysing the data on the BL Lac object (a kind of blazar) called PG 1553+113 that has been collected by the LST-1, to investigate short-term (intra-night) variabilities in its light curve.

Further reading:
* H. Luciani's [master thesis](https://hdl.handle.net/20.500.12608/51830) on the characterization of PG1553+113 with the LST-1
* Variability patterns of PG 1553 + 113 with MAGIC and other telescopes (2023) [paper](https://doi.org/10.1093/mnras/stae649)

#### CRs with DC Light

I am also working towards using IACTs to study cosmic rays (CRs) using the technique Direct Cherenkov (DC) light detection. Primarly designed to detect Cherenkov light from gamma-ray air showers, IACTs have also been used to study cosmic rays (CRs) using DC light, which is the Cherenkov radiation emitted by a highly energetic CR particle before producing an air shower. The flux of DC light is directly proportional to <i>Z<sup>2</sup></i>, the squared particle charge, whereas that of the Cherenkov light of the shower is proportional to <i>Z</i>. Moreover, being generated at a higher altitude than the EAS, where the air is less dense, the DC light will arrive in a much narrower cone than the the light from the EAS, slightly shifted in position and slightly delayed in time. IACT cameras, like those of CTAO, with a sharp enough angular resolution (~0.1° FOV per pixel) and a time resolution of the order of nanoseconds can provide a strong discrimation between DC-light and EAS-light. Further, the dependance of DC-light on <i>Z<sup>2</sup></i> makes it an optimal technique for CR composition measurements, especially for iron, not only because of its high <i>Z</i> but also because of its relatively higher abundance. However, there are still significant limiting factors of this technique which make DC light detection quite challenging.

Further reading:
* DC light with H.E.S.S. (2007) [paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.75.042004)
* CR Iron spectrum using DC light with VERITAS (2018) [paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.98.022009)

### MAGIC and LST1+MAGIC

The MAGIC (Major Atmospheric Gamma Imaging Cherenkov) telescopes are a pair of IACTs also located on the Canary islands of La Palma. They are designed to operate for gamma rays in the energy range 50 GeV to more than 50 TeV. Built in 2004 and 2009, respectively, they are 85m apart and have (had) different cameras, triggers and readout systems. But they underwent [major upgrades](https://www.sciencedirect.com/science/article/pii/S0927650515000663) in 2011-2012 that improved the overall performance of the stereoscopic system.

I am also working on familiarising myself with the software pipeline that aims to analyse MAGIC and LST-1 data simultaneously. The possibility of joint observations allows for a stereoscopic system of three telescopes that will render a higher sensitivity than for MAGIC or LST-1 alone. This has the potential to be used in source data analyses. I also hope to contribute to the DC light analyses with MAGIC only, work on which is currently in its very early stages.

Further reading:
* Performance of the joint LST-1 and MAGIC observations (2023) [paper](https://doi.org/10.1051/0004-6361/202346927) and [proceedings](https://doi.org/10.22323/1.444.0636)

### SWGO

The [SWGO](https://www.swgo.org) (Southern Widefield Gamma-ray Observatory) is upcoming gamma-ray experiment in South America which is currently in the R&D stage. I am a coordinator in the Outreach and Communications (O&C) working group, whose current focus is on generating awareness about the project, especially in the countries where the candidate sites are located, with special attention to the concerns of the local communities. Given the nascent stage of the project, we are still deciding on the approach towards a more prominent social media presence. 

As far as scientific activities are concerned, I will be making some sensitvity studies for the array in the coming months. More updates on this will follow later!


## Cosmic Rays from Space

During my PhD, I worked in the DAMPE (DArk Matter Particle Explorer) collaboration, which is a space-borne particle detector that was launched in December 2015 and has been taking data since. The detector system consists of a PSD (Plastic Scintillator Detector) for charge measurement, STK (Silicon-tungsten TracKer-convertor) for tracking incident particles,  BGO (bismuth germanium oxide) calorimeter for energy measurement, and NUD (neutron detector) that further aids in lepton-hadron separation. I analysed more than six years of cosmic-ray data to measure the helium flux in the energy range 70 GeV to 1 PeV. In [this work](https://archive-ouverte.unige.ch/unige:170702), I implemented the newly-developed deep learning techniques in the collaboration, a first, to [improve particle tracking and identification](https://www.sciencedirect.com/science/article/pii/S0927650522000962?via%3Dihub) and to [compensate for the energy lost in the calorimeter at high energies due to saturation of the electronics](https://iopscience.iop.org/article/10.1088/1748-0221/17/06/P06031). The study confirmed a previously observed hardening feature in the energy spectrum and also a subsequent softening feature that was [reported by DAMPE in 2021](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.201102). Also, a comparison with the proton flux tended to favour the charge-dependant scenario of cosmic-ray fluxes over a mass-dependant one.

## High-Energy Particle Physics

My first "real" to the fascinating world of particle physics was during the eight weeks that I spent at CERN in 2015 as a summer student. In the months that followed, I learnt even more about the subject, including detection methods, statisticals analyses, and the current state of the art at various schools, workshops and short research projects. For my [thesis](https://cds.cern.ch/record/2653340), I worked with data from the ATLAS (A Toroidal LHC Apparatus) experiment at the LHC (Large Hadron Collider) in CERN, to analyse the decays of top quarks and study the phenomenon of flavour violation in charged leptons.

Prior to joining ATLAS, I’d had the opportunity to work in the [COMPASS](https://doi.org/10.1016%2Fj.nima.2007.03.026) (Common Muon and Proton Apparatus for Structure and Spectroscopy) experiment for a few months, which will soon be succeeded by the [COMPASS++/AMBER](https://cds.cern.ch/record/2826884) (Apparatus for Meson and Baryon Experimental Research) experiment. One of the aims of this experiment will be to measure the proton-induced antiproton production cross section, which will help in reducing some of the systematic uncertainties that riddle DM searches. 

After my master thesis, I worked for a few months with the [CAST](https://www.sciencedirect.com/science/ article/pii/S0168900298014429.) (CERN Axion Solar Telescope) collaboration, my first encounter with astroparticle physics. CAST is looking for axions (hypothetical particles that have become one of the [leading DM candidates](https://www.science.org/doi/full/10.1126/sciadv.abj3618) over the past few years) that originate in the Sun. My work was aimed at the computation of an upper limit on the axion-electron coupling constant. In order to achieve this, I made improvements on the solar axion flux calculations, implementing the model described [here](https://doi.org/10.1088%2F1475-7516%2F2013%2F12%2F008).

*[VHE]: Very High Energy
*[CR]: Cosmic Ray
*[DM]: Dark Matter