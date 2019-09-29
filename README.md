## TEAM NULLFUNTION 
![Nullfunctionlogo](https://github.com/moonchangin/nullfuction/blob/master/Image%20from%20iOS.jpg)
Open NFhackathon *2019 Nullfunciton Presentation_finalized_CIM.pptx* to see our presentation @ CTF and workflow.
If you have questions about our work, look on the bottom right corner to see contributors for the work and send an email.

Saikrithika Gandhi (Drug discovery) Researcher, saikrithi@gmail.com

Xiucheng Quek (PPI network) DNAnexus, xquek@dnanexus.com

Xiaowei Zhu (Burden test, PPI network), Stanford University, xwzhu@stanford.edu

Chang In Moon (RNA analysis, presenter), Washington University in St. Louis, moonchangin@wustl.edu 

Xiangying Sun (RNA analysis), Thermo Fisher

Tiange Alex Cui (RNA analysis, Team logo), Cofactor Genomics, alextreecn@gmail.com

Lu Yang (Drug discovery), Stanford University, luy@stanford.edu

## Presented Work @ CTF NF Conference 2019
![CTF_NF_CONF](https://github.com/moonchangin/nullfuction/blob/master/CTF_LOGO.png)

## Abstract *: Summarize everything in a few sentences.*
![IntroImage](https://github.com/moonchangin/nullfuction/blob/master/introduction.PNG)
Neurofibromatosis types I (NF1) an autosomal dominant genetic disorder due to mutation in NF1 gene. The clinical manifestations are diverse, and 8-13% of patients develop malignant peripheral neural sheath tumor (MPNST). However, the genetic basis for phenotypic diversity is poorly understood. In our study, we used an integrative analysis on single nucleotide variations (SNVs) and gene expression dysregulation, to characterize the genetic landscape of additional disruptions in plexiform neurofibroma (PN) and MPNST.
## Introduction *: What's the problem? Why should we solve it?*
#### Neurofibromatosis type 1
Neurofibromatosis type 1 (NF1) is one of the most common inherited tumor predisposition syndromes, affecting 1:2500-3000 individuals worldwide.[1, 2] As such, affected individuals begin life with one inactivated (germline mutation) copy and one functional copy of the NF1 gene in every cell in their body.[3, 4] The presence of this germline mutation increases the risk of tumor formation, which requires only somatic loss of the remaining functional NF1 gene[5].  

#### Malignant peripheral nerve sheath tumors (MPNSTs). 
MPNSTs are clinically-aggressive sarcomas,[6] arising in individuals with NF1 at an estimated frequency of 8-13%[7]. Composed of neoplastic Schwann cells, these cancers recur in ~50% of individuals, and most people die within five years of diagnosis, despite surgical resection, radiation and chemotherapy.[8-10] 

#### Plexiform neurofibromas (PN).
Plexiform neurofibromas are strongly related to NF1, affecting 20% to 40% of patients suffering from this condition.[1, 11] These tumors often occur in the head, skull base, or neck but also manifest themselves on the trunk and limbs. Plexiform neurofibromas have the potential to transform into MPNST. However, not all MPNST develop from pre-existing neurofibromas, as approximately half of all MPNST arise sporadically without a known precursor.[12]

#### Molecular pathogenesis of NF1-MPNSTs. 
NF1 gene inactivation and loss of NF1 protein (neurofibromin) expression characterize the majority of NF1-MPNSTs.[13] While NF1 loss is necessary for MPNST development, it is not sufficient for malignant transformation. This conclusion is supported by numerous genetically-engineered mouse studies, demonstrating that conditional Nf1 gene inactivation in Schwann cell precursors results in benign plexiform neurofibroma formation only,[14-16] whereas murine MPNST formation requires the co-existence of additional genetic mutations. In both mouse and human MPNSTs, alterations in the TP53, CDKN2A, and EGFR genes have been reported as cooperating secondary genetic alterations that facilitate MPNST development.[17-20] Efforts to identify the full spectrum of cooperating genetic changes important for MPNST pathogenesis have employed many different discovery techniques [21-25]; however, few of the identified genes were shared across studies, and none were accurate predictors of disease pathogenesis or effective in clinical trials.


## Methods *: How did we go about solving it?*
1)    SNV analysis
We first characterized the burden of deleterious single SNVs in 14 plexiform neurofibroma samples and 10 MPNST samples. The SNVs were selected for 1) population allele frequency < 0.5%, 2) SIFT score < 0.05 and 3) shared among <5 samples. We then defined the burden of a gene as the percentage of subjects that carried at least one the deleterious mutation.
2)    Gene expression analysis
We compared the gene expression profile between 6 plexiform neurofibromas and 6 MPNST tumor tissue. We characterized genes with differential expression and defined the functional pathways with significant enrichment.
3)    Integrative analysis
We overlaid protein-protein interaction networks to connect genes with extreme burdens of genetic mutations and genes with abnormal expression levels.

