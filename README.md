# Quantitative-analysis-of-visual-codewords-of-a-protein-distance-matrix

Abstract

3D protein structures can be analyzed using a distance matrix calculated as the pairwise distance between all Cα atoms in the protein model. Although researchers have efficiently used distance matrices to classify proteins and find homologous proteins, much less work has been done on quantitative analysis of distance matrix features. Therefore, the distance matrix was analyzed as gray scale image using KAZE feature extractor algorithm with Bag of Visual Words model. In this study, each protein was represented as a histogram of visual codewords. The analysis showed that a very small number of codewords (~1%) have a high relative frequency (> 0.25) and that the majority of codewords have a relative frequency around 0.05. We have also shown that there is a relationship between the frequency of codewords and the position of the features in a distance matrix. The codewords that are more frequent are located closer to the main diagonal. Less frequent codewords, on the other hand, are located in the corners of the distance matrix, far from the main diagonal. Moreover, the analysis showed a correlation between the number of unique codewords and the 3D repeats in the protein structure. The solenoid and tandem repeats proteins have a significantly lower number of unique codewords than the globular proteins. Finally, the codeword histograms and Support Vector Machine (SVM) classifier were used to classify solenoid and globular proteins. The result showed that the SVM classifier fed with codeword histograms correctly classified 352 out of 354 proteins.



The supplemental data includes all 7308 distance matrix images (grayscale, PNG format) and a Matlab script that calculates the bag of features, histograms (feature vector), and classification accuracy. 

We also provided a dataset of globular and solenoid proteins (247+105 images, grayscale, PNG format) and a Matlab script (SVM_2fold.m) to classify proteins using SVM. In summary, the supplementary material contains all the inputs needed to run Matlab scripts.

Citation: Pražnikar J, Attygalle NT (2022) Quantitative analysis of visual codewords of a protein distance matrix. PLoS ONE 17(2): e0263566. https://doi.org/10.1371/journal.pone.0263566


The data set is available at:
https://zenodo.org/record/5906637

