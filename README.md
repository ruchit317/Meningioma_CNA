# Meningioma_CNA
Scripts for figure generation related to meningioma microarray data. No custom code or packages were utilized, as seen in scripts.

Scripts included here were used to assess copy number alterations in meningioma. Scripts include code chunks used to open and format processed microarray data
and create manuscript associated figures - code chunks should be used as examples as clinical data cannot be released publicly. Scripts present here were also used to analyze publicly available DNA methylation data.

Mening_CNA_Arm_Percent_Master.Rmd begins organizing the data and the bulk of figure generation.
Mening_CNA_Genome_Locations.Rmd helps plot copy number alterations across the genome to generate frequency maps at genome locations.
Primary_Recurrent_CNA.Rmd looks at subset comparison of paired primary and recurrent cases and changes in copy number alteration location/size.
Methylation_Processing_CNA.Rmd uses the conumee package to look at multifocal sampled meningiomas and primary-recurrent meningiomas where copy number is derived from methylation data.
Mening_CNA_Validation.Rmd looks at impact of copy number thresholds on other meningioma molecular classifiers seperate from the Integrated Grade.
Mening_CNA_Arm_Sensitivity.Rmd analyzes each chromosome arm and how susceptible each is to variations in copy number thresholds
Mening_CNA_ExtraStats.Rmd include code chunks that perform statistics and some additional Kaplan-Meier curve plots.

Scripts included here are associated with manuscript [doi to be added upon publication]. Please contact the corresponding author on the manuscript for additional information.
