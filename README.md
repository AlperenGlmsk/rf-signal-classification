# RF Signal Classification Using Spectrogram-Based Semantic Segmentation

This project focuses on **classifying Radio Frequency (RF) signals** by leveraging **spectrogram-based semantic segmentation** and deep learning architectures. The main objective is to **differentiate between various RF signal types** using visual representations of the signals in the time–frequency domain.

---

## 📌 Overview

1. **Signal Representation**  
   - Raw RF signals are converted into **spectrogram images** to capture both temporal and frequency features.  
   - These spectrograms serve as input to semantic segmentation models, enabling the extraction of discriminative spectral patterns.

2. **Models Used**  
   - **ResNet-18**  
   - **ResNet-50**  
   - **MobileNetV2**  
   Each model was trained and tested to evaluate performance on the classification task.

3. **Methodology**  
   - **Preprocessing**: Signal normalization and spectrogram generation.  
   - **Semantic Segmentation**: Highlights important spectral regions.  
   - **Feature Extraction**: Using pre-trained CNN backbones (transfer learning).  
   - **Classification**: Predicts the corresponding RF signal type.

4. **Key Features**  
   - End-to-end MATLAB implementation.  
   - Supports multiple CNN architectures for comparison.  
   - Modular code for easy experimentation with different datasets and models.

---

## 🧪 Results
- Models were compared in terms of **accuracy, precision, recall, and F1-score**.  
- **ResNet-50** achieved the highest overall classification accuracy.  
- **MobileNetV2** provided the best speed–performance trade-off.

---

## 🚀 Technologies & Tools
- **MATLAB** (Deep Learning Toolbox)  
- **Spectrogram Analysis**  
- **Transfer Learning with CNNs**

---

