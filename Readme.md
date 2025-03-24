# ﻿**🚀 Deep Learning with Depth-wise Separable Convolutions: CIFAR-10 Classification**

# **📌 Project Overview**

This project implements a **Convolutional Neural Network (CNN) architecture** utilizing **four dense blocks** with **depth-wise separable convolutions**. The model is trained and evaluated on the **CIFAR-10 dataset**, a widely used benchmark for image classification tasks.

**🔥 Key Features**

- **Depth-wise Separable Convolutions** for efficient computation
- **Four Dense Blocks** to enhance feature propagation
- **Trained on CIFAR-10** with 10 object categories
- **Performance Metrics**: Accuracy, Precision, Recall, F1-score
- **Comparative Study** of traditional vs. depth-wise separable convolutions
- **Training for 100+ epochs** or until convergence

**📊 Performance Evaluation**

The trained model is assessed using the following metrics: ✅ **Classification Accuracy**
✅ **Precision & Recall**
✅ **F1-score**
✅ **Computational Efficiency Analysis** (Traditional vs. Depth-wise convolutions)

# **🏗️ Model Architecture**

The CNN follows a hierarchical design: 1️⃣ **Depth-wise Convolutions** for spatial feature extraction
2️⃣ **Point-wise Convolutions** for dimensionality reduction
3️⃣ **Dense Blocks** to enhance feature reuse
4️⃣ **Global Average Pooling** instead of fully connected layers
5️⃣ **Softmax Output Layer** for classification

**📚 Dataset: CIFAR-10**

- 50,000 training images
- 10,000 test images
- 10 classes: Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

**📈 Training Strategy**

✔ **100+ epochs** (or until loss stabilizes)
✔ **Adaptive Learning Rate Scheduling**
✔ **Data Augmentation** for better generalization
✔ **Batch Normalization & Dropout** for stability

# **📂 Implementation**

The model implementation is provided in the Jupyter Notebook: **DepthWise-CIFAR.ipynb**.

# **🔍 Comparative Study: Traditional vs. Depth-wise Convolutions**

The project includes a **comparative analysis** of:

- **Computational efficiency** (FLOPs, latency, memory usage)
- **Model effectiveness** (accuracy, precision, recall, F1-score)

# **📜 Results & Insights**

📌 Depth-wise separable convolutions significantly **reduce computational cost** while maintaining high accuracy.
📌 The model generalizes well on CIFAR-10 with optimized hyperparameters.
📌 Training stabilizes around **100 epochs**, showing robust convergence.

![5](https://github.com/user-attachments/assets/57a647ad-3321-47a1-90fc-78763f689186)
![4](https://github.com/user-attachments/assets/4fb4649e-ae60-4dff-9447-09b57a6a257f)
![3](https://github.com/user-attachments/assets/7b957d2b-2b20-425c-bff1-f8938eff3f7d)
![2](https://github.com/user-attachments/assets/687ee8b2-5380-42cc-b2ae-6d2c0ee2ad78)
![1](https://github.com/user-attachments/assets/1b260c0f-fc82-4a98-bb18-1616d4399157)

