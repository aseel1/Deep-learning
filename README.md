# 🚀 Deep Learning

A **comprehensive guide** covering all deep learning topics for exam preparation. This repository includes fundamental concepts, architectures, optimization techniques, and advanced topics like **Transformers & Attention Mechanisms**.

---

## 📌 Topics Covered

### **1️⃣ Introduction to Deep Learning**
- Definition and importance of deep learning.
- Difference between deep learning and traditional machine learning.
- Neural networks: structure and components (neurons, layers, activation functions).

---

### **2️⃣ Activation Functions & Non-linearity**
- **Sigmoid Function**: Issues with vanishing gradient.
- **Tanh Function**: Zero-centered but still suffers from vanishing gradients.
- **ReLU (Rectified Linear Unit)**: Solves vanishing gradient but may have **dying ReLU** issue.
- **Leaky ReLU, ELU, GELU**: Variations of ReLU for better performance.

---

### **3️⃣ Cost Functions & Loss Functions**
- **Binary Cross-Entropy**: For binary classification.
- **Categorical Cross-Entropy**: For multi-class classification.
- **Mean Squared Error (MSE)**: For regression tasks.
- **Log-Likelihood Loss**: Connection to cross-entropy.

---

### **4️⃣ Backpropagation & Gradient Descent**
- **Chain Rule in Backpropagation**.
- **Vanishing & Exploding Gradients**:
  - Small gradients → No learning in early layers.
  - Large gradients → Unstable updates.
- **Solutions**:
  - ReLU Activation.
  - Batch Normalization.
  - Xavier & He Initialization.

---

### **5️⃣ Optimization Algorithms**
- **SGD (Stochastic Gradient Descent)**: Basic optimization method.
- **Momentum**: Accelerates convergence.
- **AdaGrad, RMSProp**: Adaptive learning rates.
- **Adam Optimizer**: Combines **Momentum & RMSProp** for better convergence.

---

### **6️⃣ Regularization Techniques**
- **Early Stopping**: Stops training when validation loss increases.
- **Dropout**: Prevents overfitting by deactivating neurons randomly.
- **L2 Regularization (Weight Decay)**: Penalizes large weights.
- **Batch Normalization**: Stabilizes training & helps with vanishing gradient.

---

### **7️⃣ Convolutional Neural Networks (CNNs)**
- **Convolution Operations**: Feature extraction with filters.
- **Pooling Layers**:
  - Max Pooling (Preserves key features).
  - Average Pooling (Smooths feature maps).
- **Stride & Padding**:
  - **Stride > 1** reduces feature map size.
  - **Padding** preserves spatial dimensions.
- **Architectures**:
  - **Inception Network (GoogLeNet)**.
  - **ResNet (Residual Networks)**: Skip connections solve vanishing gradients.
  - **DenseNet**: Feature reuse via dense connections.

---

### **8️⃣ Advanced CNN Concepts**
- **1×1 Convolution**:
  - Reduces depth & transforms features.
- **Global Average Pooling (GAP)**:
  - Replaces fully connected layers, reducing overfitting.
- **Transposed Convolution (Deconvolution)**:
  - Used in **upsampling & segmentation tasks** (e.g., U-Net).

---

### **9️⃣ Recurrent Neural Networks (RNNs)**
- **Vanilla RNN**: Suffers from vanishing gradients.
- **LSTM (Long Short-Term Memory)**:
  - Solves vanishing gradient with **cell state & gating mechanisms**.
- **GRU (Gated Recurrent Unit)**:
  - Simplified LSTM with fewer parameters.

---

### **🔟 Sequence-to-Sequence & Attention**
- **Encoder-Decoder Models**:
  - Used in **machine translation & NLP tasks**.
- **Attention Mechanism**:
  - Allows model to **focus on relevant words** in a sequence.
- **Self-Attention & Transformers**:
  - **Multi-Head Attention**: Computes multiple attention scores.
  - **Positional Encoding**: Adds order information to sequences.

---

### **1️⃣1️⃣ Transformers & BERT**
- **Transformers**: Encoder-Decoder structure replacing RNNs.
- **BERT (Bidirectional Encoder Representations from Transformers)**:
  - Pretrained on massive text corpora.
  - Uses **masked language modeling (MLM)**.
- **GPT (Generative Pretrained Transformer)**:
  - Autoregressive model for text generation.

---

### **1️⃣2️⃣ Generative Models**
- **Autoencoders**: Learn compressed representations.
- **Variational Autoencoders (VAEs)**: Learn **probabilistic latent space**.
- **GANs (Generative Adversarial Networks)**:
  - **Generator vs. Discriminator** for realistic data generation.

---

### **1️⃣3️⃣ Self-Supervised Learning**
- **Difference between Generative & Self-Supervised Learning**:
  - **Generative Learning**: Models **data distribution**.
  - **Self-Supervised Learning**: Uses **pretext tasks** for feature learning.
- **Evaluation of Self-Supervised Learning**:
  - Train on **unlabeled data**.
  - Fine-tune on a **small labeled dataset**.

---

### **1️⃣4️⃣ Multi-Task Learning**
- Learning multiple objectives simultaneously.
- **Benefits**:
  - Improves **generalization**.
  - Reduces **overfitting**.
- **Examples**:
  - GPT (Text completion, translation, Q&A).
  - Self-driving cars (Object detection, lane recognition).

---



---

### 📢 Contributions & Feedback
If you find an error or have suggestions, feel free to **open an issue** or **submit a pull request**!  

🔥 **Happy Learning & Good Luck with Your Exam!** 🚀🎯  
