# Skin Disease Detection using Convolutional Neural Networks

## Overview
This project implements a deep learning-based approach to detect and classify skin diseases from images. Using Convolutional Neural Networks (CNNs), specifically the EfficientNetB2 architecture, the system analyzes skin lesion images to provide automated diagnosis assistance for 10 different types of skin conditions.

## Project Highlights
- Achieved 83.84% accuracy on the test dataset
- Utilizes EfficientNetB2 as the base model with optimized hyperparameters
- Implements comprehensive data preprocessing and augmentation techniques
- Classifies 10 different types of skin diseases

## Problem Statement
Skin diseases contribute 1.79% to the global disease burden. Timely and accurate diagnosis is critical to prevent progression and minimize impact on patients' quality of life. This project addresses the challenge by providing a reliable and efficient method for skin disease classification, which can assist dermatologists in making more precise decisions in clinical settings.

## Dataset
The model is trained on a dataset of skin disease images including:
1. Eczema
2. Melanoma
3. Atopic Dermatitis
4. Basal Cell Carcinoma (BCC)
5. Melanocytic Nevi (NV)
6. Benign Keratosis-like Lesions (BKL)
7. Psoriasis, Lichen Planus and related diseases
8. Seborrheic Keratoses and other Benign Tumors
9. Tinea Ringworm Candidiasis and other Fungal Infections
10. Warts Molluscum and other Viral Infections

## Methodology
### Data Preprocessing
- Image standardization (resizing, normalization)
- Data cleaning to remove outliers and improve quality

### Data Augmentation
To balance the dataset and improve model generalization, various augmentation techniques were applied:
- Flipping
- Rotation
- Zooming
- Brightness and contrast adjustments

### Model Architecture
- Base model: EfficientNetB2
- Fine-tuned hyperparameters:
  - Epochs: 10
  - Patience: 3
  - Learning rate: Optimized with early stopping
  - Batch size: Optimized for performance

### Model Evaluation
The model was evaluated using multiple metrics:
- Accuracy: 83.84% on the test dataset
- Precision, recall, and F1-score for each class
- Confusion matrix to visualize classification performance

## Results
The model achieved high performance across different skin disease classes, with particularly strong results for:
- Melanoma (Class 2): 100% recall, 0.97 F1-score
- Melanocytic Nevi (Class 5): 0.97 precision, 0.92 recall, 0.94 F1-score
- Basal Cell Carcinoma (Class 4): 0.94 precision, 0.85 recall, 0.89 F1-score

## System Requirements
### Hardware Requirements
- Processor: Intel Core i5 (minimum), Intel Core i3 (recommended)
- RAM: 4GB (minimum), 6GB (recommended)
- Hard Disk: 300GB (minimum), 400GB (recommended)
- GPU: 8GB (minimum), 12GB (recommended)

### Software Requirements
- Operating System: Windows
- Tool: Google Colaboratory
- Programming Language: Python
- Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Scikit-learn

## How to Use
1. Clone the repository
2. Upload the notebook to Google Colaboratory or run locally
3. Install required dependencies
4. Upload a skin lesion image
5. Run the prediction module to get the disease classification

## Conclusions
This system provides quicker results than prevailing systems, significantly reducing detection time. It can aid in early detection of skin diseases, which is critical for effective treatment and management. The high accuracy of 83.84% makes it a reliable tool for dermatological applications.

## Future Enhancements
- Multi-class classification: Expand to include more skin disease types
- Improved pre-processing techniques: Explore new methods to enhance image quality
- Transfer learning: Leverage pre-existing knowledge from pre-trained models to improve performance

## Authors
- Diksha Krishnan
- Aishwarya B
- Farhana Sabreen M

**Institution**: Meenakshi Sundararajan Engineering College, Chennai, India

## License
[Specify your preferred license for the project]
