# Paper

The spectral parameterization method and tool is described in the 
[Parameterizing Neural Power Spectra](https://doi.org/10.1038/s41593-020-00744-x) paper.

The paper includes a series of investigations and applications of the algorithm, all of which have openly available code repositories demonstrating the analyses, which are described and linked here.

If you are looking for information on citing this paper, and how to report on using spectral parameterization, check the 
[reference](https://fooof-tools.github.io/fooof/reference.html) page on the documentation.

### Power Spectrum Model

The power spectrum model itself is implemented and available in the
[FOOOF](https://github.com/fooof-tools/fooof) repository.

This repository covers:
- Figure 1, overlapping nature of periodic and aperiodic spectral parameters
  - this schematic figure is also available in [code](https://fooof-tools.github.io/fooof/auto_motivations/measurements/plot_PeriodicAperiodicFeatures.html#sphx-glr-auto-motivations-measurements-plot-periodicaperiodicfeatures-py) as part of the documentation
- Figure 2, algorithm overview
  - this figure is a variant of one of the [tutorials](https://fooof-tools.github.io/fooof/auto_tutorials/plot_03-FOOOFAlgorithm.html#sphx-glr-auto-tutorials-plot-03-fooofalgorithm-py) from the documentation

Direct Link (Code): https://github.com/fooof-tools/fooof

Direct Link (Documentation): https://fooof-tools.github.io/

### Simulations

The power spectrum model was tested on simulated data, which is available in the 
[SIMparam](https://github.com/TomDonoghue/SIMparam/) repository.

This analysis covers:
- Figure 3, algorithm performance on simulated data
- Figure S2, algorithm performance on simulated data across a broader frequency range
- Figure S3, algorithm performance on simulated data that violate model assumptions
- Figure S5, methods comparisons of measures of the aperiodic component

Direct Link: https://github.com/TomDonoghue/SIMparam/

### EEG Data

The power spectrum model was applied to both resting state and task electroencephalography (EEG) data, 
which is available in the [EEGparam](https://github.com/TomDonoghue/EEGparam/) repository.

This analysis covers:
- Figure 5, age-related shifts in spectral parameters during resting state
- Figure 6, event-related spectral parameterization of working memory in aging

Direct Link: https://github.com/TomDonoghue/EEGparam/

### MEG Data

The power spectrum model was also applied to a large collection of open-access magnetoencephalography (MEG) data, which is available in the [MEGparam](https://github.com/TomDonoghue/MEGparam) repository.

This analysis covers:
- Figure 7, large scale analysis spectral parameters in of resting state MEG data
- Figure S4, oscillation band occurrences and relative powers

Direct Link: https://github.com/TomDonoghue/MEGparam
