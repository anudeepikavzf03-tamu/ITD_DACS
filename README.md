# ITD_DACS

Insider Threat Detection - Using Sampling and Feature Extraction Techniques

Insider threats pose a significant security risk for organizations. However, detecting these threats is challenging due to class imbalance and limited real-world training data. Prior research on insider threat detection has applied various techniques including user behavior modeling, information retrieval for communications analysis, and graph-based anomaly detection. Specific approaches explored include statistical methods, machine learning, natural language processing, and network analysis to model normal behavior patterns and identify deviations that may indicate malicious intent. Evaluation of techniques has been performed on CERT dataset insider threat corpus. 


Our project will advance insider threat detection through a multi-pronged approach:

Feature Engineering: We aim to identify the most discriminative features attributes from log files, including activities like logons, device usage, and file access, as well as user psychometric scores. By leveraging domain expertise and data preprocessing techniques, our goal is to engineer an effective set of features that can profile user behaviors and enable the detection of insider threats.
Custom Oversampling: We will develop tailored oversampling techniques that synthesize realistic insider threat examples while retaining crucial data characteristics. This allows for enhanced model training.
Comparative Benchmarking: We will benchmark the engineered features and synthetic training data on existing insider threat detection models including anomaly detection and classification algorithms. Extensive comparative analysis on metrics like accuracy, precision, recall and F1 will reveal the optimal combinations of data enhancements and models.


The key research goals are:

Derive highly informative feature representations to distinguish between benign and malicious user activities.
Design tailored oversampling methodology tuned for insider threat data properties.
Perform comprehensive benchmarking of enhanced data on existing models and comparative analysis to determine best performing combinations of oversampling, feature engineering, and modeling algorithms.

This project will advance state-of-the-art insider threat detection through improved training data and features while revealing the most effective modeling techniques through rigorous benchmarking. The enhancements aimed at addressing class imbalance and limited data issues coupled with comparative analysis will provide actionable insights to guide future insider threat detection efforts.


Dataset:


https://kilthub.cmu.edu/articles/dataset/Insider_Threat_Test_Dataset/12841247/1

This project utilizes CERT’s version 3.2-6.1 dataset containing labeled synthetic user activities like logon, device connections and file actions, which includes normal and malicious behavior.
