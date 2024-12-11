# Landmark-Classification-Tagging-for-Social-Media-Project
Dataset:
The project uses a subset of the Google Landmarks Dataset v2, which consists of images depicting various global landmarks. These images are employed to train and evaluate convolutional neural network (CNN) models for classifying landmarks. The dataset link and licensing information are available on Kaggle.
Objective:
The goal of this project is to develop a machine learning system capable of identifying the location of an image by classifying discernible landmarks depicted in it. This solution addresses challenges in photo-sharing platforms where location metadata might be missing due to privacy concerns or limitations in the capturing device. By automating landmark recognition, this project facilitates advanced features such as:
Automatic tagging and organization of photos
Enhancing user experience with location-based photo suggestions
Through this project, the end-to-end process of designing and training CNNs, evaluating their performance, and leveraging transfer learning for better results is demonstrated.
Application:
This project highlights practical applications in photo-sharing and storage services. The developed solution can be integrated to infer missing metadata, organize photos by location, and enhance photo recommendation systems. Additionally, the project involves:
Training a CNN Model from Scratch:
Visualizing the dataset and processing it for training.
Designing and training a CNN from scratch to classify landmarks.
Exporting the trained model using Torch Script for deployment.
Using Transfer Learning:
Exploring various pre-trained models and selecting an optimal one for landmark classification.
Fine-tuning the selected model to improve classification accuracy.
Exporting the final transfer-learned model using Torch Script.
Creating a Landmark Prediction Algorithm:
Developing an interface for users to interact with the trained model for landmark classification.
Testing the algorithm with real-world images and reflecting on the model's strengths and limitations.
This project underscores the importance of convolutional neural networks in image classification tasks and their potential for deployment in real-world applications like social media platforms.
