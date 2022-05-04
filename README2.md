# GEN 711 Final Project: COVID-19 Spike Protein Mutation

## BACKGROUND [Julia]

At the end of 2019, this virus first infected the Chinese population and through sequencing of isolates it was determind to be a novel coronavirus dubbed SARS-CoV-2 and subsequently the disease it caused was caled COVID-19. This is the seventh coronavirus known to infect humans.
This project was inspired by a research report published in March 2021, which discusses in depth the sequencing methods that could be employed to better understand the infection mechanism of SARS-CoV-2 with ACE2 receptor binding in different organ tissues, and how this information can be related to treatment methodologies in the future for affected patients of differing origins of infection. 
Next-generation sequencing techniques of the metagenome and single-cell sequencing was applied to locate SARS-CoV-2 cellular hosts, to prevent interspecies transmission of this disease as well as other related public health scares to come. There is also indepth phylogenic analysis of COVID-19 that has lead to the identification and tracing of strains.
Our project compares ten different COVID-19 geneome sequences of the oronasopharynx isolation, five from each time span of April 2020 and 5 from April 2022, in the United States patients, using fasta files to generate a Phylogenetic tree to visualize ancestral alterations and run an alignment for nucleotide sequence similarity. These sequences were aligned and imported to DNAsp to identify the spike protien region to furhter reveal nucleotide differences.

![image](https://github.com/teehector10/gen711_final_project/blob/main/CovidDomainsSmaller.png)
### Figure 1 
The structure of the 29.3kb COVID-19 genome, highlighting the domains of the spike-protein

## Methods
10 complete sequences of SARS-CoV-2 from 2 different time periods (April 2020 & April 2022) were aquired from NCBI, with specifications of being isolated from oronasopharynx and of those located in MA, USA.
Useing NCBI, a phylogentic tree was constructed, Figure 2, and an alignment was done, Figure 3. The alignment tool was limited to a certain number of nucleotides and unfortunatly we could not perform an analysis on a much larger sample. This alignment was imported to DNAsp, where the sequene was cut down to the 1274bp spike protein.

![image](https://github.com/teehector10/gen711_final_project/blob/main/spikeProtein2022.png)
### Figure 2
Spike protein Domains

## Findings [Izzy]
When conducting our phylogenic tree, we were able to visualize the ancestral background of differing COVID-19 isolations. We were not able to add the Wohan strain to this tree because of constraints with the NCBI website feature. It would also have been nice to do more then 10 samples, but the alignment limited us and we chose to just do the 10 samples that were analyzed later on.

As seen below, there is an obvious different phylogony to 2020 samples and 2022 samples. With possibility of there being 3 strains, 2022 having 2 forking from eachother.
![image](https://user-images.githubusercontent.com/103778546/166160815-f95a3ff4-ac0d-4ae6-b81e-3d841cc8141d.png)
### Figure 3

When aligning the sequences in NCBI, we were able to look at how the COVID-19 genome differend in nucleotides sequences. The red color above shows areas of differences. There is obvious differences in the 2020 and 2022 samples, with an outlier sample in 2022. There are alot more mutations in comparion in the 2022 samples.

### Figure 3 [Brenna]
<img width="1404" alt="Screen Shot 2022-04-29 at 4 22 42 PM" src="https://user-images.githubusercontent.com/103778546/166161725-1fa7f79c-138d-4303-9518-dd243ed94291.png">

Using a program called SnapGene we were able to align our sequences and compare them to the original sequence from Wuhan and looked for changes. Our goal with using this program was to just look for differences but we decided to go further and try and look at where the most mutations occured. The spike protein is a known area of mutation between strains and is located at 21,500bp and 25,300bp (PubMed). So by analyzing this alignment we are able to see that there are mutations where this spike protein is located that are oresent in the 2022 sequences and not the 2020, showing us how COVID has mutated over time. 

<img width="802" alt="Screen Shot 2022-05-04 at 11 29 43 AM" src="https://user-images.githubusercontent.com/103778546/166808493-7fa9e8e3-b2e8-4fb8-96e9-43a1ed748742.png">


## Sources 

     Xiaomin,C., Kang,Y., Luo,J., Pang,K., Xu,X., Wu,J., Li,X. and Jin,S. “Next-Generation Sequencing Reveals the Progression of COVID-19.” Frontiers in Cellular and Infection Microbiology, vol. 11, no. 2235-2988, 2021, https://doi.org/10.3389/fcimb.2021.632490. 
     
     PubMed, "S surface glycoprotein [ Severe acute respiratory syndrome coronavirus 2 ]"30 Apr. 2022, www.ncbi.nlm.nih.gov/gene/43740568?report=full_report. 

     Huang, Y., Yang, C., Xu, Xf. et al. Structural and functional properties of SARS-CoV-2 spike protein: potential antivirus drug development for COVID-19. Acta Pharmacol Sin 41, 1141–1149 (2020). https://doi.org/10.1038/s41401-020-0485-4

     Tahir S Pillay. Department of Chemical Pathology, Faculty of Health Sciences, University of Pretoria & National Health Laboratory Service, Pretoria, South Africa Division of Chemical Pathology, University of Cape Town, Cape Town, South Africa. https://jcp.bmj.com/content/73/7/366



## Isolation sources
     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T.,Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D. “Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-3KU8AQYTU/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345302. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B.,Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-B4PJHW57C/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345293. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-BAW3HNWUN/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345291. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B., Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKEF52PWY/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345296. 

     Howard,D., Batra,D., Cook,P.W., Caravas,J., Rambo-Martin,B. Sammons,S., Unoarumhi,Y., Schmerer,M., Lacek,K.A., Kendall,T., Caban Figueroa,V., Ca,H., Morrison,S., Gulvick,C., Sula,E., Paden,C.R. and MacCannell,D.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA-CDC-STM-CKPQ8WHER/2022, Complete Genome.” NCBI Nucleotide, 26 Apr. 2022, www.ncbi.nlm.nih.gov/nuccore/ON345288. 

     Lemieux,J.E., Siddle,K.J., Shaw,B., Adams,G., Pierce,V., Turbett,S., Anahtar,M., Branda,J., Slater,D., Harris,J., Lin,A.E.,Gladden-Young,A., Lagerborg,K., Rudy,M., DeRuff,K., Carter,A.,  Normandin,E., Bauer,M., Reilly,S., Tomkins-Tinch,C., Loreth,C.,Chaluvadi,S., Neumann,A., Cusick,C., Chapman,S.B., Gnirke,A.,Flowers,K., Cerrato,F., Birren,B.W., Gallagher,G., Smole,S., Park,D.J., MacInnis,B.L., Ryan,E., LaRocque,R., Rosenberg,E. and Sabeti,P.C.“Severe Acute Respiratory Syndrome Coronavirus 2 Isolate SARS-CoV-2/Human/USA/MA_MGH_00424/2020, Complete Genome.” NCBI Nucleotide, 4 June 2020, www.ncbi.nlm.nih.gov/nuccore/MT520472. 
