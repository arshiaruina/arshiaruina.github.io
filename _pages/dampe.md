---
layout: archive
title: "DAMPE"
permalink: /research/space-based-cosmic-ray-detection/dampe
author_profile: true
---

<figure>
  <img src="https://eoportal.org/ftp/satellite-missions/d/DAMPE-010621/DAMPE_AutoB.jpeg" alt="dampe-satellite" />
  <figcaption style="font-size: 14px; text-align: left;">Illustration of DAMPE, also known as the Wukong satellite. Image credit: <a href="https://www.eoportal.org/satellite-missions/dampe" target="_blank">China Daily</a>
  </figcaption>
</figure>

The [DAMPE](http://dpnc.unige.ch/dampe/) (DArk Matter Particle Explorer) is a space-borne particle detector that was launched in December 2015 and has been taking data since. The detector system consists of 

* PSD (Plastic Scintillator Detector) for charge measurement, 
* STK (Silicon-tungsten TracKer-convertor) for tracking incident particles,
* BGO (bismuth germanium oxide) calorimeter for energy measurement, and 
* NUD (neutron detector) that further aids in lepton-hadron separation.

<figure>
  <img src="/assets/images/dampe-components.png" alt="dampe-components" />
  <figcaption style="font-size: 14px; text-align: left;">The sub-detectors of the DAMPE and an illustration of how different the signals left behind by a cosmic-ray particle and a gamma-ray could look.
  </figcaption>
</figure>

I analysed more than six years of cosmic-ray data (i.e. nearly 13 billion cosmic-ray events detected by DAMPE, equivalent to approximately 200 terabytes of data) to measure the helium flux in the energy range 70 GeV to 1 PeV. My work ([link to thesis](https://archive-ouverte.unige.ch/unige:170702)) involved deploying the newly-developed **deep-learning techniques** in the collaboration, a first. These improved **particle tracking and identification** [Tykhonov et al. (2023)](https://www.sciencedirect.com/science/article/pii/S0927650522000962?via%3Dihub) and **compensated for the energy lost in the calorimeter at high energies due to saturation of the electronics** [Stolpovskiy et al. (2022)](https://iopscience.iop.org/article/10.1088/1748-0221/17/06/P06031), extending the capabilities of the detector beyond its design values.

These new results confirmed previously observed features in the energy spectrum **as reported by DAMPE in 2021** [Alemanno et al.(2021)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.201102) with more data and higher precision. Indeed, the cosmic-ray spectrum is not a smoothly falling power-law distribution and in my thesis, I discuss in more detail with the help of statistical analyses.

In addition, I played key roles in 

* maintaining the data-cleaning procedures that were used in all our analyses made by the
European side of the collaboration,
* the development and deployment of a signal correction procedure for the STK which led
to a 39% improvement in the measurement precision and 30% reduction in contamination from background interactions

**Further reading:**

* My presentation at the 38th International Cosmic Ray Conference in Nagoya, Japan (2023) [proceedings](https://pos.sissa.it/444/170)

[Back to top](#)
