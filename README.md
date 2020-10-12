# Dataset: Carbon-Epoxy Composite Plate UN01
<img src="estrutura.jpg " width="70%">

A carbon-epoxy laminated with layup containing ten plies unidirectionally oriented along 0º with four PZTs SMART Layers from Accelent Technologies, with 6.35 mm in diameter and 0.25 mm in thickness with a free-free boundary condition. PZT 1 is used as an actuator with a five-cycle tone burst input signal applied with 35 V of amplitude and center frequency of 250 kHz.

<img src="geral.JPG " width="25%">

The outputs are collected in PZT 2, PZT 3, and PZT 4 with a sampling rate of 5 MHz and timespan of 200 ms with all channels synchronized measured. Data acquisition was controlled by Labview using a NI USB 6353 from National Instrument (NIDaq) and an oscilloscope DSO7034B Keysight assuming a controlled temperature test conducted inside a thermal chamber from Thermotron (see figure below). Seven temperature levels from 0°C to 60°C with a variation of 10°C in each level were saved.

<img src="temperatura.JPG " width="25%">

Damage is simulated by inserting an industrial adhesive putty on the surface’s plate. This additional localized
mass simulates local changes in the damping of the plate, which has some similarities to delamination in composites structures. The damage progression is simulated by increasing the area covered by the industrial putty. The conditions tested are presented in Table 1. Healthy conditions are referred to as H(t) and damaged as D(t)^(s), where the superscript t denotes the temperature of the test and subscript s the number of damaged state. Baseline condition is defined as the structure in a healthy state at 30°C, represented by Hbaseline. For each condition, 100 output signals were collected sequentially. The progressive damage
conditions were simulated by the increase in the area covered with the putty, which has a circular format and constant mass.

<img src="tabela.png " width="50%">
________________________________________________________________________________
This dataset was used in these papers:

da Silva S, Paixão J, Rébillat M, Mechbal N. Extrapolation of AR models using cubic splines for damage progression evaluation in composite structures. Journal of Intelligent Material Systems and Structures. October 2020. https://doi.org/10.1177/1045389X20963171

Paixão J.A.S., da Silva S., Figueiredo E. (2020) Damage Quantification in Composite Structures Using Autoregressive Models. In: Wahab M. (eds) Proceedings of the 13th International Conference on Damage Assessment of Structures. Lecture Notes in Mechanical Engineering. Springer, Singapore. https://doi.org/10.1007/978-981-13-8331-1_63

Paixão, J. A. S. ; da Silva, Samuel ; Figueiredo, Eloi ; RADU, L. ; PARK, G. . Delamination area quantification in composite structures using Gaussian process regression and AR models. JOURNAL OF VIBRATION AND CONTROL, 2020.

da Silva, S. Data-driven model identification of guided wave propagation in composite structures. J Braz. Soc. Mech. Sci. Eng. 40, 543 (2018). https://doi.org/10.1007/s40430-018-1462-4

________________________________________________________________________________
