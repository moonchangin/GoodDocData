## TEAM NULLFUNTION 
![Nullfunctionlogo](https://github.com/moonchangin/nullfuction/blob/master/Image%20from%20iOS.jpg)

## Website *(if applicable)*

## Abstract *: Summarize everything in a few sentences.* 
Neurofibromatosis types I (NF1) an autosomal dominant genetic disorder due to mutation in NF1 gene. The clinical manifestations are diverse, and 5-13% patients develop highly malignant tumor (malignant peripheral neural sheath tumor, MPNST). However, the genetic basis for the phenotypic diversity is poorly understood. In our study, we used an integrative analysis on single nucleotide variations (SNVs) and gene expression dysregulation, to characterize the genetic landscape of additional disruptions in plexiform neurofibroma and MPNST. In particular, we aimed to understand the mechanisms that lead to the progress from plexiform neurofibroma towards MPNST.
## Introduction *: What's the problem? Why should we solve it?*
One of the most common cancers affecting adults with neurofibromatosis type 1 (NF1) is the malignant peripheral nerve sheath tumor (MPNST), a highly aggressive tumor. Sadly, for those individuals with NF1 who develop these cancers, there are limited treatment options, and the vast majority of people with these malignancies will die within 5 years of diagnosis. Over the past decade, research has revealed that NF1-MPNSTs represent a group of diverse cancer types, characterized by different genetic changes. 
## Methods *: How did we go about solving it?*
1)    SNV analysis
We first characterized the burden of deleterious single SNVs in 14 plexiform neurofibroma samples and 10 MPNST samples. The SNVs were selected for 1) population allele frequency < 0.5%, 2) SIFT score < 0.05 and 3) shared among <5 samples. We then defined the burden of a gene as the percentage of subjects that carried at least one the deleterious mutation.
2)    Gene expression analysis
We compared the gene expression profile between 6 plexiform neurofibroma and 6 MPNST tumor tissue. We characterized genes with differential expression and defined the functional pathways with significant enrichment.
3)    Integrative analysis
We overlaid protein-protein interaction networks to connect genes with extreme burdens of genetic mutations and genes with abnormal expression levels.
## Results *: What did we observe? Figures are great!*
![distance-based](https://github.com/moonchangin/nullfuction/blob/master/alex-fig.png)
Due to limited time, we decided to use a novel distance-based method to have a quick sense of the data. All RNASeq gene expression profiles were converted into Pearson distance and visualized in a 2-D plain. In this way, we can quickly get an overall impression of the data and see if there are some obvious outliers need to be removed.
![Heatmap](https://github.com/moonchangin/nullfuction/blob/master/Heat%20map%20(1).png)
Differential gene expression analysis from plexiform neurofibromas and MPNST patients. We did a hierarchical clustering based on gene counts. The heatmap shows a group of genes that highly expressed for a group of MPNST.
![PN_network](https://github.com/moonchangin/nullfuction/blob/master/PN_network.png)
We identified additional candidate “driver” genes, such as ATM in plexiform neurofibroma and EP300 in MPNST, and our results suggest that cilium function is associate with the progress of neurofibroma. These results were confirmed in an independent dataset through personal communications.

## Conclusion/Discussion: 
The phenotypic diversity within NF1 is likely due to additional mutations. With the integration of multidiscipline analysis from DNA sequencing, RNA sequencing, as well as the previous knowledge about the gene interactions, we can identify new target genes for further drug discoveries.
### Please make sure you address ALL of the following:

#### *1. What additional data would you like to have*
A larger cohort of data with well controlled experimental conditions.

#### *2. What are the next rational steps?* 
A meta analysis with other tumor types, and testing drugs for the new candidate genes

#### *3. What additional tools or pipelines will be needed for those steps?*
A new pipeline that can integrates data of various resource and a tool that can help to reduce batch artifacts.

#### *4. What skills would additional collaborators ideally have?*
A collaborative effort from specialists in genomics, clinicians, and biostatisticians.

## Reproduction: *How to reproduce the findings!*

### Docker

*The Docker image contains <R/jupyter> notebooks of all analyses and the dependencies to run them. *Be sure to note if you need any special credentials to access data for these analyses, **don't package restricted data** in your containers!*

Instructions for running the following notebooks: *be sure to adjust these instructions as necessary! check out https://github.com/Sage-Bionetworks/nf-hackathon-2019 for example containers and instructions*

1. `docker pull <your dockerhub repo>/<this container>` command to pull the image from the DockerHub
2. `docker run <your dockerhub repo>/<this container>` Run the docker image from the master shell script

### Important Resources *: primary data, github repository, Synapse project, dockerfile link etc.*


