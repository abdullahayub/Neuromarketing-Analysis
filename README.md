## MS DataScience from Essex of University
## Neuromarketing Analysis using AI | Dissertation Project

Neuromarketing is an emerging field that combines neuroscience and marketing together. now a days brands publicity, tv commercials and products has great influence over the consumers. In this research we measure the attention, emotional engagement, and consumer behaviour. 
This article proposed the literature review of neuromarketing tools, methods, and specific techniques. In this study emphasis about analysis on neuroimaging tools EEG, FMRI and physiology techniques Eye tracking, Facial emotional coding, and recency frequency monetary (RFM) analysis. 

### Consumer Behaviour Analysis Using EEG
In EEG analysis brain signals were recorded and then it classifies into consumer feelings. In the experiment one male and female has shown different movies and response was recorded using EEG signal tracking device. Furthermore, analysis was performed on the consumer response and consider decision making of customers in a like/dislike task. Dataset is avail able on Kaggle. Features were extracted, one hot encoding was applied on labels, split the dataset with the ratio 80% and 20% into training set and testing set respectively. LSTM model was applied, accuracy was achieved 96%. We also compared our results by applying other machine learning models such as random forest, Gaussian NB, Logistic regression and SVC.

### Eye Motion Tracking and Gaze Detection (This code is in <a href="https://github.com/abdullahayub/Neuromarketing-Analysis/tree/my-new-branch" target="blank">**My-new-branch**</a>)

We created an application that can track customer eyes which is very helpful in neuromarketing analysis. it can find out that what customers are looking for extract the useful information for future analysis for making strategies and decision making. There are two functionalities in application. First one is gaze and eye blinking detection in which we calculate eye gaze ratio to detect direction of eye movement for instance, he/she is looking at Right, Left, and Centre. For eye blinking, we calculate the eye blinking ratio. So, when we close our eyes, the system will detect and show the person is blinking his eyes. 

In the other part, we can control mouse cursor on laptop screen using our eyes. We take the dataset of eye images available of Kaggle, perform data pre-processing, feature extraction. Training dataset fed into the CNN model. Accuracy of the model achieved 87%. This system works like it creates the path of consumer eye movements from which analyst extract the useful information which is beneficial for their business processes.


### Emotion Recognition

#### Emotion Recognition using Facial Dataset
In this project, I will detect the facial expression through automatic system. Emotion recognition is the process of identifying the human emotion. It the technology used for to analyse human emotions from images or live videos and then stated out the result on the basis of emotions classification. The programmed facial appearance has many applications for instance, Social Behaviour Understanding, recognition of mental condition, and artificial humanoid expression. One of the main uses of this automatic system is to evaluate the candidate during the interview and to measure how he defended to certain questions. It is also useful and important for security and healthcare purposes. 

This project will recognize your facial emotions using live webcam feed. The main processes in this project are as follows: • Upload and Adjust the Data set • Implementing the Facial Emotion Recognition Model Using CNN • Compile and Train Model Using CNN • Evaluate the Model • Save CNN Model • Evaluate the Model • Test the Mode

#### Emotion Recognition using Eye Dataset
We used eye emotion dataset DIU available on Kaggle. Build an application that can take human eyes as an input, with the help of trained CNN model will classify the image into human expressions. Data pre-processing was done, one hot encoding was applied on labels. InceptionV3 and Xception pretrained CNN model was used for feature extraction. CNN model was built, and train dataset was fed into model. Accuracy of the model achieved 72%. I build another Jupiter file that allows to use live webcam of your laptop using OpenCV library, it takes human face as an input image, crop the image to region of interest and classify the human expressions.

### Functional Magnetic Resonance Imaging (FMRI)
Functional magnetic resonance imaging is one of the neuroimaging tools. This technology also used for assessing consumer behavior. The main objective to get FMRI scans, so we can get reports of specified ROI of brain that are involved and activated, while when consumer make purchase decisions (buy or not buy). So, I used structural and functional dataset available on SPM website. Visualize the brain scan in 3-d dimensions, divide it into slices. Wecreated the EPI image. Calculate the correlation coefficients and find out the region with highest correlations. Results were bit noisy, so to improve the results I applied general linear model and get the smooth EPI images.


### RFM Analysis customer Segmentation
Dataset between year 2010- 2011 of retail online UK store was collected. Recency, frequency and monetary (RFM) analysis was performed. Did customer behaviour segmentation base on their RFM score? Rating was assigned to the customers. Quantile method is used to calculate RFM score and then segment the customers. K means algorithm was also applied; 5 clusters were created due to the rating between 1star to 5star. Segment the customers based on clusters by calculating their RFM score

