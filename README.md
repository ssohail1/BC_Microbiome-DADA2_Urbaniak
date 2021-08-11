# BC_Microbiome-DADA2_Urbaniak
## Sidra Sohail 
## Analyzing the Breast Cancer Microbiome
### DADA2 Analysis of the study by [Urbaniak et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4968547/)
#### Background
The microbiome is a collection of bacteria that reside in tissues where in cancer it has been implicated in a variety of tissues, and specifically distinct microbial communities have been linked to different types of cancers [[Hieken et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4971513/)]. The association of microbial communities to human health has prompted researchers to investigate the microbial ecology of various tissues leading to a surplus of microbial data. This in turn has led to the development of various software and tools that can analyze microbial data and disentangle the biological variation from amplicon sequencing errors [[Callahan et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4927377/)]. Here, I analyze data from _The Microbiota of Breast Tissue and Its Association with Breast Cancer_ study by [Urbaniak et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4968547/) using DADA2 [[Callahan et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4927377/)], where the dataset can be downloaded from the [SRA](https://www.ncbi.nlm.nih.gov/sra) using this accession number SRP076038.
#### Packages and software to install before running
R: Bioconductor, dada2, phyloseq, Biostrings, ggplot2, DECIPHER, phangorn

#### Files in repo
- dada2:
  - DADA2_Analysis.R: Rscript for running DADA2 pipeline 
- phylogenetic:
  - Phylogenetic_Analysis.R: Rscript for phylogenetic analyses where final product is a tree that can be used as input for constructing UniFrac plots. UniFrac is for calculating microbial community and abundance, and can be made in two forms weighted and unweighted.
- proportional_abundance:
  - ProportionalAbundance_Analysis.R: Rscript to visualize the phyloseq object in the form of abundance plots at the phylum, family, and genus levels.

#### How to use
Clone repository into personal directory using this command,  
`git clone https://github.com/ssohail1/BC_Microbiome-DADA2_Urbaniak.git`

To move into BC_Microbiome-DADA2_Urbaniak directory use `cd`,  
`cd BC_Microbiome-DADA2_Urbaniak`
