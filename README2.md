# GEN 711 Final Project: COVID-19 Spike Protein Mutation

## BACKGROUND 

Our final project focuses on the COVID-19 pandemic. A disease which first infected the Chinese population, COVID-19 was determined to be a novel coronavirus of SARS-CoV-2 through sequencing of isolates, and the seventh known to infect humans (Huang et al. 2020). As COVID-19 is caused by the highly transmissbale SARS-CoV-2, this project specifcially looks at the human-transmission isolation source of the oronasopharynx, meaning the mouth, nose, and pharynx region of the body. This study was inspired by a research report published in March 2021, which discusses in depth the sequencing methods that were employed to better understand the infection mechanism of SARS-CoV-2 via ACE2 receptor binding in different organ tissues, as well as how this information can be related to treatment methodologies in the future for affected patients of differing origins of infection. The paper compares ACE2 receptor expression levels in susceptible human tissues and organs at a variety of locations across the body, thus correlating to the origin of infection site in each patient. Next-generation sequencing techniques of the metagenome and single-cell sequencing were applied to locate SARS-CoV-2 cellular hosts, in order to prevent interspecies transmission of this disease as well as other related public health scares to come (Xiaomin et al. 2021). Additionally, a second research report used for reference titled "Structural and functional properties of SARS-CoV-2 spike protein: potential antivirus drug development for COVID-19" depicts an in-depth analysis of COVID-19 ancestral relations of mutation history that have lead to the identification and tracing of strains. Our project compares ten different COVID-19 geneome sequences of the oronasopharynx isolation, five from each time span of April 2020 or April 2022, located in Massachussetts, U.S. The data came from fasta files used to generate a Phylogenetic tree to visualize ancestral alterations as well as to run an alignment for nucleotide sequence similarity. These aligned sequences were then imported into DNAsp to identify important spike protein regions and further reveal diferences in nucleotides. All of these techniques can be utilized to deeper examine the genome alterations behind the deadly COVID-19 disease.   

### Figure 1 

