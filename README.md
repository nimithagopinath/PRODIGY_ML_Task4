# Hand Gesture Recognition System
This project aims to develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

# Description
The project focuses on creating a deep learning model for hand gesture recognition within gesture-based control systems. The model employs Convolutional Neural Networks (CNNs) to extract features from images. It was trained on a dataset of 15,000 hand gesture images over approximately 100 epochs. The model is designed to classify 10 specific hand gestures:

Palm
Palm - Moved
Fist
Fist - Moved
Thumb
Index
OK
Down
L
C
The trained model achieves an accuracy of 88% on the testing dataset.

# Evaluation
During the training phase, the model's performance was monitored and evaluated. Metrics such as accuracy and loss were tracked over each epoch to ensure the model was learning effectively and not overfitting. The training history showed that the model consistently improved and reached a satisfactory level of accuracy.

# Inference
Once the model was trained, it was used to classify new hand gesture images. The inference process involves feeding an image into the model, which then predicts the hand gesture depicted. This step demonstrated the model's practical application in real-time hand gesture recognition, providing a robust basis for gesture-based control systems.

# Dataset
The dataset used for this project is the Hand Gesture Recognition Database provided by gti-upm on Kaggle. This database comprises near-infrared images captured using the Leap Motion sensor. It includes 10 different hand gestures performed by 10 different subjects (5 men and 5 women). In total, the database consists of 20,000 annotated images, organized into folders based on the hand gesture and the subject performing it.


# Conclusion
This project successfully demonstrates the development of a CNN-based model for hand gesture recognition. With an accuracy of 88% on the testing dataset, the model shows promise for applications in gesture-based control systems. The use of a comprehensive dataset and effective training strategies underlines the potential of deep learning techniques in human-computer interaction.
