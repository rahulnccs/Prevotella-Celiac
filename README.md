# Prevotella-Celiac
Microbiome analysis in gluten sensitive mice before and after gavage of Prevotella species

Stool samples were collected at the beginning and the termination of the experiment. Total DNA was extracted using a QIAGEN DNA extraction kit according to the manufacturer’s instructions. The amplicon sequencing of the V3-V5 region of 16S rRNA was done using Illumina Miseq. The microbiome analysis was done by processing demultiplexed fastq using QIIME pipeline (Caporaso et al., 2010).

For diversity analyses, phyloseq and microbiome R package were used and visualization of plots and figure was done using ggplot package in R (Hadley Wickham, 2016; Leo and Shetty, 2017; McMurdie and Holmes, 2013). 

Alpha bacterial diversity was measured using the shannon diversity index. The shannon index is a commonly used diversity index that takes into account both abundance and evenness of species present in the community (Kim et al., 2017). 

To compare the microbial communities among the treatment groups at the beginning and after treatment, beta diversity was calculated using the Bray-Curtis distance matrix. 

In the name of Rmd files GFD stands for Gluten free diet and GCD for gluten containg diet. All of the Rmd files starting with name GFD has codes for microbiome analyis of Gluten free diet fed mice. Whereas, all of the Rmd files starting with name GCD has codes for microbiome analyis of Gluten containing diet fed mice.