## Results *: What did we observe? Figures are great!*
![distance-based](https://github.com/moonchangin/nullfuction/blob/master/alex-fig.png)

Due to limited time, we decided to use a novel distance-based method to have a quick sense of the data. All RNASeq gene expression profiles were converted into Pearson distance and visualized in a 2-D plain. In this way, we can quickly get an overall impression of the data and see if there are some obvious outliers need to be removed.

![Heatmap](https://github.com/moonchangin/nullfuction/blob/master/Heat%20map%20(1).png)

Differential gene expression analysis from plexiform neurofibromas and MPNST patients. We did a hierarchical clustering based on gene counts. The heatmap shows a group of genes that highly expressed for a group of MPNST.

![PN_network](https://github.com/moonchangin/nullfuction/blob/master/PN_network.png)

We identified additional candidate “driver” genes, such as ATM in plexiform neurofibroma and EP300 in MPNST, and our results suggest that cilium function is associated with the progress of neurofibroma. These results were confirmed in an independent dataset through personal communications.

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

## NF Hacakthon 2019
![NF_HACK_IMAGE](https://github.com/moonchangin/nullfuction/blob/master/EEX0kSrXkAER0rX.jpg)
https://sv.ai/neurofibromatosis

## Reference
1.	Huson, S.M., P.S. Harper, and D.A. Compston, Von Recklinghausen neurofibromatosis. A clinical and population study in south-east Wales. Brain, 1988. 111 ( Pt 6): p. 1355-81.
2.	Lammert, M., et al., Prevalence of neurofibromatosis 1 in German children at elementary school enrollment. Arch Dermatol, 2005. 141(1): p. 71-4.
3.	Gutmann, D.H., et al., Neurofibromatosis type 1: modeling CNS dysfunction. J Neurosci, 2012. 32(41): p. 14087-93.
4.	Ferner, R.E., et al., Guidelines for the diagnosis and management of individuals with neurofibromatosis 1. J Med Genet, 2007. 44(2): p. 81-8.
5.	Arun, D. and D.H. Gutmann, Recent advances in neurofibromatosis type 1. Curr Opin Neurol, 2004. 17(2): p. 101-5.
6.	Ferner, R.E. and D.H. Gutmann, International consensus statement on malignant peripheral nerve sheath tumors in neurofibromatosis. Cancer Res, 2002. 62(5): p. 1573-7.
7.	Evans, D.G., et al., Malignant peripheral nerve sheath tumours in neurofibromatosis 1. J Med Genet, 2002. 39(5): p. 311-4.
8.	Hruban, R.H., et al., Malignant peripheral nerve sheath tumors of the buttock and lower extremity. A study of 43 cases. Cancer, 1990. 66(6): p. 1253-65.
9.	Kourea, H.P., et al., Subdiaphragmatic and intrathoracic paraspinal malignant peripheral nerve sheath tumors: a clinicopathologic study of 25 patients and 26 tumors. Cancer, 1998. 82(11): p. 2191-203.
10.	Wong, W.W., et al., Malignant peripheral nerve sheath tumor: analysis of treatment outcome. Int J Radiat Oncol Biol Phys, 1998. 42(2): p. 351-60.
11.	Tonsgard, J.H., et al., CT imaging in adults with neurofibromatosis-1: frequent asymptomatic plexiform lesions. Neurology, 1998. 50(6): p. 1755-60.
12.	Subramanian, S., et al., Genome-wide transcriptome analyses reveal p53 inactivation mediated loss of miR-34a expression in malignant peripheral nerve sheath tumours. J Pathol, 2010. 220(1): p. 58-70.
13.	Reuss, D.E., et al., Neurofibromin specific antibody differentiates malignant peripheral nerve sheath tumors (MPNST) from other spindle cell neoplasms. Acta Neuropathol, 2014. 127(4): p. 565-72.
14.	Yang, F.C., et al., Nf1-dependent tumors require a microenvironment containing Nf1+/-- and c-kit-dependent bone marrow. Cell, 2008. 135(3): p. 437-48.
15.	Zheng, H., et al., Induction of abnormal proliferation by nonmyelinating schwann cells triggers neurofibroma formation. Cancer Cell, 2008. 13(2): p. 117-28.
16.	Zhu, Y., et al., Neurofibromas in NF1: Schwann cell origin and role of tumor environment. Science, 2002. 296(5569): p. 920-2.
17.	Cichowski, K., et al., Mouse models of tumor development in neurofibromatosis type 1. Science, 1999. 286(5447): p. 2172-6.
18.	Legius, E., et al., TP53 mutations are frequent in malignant NF1 tumors. Genes Chromosomes Cancer, 1994. 10(4): p. 250-5.
19.	Perry, A., et al., Differential NF1, p16, and EGFR patterns by interphase cytogenetics (FISH) in malignant peripheral nerve sheath tumor (MPNST) and morphologically similar spindle cell neoplasms. J Neuropathol Exp Neurol, 2002. 61(8): p. 702-9.
20.	Wu, J., et al., EGFR-STAT3 signaling promotes formation of malignant peripheral nerve sheath tumors. Oncogene, 2014. 33(2): p. 173-80.
21.	Miller, S.J., et al., Large-scale molecular comparison of human schwann cells to malignant peripheral nerve sheath tumor cell lines and tissues. Cancer Res, 2006. 66(5): p. 2584-91.
22.	Watson, M.A., et al., Gene expression profiling reveals unique molecular subtypes of Neurofibromatosis Type I-associated and sporadic malignant peripheral nerve sheath tumors. Brain Pathol, 2004. 14(3): p. 297-303.
23.	Yu, J., et al., Array-based comparative genomic hybridization identifies CDK4 and FOXM1 alterations as independent predictors of survival in malignant peripheral nerve sheath tumor. Clin Cancer Res, 2011. 17(7): p. 1924-34.
24.	Holtkamp, N., et al., Differentially expressed genes in neurofibromatosis 1-associated neurofibromas and malignant peripheral nerve sheath tumors. Acta Neuropathol, 2004. 107(2): p. 159-68.
25.	Fang, Y., et al., Molecular characterization of permanent cell lines from primary, metastatic and recurrent malignant peripheral nerve sheath tumors (MPNST) with underlying neurofibromatosis-1. Anticancer Res, 2009. 29(4): p. 1255-62.


## Reproduction: *How to reproduce the findings!*

### Docker

*The Docker image contains <R/jupyter> notebooks of all analyses and the dependencies to run them. *Be sure to note if you need any special credentials to access data for these analyses, **don't package restricted data** in your containers!*

Instructions for running the following notebooks: *be sure to adjust these instructions as necessary! check out https://github.com/Sage-Bionetworks/nf-hackathon-2019 for example containers and instructions*

1. `docker pull <your dockerhub repo>/<this container>` command to pull the image from the DockerHub
2. `docker run <your dockerhub repo>/<this container>` Run the docker image from the master shell script

### Important Resources *: primary data, github repository, Synapse project, dockerfile link etc.*


