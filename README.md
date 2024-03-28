# MS DataScience from Essex University
# Neuromarketing Analysis using AI | Dissertation Project

Neuromarketing is an emerging field that combines neuroscience and marketing together. now a days brands publicity, tv commercials and products has great influence over the consumers. In this research we measure the attention, emotional engagement, and consumer behaviour. 
This article proposed the literature review of neuromarketing tools, methods, and specific techniques. In this study emphasis about analysis on neuroimaging tools EEG, FMRI and physiology techniques Eye tracking, Facial emotional coding, and recency frequency monetary (RFM) analysis. 

# Consumer Behaviour Analysis Using EEG
In EEG analysis brain signals were recorded and then it classifies into consumer feelings. In the experiment one male and female has shown different movies and response was recorded using EEG signal tracking device. Furthermore, analysis was performed on the consumer response and consider decision making of customers in a like/dislike task. Dataset is avail able on Kaggle. Features were extracted, one hot encoding was applied on labels, split the dataset with the ratio 80% and 20% into training set and testing set respectively. LSTM model was applied, accuracy was achieved 96%. We also compared our results by applying other machine learning models such as random forest, Gaussian NB, Logistic regression and SVC.

# Eye Motion Tracking and Gaze Detection
We created an application that can track customer eyes which is very helpful in neuromarketing analysis. It can track eye movement if subject looks in different directions, also control cursor on computer screen. Images dataset was downloaded from Kaggle, perform data pre-processing, feature extraction, split the dataset into training and testing set then apply deep learning model CNN to predict the accuracy of model. The accuracy of overall model was achieved 87%

# Emotion Recognition
Facial coding performed to recognize consumer emotions towards products. The advantage of this application that we can recognize the consumer expressions, how as they are feeling and what emotions they have about specific product. Eye images were collected from Kaggle. Inception and Xception model were used for features extraction. Training dataset was fed into CNN model to classify into human expressions. Accuracy of the model was obtained 72%. We also compared our results without applying pretrained convolutional network Inception-v3 and Xception model, then accuracy was achieved just 13% with 185% loss on testing dataset. 

# RFM Analysis customer Segmentation
Dataset between year 2010- 2011 of retail online UK store was collected. Recency, frequency and monetary (RFM) analysis was performed. Did customer behaviour segmentation base on their RFM score? Rating was assigned to the customers. Quantile method is used to calculate RFM score and then segment the customers. K means algorithm was also applied; 5 clusters were created due to the rating between 1star to 5star. Segment the customers based on clusters by calculating their RFM score

