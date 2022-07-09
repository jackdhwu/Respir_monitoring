# Respir_monitoring
The source code and dataset of "Simultaneously monitor the respiratory behavior of multiple cows based on computer vision and deep learning".
You could find the demo video of this study at:  https://youtu.be/sf4mx50mWAo


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

| Authors                | Sensor type        |Method                                      | Application object        | Recognition result              |
| ---------------------- | ------------------ |----------------------------------------    | ------------------        |--------------------------       |
| Tao et al              |    RGBD            |Monitor abdominal fluctuations              |   Single target           | Accuracy:85.30%                 |
| Barbosa et al          | Thermal image      |Perceive the temperature change of the nose |   Single target           | Error:85.30%                    |
| Lowe et al             | Thermal image      |Perceive the temperature change of the nose |   Single target           | Highly correlated with breathing|
| Kim et al              | RGBT               |Perceive the temperature change of the nose |   Single target           | Correlation:0.92                |
| Song et al             | RGB                |Monitor abdominal fluctuations              |   Single target           | Accuracy:98.58%                 |
| Wu et al               | RGB                |Monitor abdominal fluctuations              |   Single target           | Accuracy:93.04%                 |
|__Ours__                |  __RGB__           | __Monitor abdominal fluctuations__         | __Multiple targets__      | __Accuracy:93.56%__             |
****
* ### Recognition and segmentation of multiple dairy cows based on YOLACT algorithm.
![image](https://user-images.githubusercontent.com/108980498/178104219-9c4bc9e1-6e27-462c-a28e-d868b85017a3.png)
* ### Respiratory behavior monitoring of the standing cow.
![image](https://user-images.githubusercontent.com/108980498/178104268-4fc58338-a1a9-48b1-818e-e71aadb550ce.png)
![image](https://user-images.githubusercontent.com/108980498/178104274-7957b19f-6470-409e-9f47-7fa6a54e4a1a.png)
* ###  Respiratory behavior monitoring result of the lying resting cow.
![image](https://user-images.githubusercontent.com/108980498/178104169-8ee51a3a-ae46-4254-af00-bb9b200f64e6.png)
![image](https://user-images.githubusercontent.com/108980498/178104194-8a0ce1ba-673b-4dd9-8456-fd34ffc7764f.png)
****
