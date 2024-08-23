---
title: "Uncertainties in Kilonova Properties"
layout: single-portfolio
excerpt: "<img src='/images/research/gw170817.png' alt=''>"
collection: research
order_number: 20
header: 
  og_image: "research/gw170817.png"
---

When generating a simulation of a kilonova, there are countless assumptions that researchers have to make because we do not have perfect knowledge of the system: what is the density structure of the ejecta, what is the precise elemental composition of the ejecta, what is the r-process heating heat, to name a few. Ideally, these assumptions do not greatly affect the results of the simulations, but that is not always true. In those cases, work needs to be done to understand how those assumptions affect the results and quantify the effect. To that end, this work focuses on quantifying the effect of two other assumptions that we have to make in order to simulate a kilonova: the atomic structure of lanthanide elements and the thermalization efficiency.

Understanding the effect these assumptions have on astronomers' ability to derive the properties of the kilonova has direct implications to our understanding of the universe. An accurate understanding of kilonova properties allows us to answer fundamental questions about the universe such as whether or not the collisions of neutron stars are responsible for the production of all the heaviest elements or if there are other production sites in the universe, what is left behind from the collision of neutron stars, and what is the heaviest possible neutron star?

## Atomic Structure

A defining characteristic of the kilonova is how bright they are in the [infrared](https://science.nasa.gov/ems/07_infraredwaves/). This is a direct result of the presence of some of the heaviest metals in the universe, the [lanthanides](https://en.wikipedia.org/wiki/Lanthanide), within the ejecta. The lanthanides have a valence f-shell electron, which means the atomic structure is highly complex. This manifests as very large [opacities](https://en.wikipedia.org/wiki/Opacity) at [optical](https://science.nasa.gov/ems/09_visiblelight/) and [ultraviolet](https://science.nasa.gov/ems/10_ultravioletwaves/) wavelengths. This complexity means that it is very difficult to accurately model the precise atomic structure of the lanthanides, and so the true wavelength dependent opacity is highly uncertain. 

This results in an uncertainty in exactly how much of these lanthanides are present in the ejecta, which has implications for whether or not the collisions of neutron stars are responsible for producing all of the heaviest elements.

## Thermalization Efficiency

The underlying 'battery' or source of energy that powers the brightness of a kilonova is the radioactive decay of elements synthesized in the collision of the neutron stars, much like how a nuclear power plant generates energy from the radioactive decay of elements like uranium. However, when an atom in the kilonova ejecta radioactively decays and releases energy, not all of that energy gets deposited into the surrounding material. This is because when an atom radioactively decays, it emits a whole suite of particles and light called decay products; from a highly energetic gamma ray to electrons traveling at high speeds (usually referred to as [beta particles](https://en.wikipedia.org/wiki/Beta_particle) in this context) to the 'unstoppable' [neutrino](https://www.energy.gov/science/doe-explainsneutrinos). Each decay product will impart its energy into the surrounding material differently. The neutrinos almost never deposit any of their energy, the gamma rays may deposit their energy if there is enough material between them and escaping the ejecta, and the electrons bounce around and deposit their energy if there are other atoms nearby to collide with like billiard balls. Thus, not all of the energy released from radioactive decay makes it into the ejecta and we define a 'thermalization efficiency' f as the fraction of the total energy that goes into heating up the ejecta.

The thermalization efficiency f can be implemented into simulations a couple different ways. It can either be determined by the density of the particular location of the simulation (i.e the more dense the region radioactive decay occurs, the more likely the beta particles will collide and impart their energy), or a single thermalization efficiency f can be assigned to all locations in the simulation which is the average thermalization efficiency of the entirety of the ejecta. These two different prescriptions are referred to as the 'local' thermalization efficiency prescription and the 'gloabl' thermalization efficiency prescription, respectively.





## Methods

## Results




[ADS Link](https://ui.adsabs.harvard.edu/abs/2024arXiv240802731B/abstract)
