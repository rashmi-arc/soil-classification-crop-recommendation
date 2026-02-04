# Soil Classification Using MobileNetV2 for Crop Recommendation

## Overview
This project classifies soil images using MobileNetV2 and recommends crops based on predicted soil type.

## Dataset
Comprehensive Soil Classification Dataset (~6,286 images, 7 classes).

Classes:
- Alluvial_Soil
- Arid_Soil
- Black_Soil
- Laterite_Soil
- Mountain_Soil
- Red_Soil
- Yellow_Soil

## Model
- MobileNetV2 (Transfer Learning)
- Input size: 224x224
- Optimizer: Adam
- Loss: Categorical Crossentropy

## Results
- Training Accuracy: ~97%
- Validation Accuracy: ~81–83%
- Supports multi-image testing and automatic crop recommendation.

## How to Run
1. Open the notebook in Google Colab.
2. Run cells top to bottom.
3. Upload test images to `/content/test_images`.
4. Execute the multi-image prediction cell.

## Output
The system predicts soil type and recommends suitable crops for each input image.
