# dentalImpute
### The Problem
Dental anthropology is a specialized subset of Biological anthropology that focuses on the development and morphology of dentition. Most of the data that dental anthropologists work with on the morphological side are discrete and/or ordinal traits. When working with bioarchaeological skeletal collections, traits are often unable to be scored due to missing teeth or extreme wear of the enamel. Therefore, dental anthropological data is wrought with missing data. As a result, most dental anthropological methods use breakpoints to collapse raw data into absense (0) and presence (1), followed by frequency calculations to allow for the use of continuous data. The loss of dental morphological variation when applying such methodology is vast, and additional avenues of data analyses should be explored.

### Project Objective
The goal of this project was to test a number of data imputation techniques to explore which methods may be best applied to dental moprhological trait scores. The objective of these imputation methods is to preserve the general biodistance analyses trends observed between pre-defined groups of a complete set of selected dental traits.

The following three (3) imputation methods were tested:  
1. Hot Deck (HD)  
2. *k*-Nearest Neightbors (KNN)  
3. Variable Medians (VM)  


Methodologies for simulating missing data and overall evaluation of each imputation method follow a similar workflow to that of [Kenyhercz et al. (2019)](https://doi.org/10.5744/fa.2019.1015) using cranial morphological traits. 

Following the identification of *k*-Nearest Neighbor as the best-performing imputation method on simulated missing data, the method was applied to another dataset to ensure among-population relationships were reatained when imputation was conducted.

Code and iterative processes are provided in **HTML** and **RMD** format.
