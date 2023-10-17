# clf-iir-evo
Code accompanying paper "Numeral classifiers and number marking in Indo-Iranian: a phylogenetic approach"

To replicate results and graphics, run the following commands:

```
python make_states.py
Rscript inference_stan_constrained.R
Rscript make_graphics_pdf.R
Rscript make_density_map.R
Rscript make_consensus_simmap_with_probs.R
Rscript ia_iran_trans.R
```

Code used to generate the tree sample can be found here: https://github.com/gerhardJaeger/indo-iranian-ASJP-trees/blob/master/code/indoiranian.Rev

[![DOI](https://zenodo.org/badge/291749343.svg)](https://zenodo.org/doi/10.5281/zenodo.10013713)
