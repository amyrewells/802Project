# Dataset 
[Breast Cancer (METABRIC, Nature 2012 & Nat Commun 2016)](https://www.cbioportal.org/study/summary?id=brca_metabric)

# Research question: 
Does molecular classification information provide improvement in overall survival prediction when combined with standard clinical information in breast cancer patients? If so, which system offers the greatest improvement? 


# Hypothesis:
We hypothesize that including molecular classification information will improve survival prediction compared with a model based solely on clinical variables. Furthermore, we expect the IntClust classification system to provide the greatest prognostic value because it incorporates broader genomic information and may more comprehensively capture tumour heterogeneity than PAM50 or the 3-Gene Classifier.  

# File Organization
|Filename|Description|
|----|------------|
|MainStory.ipynb| Contains the analysis to answer our main research question|
|Trial1.ipynb|Uses clinical and molecular subclass data to predict Survival Outcome (4 categories)|
|Trial2.ipynb| Repeats Trial 1 using knn instead of statistical imputation for molecular classifier subtypes|
