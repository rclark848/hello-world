**Scripts:**
 * **BF Correlation Plots.R:** Reads in .csv file of Bayes Factors and XtX values outputted by BayPass and creates correlation plots by environmental variables.
 * **Diversity_Script.R:** Calculates Ho, He and Fis from allele frequencies.
 * **ECDFS for Sim v Real BFs.R:** Contains code for Mann-Whitney U-tests and plots of empirical cumulative distribution functions for Bayes Factors from raw data and permuted data.
 * **Fst_script.R:** Calculates per-locus Fst and population pairwise Fst values from VCF.
 * **PCAs.R:** Reads in eigenvector information from plink and creates PCA plots.
 * **Pull_BFs.R:** Reads in raw "summary_betai.txt" files from BayPass and reorganizes into one .csv file for easier downstream analysis. Also pulls out candidate loci.
 * **STRUCTURE_script.R:** Reads in STRUCTURE output files, runs CLUMPP and creates output plots for visualization of STRUCTURE results. Also creates ML and Evanno method plots to identify the "best" value of K.
 * **TajimaD_script.R:** Reads in .csv files containing Tajima's D output from VCFtools and calculates the mean (+ SE) Tajima's D in each population and with all populations pooled. Also contains code for Mann-Whitney U-tests and plots of empirical cumulative distribution functions (outlier vs. all transcripts).
 * **Write Simulation Pop Data for BayPass.R:** Creates permuted datasets to run in BayPass and create distributions of Bayes Factors under null hypothesis (no association between allele frequencies and environmental factors).
 * **Write_Sim_Data_Het_CIs.R:** Writes simulation populations and bootstraps to create CIs for Ho, He and Fis.
 * **XtX_Calibration.R:** Moddified code from Gautier (2015) to create pseudo-observed datasets (PODs) to generate 95% significance thresholds for XtX values. Once PODs are run in BayPass, contains modified code to calculate XtX significance cut-off.
 * **pi.R:** Reads in .csv files containing site pi output from VCFtools and calculate sthe mean (+ bootstrapped CI) for pi in each populatoin and with all populations pooled.
 * **relatedness.R:** Calculates pairwise relatedness (point estimates for all possible pairs, mean within-population relatedness, and CI for within-population relatedness).
 
 *If input files for a script were created by running code and/or calling programs on a remote workstation, details on the code used can be found in /Scripts/Upstream_Analyses.*