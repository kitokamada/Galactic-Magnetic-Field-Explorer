# Galactic-Magnetic-Field-Explorer 銀河磁場探検家
JF-12 Magnetic Field Explorer (a side project of arxiv.2303.15562)


Author: K.K.Liao

--- A side project of Relic Neutrino Helicity Evolution in GMF

( arxiv.2303.15562 -- simulating the evolution of the helicity of relic neutrinos as they propagate to Earth through a realistic model of the Galactic magnetic field )

--- The script provides Python script to study the JF-12 Magnetic Field numerical model for astrophysics research.


Potentional Use: (1) Cosmic Ray Propogation while interacting with GMF
                 (2) arxiv.2303.15562 , studying Dirac $\nu$'s helicity evolution in GMF
                 (3) GMF structure studies

*Required Package: 
Numpy, Healpy, matplotlib.pyplot, pandas

*Required Magnetic Field File:
Numerical + Analytic Model ~ https://arxiv.org/abs/1210.7820 
Numerical Grid model generation from : https://crt.osu.edu/fields.html

Folder: LOS_Field_rho calculated the magnetic field density along the LOS using JF12 magnetic field model

eg1. Results of JF-12 galactic magnetic field $B_{\perp}$ perpendicular to LOS at $N_{side}$=32 , $N_{Pixel}$=12288 over Healpy Mollview Sky Plot:

![Alt text](https://github.com/kitokamada/Galactic-Magnetic-Field-Explorer/blob/main/results/BperpMollview.png)


eg2. Results of JF-12 galactic magnetic field $B_{\perp}$ perpendicular to LOS at $N_{side}$=32 , $N_{Pixel}$=12288 over 
Healpy ProjectView Sky Plot:

![Alt text](https://github.com/kitokamada/Galactic-Magnetic-Field-Explorer/blob/main/results/BperpProjectview.png)
