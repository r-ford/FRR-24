This repository contains the code (in Jupyter Notebooks) and some data used to generate the figures in [Ford et al. (2025)](https://doi.org/10.1175/JCLI-D-24-0164.1).

There are four notebooks:
- `kernel-feedback-analysis`, which performs a feedback analysis using radiative kernels that is used in the `feedback-figures` notebook
- `nonfeedback-figures`, which generates Figs. 1–4 and 7–10
- `feedback-figures`, which generates Figs. 5 and 6
- `appendix-figures`, which generates Figs. A1–A4

The CESM output used in these notebooks is remotely accessed through a Jetstream2 object store. The hfds (OHU) datasets are included in this repository in the `hfds_TCR_diff_1x1` folder. The CAM5 kernels (Pendergrass 2018) used in the feedback analysis are not included here and should be downloaded from [![DOI](https://zenodo.org/badge/DOI/10.5065/D6F47MT6.svg)](https://zenodo.org/records/997902) in order to run `kernel-feedback-analysis` locally. (Note: it is not necessary to rerun the feedback analysis in order to run the `feedback-figures` notebook, since a dataset with the feedback values is included in the Jetstream2 object store).

Ford, R. R., B. E. J. Rose, and M. C. Rencurrel, 2025: Transient Climate Sensitivity Shaped by Low Cloud Changes Remotely Driven by Southern Ocean Processes. _Journal of Climate_, **38**, 797–813, https://doi.org/10.1175/JCLI-D-24-0164.1.

Pendergrass, A. G., A. Conley, and F. M. Vitt, 2018: Surface and top-of-atmosphere radiative feedback kernels for CESM-CAM5. _Earth System Science Data_, **10**, 317–324, https://doi.org/10.5194/essd-10-317-2018.
