### **1. Background on EMG Signal Processing**

- Overview of **EMG signals** and their physiological basis.
- Common preprocessing techniques: Noise removal, signal normalization, feature extraction (e.g., RMS, mean absolute value, power spectrum density).
- Challenges in EMG signal processing, such as signal variability, muscle crosstalk, and non-linearity.

---

### **2. Hand Tracking and Gesture Recognition Using EMG**

- Survey traditional methods for hand tracking using EMG signals.
- Highlight popular algorithms like Support Vector Machines (SVM), Decision Trees, and k-Nearest Neighbors (k-NN).
- Explore limitations of classical methods compared to modern deep learning approaches.

---

### **3. Machine Learning and Deep Learning in EMG Applications**

#### a. **LSTMs and Recurrent Neural Networks (RNNs)**

- Review studies leveraging LSTMs for time-series EMG data.
- Discuss their ability to capture temporal dependencies and their limitations (e.g., vanishing gradients, computational cost).

#### b. **Attention Mechanisms**

- Introduce the concept of attention in deep learning and its application to time-series data.
- Highlight any research where attention mechanisms have been applied to EMG for feature enhancement or better sequence modeling.

#### c. **KAN (Kolmogorov-Arnold Networks)**

- Explain the theoretical basis of KAN and their use in complex, non-linear modeling tasks.
- Identify gaps in literature about KAN applied to bio-signals like EMG.

#### d. **Other Advanced Models**

- Brief mention of transformers, CNNs, or hybrid models (e.g., CNN-LSTM) used in EMG signal classification or regression tasks.

---

### **4. Feature Extraction and Dimensionality Reduction Techniques**

- Survey the feature extraction methods used with EMG signals (e.g., time-domain, frequency-domain, and time-frequency features).
- Review dimensionality reduction methods like PCA, t-SNE, or deep autoencoders for improving computational efficiency.

---

### **5. Applications in Real-Time Systems**

- Discuss systems that use EMG-based tracking for prosthetics control, gaming, or robotic interfaces.
- Review studies focusing on real-time performance, latency, and accuracy challenges.

---

### **6. Evaluation Metrics and Benchmarks**

- Overview of common evaluation metrics (e.g., accuracy, F1 score, RMSE for regression, classification latency).
- Discuss existing datasets and benchmarks used in the field, such as Ninapro or BioPatRec.

---

### **7. Gaps and Opportunities**

- Summarize gaps in the current literature:
    - Limited use of advanced neural networks (KAN, transformers) for EMG.
    - Challenges in real-time implementation with low latency.
    - Scarcity of large, labeled EMG datasets for robust training.
- Emphasize how your approach (e.g., KAN or attention mechanisms) can address these gaps.

---

### **8. Conclusion**

- Reiterate the importance of exploring advanced models like KAN or attention mechanisms for EMG-based hand tracking.
- Highlight how your research aligns with or builds upon the existing body of work.


# Notes

There are many papers that classify motions, even using attention and a one with KAN.

There are also existing datasets for the classification task.

But a few papers implement a continous tracking, moreover no papers with developing into KANs and attention mechanics are found.

There are no found continuous tracking datasets.

A good thing to consider is EMD.

A good thing to consider is dynamic adoptation of model to a person (maybe research this way).

A good thing to consider is using convolution.

need to determine the minimal number of channels,

how to best place the electrodes,

what is the minimal sampling rate,

what filters to apply to signal,

what features to extract,

what dimensionality reduction to use (maybe not to use if using KANs),

how to best get the ground truth of hand pose