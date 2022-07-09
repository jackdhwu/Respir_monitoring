# Respir_monitoring
The source code and dataset of "Simultaneously monitor the respiratory behavior of multiple cows based on computer vision and deep learning"
****

## Motivation
* __Respiration is one of the important physiological parameters of dairy cows and also an important basis for researchers and managers to analyze their physiological status, diseases and nutrition.__

* __Traditional manual observation is time-consuming and labor-intensive, while professional medical measurement equipment requires high usage environment and is difficult to achieve efficient monitoring on farms.__

* __Intelligent monitoring of the cow’s respiratory behavior is not only the basis of its health assessment and assessment, but also helps to optimize the feeding scheme and improve animal welfare and farm benefits.__
****

## Methods
* __In this study, we built a camera monitoring platform on a dairy farm and proposed a method for simultaneous monitoring of multiple cows’ respiration based on computer vision and deep learning, with a view to contributing to labor liberation and intelligent health assessment.__ 
* __Initially, 4000 manually labeled images were employed to fine-tune the YOLACT (You Only Look At CoefficienTs) for multiple cows’ recognition and segmentation.__ 
* __Then, specific behaviors of different individuals (lying resting and standing resting) were identified by fusing CNN (Convolutional Neural Network) and Bi-LSTM (Bidirectional Long and Short-term Memory).__ 
* __Finally, corresponding detection algorithm (lying or standing) was employed for respiratory behavior monitoring.__
****

## Results
* __The test results of 60 videos containing different interference indicated that the average ACC of the method was 93.56%, and the MAE and RMSE were 3.42 and 3.74, respectively. The study contributes to the remote diagnosis of respiratory-related diseases and the development of intelligent monitoring robots in precision farming.__
****
