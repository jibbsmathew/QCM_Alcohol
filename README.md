# QCM_Alcohol

The **QCM_Alcohol** project focuses on the classification of five different types of alcohols (1-octanol, 1-propanol, 2-butanol, 2-propanol, and 1-isobutanol) using Quartz Crystal Microbalance (QCM) sensors of various structures. This study is particularly significant in the context of recognizing chemical compounds, detecting harmful effects, and designing cost-effective systems, which is crucial for both research and industrial applications.

### Background
- **Alcohol Types:**
  - **1-octanol:** Fatty alcohol, used in perfumes and flavorings (Chemical formula: CH3(CH2)7OH).
  - **1-propanol:** Aliphatic alcohol, resembles ethyl alcohol but has a strong and toxic odor, mainly used as a solvent (Chemical formula: CH3CH2CH2OH).
  - **2-butanol:** Secondary alcohol, a strong solvent (Chemical formula: CH3CH(OH)CH2CH3).
  - **2-propanol:** Isopropyl alcohol, used at home and in industry, an example of a secondary alcohol (Chemical formula: CH3CHOHCH3).
  - **1-isobutanol:** Used as a solvent (Chemical formula: (CH3)2CHCH2OH).

### Objective
The primary goal is to measure the reaction of different QCM sensors to these alcohols, determining which type of sensor is more successful in classifying them.

### Dataset
Utilize the attached dataset containing the resonance frequency Δf changes for five QCM sensors. The dataset includes proportions of air in each gas concentration and the class of gas.

### Methodology
1. **Individual Sensor Analysis:**
   - Apply the classifier to each QCM sensor separately.
   - Compare the performance of sensors for classification.
   - Calculate sensitivity, specificity, and total accuracy for each dataset and classifier.

2. **Comparison of Classifiers:**
   - Use supervised classifiers (MLP, SVM, HMM) and unsupervised classifiers (K-means clustering, FCM clustering).
   - Evaluate performance when 20% of the data is used for testing (MLP, SVM, HMM) and all data for clustering.

3. **Feature Selection:**
   - Combine data from all sensors to create a dataset with 50 features (10*5).
   - Apply Minimum Redundancy Maximum Relevance and Relief methods to find the best features.
   - Calculate sensitivity, specificity, and total accuracy for the five classes.

4. **Submission:**
   - Submit results in a PowerPoint presentation.
   - Name codes with "classification method_QCMXX_LastName_FirstName," where XX is the sensor number.

### Conclusion
This project not only contributes to the field of data science but also sheds light on the practical applications of AI in chemical compound recognition. The comparison of classifiers and feature selection methods will provide valuable insights for future research.

Feel free to customize this README to include any additional details or specific instructions related to your project.
