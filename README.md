[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/poplarShift/ice-edge/master) [![DOI](https://zenodo.org/badge/184116955.svg)](https://zenodo.org/badge/latestdoi/184116955)

Welcome! This repository reproduces the analysis of [Randelhoff et al. (2019), "The evolution of light and vertical mixing across a phytoplankton ice-edge bloom"](https://www.elementascience.org/articles/10.1525/elementa.357/), published in [the "Green Edge" special issue](https://collections.elementascience.org/green-edge) and available from the journal or [my website](https://poplarshift.github.io/papers/randelhoff2019evolution.pdf).

> Randelhoff, A., Oziel, L., Massicotte, P., Bécu, G., Galí, M., Lacour, L., Dumont, D., Vladoiu, A., Marec, C., Bruyant, F., Houssais, M.-N., Tremblay, J.-É., Deslongchamps, G. and Babin, M., 2019. The evolution of light and vertical mixing across a phytoplankton ice-edge bloom. Elem. Sci. Anth., 7(1), p.20. DOI: 10.1525/elementa.357

The main files are:
- the [jupyter notebook](https://nbviewer.jupyter.org/github/poplarShift/ice-edge-bloom/blob/master/iceedge_analysis.ipynb?flush_cache=true), also available as [html](iceedge_analysis.html), which contains all the code used for treating the data and turning them into figures. The Supplementary Material was generated directly from [another](iceedge_supmat.html) [notebook](https://nbviewer.jupyter.org/github/poplarShift/ice-edge-bloom/blob/master/iceedge_supmat.ipynb?flush_cache=true).
- hydrographic data as have been used for the present analysis, e.g. [quantities derived per station](data/Randelhoff-et-al-2019_GreenEdge_per-station_v1.0.csv), [C-OPS data with recontructed under-ice and open-water PAR profiles, sea ice concentration etc.](data/Randelhoff-et-al_GreenEdge_PAR_corrected_v1.0.csv), or the [ANP tracer](data/Randelhoff-et-al-2019_GreenEdge_ANP_v1.0.csv).

Note that all data available in this repository (e.g. [nb_data](nb_data)) are provided as have been used in the article and as were available at the time of writing. If you plan on using these data for your own research, it is your responsibility to ensure everything is up to date by using [the official Green Edge data repository](http://www.obs-vlfr.fr/proof/php/GREENEDGE/greenedge.php), and that all data have been treated the way you think they are.

For convenience, you can also find some of the data exactly as have been plotted (for a few figures from the main text).

The code in this repository is licensed under GNU GPL. Data are explicitly exempt from this license and are handled under the terms of the Green Edge data policy.

If you have any requests or comments, let me know! Find contact information on [my website](https://poplarshift.github.io).
