# Medical department classification

ABSTRACT

This interdisciplinary research project aims to 
enhance the precision and scope of voice-driven medical 
department classification by integrating advanced natural 
language processing methodologies. Utilizing Clinical BERT for 
nuanced language comprehension, K-means clustering 
effectively segments data. Named Entity Recognition (NER) 
benefits from integrating Med7 and BC5CDR models, facilitating 
thorough identification and classification of entities in medical 
records. For multi-class classification, LSTM networks, along 
with separate BiLSTM and CRF models, are employed to 
improve contextual analysis and capture sequential 
dependencies. Additionally, a CNN model is introduced to extract 
features from input data, enhancing the classification process. 
This integrated framework operates seamlessly on both labeled 
and unlabeled data, advancing automated healthcare systems 
and offering valuable insights into voice-driven medical record 
analysis. Its potential for transformative impacts in the field is 
significant. Model accuracy rates are as follows: BiLSTM 67%, 
LSTM 76%, CRF 78%, and CNN 97%. K-means clustering was 
utilized to group unlabeled patient data, providing insights into 
how symptoms affect cluster formation and convergence.

RESULTS AND DISCUSSION

The outputs from these models are then used in multiclass classification models to categorize symptoms and map them to their respective departments. Additionally, leveraging BERT-based models such as clinical BERT, k-means clustering is utilized to discern medical department associations for unlabeled data. The experimental findings reveal the efficacy of various models: Bi-LSTM yielded an accuracy of 67%, followed by LSTM at 76%, and CRF at 78%. Furthermore, the exploration of CNN for sequential text analysis demonstrated remarkable accuracy, reaching 97%. 

Bar graph of models and their comparison

![image](https://github.com/user-attachments/assets/498a0591-8e96-4463-9aea-7512754121b4)

Confusion matrix of BiLSTM

![image](https://github.com/user-attachments/assets/1f4d019c-92cc-4dac-b7b3-b0677fffe27c)

Confusion matrix of LSTM

![image](https://github.com/user-attachments/assets/2bc897cf-3a30-453d-8302-20c6fb2da21f)

Confusion matrix of CRF

![image](https://github.com/user-attachments/assets/b3b84257-1898-4cf9-9ddd-8dbe4bf3b8c7)

Confusion matrix of CNN

![image](https://github.com/user-attachments/assets/625e37d1-88f7-49a9-b442-49e4f1a7c1d2)

K-Means Clustering output

![image](https://github.com/user-attachments/assets/90fecd40-1af1-49d4-8bd2-6c62075c4f3f)

CONCLUSION

In conclusion, this interdisciplinary research project represents a significant breakthrough in voice-driven medical department classification, leveraging advanced natural language processing methodologies. Through the integration of cutting-edge techniques like Clinical BERT, K-means clustering, and Med7 and BC5CDR models, the system achieves remarkable accuracy rates, showcasing the power of both supervised and unsupervised learning.

The seamless alignment of voice-recorded inputs with NER-based classification demonstrates the system's adaptability and effectiveness in handling diverse data sources. With accuracy rates of 67% for BiLSTM, 76% for LSTM, 78% for CRF, and an impressive 97% for CNN, the system excels in accurately identifying and categorizing medical entities within voice-recorded medical records.

Beyond its technical achievements, this project holds promise for revolutionizing healthcare informatics by improving the efficiency and accuracy of medical data processing. By reshaping the intersection of technology and healthcare, the research not only advances automated healthcare systems but also addresses practical needs in voice-driven medical record analysis, ultimately enhancing patient care and outcomes. As such, the project's implications extend far beyond its initial scope, signaling a transformative shift in the way medical data is analyzed and utilized.






