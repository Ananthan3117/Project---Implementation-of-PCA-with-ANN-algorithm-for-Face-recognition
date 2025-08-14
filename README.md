# Implementation of PCA with ANN algorithm for Face recognition

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A machine learning project for **face recognition** using **Principal Component Analysis (PCA)** for dimensionality reduction and **Artificial Neural Networks (ANN)** for classification.

---

##  Features
- **PCA** for extracting principal components from face images.
- **ANN** for classifying faces into different identities.
- **Face reconstruction demo** to visualize PCA performance.
- **Confusion matrix** to evaluate classification results.

---

##  Results

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### PCA Face Reconstruction Demo
![PCA Reconstruction](pca_reconstruction.png)

---

##  Project Structure
```
Project/
│-- Project.ipynb               # Main Jupyter Notebook
│-- requirements.txt            # Dependencies
│-- LICENSE                      # MIT License
│-- README.md                    # Project Documentation
│-- images/                      # Output images (confusion matrix, PCA reconstruction)
```

---

##  Installation

1️. Clone this repository:
```bash
git clone https://github.com/yourusername/face-recognition-pca-ann.git
cd face-recognition-pca-ann
```

2️. Install dependencies:
```bash
pip install -r requirements.txt
```

️3. Run the Jupyter Notebook:
```bash
jupyter notebook Project.ipynb
```

---

##  How It Works
1. **Data Preprocessing**: Load and normalize grayscale face images.
2. **PCA Transformation**: Reduce dimensionality while retaining important features.
3. **ANN Training**: Train a neural network on the PCA-reduced dataset.
4. **Evaluation**: Visualize confusion matrix and reconstruction results.

---

##  License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

##  Author
**Ananthakrishnan A L**  
ananthan31117@gmail.com  
[GitHub Profile](https://github.com/yourusername)
