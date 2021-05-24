Host-specific epibiomes of distinct Acropora cervicornis genotypes persist after field transplantation
-----------
	
R scripts and input files for completing phylogenetic analyses described in "Host-specific epibiomes of distinct Acropora cervicornis genotypes persist after field transplantation", Emily Aguirre, emilyagu@usc.edu

We studied the epibiome of ten Acropora cervicornis genotypes residing at an in-situ nursery (T0) and after transplantation to nine different environments, one year later (T12) to investigate the relative roles of host genotype and environment in structuring the epibiome. We applied amplicon sequencing of the 16S rRNA gene to assess microbial composition, richness and beta-diversity throughout time and transplant field sites. Here, we extract MD3-55 sequences from the phyloseq object, "ps_midi" in the final script : final_script_acer1.txt, (see : https://github.com/symbiotic-em/acer_epi_final) and create a .treefile file for visualization.

Annotations in the .R script describe input files, although all analyses can be re-created by starting with the raw .fastq files available for download at NCBI SRA under accession code: PRJNA630333.
	
Files in this repository 
-----------

    Phylogenetic analysis/placement of MD3-55 sequences
	- Input file: acer_phylo_tree_script.txt           script
	- Input file: all_ricks_seqs.fa                    fasta with MD3-55 and other Rickettsiales 16S rRNA sequences
	- Input file: midi.tsv                             .tsv containign extracted MD3-55 ASV sequences from a phyloseq object 
	
