# AffectiX - An Emotion Detection System
## Authors
1. Emaan Umer 
2. Fahd Ahmad

School of Electrical Engineering and Computer Science (SEECS), National University of Sciences and Technology (NUST), H12, Pakistan

## Keywords
- FER2013 dataset
  
  ![image](https://github.com/user-attachments/assets/12322fe3-3ea0-494c-a1fa-d2d0b929b20b)

- VGG16
- ResNet50v2
- Facial Emotion Recognition
- Transfer Learning

This project addresses the challenge of recognizing human emotions through facial expressions using deep learning. It leverages the FER2013 dataset and uses transfer learning with pretrained models like VGG16 and ResNet50V2 to develop an efficient real-time emotion detection algorithm. The VGG16 model achieved a testing accuracy of 87.7%.

| Hyperparameter            | Value               |
|---------------------------|---------------------|
| Learning Rate             | 0.001               |
| Optimizer                 | Adam                |
| Learning Rate Scheduler   | ReduceLROnPlateau   |
| Number of Epochs          | 50                  |
| Batch Size                | 32                  |
| Activation Function       | ReLU                |

## Accuracy and Loss Curve

![image](https://github.com/emaanumer012/emotion-detection-algorithm/assets/108564940/b7935d0e-ca4a-4562-b92a-ae388b8a1fcd)

## Confusion Matrix
![image](https://github.com/emaanumer012/emotion-detection-algorithm/assets/108564940/aa83234d-8207-4442-854f-6fefaf82a80d)
