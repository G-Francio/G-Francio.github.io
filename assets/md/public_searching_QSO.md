---
layout: page
title: Searching for bright and high redshfit QSOs
---

**A Quick Overview**: QSOs (Quasi Stellar Objects, particularly bright Active Galactic Nuclei) allow a wide range of studies (spanning from cosmology to galaxy evolution), but we need bright targets to be efficient with telescope time. These were lacking especially in the southern sky, and several surveys were started to find previously undiscovered objects. Among these there is QUBRICS, on which I contributed for a large part of my PhD. After nearly five years, QUBRICS has identified and spectroscopically confirmed more than 2000 QSOs, some of which are the brightest currently available, significantly reducing the time needed to perform future experiments.

[ChatGPT version, where I asked for a more conversational tone](/assets/md/intro_research_chat_gpt.md)

---

**A needle in a haystack problem**  

A large part of my PhD has been dedicated to the search for bright and high-redshift QSOs. QSOs (Quasi Stellar Objects, as they appear as point-like sources on the sky) are extremely important for a variety of reasons: to name a few, we think that they [contribute to the evolution of galaxies ](https://arxiv.org/pdf/2004.06132.pdf) (the so-called quenching, the process through which star formation is suppressed), they allow us to [probe the intergalactic medium](https://arxiv.org/abs/2212.06907) (the gas, mostly hydrogen and helium, that can be found between galaxies), they can be used to test whether [fundamental constants of physics change with time](https://arxiv.org/pdf/2112.05819.pdf), [measure primordial abundances,](/assets/md/public_cosmo_params.md) or even to [measure the expansion of the Universe in "real time"](https://arxiv.org/pdf/0802.1532.pdf). They are nonetheless interesting sources on their own: our current understanding is that QSOs are powered by a supermassive black hole, with matter swirling around it in an accretion disk (Fig. 1). Some of this material is chewed up by the black hole, expelling a large amount of radiation as it does so.

<figure>
    <a title="ESO/M. Kornmesser, CC BY 4.0 &lt;https://creativecommons.org/licenses/by/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Artist%27s_rendering_ULAS_J1120%2B0641.jpg">
        <img width="512" alt="Artist&#039;s rendering ULAS J1120+0641" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Artist%27s_rendering_ULAS_J1120%2B0641.jpg/512px-Artist%27s_rendering_ULAS_J1120%2B0641.jpg" />
    </a>
    <figcaption>1. Artist rendering of a QSO, via Wikimedia Commons. Credit ESO/M. Kornmesser. </figcaption>
</figure>

Despite being intrinsically bright (if we were to represent the power output of the sun as 1 second, the power output of the average QSO would be 3 million years!), they are also far, far away - the currently record holder is a [QSO found at redshift 7.642](https://arxiv.org/2101.03179.pdf),  when the Universe was just 600 million years old. Light becomes dimmer with distance, and as such the apparent luminosity of these objects is rather low. 

This, for observational astronomers, is very unfortunate: getting data where the signal is sufficiently strong, compared to the noise, requires observing the same object for a long time. Moreover, for some of the open questions we are trying to answer, we  need QSO at high redshift (the definition of high redshift is very loose and depends on who you ask!), which are almost always fainter because of their larger distance compared to us. For some experiments, such as the measurement of the expansion of the Universe in real time, we would need to observe objects at redshift greater than 3 for more than 2500 hours, if we limited ourselves to the QSOs known before 2018 in the Southern Hemisphere. That's ***a lot*** of time!

Fortunately, we can work towards trying to find a solution: we can, for example, build larger telescopes, or find brighter QSOs! On the first solution, the [European Southern Observatory](https://www.eso.org/public/) is currently building the largest telescope in the world, the [Extremely Large Telescope](https://elt.eso.org/) (ELT for short). Unfortunately for us, the estimate of 2500h was already computed by imagining a telescope of the same size as the ELT. We then need to find brighter QSOs!

This is challenging! QSOs are very few compared to the number of stars we see: the [largest collection of QSOs](https://heasarc.gsfc.nasa.gov/W3Browse/all/milliquas.html) publicly available contains ~910 000 QSOs across the entire sky, compared to hundreds of millions stars readily available. Moreover, most quasar are fainter than we would need. Finally, QSOs look exactly like stars if we just look up at the sky (Fig. 2). Given these premises, the search seems hopeless :(

<figure>
    <a
        title="APM 08279+5255, the quasar with the highest apparent luminosity found to date. Image from Aladin lite."
        href="https://aladin.cds.unistra.fr/AladinLite/?target=08%2031%2041.711%2B52%2045%2017.62&fov=0.18&survey=CDS%2FP%2FPanSTARRS%2FDR1%2Fcolor-z-zg-g"
    >
        <img width="512" alt="Sky patch with APM 08279+5255 in the middle, stars and galaxies" src="/assets/img/APM_08279+5255.webp" />
    </a>
    <figcaption>2. The source in the center of the image is APM 08279+5255, the quasar with the highest apparent luminosity found to date. Around it, a lot of stars that look about the same as the QSO.</figcaption>
</figure>


**QSO surveys: the efforts to find the needle**

However, for once, we are lucky! The spectrum (i.e., the amount of light that reaches us as a function of wavelength) of QSOs looks always about the same (Fig. 3)! And, more importantly, the shape of the spectrum is rather unique and different from that of stars or galaxies. We can make use of these properties and design specific surveys with the aim of identifying the largest number of QSOs possible.

<figure>
    <a title="Spectra of two quasars, one at z = 0.158, the other at z = 3.62" href="https://www.astro.ucla.edu/~wright/Lyman-alpha-forest.html">
        <img width="512" alt="Spectra of two quasars" src="https://www.astro.ucla.edu/~wright/Lya-forest-60.gif" />
    </a>
    <figcaption>3. Spectra of two QSOs at very different redshift. Despite the different distance, their instrisic spectrum is very similar.</figcaption>
</figure>


This is a work that has continued incessantly since the discovery of the first QSO in 1962 and that will continue in the future. Several large projects (such as the [Sloan Digital Sky Survey](https://www.sdss.org/), SDSS for short) have produced large catalogues of QSOs, the latest containing more than 800 000 targets. Unfortunately (again!) the largest efforts in searching QSOs have been focused on the Northern Hemisphere, while the ELT is being built in the South.

Repeating a project such as the SDSS in the South would be an immense feat, and although there were plans to do so, none were close to completion when this story began in 2018. More focused projects were started, with the aim of identifying the brightest QSOs available in the Southern Sky: examples include the ELQs surveys ([ELQS](https://arxiv.org/abs/1812.04639) and [PS-ELQS](https://arxiv.org/pdf/1905.04069.pdf)), [AllBRICQS](https://arxiv.org/pdf/2209.09342.pdf) and [QUBRICS](https://arxiv.org/pdf/1909.06391.pdf).


**Well, but how did you contribute to this story?**

QUBRICS has been a large focus of my PhD work: since joining the collaboration, I have worked on the selection of quasar candidates using machine learning (working with an extension of the Random Forest, the [Probabilistic Random Forest](https://arxiv.org/pdf/1811.05994.pdf)). Once a list of candidates is ready, we observe them targeted campaigns, in order to confirm their nature and redshift. I have also been responsible for writing proposals, coordinating with support astronomers and was lucky enough to [travel to Chile](/assets/img/me_La_silla), at the La Silla Observatory, for two visitor mode runs. To date, QUBRICS has observed more than 1200 candidates, finding hundreds of bright and high redshift QSOs (Fig. 4).
<figure>
    <a title="Current status of QUBRICS, from Cristiani et al. 2023" href="https://arxiv.org/pdf/2304.00362.pdf">
        <img width="512" alt="Scatter plot of i magnitude vs redshift for QSOs in QUBRICS" src="/assets/img/current_status_QUBRICS.webp" />
    </a>
    <figcaption>4. Current status of QUBRICS. Blue and red dots are QSOs discovered by our survey, grey dots sources known beforehand.</figcaption>
</figure>


Most importantly, objects found by these joined efforts are extremely bright! In fact, they are the brightest we can currently access. The scientific exploitation of these objects has already started: an [ESO large programme](https://archive.eso.org/wdb/wdb/eso/approved_runs/query?tel=UT2&prog_id=112.25NR.001&period=112&remarks=Type:%20Large), of which I am CoI of, has been approved, targeting a subset of QUBRICS' discoveries. This will provide a large dataset of high quality data that can be used to tackle some of the open questions mentioned above. Moreover, [we recently revised](https://arxiv.org/pdf/2304.00362.pdf) the estimates for the time required to perform the measurement of the expansion of the Universe in real time. Using these new QSOs, the time needed decreases to 1500h, and observations have already started targeting the two brightest QUBRICS discoveries. I must admit that 1500h is still a long time, but a significant improvement!


**A look to the future**

QUBRICS is not done, and there are plans to continue the search for QSOs in the future. At present, our efforts are directed towards the identification of higher redshift targets (approximately at redshift ~5.0) in order to understand how to the QSO luminosity function evolves; these objects are also fundamental to understand the re-ionization history of the Universe (the process through which most of the gas in the Universe changed form a neutral to an ionised state). In parallel, we have started a targeted search for lensed objects, using publicly available catalogues. There are exciting discoveries waiting for us!