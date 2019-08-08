This directory contains the source code for the CGM project

a) ClassicalFeatureExtraction.ipynb
    This is just an experimental code, not relevant to the project and can be ignored.
    
b) consolidated_feature_extraction.ipynb
    This file contains the python code for all 8 features extracted from the raw CGM signals. Run this code to extract consolidated features.
    
c) consolidated_listofdata.ipynb
    This python notebook converts the features from all input files into a single consolidated .csv file which contains the mealid followd by the 8 extracted features and the ground truth for fat, carb, protein. This is the final .csv file which is further used in classificatin problem
    
d) Feature Extraction - (Mean, Standard Deviation and AUC).ipynb
    This file is no longer used. This is an intermediary file, this code has been integrated into consolidated_feature_extraction.ipynb
    
e) Feature extraction-skewness-lasthalfhrcgm.ipynb
    This file is no longer used. This is an intermediary file, this code has been integrated into consolidated_feature_extraction.ipynb
    
f) FeatureExtraction-maxpeak-halfpkdiff-tailpart.ipynb
    This file is no longer used. This is an intermediary file, this code has been integrated into consolidated_feature_extraction.ipynb