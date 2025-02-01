# Prediction-of-LC50-Value-using-Quantitative-structure

![QSAR_Overview](https://github.com/user-attachments/assets/48858f15-9368-4307-8b3c-796786d57417)


Quantitative structure-activity relationship (QSAR) modeling pertains to the construction of predictive models of biological activities as a function of structural and molecular information of a compound library. Typical molecular parameters that are used to account for electronic properties, hydrophobicity, steric effects, and topology can be determined empirically through experimentation or theoretically via computational chemistry.
A given compilation of data sets (set of multiple data scriptor values) is then subjected to data preprocessing and data modeling through the use of statistical and/or machine learning techniques. Quantitative structure-activity relationship (QSAR) and quantitative structure- property relationship (QSPR) makes it possible to predict the activities/properties of a given compound as a function of its molecular substituent. Essentially, new and untested compounds possessing similar molecular features as compounds used in the development of QSAR/QSPR models are likewise assumed to also possess similar activities/properties.
The construction of QSAR/QSPR model typically comprises of two main steps: 
(i) description of molecular structure 
(ii) multivariate analysis for correlating molecular descriptors with observed activities/properties. An essential preliminary step in model development is data understanding. Intermediate steps that are also crucial for successful development of such QSAR/QSPR models include data preprocessing and statistical evaluation.
The goal here is to build an end-to-end automated Machine Learning model that predicts the LC50 value, the concentration of a compound that causes 50% lethality of fish in a test batch over a duration of 96 hours, using 6 given molecular descriptors.

Feature Description

For this project, we already have the molecular descriptors obtained for us.

MLOGP: molecular properties

CIC0: information indices

GATS1i: 2D autocorrelations

NdssC: atom-type counts

NdsCH: atom-type counts

SM1_Dz(Z): 2D matrix-based descriptors
