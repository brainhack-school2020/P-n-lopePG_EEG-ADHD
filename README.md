
## PenelopePG_EEG-ADHD
This project is realized as part of the Brainhack School 2020 and in collaboration with Béatrice De Koninck

Summary:
ADHD is a neurodevelopmental disorder which manifests itself through a variety of cognitive and 
behavioral symptoms. It is well known in the ADHD litterature that there are many subtypes of this
disorder, but not all research papers agree on what these subtypes are. Those subtypes are also
mostly based on behavioral and self-report data and not on neurophysiological assessmentl; a need for clear
biomarkers is needed for clarification of the identification of ADHD in adults (Hegerl et al. 2016; Olbrich,
Dinteren & Arns, 2015).

Using EEG data from young adults with ADHD, we will investigate the presence of subtypes and
the possible associations between the reported and behavioral symptoms and the different 
amplitude and distribution of the brainwaves.


Details
Our sample consists of 92 college students with ADHD. EEG was performed using a 19 channel 
electrodes cap using the international 10-20 system while participants were resting with their eyes opened
for 5 minutes. Time-frequency analysis were performed in order to extract the mean amplitude of each frequency for each electrode.
Neuropsychological measures include
- Conners questionnaire (self-report)
- WAIS-IV working memory subscale (data has not been accessed yet, but should be in the next few days)
- IVA-II behavioral test

Analyses
Our sample contains many types of data, which are very heterogenous and vary in scale (self-report, 
behavioral and EEG).
The simplest method in order ton investigate the role of each component would be to use normalized data.
However, this would lead to a loss of pertinent information. Clustering is an interesting alternative,
which will be assessed and compared to the new Network Similarity Fusion method.

The SNF method uses networks of samples as a basis for integration, combines data from a participant
sample, and creates a participant network. Is is realized in two steps:
	1. Construction of a sample-similarity network for each data type
	2. Integration of these networks into a single similarity network using a nonlinear combination
	   method
It offers insight on how informative each data type is to the observed similarity between samples,
is robust to noise and data heterogeneity. The purpose of our use of SNF is to identify subtypes
among our sample by clustering and predict labels for new samples based on the constructed network.	
  
This method will be executed in parallel with another more well know method; clustering and classification.


Tools
Network Similarity Fusion
Clustering
Classification algorithm (to be determined)
Jupyter Notebook
GitHub
Python
BIDS
MNE


Deliverables
We plan on making our data-set BIDS-compatible using MNE python. 
The project will also be published in a github repository.

Results
TBA

Tools plan on learning for this project
MNE python
Similarity Fusion
GitHub
BIDS
Get more proficient in python



