# GEN 711 Final Project: COVID-19 

## BACKGROUND [Julia]
Our final project focuses on the COVID-19 pandemic which has taken place over the past couple years. COVID-19 is a disease caused by the highly transmissbale SARS-CoV-2, and this project specifcially looks at the human-transmission isolation source of the oronasopharynx, meaning the mouth, nose, and pharynx region of the body. This study was inspired by a research report published in March 2021, which discusses in depth the sequencing methods that could be employed to better understand the infection mechanism of SARS-CoV-2 with ACE2 receptor binding in different organ tissues, and how this information can be related to treatment methodologies in the future for affected patients of differing origins of infection. The paper compares ACE2 receptor expression levels in susceptible human tissues at a variety of locations across the body which correlates to the origin of the SARS-CoV-2 infection site in each patient (Xiaomin et al. 2021). Next-generation sequencing techniques of the metagenome and single-cell sequencing was applied to locate SARS-CoV-2 cellular hosts, to prevent interspecies transmission of this disease as well as other related public health scares to come. Our project compares ten different COVID-19 geneome sequences of the oronasopharynx isolation, five from each time span of April 2020 or April 2022, in the United States patients, using fasta files to generate a Phylogenetic tree to visualize ancestral alterations and run an alignment for nucleotide sequence similarity. 

### Figure 1 
This image from the previously cited paper titled "Next-Generation Sequencing Revals the Progression of COVID-19" shows ACE2 expression levels in the human body as percentages per organ location (Xiaomin, et al. 2021). To apply to our project, the thyroid level of expression can correlate to the oronasopharynx isolation region.

![image](https://user-images.githubusercontent.com/103778390/166063050-5dc2afef-0e22-4914-932f-a1e870fcead1.png)

## Methods [Tobi]
For our project we downloaded fasta files containing the complete SARS-CoV-2 genome from samples taken from the oronasopharynx of infected individuals provided by the National Center for Biotechnology Information. We compared the sequences by running a BLAST alignment to observe any differences in the genomes between 2020 and 2022. Additionally, we constructed a phylogenic tree from the individual samples taken from each year to look at how closely related the two are, and whether there was minimal or greater divergence between the samples.

## Findings 
When conducting our phylogenic tree, we were able to visualize the ancestral background of differing COVID-19 isolations. 

### Figure 2 [Izzy]
<img width="554" alt="Screen Shot 2022-05-01 at 3 03 05 PM" src="https://user-images.githubusercontent.com/103778546/166160815-f95a3ff4-ac0d-4ae6-b81e-3d841cc8141d.png">

When aligning the sequences, we were able to look at how COVID-19 has changed in nucleotides by comparing and contrasting and looking at the mutations and how consistent they were between the two time periods. Now when we looked at our alignment, we found that nearly all of our sequences from the same time period had the same mutation, with only a few outliers. 

### Figure 3 [Brenna]
<img width="1404" alt="Screen Shot 2022-04-29 at 4 22 42 PM" src="https://user-images.githubusercontent.com/103778546/166161725-1fa7f79c-138d-4303-9518-dd243ed94291.png">

Using a program called SnapGene we were able to align our sequences and compare them to the original sequence from Wuhan and looked for changes. Our goal with using this program was to just look for differences but we decided to go further and try and look at where the most mutations occured. This happened between 21,500 and 25,300 which is where according to protein coding sequence analzyzed by the NIH and PubMED is where the spike protein or the S surface glycoprotein is located (PubMed). So by analyzing this alignment we are able to see that there are mutations where this spike protein is located that are oresent in the 2022 sequences and not the 2020, showing us how COVID has mutated over time. 

<img width="741" alt="Screen Shot 2022-04-29 at 5 06 56 PM" src="https://user-images.githubusercontent.com/103778546/166611587-e57c2f2b-b861-4f0b-8013-5a292182ccda.png">

## Sources 
     Xiaomin,C., Kang,Y., Luo,J., Pang,K., Xu,X., Wu,J., Li,X. and Jin,S. “Next-Generation Sequencing Reveals the Progression of COVID-19.” Frontiers in Cellular and Infection Microbiology, vol. 11, no. 2235-2988, 2021, https://doi.org/10.3389/fcimb.2021.632490. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T.,Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D. “Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-3KU8AQYTU/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345302. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B.,Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-B4PJHW57C/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345293. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-BAW3HNWUN/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345291. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKEF52PWY/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345296. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B. Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKPQ8WHER/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345288. 

     Lemieux,J.E., Siddle,K.J., Shaw,B., Adams,G., Pierce,V., Turbett,S., Anahtar,M., Branda,J., Slater,D., Harris,J., Lin,A.E.,Gladden-Young,A., Lagerborg,K., Rudy,M., DeRuff,K., Carter,A.,  Normandin,E., Bauer,M., Reilly,S., Tomkins-Tinch,C., Loreth,C.,Chaluvadi,S., Neumann,A., Cusick,C., Chapman,S.B., Gnirke,A.,Flowers,K., Cerrato,F., Birren,B.W., Gallagher,G., Smole,S., Park,D.J., MacInnis,B.L., Ryan,E., LaRocque,R., Rosenberg,E. and Sabeti,P.C.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA_MGH_00424/2020, Complete Genome.” NCBI Nucleotide, 4 June 2020, www.ncbi.nlm.nih.gov/nuccore/MT520472. 
     
     PubMed, 30 Apr. 2022, www.ncbi.nlm.nih.gov/gene/43740568?report=full_report. 
