---
layout: page
title: SETI
show: hide
---

I began working on SETI as a summer REU student at [Breakthough Listen](https://breakthroughinitiatives.org/initiative/1) and the [Berkeley SETI Research Center](https://seti.berkeley.edu/listen/) in 2022. Below are my past and current projects.

### Signal Synchronization Strategies and Time Domain SETI
![SETI Ellipsoid](/images/seto_scheme.jpg "SETI Ellipsoid")
*Credit: Danielle Futselaar / Breakthrough Listen*

As a summer REU student, I worked with [James Davenport](https://jradavenport.github.io/) (UW) and [Steve Croft](https://w.astro.berkeley.edu/~scroft/) (UCB) on implementing signal synchronization strategies with Gaia Data Release 3. The idea that an extraterrestrial civilization may synchronize their transmission with a conspicuous astrophysical event, such as a supernova, forms the basis of the SETI Ellipsoid and the related signaling scheme proposed by [Seto (2021)](https://iopscience.iop.org/article/10.3847/1538-4357/ac0c7b). It has only recently become feasible to implement these frameworks with the precise astrometric capabilities of Gaia.

![Seto Scheme](/images/setoAnimation.gif "Seto Scheme")
Seto Scheme *Credit: Andy Nilipour*

After constraining possible SETI candidates with these signal synchronization frameworks, I developed a novel time domain SETI analysis that is sensitive to unexpected changes in a star's light curve that occur when the star is expected to be a prime search candidate according to either the SETI Ellipsoid or the Seto scheme. While I only applied this to Gaia light curves, it can easily be extended to other time domain instruments, such as TESS or the upcoming Vera Rubin Observatory.

Although no particular interesting candidates were found, we are continuing the search and the utilization of these tools. We used the SETI Ellipsoid with SN 2023ixf, a supernova detected in the galaxy M101 in May 2023, to select a sample of technosignature candidates, which we then observed with the Allen Telescope Array and the Green Bank Telescope; this is described in more detail in [Davenport et al. (2023)](https://iopscience.iop.org/article/10.3847/2515-5172/acdc24).

The GitHub repository for this project is available [here](https://github.com/anilipour/Gaia-DR3-Time-Domain-SETI). More information can be found in the paper, [Nilipour et al. (2023)](https://iopscience.iop.org/article/10.3847/1538-3881/acde79). The arXiv version is available [here](https://arxiv.org/abs/2308.00066). There has also been some press coverage of this project, including in [The Economist](https://www.economist.com/science-and-technology/2023/01/18/ideas-for-finding-et-are-getting-more-inventive) and [YaleNews](https://news.yale.edu/2023/07/31/searching-extraterrestrial-life-keeping-eye-exploding-stars).