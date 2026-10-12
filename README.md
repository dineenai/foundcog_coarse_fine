# foundcog_coarse_fine

Code, model weights and data accompanying:

> Dineen, Á.T., O'Doherty, C., Truzzi, A., Kravchenko, A., Wade, A.R., King, G., D'Arcy, E.-L., Byrne, A.T., Tarrant, A., Foran, A., Molloy, E.J., and Cusack, R. **The development of coarse and fine feature tuning in infant visual cortex.** (Manuscript submitted.)

> **Status:** Code, documentation and model weights are being finalised and will be uploaded shortly.

## Overview

This repository will contain the code to reproduce the analyses and figures in the paper. The study combines awake infant fMRI (FOUNDCOG project; 2-month-olds, 9-month-olds and adults) with deep neural networks (ResNet-50) trained and tested on blurred or bandpass-filtered images, using representational similarity analysis (RSA) to characterise tuning to coarse and fine visual features along the developing ventral visual stream.

## Resources

| Resource | Location |
|---|---|
| Model weights (blur-trained and bandpass-trained networks) and model–brain correlation values | Zenodo: [doi:10.5281/zenodo.23326150](https://doi.org/10.5281/zenodo.23326150) |
| Infant fMRI data (participants whose caregivers consented to public sharing) | OpenNeuro: [ds006883](https://openneuro.org/datasets/ds006883) |
| FOUNDCOG stimuli and experimental paradigm | [github.com/ClionaOD/foundcog_paradigm](https://github.com/ClionaOD/foundcog_paradigm) |
| FOUNDCOG fMRI preprocessing pipeline | [github.com/ClionaOD/foundcog_analysis](https://github.com/ClionaOD/foundcog_analysis) |

## Licence

Code in this repository is released under the BSD 3-Clause licence (see `LICENSE`). Model weights and data on Zenodo are released under CC-BY-4.0.

## Contact

Áine T. Dineen — dineenai@tcd.ie
