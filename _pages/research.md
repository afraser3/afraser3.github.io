---
permalink: /research/
title: "Research"
author_profile: true
---

I study fluid and plasma instabilities and turbulence in a wide range of physical systems. Lately, I've been particularly interested in magnetohydrodynamic (MHD) turbulence in stably stratified regions in stellar interiors (radiation zones), and in gas giant planets.

Below, I list a few of my recent research directions.

### Double-diffusive convection, and chemical mixing in stars

In my first postdoc with Prof. Pascale Garaud at UCSC, I began studying [double-diffusive convection](https://en.wikipedia.org/wiki/Double_diffusive_convection) (DDC), a form of turbulence that occurs when two buoyancy effects with different diffusivities (usually temperature and either salinity in oceans, or mean molecular weight in stars) are in competition, with, for instance, a stabilizing (sub-adiabatic) temperature gradient and a destabilizing gradient of the other quantity (salt water over fresh water in oceans, or a μ inversion in stars). The situation just described leads to one of two branches of DDC, known sometimes as salt-finger or thermohaline convection. The other form of DDC—where the temperature gradient is destabilizing (super-adiabatic) and the other quantity is stabilizing, is sometimes known as the diffusive branch of DDC, as oscillatory DDC (ODDC), or, by astrophysicists, as "semiconvection" (though note that "semiconvection" is sometimes used to refer to something that isn't exactly ODDC).

The role of both forms of DDC in astrophysical systems is covered very well by [this](https://doi.org/10.1146/annurev-fluid-122316-045234) review paper by Garaud, who also has [this](https://arxiv.org/abs/2103.08072) very nice set of lecture notes on the arXiv aimed at an astrophysical audience. A major facet that I care about is the anomalous chemical mixing ("extra mixing") inferred by observations of red giant branch (RGB) stars. As described in the above review (or see the introduction in [this paper](https://doi.org/10.3847/1538-4357/aca024) of mine), the deep interiors of RGB stars must host some form of turbulence in order to explain certain surface observations (specifically, changes in abundance and/or isotopic ratios involving C12, C13, N, and Li shortly after the luminosity bump). The leading candidate to explain this phenomenon is thermohaline mixing, but predictive models for the chemical mixing rate of this process agree with *either* observations *or* 3D hydrodynamic simulations, but not both.

#### MHD thermohaline mixing and the FRG24 model
Harrington & Garaud, ApJL 2019 (HG19; [link](https://doi.org/10.3847/2041-8213/aaf812)) identified the possibility that magnetic fields might enhance the mixing rate dramatically, even for magnetic field strengths of 100G, thus possibly addressing this tension between observations and simulations; they also provided a reduced model for predicting the mixing rate *a priori* for use in, say, stellar evolution codes like [MESA](https://docs.mesastar.org/en/24.08.1/about.html). In Fraser, Reifenstein, and Garaud, ApJ 2024 ("FRG24"; [link](https://ui.adsabs.harvard.edu/abs/2024ApJ...964..184F/abstract)), I collaborated with Prof. Garaud and UCSC student Sam Reifenstein to study this process in more detail. We found that the HG19 model is flawed and often does not faithfully capture the effect of magnetic diffusivity on the process. We improved upon the model and showed that our improved FRG24 model *does* agree with our extensive suite of 3D MHD simulations across a broad range of parameters, varying background gradients, magnetic field strength, and magnetic diffusivity.

**Next steps**: I have worked with Evan Bauer (CFA /| Harvard & Smithsonian), Matteo Cantiello (Flatiron CCA, Princeton), Rich Townsend (UW-Madison), Jarrett Rosenberg (UW-Madison), and Pascale Garaud (UCSC) to implement the FRG24 model into the [MESA stellar evolution code](https://docs.mesastar.org/en/24.08.1/about.html) so the broader astrophysics community can use our model to study implications for a broader range of astrophysical systems, including in magnetic white dwarfs and as a possible Cameron-Fowler mechanism to produce lithium in red giants. 

I am also working with CU-Boulder PhD student Imogen Cresswell (Astrophysical and Planetary Sciences Department) to compare the FRG24 model and related models against *global* 3D simulations, with exciting implications for both RGB stars and polluted white dwarfs.

### Angular momentum transport in stars, and the Tayler-Spruit Dynamo

### Shear-flow instabilities persisting despite magnetic fields

#### Unstable Alfvén waves, and other transverse waves, driven by periodic shear flows

#### Nonmodal growth in shear layers in MHD
