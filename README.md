# Sleep Posture Classification

This project implements a **Sleep Posture Classification System** using sensor data from wearable devices. The objective is to classify the subject's posture into predefined categories with high accuracy, using machine learning techniques. This project leverages **Linear Discriminant Analysis (LDA)**, comprehensive feature engineering, and data augmentation to enhance model performance.

---

## Features
- **Machine Learning Techniques**: Implements Linear Discriminant Analysis (LDA) for posture classification.
- **Data Preprocessing**: Scales raw sensor data to a range of [0-255] and applies data augmentation techniques to improve model robustness.
- **Performance Metrics**: Achieves **92% accuracy** and an F1 score of **0.89**.
- **Visualization**: Provides detailed visualizations of classification outcomes for clear insights into model performance.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Dataset Description](#dataset-description)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Future Enhancements](#future-enhancements)
8. [Contributors](#contributors)
9. [License](#license)

---

## Introduction
Sleep posture plays a critical role in physical health, affecting areas such as spinal alignment, breathing, and sleep quality. This project addresses the need for automated posture classification systems using data from wearable devices. By leveraging **machine learning** techniques and advanced data preprocessing, the project delivers reliable results suitable for real-world applications.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn
- **Model**: Linear Discriminant Analysis (LDA)

---

## Dataset Description
The dataset consists of raw sensor readings from wearable devices. Key details include:
- **Input Features**: Sensor data from accelerometers and gyroscopes.
- **Target Variable**: Posture categories (e.g., Back, Side, Stomach).
- **Preprocessing**:
  - Scaled sensor readings to [0-255].
  - Applied augmentation techniques to improve generalization.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vineeth-chaitanya/sleep_posture_classification.git
   cd sleep_posture_classification


# Sleep Posture Classification

This project implements a system to classify sleep postures using machine learning techniques. The model achieves high accuracy through feature engineering, data preprocessing, and robust evaluation methods.

---

## Results

The system demonstrated the following outcomes:

- **Accuracy**: 92%
- **F1 Score**: 0.89
- **Classification Improvement**: Achieved a 20% improvement in performance through advanced feature engineering.

### Visualization

- **Performance Metrics**:
  - Confusion matrix and classification reports for detailed performance analysis.
- **Sensor Data Plots**:
  - Visualized augmented and original data to highlight preprocessing improvements.

---

## Future Enhancements

The project has scope for the following improvements:

1. **Deep Learning Integration**:
   - Implement advanced models like Convolutional Neural Networks (CNN) or Recurrent Neural Networks (RNN) to better handle time-series data.

2. **Real-time Classification**:
   - Develop a pipeline for real-time posture detection using streaming sensor data.

3. **Expanded Dataset**:
   - Include data from multiple wearable devices to improve the model's generalization and robustness.

---


