  For my final project, I analyzed ATAC-seq of 24 seq files from Drosopholia. I was able to find the opening regions from 
peak calling MACS2 functions. The peaks were merged. Each bam file was called into the peak regions seperately and cat all
together to generate a matrix with peak regions as rows and sample names as columns. Also RPKM was done to normalize the 
data. I used EdgeR to treat half of data as Eye Dics and the other half as Wing Dics and was able to find opening regions
that are associated with genes that are important for eye or wing development. For example, Antp is associated with Wing 
development while eya is associated with Eye development. Gene ontology was also done to get a bigger of each gene list that
was specific to either eye dics and wing dics samples. There are other ways to analyze data as I could analyze the differences
among the phenotypes. Overall, in terms of eye and wing dics, there are clear opening regions that are specific to one another.

![Volcano plot]
(https://github.com/Paladin258/Final_Project_Advanced_Bioinformatic/blob/Final_Project_Version1/Volcano%20plot.png)

![Peak Annotation pie chart](https://github.com/Paladin258/Final_Project_Advanced_Bioinformatic/blob/Final_Project_Version1/Peak%20Annotation.png)

![Antp Genome Track]
(https://github.com/Paladin258/Final_Project_Advanced_Bioinformatic/blob/Final_Project_Version1/Genome_Track_Antp.png)

![eya Genome Track]
(https://github.com/Paladin258/Final_Project_Advanced_Bioinformatic/blob/Final_Project_Version1/Genome_Track_eya.png)

![gene ontology]
(https://github.com/Paladin258/Final_Project_Advanced_Bioinformatic/blob/Final_Project_Version1/Gene_Ontology.png)
