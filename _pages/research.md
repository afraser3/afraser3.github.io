---
permalink: /research/
title: "Research"
author_profile: true
---

I study fluid and plasma instabilities and turbulence in a wide range of physical systems. Lately, I've been particularly interested in magnetohydrodynamic (MHD) turbulence in stably stratified regions of gas giant planets and in stellar interiors (radiation zones). These are regions where fluid motions have traditionally been assumed to be relatively laminar, but many observations can only be explained by invoking some form of turbulence.

Below, I list a few of my recent research directions.

## Double-diffusive convection and chemical (or salt) mixing in stars (or oceans)

In my first postdoc with Prof. Pascale Garaud at UCSC, I began studying [double-diffusive convection](https://en.wikipedia.org/wiki/Double_diffusive_convection) (DDC), a form of turbulence that occurs when two buoyancy effects with different diffusivities (such as temperature and salinity) are in competition with, say, a stabilizing (sub-adiabatic) temperature gradient and a destabilizing gradient of the other quantity (salt water overlying fresh water in oceans, or a μ inversion in stars). The situation just described leads to one of two branches of DDC, known sometimes as salt-finger or thermohaline convection. The other form of DDC—where the temperature gradient is destabilizing (super-adiabatic) and the other quantity is stabilizing—is sometimes called the diffusive branch of DDC, oscillatory DDC (ODDC), or "semiconvection" (though note that "semiconvection" sometimes refers to something a little different).

The role of both forms of DDC in astrophysical systems is covered very well by [this](https://doi.org/10.1146/annurev-fluid-122316-045234) review paper by Garaud, who also has [this](https://arxiv.org/abs/2103.08072) very nice set of lecture notes on the arXiv aimed at an astrophysical audience. A major facet that I care about is the anomalous chemical mixing ("extra mixing") inferred by observations of red giant branch (RGB) stars. As described in the above review (or see the introduction in [this paper](https://doi.org/10.3847/1538-4357/aca024) of mine), the deep interiors of RGB stars must host some form of turbulence in order to explain certain surface observations (specifically, changes in abundance and/or isotopic ratios involving C12, C13, N, and Li shortly after the luminosity bump). The leading candidate is thermohaline mixing, but predictive models for the chemical mixing rate of this process agree with *either* observations *or* 3D hydrodynamic simulations, but not both.

### MHD thermohaline mixing and the FRG24 model
Harrington & Garaud, ApJL 2019 ("HG19"; [link](https://doi.org/10.3847/2041-8213/aaf812)) identified the possibility that magnetic fields might enhance the mixing rate dramatically, even for magnetic field strengths of 100G, thus possibly addressing this tension between observations and simulations; they also provided a reduced model for predicting the mixing rate *a priori* for use in, say, stellar evolution codes like [MESA](https://docs.mesastar.org/en/24.08.1/about.html). In Fraser, Reifenstein, and Garaud, ApJ 2024 ("FRG24"; [link](https://ui.adsabs.harvard.edu/abs/2024ApJ...964..184F/abstract)), I collaborated with Prof. Garaud and UCSC student Sam Reifenstein to study this process in more detail. We found that the HG19 model is flawed and generally does not capture the effect of magnetic diffusivity on the process. We improved upon the model and showed that our improved FRG24 model *does* agree with our extensive suite of 3D MHD simulations across a broad range of parameters, varying background gradients, magnetic field strength, and magnetic diffusivity.

**Next steps**: As part of a team including Jarrett Rosenberg (UW-Madison), Rich Townsend (UW-Madison), Evan Bauer (CFA / Harvard & Smithsonian, LLNL), and Matteo Cantiello (Flatiron CCA, Princeton), we have implemented the FRG24 model into the [MESA stellar evolution code](https://docs.mesastar.org/en/24.08.1/about.html) so the broader astrophysics community can use our model to study implications for a wider range of astrophysical systems, such as magnetic white dwarfs or as a possible Cameron-Fowler mechanism to produce lithium in red giants. 

I am also working with CU-Boulder PhD student Imogen Cresswell (Astrophysical and Planetary Sciences Department), Ben Brown (CU-Boulder), and Evan Bauer to compare the FRG24 model and related models against *global* 3D simulations, with exciting implications for both RGB stars and polluted white dwarfs.

## Angular momentum transport in stars, and the Tayler-Spruit Dynamo

More to come, but this is the subject of [my recent NSF award](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2402142&HistoricalAwards=false).

## Shear-flow instabilities persisting despite magnetic fields

### Unstable Alfvén waves, and other transverse waves, driven by periodic shear flows

In [this recent paper](https://doi.org/10.1017/jfm.2022.782) with Garaud and Cresswell, we found that periodic shear flows make Alfvén waves (a kind of transverse wave that lives on magnetic field lines, where magnetic tension is the restoring force similar to how tension permits waves on a string) go unstable in parameter regimes where ordinary shear-flow instabilities (think [Kelvin-Helmholtz](https://en.wikipedia.org/wiki/Kelvin%E2%80%93Helmholtz_instability)) are stable. We also found that these waves look like solitons as the reach finite amplitude. 

It seems that this feature of transverse wave + periodic shear flow is quite generic, and I'm eager to see just how generic it is. In ongoing work led and started by then- UW-Madison PhD students Alexandre Sainterme (now Princeton) and Joey Duff (now Type One Energy), including collaborators Jeff Oishi (UNH) and Paul Terry (UW-Madison), we are exploring how these dynamics affect the interaction between zonal flows and plasma drift waves (transverse waves sometimes analogous to atmospheric Rossby waves) in fusion devices.

### Nonmodal growth in shear layers in MHD

More to come!
