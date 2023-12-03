# Facial_emotion_recognition_using_transfer_learning
Performing facial emotion recognition by training with custom CNN based model, transfer learning with Mobilenet pretrained model and fine tunning

Facial Emotion recognition dataset contains 7 classes (angry, happy, sad, surprise, disgust, fear, neutral)

Performed training on the data using simple convolutional neural networks based model, mobilenet pretrained model, and fine tunning it.

Models are trained for 40 epochs

|     Model       |training accuracy|test accuracy|
|simple CNN model |       65%       |    61.5%    |
|    MobileNet    |       59%       |    53.3%    |
|  Fine Tunning   |       85%       |    63.8%    |


Confusion Matrices for all three models is as follows
Simple CNN based model
![simple_CNN_confusion matrix](https://github.com/Sravan4465/Facial_emotion_recognition_using_CNN_based_model/assets/114973592/54f04a9c-e30b-4bb7-90f5-7e59252469ac)

MobileNet model
![mobilenet_confusion matrix](https://github.com/Sravan4465/Facial_emotion_recognition_using_CNN_based_model/assets/114973592/a9ccba10-89b2-4816-8056-97a80c84d820)

Fine Tunning
![mobilenet_fine_tunning_confusion matrix](https://github.com/Sravan4465/Facial_emotion_recognition_using_CNN_based_model/assets/114973592/700b2c12-c8ef-48c8-aa7b-45bd6c717ad5)

