# rare_common
Data and analysis scripts for Gibson et al. 2020 An experimental test of parasite adaptation to common versus rare host genotypes

Analysis file: 
1) Gibson_BiolLett_Revision.rmd - contains all analyses associated with the paper


Data files:
1) CommonClone_ancestor: associated with Fig S1; contains ID(unique ID code), Experiment (experimental evolution project, either 1, AKG or 2, PSW), date of mortality assay, assayed host genotype, technical replicate, individual counting bodies, number of live hosts on mortality assay plates, total number added, number estimated to be dead, mortality rate, and average and SE across technical replicates
2) CommonClone_homogeneous: associated with Fig S2 and Table S1 and text of the Supplemental Results; contains Experiment, Assay (two distinct assays), assay date, experimental treatment of parasite lineage, parasite lineage replicate number, assayed host genotype, technical replicate in mortality assay, individual counting bodies, number of live hosts on mortality assay plates, total number added, number estimated to be dead, and mortality rate
3) CommonClone_dataset: focal dataset presented in Fig 2, Table S2, Table S3, and text of the Results and Supplemental Results; contains Experimenta, assay, assay date, experimental treatment (heterogeneous host combination in which parasite lineage was selected), parasite lineage replicate number, assayed host genotype, frequency of host genotype during experimental selection, host genotype that was common in experimental selection, technical replicate of mortality assay, individual counting bodies, number of live hosts on mortality assay plates, total number added, number estimated to be dead, mortality rate, mortality rate of ancestral parasites on assayed host genotype and standard error, difference between evolved mortality and ancestral mortality, proportional change from ancestral parasites
4) CommonClone_meta: dataset for meta-analysis in Fig. S3 and Supplemental Results; derived from CommonClone_dataset, includes calculations of effect sizes
