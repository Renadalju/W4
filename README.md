#  Week 4: Weekly Project & Assignments

This repository contains my solutaions for **weekly project** and **weekly assignments**.

---

## Weekly Project: Transfer Learning for Image Classification

**Objective:**  
Apply **Transfer Learning** to an image classification task using a pretrained CNN and compare two training strategies.

**Model & Approach:**
- Pretrained **ResNet-18**
- Image classification using a labeled image dataset

**Training Strategies Implemented:**
1. **Feature Extraction**
   - Freeze the convolutional backbone
   - Train only the final fully connected layer

2. **Fine-Tuning**
   - Unfreeze the model layers
   - Train the full network for better performance

**Workflow:**
- Data loading and preprocessing
- Train/validation split
- Model training with both strategies
- Performance evaluation (loss & accuracy)
- Inference on custom images
- Saving trained models and checkpoints

The full implementation is available in:
- `W4/WeeklyProject`

---

## Weekly Assignments

This repository also includes solved **weekly assignments**, covering:

- **M1 Assignments**
- **M2 Assignments**
- **M4 Assignments**

Each assignment was solved following the course instructions, and each task was committed separately.

---

## Trained Models & Full Project Files

Due to size limitations, **all trained models** are uploaded to Google Drive:

 **Google Drive (models & full files):**  
https://drive.google.com/drive/folders/1V23sqfIcHKzgf3YIk1JB_fb3BbPOGRm0?usp=drive_link

This includes:
- Trained model checkpoints
- Saved weights for feature extraction and fine-tuning
- All Assignment Files and Project

---

##  Notes
- Commits are structured and separated per task/assignment
