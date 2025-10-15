# Fashion_Mnist_Classifier
This project implements a simple fully connected neural network (MLP) to classify grayscale clothing images from the Fashion-MNIST dataset using PyTorch.

---

## 🚀 Overview
- Dataset: Fashion-MNIST (10 clothing categories)
- Model: 3-layer fully connected neural network  
  - Input: 784 features (28×28)  
  - Hidden Layers: 256 → 128 neurons (ReLU activations)  
  - Output: 10 neurons (for 10 classes)
- Optimizer: Adam (lr = 0.001)  
- Loss Function: CrossEntropyLoss    
- Epochs: 8  
- Test Accuracy: ~88%

---

## 🧩 Improvements
- Added Dropout (0.3) to reduce overfitting.  
- Added Learning Rate Scheduler for smoother convergence.  
- Visualized Training Loss, Accuracy per Epoch, and Confusion Matrix.

---

## 📊 Results
| Metric | Value |
|--------|--------|
| Training Accuracy | ~91% |
| Test Accuracy | ~88% |
| Target | > 85% ✅ |

---

## 🖼️ Example Outputs
- Visualization of correct and incorrect predictions  
- Confusion matrix of 10 clothing categories  
- Accuracy and loss plots per epoch  

---

## 🧠 Conclusion
The model successfully classifies Fashion-MNIST images with high accuracy and demonstrates good generalization.  
Future work can include adding CNN layers or data augmentation to improve accuracy beyond 90%.

---

## ⚙️ Requirements
Make sure you have the following installed:
`bash
pip install torch torchvision torchaudio matplotlib scikit-learn

---
## Auther
Rana Walid Bishr
