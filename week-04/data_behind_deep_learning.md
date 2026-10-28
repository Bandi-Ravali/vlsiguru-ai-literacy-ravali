# Mission 1: Data Behind Deep Learning

## Introduction

Data is the foundation of deep learning. A deep learning model learns patterns from examples rather than relying only on manually written rules. The quality, quantity and variety of the data influence how well the model performs.

Data can be collected in different forms, such as images, text, audio, video and sensor readings. Before a model can use this data, it must be prepared in a suitable format.

## Understanding Image Data

A digital image consists of pixels. Each pixel contains numerical information representing its colour or intensity.

For example, a grayscale image may represent each pixel using a value from 0 to 255:

- 0 represents black.
- 255 represents white.
- Values between 0 and 255 represent different shades of gray.

An RGB image uses three colour channels: red, green and blue. A computer processes these pixel values numerically.

## Data Preparation Process

```text
Raw Data Collection
        |
        v
Data Inspection
        |
        v
Data Cleaning
        |
        v
Data Preprocessing
(Resize, Normalize, Format)
        |
        v
Data Labelling
        |
        v
Dataset Splitting
   /      |       \
  v       v        v
Training Validation Testing
  Data     Data     Data
   |
   v
Model Training
   |
   v
Prediction and Evaluation
```

## Important Data Preparation Techniques

### 1. Data Cleaning

Data cleaning identifies and handles missing values, duplicate records, corrupted files and incorrect labels.

### 2. Data Preprocessing

Preprocessing transforms raw data into a format suitable for the model. For image data, this may include resizing images to a consistent shape and converting them into numerical arrays.

### 3. Normalization

Normalization scales numerical values to a suitable range. For example, pixel values from 0 to 255 can be divided by 255 to obtain values from 0 to 1.

### 4. Data Labelling

Labels provide the expected category or answer for each training example. For example, an image may be labelled as “defective” or “non-defective.”

Incorrect labels can teach a model misleading patterns.

### 5. Dataset Splitting

- **Training set:** Used to learn model parameters.
- **Validation set:** Used to compare configurations and tune the model during development.
- **Test set:** Used for final evaluation on data not used to train or tune the model.

## Common Data Problems

**Poor-quality data:** Blurred images, missing values or corrupted files can make learning difficult.

**Class imbalance:** A dataset may contain many examples of one category and very few of another. The model may then perform poorly on the less-represented category.

**Unrepresentative data:** If training data does not reflect real-world conditions, the model may not generalize well to new examples.

**Data leakage:** Information from the test set may accidentally influence training or model selection, making evaluation results misleading.

## Engineering Example

In semiconductor manufacturing, images of silicon wafers may contain different defect patterns. These images can be labelled and used to train a model to recognize possible defects. If the dataset contains too few examples of a particular defect, the model may fail to recognize it reliably.

## Conclusion

Deep learning depends on properly prepared, representative and correctly labelled data. Careful cleaning, preprocessing and dataset splitting help improve the reliability of model training and evaluation.

## Sources

1. Google for Developers — [Working with Numerical Data](https://developers.google.com/machine-learning/crash-course/numerical-data)
2. Google for Developers — [Datasets, Generalization and Overfitting](https://developers.google.com/machine-learning/crash-course/overfitting)
3. Google for Developers — [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
