# RASAP 

Resource of AF2 predicted structures of autophagy pathway

Welcome to our GitHub repository! Here, we present a resource package that utilizes AlphaFold2, a state-of-the-art deep learning model, for improving the structural spectrum of autophagy proteins. The protein structural bandwidth of multiple proteomes has been greatly improved with the release of Google DeepMind’s AI-driven AlphaFold which can be utilized as an open-source tool .This  has significantly improved structural coverage of the proteins, which earlier lacked atomistic resolution with reasonable confidence, over previous protein prediction methods. Using the tool, we have analysed the autophagic interactome, which is comprised of key autophagic proteins and several interacting partners.

With AF2 It is now possible to explore and predict the structures of numerous monomeric and multimeric protein complexes that were previously inaccessible. 
This user-friendly framework called Resource of AF2 predicted structures of autophagy pathway contains structural information on the proteins that are involved in the autophagic process. Moreover, the resource contains predicted protein structures that can be downloaded and utilized for further analysis and study, facilitating understanding of autophagic processes. With the help of our resource, researchers can comprehensively analyse the protein structures, and potentially use them for drug development and other research inferences. We are excited to share this resource with the scientific community and hope that it can contribute to further advances in the structural understanding of proteins involved in the autophagy process.


#ATG7-LC3B tetramer predicted by AF2
![ATG7-LC3B-complex (1) (2)](https://user-images.githubusercontent.com/65184350/229588562-612097a4-4f28-4a72-ada4-ed137cdc5b77.jpg)

#Contents

1.AF2_models contains 5 AF2 predicted models of autophagic proteins/complexes, computed using standalone application of AF2. Core proteins with experimental structural coverage less than 90% in humans were taken for prediction. These include: ATG2A, ATG14, ATG10, FIP200, AMBRA1, ULK4. In addition, AF2 predicted ATG7 and ATG7-ATG10 tetramer complex models are also provided.

2.Table.xls contains list of 416 mammalian autophagic proteins, their dissection into core proteins, further categorization into the functional subgroup viz., ULK complex, PI3K complex, ATG9 complex and UBL conjugation system. Quantitative information of the experimental structural coverage of each of the proteins is enlisted along with AF2 predicted pLDDT scores for residues with no experimental structural coverage. In addition, IDRs predicted with IUPRED2 is compared with AF2 predicted pLDDT scores.

3.Pdb-Files -This folder contains all the structural files containing three dimensional organisation of the proteins  involved in  mammalian autophagy interactome listed  in Table.xls
 
#Usage

1.You can easily download the .pdb files and can view using any interactive and visulaization tools like chimera, chimeraX etc.



#Acknowledgments

This project was made possible through the use of AlphaFold, developed by DeepMind. We thank the AlphaFold team for their work and contributions to the field of protein structure prediction. We also acknowledge the support from CSIR-IGIB for infrastructure and supercomputing facilities.  

