# Transfer Learning Image Classification  
**Implemented by Luluh Almogbil**

This project explores how to use **transfer learning** with a pre-trained **ResNet-18** model to classify natural scene images. The model is adapted to identify six categories: **buildings, forest, glacier, mountain, sea, and street**. The dataset is from Kaggle and provides a great way to practice real-world image classification.

Dataset link:  
🔗 https://www.kaggle.com/datasets/puneet6060/intel-image-classification

---

## What the Project Covers

- Image loading, preprocessing, and augmentation  
- Using ResNet-18 as a **feature extractor**  
- Fine-tuning the full model for better accuracy  
- Comparing both training strategies  
- Exporting the trained model to **ONNX**  
- Running predictions on custom images  

---

## How to Run

You only need:

- Python 3.12  
- PyTorch + torchvision  
- onnxruntime (for ONNX inference)  
- Kaggle API (to download the dataset) 

Enjoy!