# Supplementary Data
Supplementary data for Brown et al. 2026 Expression of Retroviruses in Guinea Pig Lymphomas. Full details are provided in the manuscript.


## ST1_genomes.tsv

Supplementary Table 1: Table showing the species names, common names and genome builds for all genomes analysed in this study. 


## ST2_byregions.tsv
Supplementary Table 2: Table showing the details of all ERV regions identified in this study. Columns labels are listed in ST1_columns.tsv.

## ST3_bydomain.tsv
 

Supplementary Table 3: Table showing details of all individual ERV domains identified in this study. Column labels are listed in ST3_columns.tsv 

 
## ST4_superfamily.tsv

Supplementary Table 4: Table showing the SUPERFAMILY domains identified in the ERV ORFs identified in this study. 

## ST5_gps.tsv

Supplementary Table 5: Case details of Guinea pig lymphoma sections probed with RNAscop

## genome_plots
Genome structure for all regions listed in ST2. Positions are relative to the chromosome or contig in which the region is found. For coding regions, bars above the x-axis show the extent of the ORFs encoding gag, pol and env, with shaded regions within these bars showing the extent of the domain identified with HMMER. For LTRs, bars above the x-axis show the extent of the regions which could be aligned with BLAST. Bars below the x-axis show protein SUPERFAMILY domains identified within the coding regions, full details are provided in Supplementary Table 3.

## ERV_regions
BED and FASTA formatted files containing the positions / sequences of all the ERV-like regions with a BLAST bit score >200 identified in Caviomorph genomes using DIAMOND BLASTX, with hits separated by <10,000 nt merged into single regions.

## original_ORFs
BED and FASTA formarred files containing all ORFs >200 amino acids identified in the regions listed in the ERV_regions directory.

## HMMs
Profile HMMs built using HMMER to represent retroviral proteins, based on the ERVsearch database (https://github.com/KatyBrown/ERVsearch).

## domains
BED and FASTA files of ORFs for regions with gag, pol and env ORFs  >200 amino acids (plus pro for betaretroviruses), in the correct orientation, showing only the region matching the profile HMM. _aa FASTA files are translated sequences.

## phylogenies
Full sequence sets in FASTA format and phylogenetic trees in NEWICK format for each retroviral gene and genus.
