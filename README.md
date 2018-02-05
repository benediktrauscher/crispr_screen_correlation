# Reproducibility of pooled CRISPR-Cas9 dropout screens

This is a short analysis based on ~ 400 genome-scale CRISPR-Cas9 pooled dropout screens in cancer cell lines looking at replicate correlation at different levels of data processing. A detailed report is included in `crispr_screen_correlation.html`. It shows that while replicate correlation at the level of raw and normalized read counts is always high (Pearson correlation coefficient 0.98) this correlation drops consideriblay when looking at log~2~ fold changes where an average PCC of 0.63 is observed. Note that these numbers may even be biased towards higher correlation values as they are derived from published experiments.
This suggests that looking at replicate correlation at the read count level might provide an overly optimistic estimation of the experiment's reproducibility.

### Contact

For questions and feedback please contact Benedikt Rauscher (b.rauscher@dkfz.de).
