# Mound Key Wild Cotton
<img src="https://github.com/Wendellab/MoundKeyCottons/blob/main/Supplymentary/IMG_3837.JPG" width="200" />

### Codes following the data analysis order presented in the paper, including:

This is needs some work to clean the code and put things in a logical ways! - Weixuan is on it   😝

####  ▪️ Pop gene analysis (PCA, NJ-tree, Structure)
1. All AD1 65 samples' raw reads were trimmed with [Trimmomatic](https://github.com/usadellab/Trimmomatic.git).

2. Following [sentieon-dnaseq](https://github.com/Sentieon/sentieon-dnaseq.git), trimmmed reads mapping; GVCF calling; VCF calling. 
  
3. SNPs filtering via [vcftools](https://vcftools.sourceforge.net/man_latest.html) and [bcftools](https://samtools.github.io/bcftools/bcftools.html). 

4. Using biallelic SNPs to estimate population genetic groups via [PLINK](https://www.cog-genomics.org/plink/) (PCA) and [LEA](https://bioconductor.org/packages/release/bioc/html/LEA.html).
   
5. Building a rooted NJ-tree using bialleic SNPs by including additional two AD4 outgroups. 

####  ▪️ Genetic variation comparison (Pi, Dxy, Fst, He, Fis, LD)
1. [Pixy](https://github.com/ksamuk/pixy.git) was applied to 


####  ▪️ Novel SNPs tabulating
1. Bcftools

####  ▪️ MK cotton population demographic analysis (PCA, Tajima's D, SFS, Ne)


### Please cite the paper: 

Ciation: [Ning, W., Rogers, K.M., Hsu, CY. et al. Origin and diversity of the wild cottons (*Gossypium hirsutum*) of Mound Key, Florida. Sci Rep 14, 14046 (2024). https://doi.org/10.1038/s41598-024-64887-8](https://www.nature.com/articles/s41598-024-64887-8)

