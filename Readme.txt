# Human Activity Recognition using CNN-LSTM

## Overview

This project implements a **Human Activity Recognition (HAR)** system using a **CNN-LSTM deep learning model**. The model recognizes human activities from smartphone sensor data collected using accelerometers and gyroscopes.

The project uses the **UCI Human Activity Recognition (HAR) Dataset** and classifies six different human activities with high accuracy.

---

## Features

- Data preprocessing and normalization
- CNN for local feature extraction
- MaxPooling for dimensionality reduction
- LSTM for learning temporal dependencies
- Softmax classifier for multi-class classification
- Confusion Matrix
- Classification Report
- Accuracy and Loss visualization
- Saved trained model for future predictions

---

## Dataset

**Dataset Name:**
UCI Human Activity Recognition Using Smartphones Dataset

The dataset contains recordings from smartphone sensors while subjects performed daily activities.

### Activities

| Label | Activity |
|-------|----------|
| 0 | Walking |
| 1 | Walking Upstairs |
| 2 | Walking Downstairs |
| 3 | Sitting |
| 4 | Standing |
| 5 | Laying |

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## Project Workflow

Dataset

↓

Data Preprocessing

↓

Feature Selection

↓

Normalization

↓

Train/Test Split

↓

CNN Layer

↓

MaxPooling Layer

↓

LSTM Layer

↓

Dense Layer

↓

Softmax Output Layer

↓

Model Training

↓

Model Evaluation

↓

Prediction

↓

Confusion Matrix

↓

Classification Report

↓

Save Model

---



## Training Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |
| Batch Size | 32 |
| Epochs | 20 |
| Activation | ReLU, Softmax |

---

## Performance

### Test Accuracy

**93.17%**

The CNN-LSTM model successfully learned temporal patterns from sensor data and achieved excellent classification performance.

---

## Results

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

### Model Accuracy

![Model Accuracy](images/model_accuracy.png)

---

### Model Loss

![Model Loss](images/model_loss.png)

---


---


## Required Libraries

```
tensorflow
numpy
pandas
matplotlib
scikit-learn
```


---

## Running the Project

1. Download the dataset.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Update the dataset path.
4. Run all cells.
5. The notebook will:
   - Preprocess the data
   - Normalize the features
   - Train the CNN-LSTM model
   - Evaluate the model
   - Generate graphs
   - Save the trained model

---

## Saved Files

After execution, the following files are generated:

- har_cnn_lstm_model.keras
- confusion_matrix.png
- model_accuracy.png
- model_loss.png

---

## Future Improvements

- Real-time activity recognition
- Mobile application deployment
- Support for additional human activities
- Model optimization for embedded devices
- Integration with wearable sensors

---

## Author

**Pavan Kumar Vasa**

B.Tech Student

Human Activity Recognition using Deep Learning Project

---

