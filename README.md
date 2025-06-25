# shotgun-genetic-engineering
Code to generate all figures from the Shotgun Genetic Engineering paper

Scripts and sequences associated with Shotgun Genetic Engineering as described at:

Contains --

1. Pipeline for extraction of barcodes from amplicon-seq data

      - Requires concatenated paired-end fastq files (e.g. generated using pear v0.9.11)
  
2. Analysis of extracted barcodes from 4 groups of samples

      - Controls (pre-packaging; post-infection, pre-selection CHO; post-infection, pre-selection Jurkat)
      - CHO-Val
      - CHO-Ile
      - Jurkat-Val
        § Includes Random Forest model generation to delineate TUs responsible for valine prototrophy
  
3. Monte Carlo simulations of high MOI random integration events

4. CSV file containing all barcodes used in the SGE library (LibJTR012_Barcodes.csv)

5. Xlsx file containing file names and phenotypic information for each clone within each of the 4 groups of samples (SGE_Clone_Overview.xlsx)
