---
permalink: /research/
title: "Research"
author_profile: true
---

I study fluid and plasma instabilities and turbulence in a wide range of physical systems. Lately, I've been particularly interested in magnetohydrodynamic (MHD) turbulence in stably stratified regions of gas giant planets and in stellar interiors (radiation zones). These are regions where fluid motions have traditionally been assumed to be relatively laminar, but many observations can only be explained by invoking some form of turbulence.

Below, I list a few of my recent research directions.

## Double-diffusive convection and chemical mixing in stars (or oceans)

In my first postdoc with Prof. Pascale Garaud at UCSC, I began studying [double-diffusive convection](https://en.wikipedia.org/wiki/Double_diffusive_convection) (DDC), a form of turbulence that occurs when two buoyancy effects with different diffusivities (such as temperature and salinity) are in competition with, say, a stabilizing (sub-adiabatic) temperature gradient and a destabilizing gradient of the other quantity (salt water overlying fresh water in oceans, or a μ inversion in stars). The situation just described leads to one of two branches of DDC, known sometimes as salt-finger or thermohaline convection. The other form of DDC—where the temperature gradient is destabilizing (super-adiabatic) and the other quantity is stabilizing—is sometimes called diffusive convection, the diffusive branch of DDC, oscillatory DDC (ODDC), or "semiconvection" (though note that "semiconvection" sometimes refers to something a little different).

The role of both forms of DDC in astrophysical systems is covered very well by [this](https://doi.org/10.1146/annurev-fluid-122316-045234) review paper by Garaud, who also has [this](https://arxiv.org/abs/2103.08072) very nice set of lecture notes on the arXiv aimed at an astrophysical audience. A major facet that I care about is the anomalous chemical mixing ("extra mixing") inferred by observations of red giant branch (RGB) stars. As described in the above review (or see the introduction in [this paper](https://doi.org/10.3847/1538-4357/aca024) of mine), the deep interiors of RGB stars must host some form of turbulence in order to explain the chemical abundances we see at their surfaces. The leading candidate is thermohaline convection, but predictive models for the chemical mixing rate of this process agree with *either* observations *or* 3D hydrodynamic simulations, but not both.

### My latest result: maximally helical (Beltrami) flows spontaneously formed by salt fingers
In a very recent project I led with Edgar Knobloch (UC Berkeley), Adrian van Kan (UC Berkeley -> TAMU), the late Keith Julien (CU Boulder), and Chang Liu (UCONN), I used 3D simulations of salt fingers in regimes relevant to Earth's oceans to demonstrate that salt-finger turbulence can drive large-scale helical flows, in a striking (and simple!) example of spontaneous chiral symmetry breaking, very similar to what was found [here](https://www.pnas.org/doi/10.1073/pnas.1614721114) in the context of active matter turbulence. This system exhibits striking multiscale features, with tall, anisotropic salt fingers twisted into corkscrew-like shapes by the helical flow and disrupted at small scales by isotropic eddies. Informed by these multiscale dynamics, I performed a multiscale (with slow and fast vertical coordinates) asymptotic analysis that arrived at a closed system of equations for the leading-order balances. I simulated these leading-order balances numerically and, as expected, the results are the same as simulations of the full equations in the relevant limit (what I did not expect was that the reduced model works wonderfully surprisingly far from this limit). I have submitted this work to JFM and sent it to the arXiv and will update this section once I have a link.

### MHD thermohaline convection and the FRG24 model
Harrington & Garaud, ApJL 2019 ("HG19"; [link](https://doi.org/10.3847/2041-8213/aaf812)) noted that magnetic fields might enhance the mixing rate dramatically, even for relatively weak magnetic field strengths (say, 100G), thus possibly addressing this tension between observations and simulations; they also provided a reduced model for predicting the mixing rate *a priori* for use in stellar evolution codes like [MESA](https://docs.mesastar.org/en/24.08.1/about.html). In Fraser, Reifenstein, and Garaud, ApJ 2024 ("FRG24"; [link](https://ui.adsabs.harvard.edu/abs/2024ApJ...964..184F/abstract)), I collaborated with Prof. Garaud and UCSC student Sam Reifenstein to study this process in more detail. We found that the HG19 model is flawed and generally does not capture the effect of magnetic diffusivity on the process or changes in mixing rate with stratification. We improved upon the model and showed that our improved FRG24 model agrees (to within a factor of two!) with our extensive suite of 3D MHD simulations across a *massive* range of parameters, varying background gradients, magnetic field strength, and magnetic diffusivity.

**Next steps**: As part of a team including Jarrett Rosenberg (UW-Madison), Rich Townsend (UW-Madison), Evan Bauer (CFA / Harvard & Smithsonian, LLNL), and Matteo Cantiello (Flatiron CCA, Princeton), we have implemented the FRG24 model into the [MESA stellar evolution code](https://docs.mesastar.org/en/24.08.1/about.html) so the broader astrophysics community can use our model to study implications for a wider range of astrophysical systems, such as magnetic white dwarfs or as a possible Cameron-Fowler mechanism to produce lithium in red giants. 

I also have important follow-up projects that I would love to work with students on!

### Thermohaline convection in polluted white dwarfs
As a postdoc at CU, I directly supervised recent PhD graduate Imogen Cresswell (Astrophysical and Planetary Sciences Department) on a project that used 3D simulations of thermohaline convection to put to rest the debate of whether or not the process can enhance mixing in polluted WDs for long periods of time. You can read more about it in our recent publication in ApJL [here](https://ui.adsabs.harvard.edu/abs/2025ApJ...986L..10C/abstract). Here, too, I have important follow-up projects that I would love to work with students on!

## Angular momentum transport in stars, and the Tayler-Spruit Dynamo

More to come, but this is the subject of [my recent NSF award](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2402142&HistoricalAwards=false).

## Shear-flow instabilities persisting despite magnetic fields

### Unstable Alfvén waves, and other transverse waves, driven by periodic shear flows

In [this recent paper](https://doi.org/10.1017/jfm.2022.782) with Garaud and Cresswell, we found that periodic shear flows make Alfvén waves (a kind of transverse wave that lives on magnetic field lines, where magnetic tension is the restoring force similar to how tension permits waves on a string) go unstable in parameter regimes where ordinary shear-flow instabilities (think [Kelvin-Helmholtz](https://en.wikipedia.org/wiki/Kelvin%E2%80%93Helmholtz_instability)) are stable. We also found that these waves look like solitons as the reach finite amplitude. 

It seems that this feature of transverse wave + periodic shear flow is quite generic, and I'm eager to see just how generic it is. In ongoing work led and started by then- UW-Madison PhD students Alexandre Sainterme (now Princeton) and Joey Duff (now Type One Energy), including collaborators Jeff Oishi (UNH) and Paul Terry (UW-Madison), we are exploring how these dynamics affect the interaction between zonal flows and plasma drift waves (transverse waves sometimes analogous to atmospheric Rossby waves) in fusion devices.

### Nonmodal growth in shear layers in MHD

More to come!

## Rotating moist convection

Recently, I worked with CU-Boulder PhD student Whitney Powers (Astrophysical and Planetary Sciences Department) on a project studying the effect of rotation on moist convection. In rotating Rayleigh-Bénard convection, depending on the values of various control parameters, different morphological regimes are attained in the limit of rapid rotation (cells, convective Taylor columns, plumes, QG turbulence, etc.). Whitney read about a very simple, recent model for moist convection—the [Rainy-Bénard model](https://ui.adsabs.harvard.edu/abs/2019JFM...862..162V/abstract)—and had the idea to add rotation and see how the different morphological regimes compare. You can read more about it [here](https://ui.adsabs.harvard.edu/abs/2025arXiv250501626P/abstract), but the punch line is that the regimes are quite different.
