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

- Adam optimizer with default learning rate


## Gender Detection Model

