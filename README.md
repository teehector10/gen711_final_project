# GEN 711 Final Project: COVID-19 

## BACKGROUND [Julia]
Our final project focuses on the COVID-19 pandemic which has taken place over the past couple years. COVID-19 is a disease caused by the highly transmissbale SARS-CoV-2, and this project specifcially looks at the human-transmission isolation source of the oronasopharynx, meaning the mouth, nose, and pharynx region of the body. This study was inspired by a research report published in March 2021, which discusses in depth the sequencing methods that could be employed to better understand the infection mechanism of SARS-CoV-2 with ACE2 receptor binding in different organ tissues, and how this information can be related to treatment methodologies in the future for affected patients of differing origins of infection. The paper compares ACE2 receptor expression levels in susceptible human tissues at a variety of locations across the body which correlates to the origin of the SARS-CoV-2 infection site in each patient (Xiaomin et al. 2021). Next-generation sequencing techniques of the metagenome and single-cell sequencing was applied to locate SARS-CoV-2 cellular hosts, to prevent interspecies transmission of this disease as well as other related public health scares to come. Our project compares two different COVID-19 geneome sequences of the oronasopharynx isolation, April 2020 vs April 2022, in the United States patients, using fasta files to generate a Phylogenetic tree to visualize ancestral alterations and run an alignment for nucleotide sequence similarity. 

### Figure 1 
This image from the previously cited paper titled "Next-Generation Sequencing Revals the Progression of COVID-19" shows ACE2 expression levels in the human body as percentages per organ location (Xiaomin, et al. 2021). To apply to our project, the thyroid level of expression can correlate to the oronasopharynx isolation region.

![image](https://user-images.githubusercontent.com/103778390/166063050-5dc2afef-0e22-4914-932f-a1e870fcead1.png)

## Methods [Tobi]
For our project we downloaded fasta files containing the complete SARS-CoV-2 genome from samples taken from the oronasopharynx of infected individuals provided by the National Center for Biotechnology Information. We compared the sequences by running a BLAST alignment to observe any differences in the genomes between 2020 and 2022. Additionally, we constructed a phylogenic tree from the individual samples taken from each year to look at how closely related the two are, and whether there was minimal or greater divergence between the samples.

## Findings 
When conducting our phylogenic tree, we were able to visualize the ancestral background of differing COVID-19 isolations. 

### Figure 2 [Izzy]
<img width="554" alt="Screen Shot 2022-05-01 at 3 03 05 PM" src="https://user-images.githubusercontent.com/103778546/166160815-f95a3ff4-ac0d-4ae6-b81e-3d841cc8141d.png">

When aligning the sequences, we were able to look at how COVID-19 has changed in nucleotides by comparing and contrasting. 
### Figure 3 [Brenna]
<img width="1404" alt="Screen Shot 2022-04-29 at 4 22 42 PM" src="https://user-images.githubusercontent.com/103778546/166161725-1fa7f79c-138d-4303-9518-dd243ed94291.png">

## Sources 
Xiaomin, Chen, et al. “Next-Generation Sequencing Reveals the Progression of COVID-19.” Frontiers in Cellular and Infection Microbiology, vol. 11, no. 2235-2988, 2021, https://doi.org/10.3389/fcimb.2021.632490. 
