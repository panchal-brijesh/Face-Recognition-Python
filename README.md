## Neural Network for Facial Recognition from Scratch

### Project Title
Create a Neural Network to Recognize Your Face and Clearly Discern It from Other Faces and Objects

### Author
Brijeshkumar Vijaykumar Panchal

### Matriculation Number
221607

### Course
Master of Mechatronics and Robotics

### Semester
Sommersemester 2024

### Subject
Autonomous Systems: Deep Learning

### Supervisor
Prof. Dr.-Ing. Nicolaj Stache (Heilbronn University)

---

## Table of Contents
- Introduction  
- Libraries  
- Image Capturing and Data Preparation  
- Network Architecture and Training  
- Evaluation  
- Overfitting and Underfitting Analysis  
- Discussion  
- Conclusion  
- Credits  

---

## Introduction
This project develops a neural network from scratch to recognize my face and distinguish it clearly from other faces and objects. Unlike many methods that use pre-trained models, this network is trained from the ground up, allowing a better understanding and customization specific to the dataset. The process is thoroughly documented from data collection, model training, evaluation, to discussing performance and limitations.

---

## Libraries
- **os**: Access operating system functions.  
- **cv2 (OpenCV)**: For capturing images via webcam.  
- **numpy**: Scientific computing and array operations.  
- **matplotlib**: Plotting graphs and images.  
- **tensorflow**: Deep learning framework used for building and training the CNN.  
- **sklearn**: Used for train/test splitting and evaluation metrics.

---

## Tools

- **Jupyter Notebook** – Development environment for writing and running code
- **Python** – Programming language used for model development

---

## Image Capturing and Data Preparation
Images of my face and various other objects are captured using OpenCV to create a dataset. Data augmentation techniques like rotation, shifting, zooming, and flipping are applied to increase dataset diversity and robustness.

---

## Network Architecture and Training
- CNN with 3 convolutional layers, max-pooling, dropout layers, flattening, and dense layers.  
- Binary classification with softmax activation.  
- Optimizer: Adam; Loss: categorical crossentropy.  
- Early stopping to prevent overfitting.  
- Hyperparameters: batch size 32, image size 224x224, 10 epochs, learning rate 0.001.  

---

## Evaluation
- Accuracy and loss tracked on training and validation sets.  
- Visualized learning curves to monitor performance and diagnose overfitting/underfitting.  
- Achieved validation accuracy up to ~94%.  
- Tested the model on unseen validation images and visualized predictions.  

---

## Overfitting and Underfitting Analysis
- Techniques like dropout, data augmentation, and early stopping were applied to mitigate overfitting.  
- Underfitting addressed by increasing model complexity or training duration if needed.  
- Linear regression on loss curves used to assess model fitting.  

---

## Discussion
Model performs well overall but struggles under poor lighting, pose variations, and similar-looking objects. Future improvements include enlarging the dataset, enhancing augmentation, and tuning model architecture.

---

## Conclusion
This project successfully demonstrates building a CNN for facial recognition trained from scratch, handling typical deep learning challenges, and provides a foundation for further enhancements in facial recognition applications.

---

## Credits

### Books:
- *Pattern Recognition and Machine Learning* by Christopher M. Bishop  
- *The Elements of Statistical Learning* by Hastie, Tibshirani, Friedman  
- *Mathematics for Machine Learning* by Deisenroth, Faisal, Ong  

### Educational Institutions and Professor:
- Prof. Dr.-Ing. Nicolaj Stache, Heilbronn University of Applied Sciences

### Websites and Online Documentation:
- Python Official Website URL: https://www.python.org/
