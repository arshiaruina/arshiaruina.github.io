---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


My research is focussed on astroparticle physics, a field that brings together ultra-large-scale phenomena of astrophysics and the super-tiny-scale phenomena of particle physics!


1. [Ground-Based Gamma-Ray Astrophysics](#ground-based-gamma-ray-astrophysics)
	- [Experiment: LST-1 of the CTAO](#experiment-lst-1-of-the-ctao)
		* [Extra-Galactic Astrophysics](#extra-galactic-astrophysics)
		* [Cosmic Rays with Direct Cherenkov Light](#cosmic-rays-with-direct-cherenkov-light)
	- [Experiment: SWGO](#experiment-swgo)
		* [ALPs Detection](#alps-detection)

2. [Space-Based Cosmic-Ray Detection](#space-based-cosmic-ray-detection)
	- [Experiment: DAMPE](#experiment-dampe)

3. [High-Energy Particle Physics](#high-energy-particle-physics)
	- [Experiment: ATLAS](#atlas)
	- [Experiment: COMPASS](#compass)
	- [Experiment: CAST](#cast)

----

# Ground-Based Gamma-Ray Astrophysics

## Experiment: LST-1 of the CTAO

I started my journey in this field with the [prototype of the Large-Sized Telescope (LST-1) of the Cherenkov Telescope Array Observatory (CTAO)](https://www.ctao.org), first of the four planned LSTs in the northern site of CTAO, located in Observatorio del Roque de los Muchachos on the Canary island of La Palma, Spain. (The southern site is planned to be in Paranal, Chile.) [Acharyya et al. (2019)](https://www.sciencedirect.com/science/article/pii/S0927650519300234)

The CTAO is a next-generation observatory for gamma-ray astrophysics designed to detect gamma rays in the energy range 20 GeV to 300 TeV. For the best coverage of the full energy range, three categories of [IACTs](https://www.ctao.org/emission-to-discovery/telescopes/) will be deployed: Large-Sized Telescopes (LSTs), Medium-Sized Telescopes (MSTs) and Small-Sized Telescopes (SSTs). The telescopes use the [imaging air-shower technique](https://www.ctao.org/emission-to-discovery/science/how-ctao-works/), wherein a VHE gamma-ray photon, on interacting with the Earth's atmosphere, generates a cascade of charged particles that emit Cherenkov light. This faint blue-UV light is emitted when particles travel faster than light in a medium (light travels 0.03% slower in air than in vacuum!) and can be detected by an IACT. The larger the telescope, the lower its energy threshold can go. Therefore, the LSTs are designed to measure the low-energy range while the SSTs will be able to detect the highest-energy gamma rays. 


### Extra-Galactic Astrophysics

The origin of gamma-ray emissions in the jets of Active Galactic Nuclei (AGNs), as well as the location of the emissions along the jets, are important open questions in astrophysics. I'm studying VHE emissions from extra-Galactic blazars, which are a kind of AGN whose jets are closely aligned to our line of sight. As a result, their emissions, strongly modified by relativistic effects, can exhibit strong and rapid variabilities. Studying the variability in the photon fluxes with time can help us understand this better. In particular, I'm analysing the data on the BL Lac object (a kind of blazar) called PG 1553+113 that has been collected by the LST-1, to investigate short-term (intra-night) variabilities in its light curve.

Further reading:
* H. Luciani's [master thesis](https://hdl.handle.net/20.500.12608/51830) on the characterization of PG1553+113 with the LST-1
* Variability patterns of PG 1553 + 113 with MAGIC and other telescopes (2023) [paper](https://doi.org/10.1093/mnras/stae649)


### Cosmic Rays with Direct Cherenkov Light

I am also working towards using IACTs to study cosmic rays (CRs) using the technique Direct Cherenkov (DC) light detection. Primarly designed to detect Cherenkov light from gamma-ray air showers, IACTs have also been used to study cosmic rays (CRs) using DC light, which is the Cherenkov radiation emitted by a highly energetic CR particle before producing an air shower. The flux of DC light is directly proportional to <i>Z<sup>2</sup></i>, the squared particle charge, whereas that of the Cherenkov light of the shower is proportional to <i>Z</i>. Moreover, being generated at a higher altitude than the EAS, where the air is less dense, the DC light will arrive in a much narrower cone than the the light from the EAS, slightly shifted in position and slightly delayed in time. IACT cameras, like those of CTAO, with a sharp enough angular resolution (~0.1° FOV per pixel) and a time resolution of the order of nanoseconds can provide a strong discrimation between DC-light and EAS-light. Further, the dependance of DC-light on <i>Z<sup>2</sup></i> makes it an optimal technique for CR composition measurements, especially for iron, not only because of its high <i>Z</i> but also because of its relatively higher abundance. However, there are still significant limiting factors of this technique which make DC light detection quite challenging.

Further reading:

* DC light with H.E.S.S. (2007) [paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.75.042004)
* CR Iron spectrum using DC light with VERITAS (2018) [paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.98.022009)


## Experiment: SWGO

The [SWGO](https://www.swgo.org) (Southern Widefield Gamma-ray Observatory) is upcoming gamma-ray experiment in South America which is currently in the R&D stage. I am a coordinator in the Outreach and Communications (O&C) working group, whose current focus is on generating awareness about the project, especially in the countries where the candidate sites are located, with special attention to the concerns of the local communities. Given the nascent stage of the project, we are still deciding on the approach towards a more prominent social media presence. 

As far as scientific activities are concerned, I will be making some sensitvity studies for the array in the coming months. More updates on this will follow later!

### ALPs Detection

(will be updated soon!)


# Space-Based Cosmic-Ray Detection


## Experiment: DAMPE

During my PhD, I worked in the DAMPE (DArk Matter Particle Explorer) collaboration, which is a space-borne particle detector that was launched in December 2015 and has been taking data since. The detector system consists of a PSD (Plastic Scintillator Detector) for charge measurement, STK (Silicon-tungsten TracKer-convertor) for tracking incident particles,  BGO (bismuth germanium oxide) calorimeter for energy measurement, and NUD (neutron detector) that further aids in lepton-hadron separation. I analysed more than six years of cosmic-ray data to measure the helium flux in the energy range 70 GeV to 1 PeV. In [this work](https://archive-ouverte.unige.ch/unige:170702), I implemented the newly-developed deep learning techniques in the collaboration, a first, to [improve particle tracking and identification](https://www.sciencedirect.com/science/article/pii/S0927650522000962?via%3Dihub) and to [compensate for the energy lost in the calorimeter at high energies due to saturation of the electronics](https://iopscience.iop.org/article/10.1088/1748-0221/17/06/P06031). The study confirmed a previously observed hardening feature in the energy spectrum and also a subsequent softening feature that was [reported by DAMPE in 2021](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.201102). Also, a comparison with the proton flux tended to favour the charge-dependant scenario of cosmic-ray fluxes over a mass-dependant one.



# High-Energy Particle Physics

My first "real" to the fascinating world of particle physics was during the eight weeks that I spent at CERN in 2015 as a summer student. In the months that followed, I learnt even more about the subject, including detection methods, statisticals analyses, and the current state of the art at various schools, workshops and short research projects. 

## Experiment: ATLAS

For my [thesis](https://cds.cern.ch/record/2653340), I worked with data from the ATLAS (A Toroidal LHC Apparatus) experiment at the LHC (Large Hadron Collider) in CERN, to analyse the decays of top quarks and study the phenomenon of flavour violation in charged leptons.

## Experiment: COMPASS

Prior to joining ATLAS, I’d had the opportunity to work in the [COMPASS](https://doi.org/10.1016%2Fj.nima.2007.03.026) (Common Muon and Proton Apparatus for Structure and Spectroscopy) experiment for a few months, which will soon be succeeded by the [COMPASS++/AMBER](https://cds.cern.ch/record/2826884) (Apparatus for Meson and Baryon Experimental Research) experiment. One of the aims of this experiment will be to measure the proton-induced antiproton production cross section, which will help in reducing some of the systematic uncertainties that riddle DM searches.

## Experiment: CAST

After my master thesis, I worked for a few months with the [CAST](https://www.sciencedirect.com/science/ article/pii/S0168900298014429.) (CERN Axion Solar Telescope) collaboration, my first encounter with astroparticle physics. CAST is looking for axions (hypothetical particles that have become one of the [leading DM candidates](https://www.science.org/doi/full/10.1126/sciadv.abj3618) over the past few years) that originate in the Sun. My work was aimed at the computation of an upper limit on the axion-electron coupling constant. In order to achieve this, I made improvements on the solar axion flux calculations, implementing the model described [here](https://doi.org/10.1088%2F1475-7516%2F2013%2F12%2F008).

