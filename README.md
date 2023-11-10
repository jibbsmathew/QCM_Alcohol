# QCM_Alcohol
The use of gas sensors together with pattern classification methods plays a significant role in recognition
and classification of chemical compounds and detection of their harmful effects. Designing these less
costly systems is important also for the industry.
Alcohols constitute a huge portion of these compounds, and are used largely in hygiene products and
cosmetics. The aim of this study is to classify 5 different types of alcohols – 1) 1-octanol, 2) 1-propanol,
3) 2-butanol, 4) 2-propanol and 5) 1-isobutanol using QCM (quartz crystal microbalance) sensors of
different structures. Among these alcohols
1) 1-octanol is known as fatty alcohol. Its chemical formula is CH3(CH2)7OH, and with its strong odor it
is generally used in perfumes and flavorings.
2) 1-propanol is an aliphatic alcohol with a chemical formula of CH3CH2CH2OH. While it very much
resembles ethyl alcohol chemically, it has a strong and toxic odor. It is rather used as a solvent.
3) 2-butanol is called as secondary alcohol, and has a formula of CH3CH(OH)CH2CH3. Again this
alcohol is a strong solvent.
4) 2-propanol is an isopropyl alcohol with a formula of CH3CHOHCH3. It is a compound used at home
and in industry, and an example of secondary alcohol.
5) 1- isobutanol has a formula of (CH3)2CHCH2OH. It is known to be used as a solvent.
QCM sensor is a physical device that is sensitive to resonance frequency Δf changes. QCM sensors with
different structures may react very differently. The reason of using QCM sensors in this study is the
successful reaction of these sensors to the compounds. Despite their success levels, the costs of the QCM
sensors are low. The aim of the study is to measure the reaction of different QCM sensors to this 5
different alcohols, and to determine which type of sensor is more successful in classification of these
alcohols.
Use the attached dataset for 5 QCM sensors. The first 10 numbers are the resonance frequency Δf changes
for different proportion of air in each gas concentration. The last 5 numbers determine the class of gas.
For example, if the gas be octanol, the first number is 1 and the last 4 numbers are zero.
Apply the classifier to the dataset for each QCM sensor separately and compare the performance of
sensors for classification. For each dataset and classifier calculate the sensitivity, specificity, and total
accuracy.
Compare the classification performance for classifying these 5 different types of alcohols for each sensor
using supervised classifiers MLP, SVM, and HMM and unsupervised classifiers K-mean clustering and
FCM clustering approaches when 20% of the data in each class is used for testing for MLP, SVM, and
HMM and all the data is used for K-mean clustering and FCM clustering for evaluation.
Combine the data of all sensors, so the total number of features for each gas concentration would be
10*5=50. Apply Minimum Redundancy Maximum Relevance approach and Relief to find the best
features among these 50 features that gives you the best classification performance and calculate the
sensitivity, specificity, and total accuracy for 5 classes. Compare the performance of the classifiers.
Submit all your results in power point presentation along with all codes. Name the codes with
classification method_QCMXX_Last name_first name where XX is the sensor number.