![image](https://github.com/teehector10/gen711_final_project/blob/main/CovidDomainsSmaller.png)

This image shows the the structure of the 29.3 kb COVID-19 genome, highlighting the domains of individual spike proteins (Huang et al. 2020). 

### Figure 2 

![image](https://user-images.githubusercontent.com/103778390/166063050-5dc2afef-0e22-4914-932f-a1e870fcead1.png)

This image from the previously cited paper titled "Next-Generation Sequencing Revals the Progression of COVID-19" shows ACE2 expression levels in the human body as percentages per organ location (Xiaomin, et al. 2021). To apply to our project, the thyroid level of expression can correlate to the oronasopharynx isolation region.

## Methods
For our project, fasta files containing ten complete SARS-CoV-2 genome sequences, isolated from the oronasopharynx region of COVID-19 patients in Massachusettss across April 2020 and April 2022, were aquired from NCBI. NCBI, National Center for Biotechnology Information, is a public database within the United States National Library of Medicine that is officially approved of and funded by the United States government. Using this database, a phylogentic tree was constructed, Figure 4, and a alignment was performed, Figure 5. This nucleotide alignment was then downloaded and imported to SnapGene, another database, where the sequence was cut down to the 3822 bp, to represent the specified spike protein of interest, which is demonstarted in the domain image below. 

### Figure 3  

![image](https://github.com/teehector10/gen711_final_project/blob/main/spikeProtein2022.png)

This image is from a Gene of the Month article on SARS-CoV-2 within the larger Journal of Clinical Pathology, showing spike protein domains of COVID-19 (Pillay, 2020).

## Findings
When conducting our phylogenic tree, we were able to visualize the ancestral background of differing COVID-19 isolations. We were not able to add the original Wuhan strain to this tree because of constraints with the NCBI website feature. We also limited the tree to ten samples in order to create a clearer picture for the relation between a variety of isolations, rather than complicate the concept attempted to being demonstrated with a vast range of samples, those that were already exemplified in Figure 1. As seen below, there is an obvious different phylogony to 2020 samples and 2022 samples. With the possibility of there being 3 strains, 2022 has forking away from eachother as opposed to those of the 2020 origin. 

### Figure 4  

![image](https://user-images.githubusercontent.com/103778546/166160815-f95a3ff4-ac0d-4ae6-b81e-3d841cc8141d.png)

This image above shows the phylogenic tree of our sequences from the National Center for Biotechnology Information (NCBI). 

When aligning the sequences in NCBI, we were able to look at how the COVID-19 genome differend in nucleotides sequences. The red color above shows areas of differences. There is obvious differences in the 2020 and 2022 samples, with an outlier sample in 2022. There are alot more mutations in comparion in the 2022 samples.

### Figure 5 

<img width="1404" alt="Screen Shot 2022-04-29 at 4 22 42 PM" src="https://user-images.githubusercontent.com/103778546/166161725-1fa7f79c-138d-4303-9518-dd243ed94291.png">

Using a program called SnapGene we were able to align our sequences and compare them to the original sequence from Wuhan and looked for changes. Our goal with using this program was to just look for differences but we decided to go further and try and look at where the most mutations occured. The spike protein is a known area of mutation between strains and is located at 21,500bp and 25,300bp (PubMed). So by analyzing this alignment we are able to see that there are mutations where this spike protein is located that are oresent in the 2022 sequences and not the 2020, showing us how COVID has mutated over time. 

### Figure 6

<img width="802" alt="Screen Shot 2022-05-04 at 11 29 43 AM" src="https://user-images.githubusercontent.com/103778546/166808493-7fa9e8e3-b2e8-4fb8-96e9-43a1ed748742.png">
This image from snap gene shows the spike protein domain of our sequences in alignment with the Wuhan sequence. 

By using SnapGene we were able to map out the domains of the spike protein based off of Figure 2. Figure 2 was an amino acid sequence so we had to convert to nucleotide sequence. We were able to do this by multiplying the amino acid position by 3. But what is really interesting about this figure (Figure 6) is that in the Receptor-Binding Domain for the 2022 sequences (ON345288.1 - ON345302.1) there were a lot of mutations that did not exist in 2020. We believe that this may be due to ACE2 receptor that binds to a spike on the virus. 


## Research Sources 
     Huang, Y., Yang, C., Xu, Xf. et al. Structural and functional properties of SARS-CoV-2 spike protein: potential antivirus drug development for COVID-19. Acta Pharmacol Sin, vol. 41, no. 1141–1149, 2020, https://doi.org/10.1038/s41401-020-0485-4. 
     
     Pillay, T.S. "Gene of the month: the 2019-nCoV/SARS-CoV-2 novel coronavirus spike protein." Journal of Clinical Pathology, vol. 73, no. 366-369, 2020, https://jcp.bmj.com/content/73/7/366. 
     
     PubMed, "S surface glycoprotein [Severe acute respiratory syndrome coronavirus 2]." 30 Apr. 2022, www.ncbi.nlm.nih.gov/gene/43740568?report=full_report. 
     
     Xiaomin,C., Kang,Y., Luo,J., Pang,K., Xu,X., Wu,J., Li,X. and Jin,S. “Next-Generation Sequencing Reveals the Progression of COVID-19.” Frontiers in Cellular and Infection Microbiology, vol. 11, no. 2235-2988, 2021, https://doi.org/10.3389/fcimb.2021.632490. 

## Isolation sources
     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T.,Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D. “Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-3KU8AQYTU/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345302. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B.,Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-B4PJHW57C/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345293. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-BAW3HNWUN/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345291. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKEF52PWY/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345296. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B. Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKPQ8WHER/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345288. 

     Lemieux,J.E., Siddle,K.J., Shaw,B., Adams,G., Pierce,V., Turbett,S., Anahtar,M., Branda,J., Slater,D., Harris,J., Lin,A.E.,Gladden-Young,A., Lagerborg,K., Rudy,M., DeRuff,K., Carter,A.,  Normandin,E., Bauer,M., Reilly,S., Tomkins-Tinch,C., Loreth,C.,Chaluvadi,S., Neumann,A., Cusick,C., Chapman,S.B., Gnirke,A.,Flowers,K., Cerrato,F., Birren,B.W., Gallagher,G., Smole,S., Park,D.J., MacInnis,B.L., Ryan,E., LaRocque,R., Rosenberg,E. and Sabeti,P.C.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA_MGH_00424/2020, Complete Genome.” NCBI Nucleotide, 4 June 2020, www.ncbi.nlm.nih.gov/nuccore/MT520472. 
