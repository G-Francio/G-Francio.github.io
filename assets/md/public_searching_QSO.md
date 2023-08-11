---
layout: page
title: Searching for bright and high redshfit QSOs
---

TLDR: QSOs allow a wide range of studies (spanning from cosmology to galaxy evolution), but we need bright targets to be efficient with telescope time. These were lacking in the South, and several surveys were started to find previously undiscovered objects. Among these there is QUBRICS, on which I contributed for a large part of my PhD. After nealy five years, QUBRICS has identified and spectroscopically confirmed more than 2000 QSOs, some of which are the brightest available, significantly reducing the time needed to perform future experiments.

---

A large part of my PhD has been dedicated to the search for bright and high-redshift QSOs. These objects are extremely important for a variety of reasons: to name a few, we think that they [contribute to the evolution of galaxies ](https://arxiv.org/pdf/2004.06132.pdf) (the so called quenching), they allow to [probe the intergalactic medium](https://arxiv.org/abs/2212.06907) (the gas, mostly hydrogen, that can be found between galaxies), they can be used to test whether [fundamental constants of physics change with time](https://arxiv.org/pdf/2112.05819.pdf), or even to [measure the expansion of the Universe in "real time"](https://arxiv.org/pdf/0802.1532.pdf). They are nonetheless interesting sources on their own: our current understanding is that QSOs are powered by a supermassive black hole, with matter swirling around it in an accretion disk.

<a title="ESO/M. Kornmesser, CC BY 4.0 &lt;https://creativecommons.org/licenses/by/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Artist%27s_rendering_ULAS_J1120%2B0641.jpg"><img width="512" alt="Artist&#039;s rendering ULAS J1120+0641" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Artist%27s_rendering_ULAS_J1120%2B0641.jpg/512px-Artist%27s_rendering_ULAS_J1120%2B0641.jpg"></a>

Despite being instrinsecally extremely bright (if we were to represent the power output of the sun as 1 second, the power output of the average quasar would be 3 milion years!), they are also far, far away. Light becomes dimmer with distance, and as such the apparent luminosity of these objects is rather low.

This, for observational astronomers, is very unfortunate: getting data where the signal is sufficiently strong, compared to the noise, requires observing the same object for a long time. For some experiments, such as the measurement of the expansion of the Universe in real time, we'd need to observe objects for more than 2500 hours, if we limited ourselves to the QSOs known before 2018 in the Southern Hemispehere. That's ***a lot*** of time!

Fortunately, we can work towards trying to find a solution: we can, for example, build larger telescopes, or find brighter QSOs! On the first part, the [European Southern Observatory](https://www.eso.org/public/) is currently building the largest telescope in the world, the [Extremely Large Telescope](https://elt.eso.org/) (ELT for short). Unfortunately for us, the estimate of 2500h was already computed imagining a telescope of the same size of the ELT. We then need to find brighter QSOs!

This is, as one can imagine, challenging: quasars are very few compared to the number of stars we see, for example. Moreover, most quasar are fainter than we'd need. Finally, QSOs look exacly like stars if we just look up at the sky. Given this premises, the search seems hopeless :(

<a title="APM 08279+5255, the quasar with the highest apparent luminosity found to date. Image from Aladin lite." href="https://aladin.cds.unistra.fr/AladinLite/?target=08%2031%2041.711%2B52%2045%2017.62&fov=0.18&survey=CDS%2FP%2FPanSTARRS%2FDR1%2Fcolor-z-zg-g"><img width="512" alt="Sky patch with APM 08279+5255 in the middle, stars and galaxies" src="/assets/img/APM_08279+5255.webp"></a>

For once, however, we are lucky! The spectrum (i.e., the amount of light that reaches us as function of wavelength) of QSOs looks always about the same! And, more importantly, the shape of the spectrum is rather unique, and different than that of stars, or galaxies. We can make use of these property, design specific surveys with the aim of identifying the largest number of QSOs possible.

<a title="Spectra of two quasars, one closeby, one very, very far away" href="https://www.astro.ucla.edu/~wright/Lyman-alpha-forest.html"><img width="512" alt="Spectra of two quasars" src="https://www.astro.ucla.edu/~wright/Lya-forest-60.gif"></a>

This is a work that has continued incessantly since the discovery of the first QSO, in 1960, and that will continue in the future. Several large projects (such as the [Sloan Digital Sky Survey](https://www.sdss.org/), SDSS for short) have produced large catalogues of QSOs - the latest containing more than 800 000 targets. Unfortunately (again!) the largest efforts in searching QSOs have been focused on the Northern Hemisphere, while the ELT is being built in the South.

Repeating a project like the SDSS in the South would be an immense feat, and although there were plans to do so, none were close to completion when this story began in 2018. More focused project were started, with the aim of identifyng the brightest QSOs available in the Southern Sky: examples include the ELQs surveys ([ELQS](https://arxiv.org/abs/1812.04639) and [PS-ELQS](https://arxiv.org/pdf/1905.04069.pdf)), [AllBRICQS](https://arxiv.org/pdf/2209.09342.pdf) and [QUBRICS](https://arxiv.org/pdf/1909.06391.pdf).

The latter survey has been the focus of my PhD work: since joining the collaboration, I have worked on the selection of quasar candidates using machine learning (working with an extension of the Random Forest, the [Probabilistic Random Forest](https://arxiv.org/pdf/1811.05994.pdf)). Once a list of candidates is ready, we observe them targeted campaigns, in order to confirm their nature and redshift. To date, QUBRICS has observed more than 1200 candidates, finding hundreds of bright and high redshift QSOs.

<a title="Current status of QUBRICS, from Cristiani et al. 2023" href="https://arxiv.org/pdf/2304.00362.pdf"><img width="512" alt="Scatter plot of i magnitude vs redshift for QSOs in QUBRICS" src="/assets/img/current_status_QUBRICS.webp"></a>

Most importantly, objects found by these joined effors are extremely bright! As a matter of fact, they are the brightest we can access to. Given this sample, we revised the estimates for the time required to perform some experiments, such as measuring the expansion of the Universe in real time. Using these new QSOs, the time needed to perform the experiment decreases to 1500h. I admit, sill a lot of time, but a significantly better than before!