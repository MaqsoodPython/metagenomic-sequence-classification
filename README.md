# metagenomic-sequence-classification
Classifying environmental sources of metagenomic proteins using k-mers and Machine Learning.
This study investigates whether the environmental origin of metagenomic protein sequences can be predicted based solely on amino acid composition. Using the OMG_prot50 dataset containing 207 million protein sequences, we sampled approximately 20,000 sequences from five distinct environments: human gut, soil, ocean, freshwater, and thermal springs. K-mer frequency features (k=3,4,5) were extracted from protein sequences and used to train machine learning classifiers including Random Forest, Logistic Regression, and XGBoost. Our best-performing model achieved approximately 65-75% classification accuracy, demonstrating that protein sequence composition reflects environmental adaptation. Analysis of important k-mers revealed biologically meaningful patterns corresponding to known functional adaptations in different microbial communities.
# The primary objectives of this study were:
1. To develop efficient methods for sampling and processing large-scale metagenomic datasets
2. To extract k-mer frequency features from protein sequences for machine learning classification
3. To build and compare multiple classification models for predicting environmental sources
4. To identify sequence patterns that distinguish different microbial environments
5. To interpret findings in the context of known biological adaptations


