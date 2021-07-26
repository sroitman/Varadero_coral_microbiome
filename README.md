# Varadero Reef coral microbiome project
This repository contains all of the code associated with and the analyses performed for: Roitman, S., López-Londoño, T., Joseph Pollock, F. et al. Surviving marginalized reefs: assessing the implications of the microbiome on coral physiology and survivorship. Coral Reefs 39, 795–807 (2020). https://doi.org/10.1007/s00338-020-01951-5
#
The Varadero_microbiome_QIIME1_PreprocessingProcedure.txt file contains all bash code used to run QIIME1 and process the raw DNA sequences.

INPUT: See NCBI BioProject accession number PRJNA639618

OUTPUT: Biom file containing OTU information (otu_table_E18_E19.biom) and tree file (rep_set.tre)

#
The Varadero_microbiome_RMardkown.rmd file contains all R code used to conduct statistical analyses and generate figures.

INPUT: otu_table_E18_E19.biom, rep_set.tre, rep_set_tax_assignments_E18_E19_v2 (file containing taxonomy information), and rapid_map_v8_wat (mapping file).

OUTPUT: PERMANOVA and post-hoc results, PCoA plots, bar plots, and alpha diversity violin plots.


