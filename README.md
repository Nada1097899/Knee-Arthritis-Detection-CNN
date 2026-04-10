# Knee Arthritis Detection using CNN

A Deep Learning project designed to detect and classify the severity of knee osteoarthritis from X-ray images into five distinct grades (0-4).

## Project Overview
Early detection of knee arthritis can significantly improve patient outcomes. This project implements a Convolutional Neural Network (CNN) to automate the grading process, providing a reliable second opinion for radiological assessments.

## Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **Computer Vision:** OpenCV
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn.

##  Technical Methodology
- **Data Augmentation:** Used `ImageDataGenerator` to increase dataset diversity and prevent overfitting.
- **Model Architecture:** A custom CNN architecture featuring multiple Convolutional, Pooling, and Dropout layers.
- **Training Strategy:** Implemented `EarlyStopping` and `ReduceLROnPlateau` to optimize the learning process.
- **Evaluation:** Analyzed model performance using Confusion Matrix and F1-score for each grade.

##  Key Results
- **Testing Accuracy:** ~81%
- **Robustness:** The model shows high precision in identifying advanced stages of arthritis (Grades 3 and 4).

---
*Developed as part of my portfolio in Medical Image Analysis and Deep Learning.*
<img width="608" height="748" alt="image" src="https://github.com/user-attachments/assets/a1dfcf46-98ee-4900-83e5-dd91f2c87dd5" />
