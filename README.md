# FACS_data_decontamination
A data decontamination pipeline for sorting-sequencing data. The pipeline uses sheath fluid as a negative control and high biomass samples as positive control.
The pipeline directly uses DADA2 output files, the seqtab.nochim table and the taxonomy table after taxonomic assignment.
Input data is placed in the input folder.
Results will be written in the results folder.
Threshold can be set manually if preferred.
