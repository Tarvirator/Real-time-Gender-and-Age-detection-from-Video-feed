# Real-time-Gender-and-Age-detection-from-Video-feed

## Overall Workflow

![image](https://github.com/Tarvirator/Real-time-Gender-and-Age-detection-from-Video-feed/assets/66062453/2acb8315-50b3-43ff-b632-7a1f3f8fd196)

## Gender Prediction Dataset

- Combined dataset of UTKFace and Fairface
  
- Total datapoint (after cleaning)
  - Male: 56262
  - Female: 52193
    
- Male class downsampled to to ensure balance
  
- 30% data used for test set

## Age Prediction Dataset

- Combined dataset of UTKFace and FacialAge

- Total datapoint: 33421 (after cleaning)

- 30% data used for test set

- Image augmentation applied on train dataset

- Train dataset size after augmentation: 454,325


## Face Detetction Model

- Retina Face Detection model

- Tensorflow based Deep face detection framework

- Able to detect faces in low light condition


## Age and Gender Detection Models

- Based on mobilnetv2 architecture for better feature extraction 

- Base model followed by fully connected dense layers with relu activation and dropout layers

- Softmax activation on output layer


## Inference Results
![Screenshot_7](https://github.com/Tarvirator/Real-time-Gender-and-Age-detection-from-Video-feed/assets/66062453/c349dbf9-1582-40b2-bba3-937d690a1d80)
![Screenshot_5](https://github.com/Tarvirator/Real-time-Gender-and-Age-detection-from-Video-feed/assets/66062453/20adc71b-88d9-43d0-a575-8412014f38b3)
![Screenshot_6](https://github.com/Tarvirator/Real-time-Gender-and-Age-detection-from-Video-feed/assets/66062453/4b84e4e1-9397-49b2-a4c8-1c0636436c22)



