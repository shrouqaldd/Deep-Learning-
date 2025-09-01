# Deep Learning Projects  

*A collection of deep learning projects using TensorFlow and Keras for computer vision and medical diagnostics.*  

---


### 1. Face Mask Detection using CNN  
A Convolutional Neural Network (CNN) trained to classify whether a person is wearing a face mask or not.  

- **Dataset**: [Kaggle – Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)  
- **Classes**: With Mask / Without Mask  
- **Methodology**:  
  - Images resized to **128×128** and normalized.  
  - CNN with Conv2D, MaxPooling, Dropout layers.  
  - Optimizer: Adam, Loss: Sparse Categorical Crossentropy.  
- **Results**:  
  - **Test Accuracy**: ~94%  
  - High precision & recall for both classes.  
- **Applications**: Public health monitoring and compliance checking.  

---

### 2. Breast Cancer Classification (Benign vs Malignant)  
A deep learning model to classify breast cancer tumors as benign or malignant using numerical clinical features.  

- **Dataset**: [Breast Cancer Wisconsin Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)) (via scikit-learn).  
- **Features**: 30 attributes from cell nucleus measurements.  
- **Methodology**:  
  - Preprocessing with standard scaling.  
  - Dense neural network with hidden layers and ReLU activations.  
  - Evaluation with confusion matrix, classification report, and ROC curve.  
- **Results**:  
  - **Accuracy**: ~97%  
  - Strong precision and recall, especially for malignant detection.  
- **Applications**: Early cancer detection support (research purpose only).  

---

🛠️ Tech Stack

Frameworks: TensorFlow, Keras, Scikit-learn

Techniques: CNNs, Dense Neural Networks

Tools: Kaggle Datasets, Matplotlib, Seaborn

📌 Disclaimer

These projects are developed for educational and research purposes only and are not intended for clinical or medical decision-making.
