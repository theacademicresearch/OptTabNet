# OptTabNet
# Machine and Deep Learning for DDoS Detection in SDN-based VANETs
### Setitra (setitra@outlook.com)
***

> ## Published Results:

* *Detection of DDoS Attacks in SDN-based VANET using Optimized TabNet*

* doi.org/10.1016/j.csi.2024.103845

* \***Update - 02/2024** - improved detection results through better data cleaning process. Updated results on Git. 

> ## Objectives 

1. Implement Adam optimization and deploy the TabNet deep learning classifier to detect DDoS attacks in SDN-based VANET. The evaluation is conducted using two publicly available datasets.

2. Offering a thorough and comprehensive analysis of existing DDoS detectors that leverage both machine learning (ML) and deep learning (DL) approaches. The selection criteria for reviewed papers include using similar ML techniques, evaluation and comparison methodologies related to DDoS detection, the datasets employed, optimization methods utilized, and the specific system targeted (e.g., SDN or SDN-VANET).

3. Enhancing the TabNet architecture's efficiency through applying the Adam optimization technique and an exhaustive Grid Search Cross-Validation (GSCV) optimization during training. This approach aims to identify optimal hyperparameters, ensuring the TabNet classifier achieves the highest accuracy in DDoS attack classification.

4. Comparing the proposed approach against four supervised machine learning techniques and two deep learning techniques. Additionally, the performance of the proposed model is benchmarked against relevant studies in the field, providing a comprehensive evaluation of its efficacy.

5. Providing a promising solution for enhancing VANET communication security by offering accurate and interpretable predictions of DDoS attacks. This objective addresses the need for robust security measures in vehicular communication systems, contributing to the overall resilience and reliability of SDN-based VANETs.

> ## Datasets
1. SDN-DDoS dataset, available at:
S. Sambangi, L. Gondi, S. Aljawarneh, S. R. Annaluri, SDN DDoS attack image dataset (2021). doi:10.21227/k06q-3t33.
2. InSDN dataset, available at:
M. S. Elsayed, N.-A. Le-Khac, A. D. Jurcut, Insdn: A novel SDN intrusion dataset, IEEE Access 8 (2020) 165263–165284.

> ## final used model
TabNet + GSCV + Adam opt. with an accuracy of 0.9942.

> ## Environment Config.

* Ubuntu 20.0
* Python 3.7.9
* Numpy 1.19.5
* PyTorch 1.9.0
* Scikit-learn 0.24.2

***
