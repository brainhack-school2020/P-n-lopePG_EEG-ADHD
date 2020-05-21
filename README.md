
## PenelopePG_EEG-ADHD
This project is realized as part of the Brainhack School 2020.

#Summary
ADHD is a neurodevelopmental disorder which manifests itself through a variety of cognitive and 
behavioral symptoms. It is well known in the ADHD litterature that there are many subtypes of this
disorder, but there is much controversy as to what those subtypes represent and how many are accurate. 
Those subtypes are also mostly based on behavioral and self-report data and not on neurophysiological 
assessment.

# PenelopePG_EEG-ADHD
This project is realized as part of the Brainhack School 2020.

Summary:
ADHD is a neurodevelopmental disorder which manifests itself through a variety of cognitive and 
behavioral symptoms. It is well known in the ADHD litterature that there are many subtypes of this
disorder, but not all research papers agree on what these subtypes are. Those subtypes are also
mostly based on behavioral and self-report data and not on neurophysiological assessment.
>>>>>>> a526b6b05fa4074fdcf4138ac9bbfa6507ad5fdc

Using EEG data from young adults with ADHD, we will investigate the presence of subtypes and
the possible associations between the reported and behavioral symptoms and the different 
amplitude and distribution of the brainwaves.



#Details
Our sample consists of 92 college students with ADHD. EEG was performed using a 19 channel 
electrodes cap using the international 10-20 system while participants were resting with their eyes opened
for 5 minutes. Time-frequency analysis were performed in order to extract the mean amplitude of each frequency for each electrode.
Neuropsychological measures include
- Conners questionnaire (self-report)
- WAIS-IV working memory subscale (data has not been accessed yet, but should be in the next few days)
- IVA-II behavioral test

#Analyses
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


Details:
Our sample consists of 209 college students with ADHD. EEG was performed using a 32 channel 
electrodes cap while participants were resting with their eyes opened for 5 minutes. Time-frequency 
analysis were performed in order to extract the mean amplitude of each frequency for each electrode.
Neuropsychological measures include
- Conners questionnaire (self-report)
- WAIS-IV working memory subscale
- IVA-II behavioral test

Analyses:

Using clustering, we will identify which symtoms of ADHD are present in the same individuals; identifying
possible subtypes of the disorder. Those clusters will then serve as label for a classification 
algorithm whose task will be to predict the ADHD subtype of participants using EEG data. 
This will be realized using python, more specifically jupyter notebooks. 


#Tools
Network Similarity Fusion
Clustering
Classification algorithm (to be determined)
=======
Tools:

Jupyter Notebook
GitHub
Python
BIDS
MNE


#Deliverables
We plan on making our data-set BIDS-compatible using MNE python. 
The project will also be published in a github repository.

#Results
TBA

#Tools I learned during this project
TBA



Deliverables:
We plan on making our data-set BIDS-compatible using MNE python. 
The project will also be published in a github repository.

Results:
TBA

Tools I learned during this project:
TBA

