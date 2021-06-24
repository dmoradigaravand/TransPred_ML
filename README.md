# Machine learning prediction of resistance to sub-inhibitory antimicrobial concentrations from Escherichia coli genomes

Sam Benkwitz-Bedford,
Martin Palm,
Talip Yasir Demirtas,
Ville Mustonen,
Anne Farewell,
Jonas Warringer,
Danesh Moradigaravand1†*,
Leopold Parts†*

†  Corresponding authors 
* Shared last authorship  
Danesh Moradigaravand: d.moradigaravand@bhm.ac.uk
Leopold Parts: leopold.parts@sanger.ac.uk 

 
Abstract 
Escherichia coli is an important cause of bacterial infections worldwide, with multidrug resistant strains incurring substantial costs on human lives. Besides therapeutic concentrations of antimicrobials in healthcare settings, the presence of sub-inhibitory antimicrobial residues in the environment and in the clinics selects for antimicrobial resistance (AMR), but the underlying genetic repertoire is less well understood. We used machine-learning to predict the population doubling time and cell growth yield of 1,407 genetically diverse E. coli strains expanding under exposure to three sub-inhibitory concentrations of six classes of antimicrobials from single nucleotide genetic variants, accessory gene variation and the presence of known AMR genes. We predicted cell growth yields in the held-out test data with an average correlation (Spearman's ρ) of 0.63 (0.36 - 0.81 across concentrations) and cell doubling times with an average correlation of 0.59 (0.32 - 0.92 across concentrations), with moderate increases in sample size unlikely to improve predictions further. This finding points to the remaining missing heritability of growth under antimicrobials exposure being explained by effects that are too rare or weak to be captured unless sample size is dramatically increased, or by effects other than those conferred by the presence of individual SNPs and genes. Predictions based on whole genome information were generally superior to those based only on known AMR genes, and accurate for AMR resistance at therapeutic concentrations. We pinpointed genes and SNPs determining the predicted growth and thereby recapitulated many known AMR determinants. Finally, we estimated the effect sizes of resistance genes across the entire collection of strains, disclosing the growth effects for known resistance genes in each individual strain. Our results underscore the potential of predictive modelling of growth patterns from genomic data under sub-inhibitory concentrations of antimicrobials, although the remaining missing heritability poses a challenge for achieving the accuracy and precision required for clinical use. 
