📌 Overview
-----------

This project focuses on building and training a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 distinct categories, such as airplanes, cars, birds, and more.The aim is to achieve high classification accuracy using deep learning techniques.

🔍 Problem Statement
--------------------

Image classification remains a core challenge in computer vision tasks.The objective is to design an effective deep learning model that can accurately recognize and classify small (32x32 pixel) colored images into predefined categories, helping in automated image recognition systems.

📁 Dataset
----------

Used the **CIFAR-10 dataset**, a benchmark dataset provided by the Canadian Institute for Advanced Research.It contains 60,000 32x32 color images across 10 classes (6,000 images per class), divided into 50,000 training images and 10,000 test images.

(Source: CIFAR-10 dataset - Official)

🧠 Approach
-----------

1.  Loaded and preprocessed the CIFAR-10 dataset (normalized pixel values).
    
2.  Built a CNN model with convolutional, pooling, and dense layers.
    
3.  Compiled the model using 'categorical\_crossentropy' loss and 'adam' optimizer.
    
4.  Trained the model over multiple epochs to minimize loss and improve accuracy.
    
5.  Evaluated the model performance on the test dataset.
    
6.  Visualized training/validation loss and accuracy curves.
    

📈 Key Features
---------------

*   End-to-end CNN model training for image classification.
    
*   Achieved good accuracy on unseen test data.
    
*   Data augmentation techniques can be added for improving generalization.
    
*   Clear plots of accuracy and loss curves during training.
    

✅ Results
---------

*   Achieved a training accuracy of **34.30%** with a training loss of **1.7971**.
    
*   Achieved a validation (test) accuracy of **49.88%** with a validation loss of **1.3765**.
    
*   The model shows a reasonable ability to distinguish between different image classes, but further improvements can be made using techniques like data augmentation, regularization, or tuning the CNN architecture.
    

📷 Screenshots
![image](https://github.com/user-attachments/assets/eb21d8fd-2bd5-4c65-b83d-267a83bb1213)
![image](https://github.com/user-attachments/assets/9f6749cf-ea50-473a-8b66-63e1581d90fa)

📚 Learnings
------------

*   Understood how CNNs extract spatial features from images.
    
*   Learned how to prepare image data for deep learning models.
    
*   Gained experience in model evaluation and visualization of performance metrics.
    
*   Importance of tuning model architecture and parameters to improve results.
    

🤝 Acknowledgements
-------------------

Data Source: CIFAR-10 DatasetInspired by: TensorFlow/Keras documentation and multiple deep learning tutorials.
