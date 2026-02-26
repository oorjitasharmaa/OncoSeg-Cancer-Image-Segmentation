# OncoSeg – Cancer Detection via Image Segmentation

## Project Overview
OncoSeg is a deep learning-based system that detects and segments cancer cell nuclei from histopathology images. The model performs instance segmentation and classification of nuclei into 19 tissue types using CNN-based architectures.

## Dataset
Cancer Instance Segmentation and Classification (Kaggle)
- ~200,000 labeled nuclei
- 19 cell types
- Instance-level segmentation masks

## Tech Stack
- Python
- TensorFlow / PyTorch
- OpenCV
- NumPy
- Streamlit (Deployment)

## Project Pipeline
- Data preprocessing & augmentation
- Instance segmentation using Mask R-CNN / U-Net
- CNN-based classification
- Model integration & evaluation

## Results
- Accurate nucleus segmentation with visual mask outputs
- Classification predictions with probability scores

## Future Scope
- Improve accuracy using attention-based models
- Deploy as real-time diagnostic support tool
