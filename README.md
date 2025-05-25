# 📌 Machine Learning Fundamentals

A complete ML learning journey from fundamentals to deep learning, with **interactive HTML guides** that explain every notebook in plain language with school-friendly analogies.

> **💡 Click the "View Explanation" links below to see beautiful, interactive HTML pages that break down each notebook concept by concept.**

---

## 📚 Overview

| #   | Notebook                       | Topics                                                                                      | Explanation                                                                                                                                                      |
| --- | ------------------------------ | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | `machine-learning-part1.ipynb` | Supervised/Unsupervised/RL, California Housing, K-Means, Q-Learning, ML Pipeline            | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part1-explained.html) |
| 2   | `machine-learning-part2.ipynb` | Linear/Polynomial Regression, MSE/RMSE/R², Cross-Validation, Bias-Variance, Ridge/Lasso     | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part2-explained.html) |
| 3   | `machine-learning-part3.ipynb` | Logistic Regression, Decision Trees, SVM, Ensembles (RF, XGBoost), ROC/AUC, Class Imbalance | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part3-explained.html) |
| 4   | `machine-learning-part4.ipynb` | Perceptrons, Backpropagation, Activation Functions, Keras/TF, CNNs, RNNs, Optimizers        | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part4-explained.html) |
| 5   | `machine-learning-part5.ipynb` | Advanced CNNs (VGG/ResNet), Transfer Learning, Data Augmentation, YOLO, Segmentation, Pose  | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part5-explained.html) |
| 6   | `machine-learning-part6.ipynb` | Generative AI, Stable Diffusion, LLMs/Transformers, Text-to-Audio, Super-Resolution         | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Roadmap/blob/main/Explanations/ml-part6-explained.html) |

---

## 📖 What's Inside Each Explanation

Every HTML page features:

- **Expandable accordion sections** - click to explore each topic
- **School-friendly analogies** - every concept explained with everyday comparisons
- **Color-coded callouts** - key points, warnings, analogies, and info boxes
- **Comparison tables** - side-by-side model/technique breakdowns
- **Actual results** - real accuracy numbers and metrics from the notebooks

---

## 📌 What's Covered

### Part 1 - ML Fundamentals & Core Concepts

- **Linear Regression** on California Housing dataset (EDA, correlation heatmap, train/test split, evaluation metrics, residual analysis, learning curves)
- **Unsupervised Learning**: K-Means customer segmentation on synthetic data (elbow method, cluster visualization)
- **Reinforcement Learning**: Q-Learning grid world navigation (reward curves, policy visualization, state visits, animated trajectories)
- **Features & Labels** with Wine classification using Random Forest (100% test accuracy)
- **Complete ML Pipeline**: Data loading → EDA → splitting → scaling → training → evaluation
- **Underfitting vs Overfitting**: Polynomial degree comparison (degree 1, 5, 15) on synthetic sine data
- **Data Handling**: Loading, EDA, and preprocessing on synthetic customer data (missing value imputation, outlier removal via IQR, feature scaling, categorical encoding)

### Part 2 - Regression, Classification & Regularization

- **Simple Linear Regression** - CO2 emissions from engine size (R² = 0.76)
- **Multivariable Linear Regression** - CO2 from 6 vehicle features (R² = 0.90)
- **Linear Regression Assumptions** - visual examples of linearity, homoscedasticity, normality (good vs violated)
- **Comprehensive CO2 Analysis** - EDA, VIF multicollinearity check, OLS vs Ridge vs Lasso vs ElasticNet comparison, feature importance, residual diagnostics
- **Polynomial Regression** - capturing non-linear relationships, degree comparison (underfitting → good fit → overfitting)
- **Evaluation Metrics Deep Dive** - MSE, RMSE, MAE, R², Adjusted R² across normal, outlier, and heteroscedastic datasets
- **Company Profit Prediction** - linear vs polynomial regression on 1000 Companies dataset (R² = 0.98)
- **Logistic Regression** - sigmoid function, binary classification on Iris, multi-class decision boundaries
- **Decision Trees** - Iris classification with decision boundary visualization
- **Wine Quality Classification** - multi-class on UCI Red Wine dataset with detailed classification reports
- **Bias-Variance Tradeoff** - training on 50 random datasets to decompose bias², variance, and irreducible error
- **Regularization** - Ridge (L2), Lasso (L1), ElasticNet with alpha tuning via GridSearchCV
- **Model Saving/Loading** with `joblib`

### Part 3 - Classification Algorithms & Ensemble Methods

- **Logistic Regression** - binary (Breast Cancer 94.7%), multiclass (Wine 94.4%, Iris 97.4%, Digits 96.0%), sigmoid function, multinomial extension
- **Titanic Survival Prediction** - full project: missing data handling, feature encoding, StandardScaler, stratified split, ~80% accuracy (sex as strongest predictor)
- **Decision Trees** — entropy vs Gini impurity, information gain, pruning strategies (max_depth, min_samples_split/leaf), feature importance, decision path tracing
- **Support Vector Machines** - maximum margin, support vectors, C parameter (regularization), gamma parameter, kernel trick (linear, RBF, polynomial), GridSearchCV hyperparameter tuning, scaling sensitivity
- **Random Forest** - bagging, bootstrap sampling, out-of-bag (OOB) score, max_features impact on diversity, feature importance
- **AdaBoost** - sequential boosting, sample weight evolution, estimator weights, margin analysis, staged predictions
- **Gradient Boosting** - residual fitting, learning rate vs n_estimators tradeoff, partial dependence plots, stochastic gradient boosting
- **XGBoost** - L1/L2 regularization, column subsampling, early stopping, evaluation history, feature importance by gain
- **Performance Evaluation** - confusion matrix (TP/TN/FP/FN), precision, recall, F1-score, ROC curves, AUC scores, precision-recall curves, threshold analysis
- **Class Imbalance Handling** - class weights, SMOTE (synthetic minority oversampling), Balanced Random Forest - all methods boosting minority recall from ~0% to 95–100%
- **German Credit Risk Project** - real-world dataset (1,000 customers), ColumnTransformer pipeline, 4-model comparison (Logistic Regression, Decision Tree, SVM, Random Forest)

### Part 4 - Neural Networks & Deep Learning

- **Perceptron** - linear separability, perceptron learning rule, XOR problem (perceptron fails at 50%)
- **Multi-Layer Perceptron (MLP)** - hidden layers solve XOR (100% accuracy), Universal Approximation Theorem, from-scratch NumPy implementation
- **Backpropagation** - forward pass, backward pass, chain rule, gradient computation, DetailedNN class with [2,8,4,1] architecture, gradient magnitude visualization, activation distributions
- **Activation Functions** - Sigmoid, Tanh, ReLU, Leaky ReLU, Swish, GELU - properties comparison, vanishing gradient problem, dead neuron problem in ReLU
- **Keras/TensorFlow** - Sequential API, Digits classification (128→64→32 MLP), Dropout, EarlyStopping, ReduceLROnPlateau, softmax output, classification reports
- **Convolutional Neural Networks (CNNs)** - MNIST handwriting (28×28), Conv2D → BatchNorm → MaxPooling → Dropout architecture, data augmentation (ImageDataGenerator), feature map visualization, CNN vs MLP comparison
- **Recurrent Neural Networks (RNNs)** - synthetic time series prediction, 5 architectures compared: SimpleRNN, LSTM, GRU, Bidirectional LSTM, Stacked LSTM - performance vs complexity analysis
- **Optimizer Comparison** - SGD, SGD+Momentum, RMSprop, Adam, AdamW on California Housing regression - convergence speed and final performance
- **Regularization Techniques** - Baseline vs L2 vs Dropout vs BatchNormalization vs Combined - overfitting gap analysis, training stability, L2 strength sweep (0 → 1.0)

### Part 5 — Advanced CNNs & Computer Vision

- **VGG-Style Architecture** — simplified VGG on CIFAR-10 (3 blocks of double Conv2D + MaxPool, 64→128→256 filters), 61.7% test accuracy
- **ResNet-Style with Skip Connections** — residual blocks with identity shortcuts, BatchNorm, Add layers, 43.3% test accuracy (lightweight variant on small dataset)
- **Architecture Comparison** — VGG vs ResNet training curves, loss and accuracy side-by-side over 15 epochs
- **Transfer Learning (MobileNetV2)** — pre-trained on ImageNet (154 layers), frozen base + custom head (GlobalAvgPool → Dense(256) → Dropout → Softmax), CIFAR-10 images resized to 96×96, 61.5% test accuracy
- **Fine-Tuning** — unfreezing last 20 layers, recompiling with 10× smaller learning rate (1e-5), 63.0% accuracy (+1.5% improvement)
- **Data Augmentation** — ImageDataGenerator with rotation, shifts, flip, zoom; side-by-side comparison showing reduced overfitting gap with augmentation
- **ImageNet Classification** — ResNet50 pre-trained on 1,000 classes, top-5 predictions with confidence scores
- **Feature Map Visualization** — extracting and displaying 32 feature maps from the first convolutional layer to see what CNNs detect
- **YOLOv8 Object Detection** — pre-trained YOLOv8n (nano), detecting objects with bounding boxes and confidence scores (bus 86.8%, persons 81–86%)
- **YOLO on Video** — frame-by-frame detection on video files with annotated output
- **Webcam Real-Time Detection** — live YOLO detection from camera feed
- **Custom YOLO Training** — dataset structure (images/labels folders), YOLO label format, data.yaml config, training pipeline
- **Instance Segmentation** — YOLOv8n-seg producing pixel-level masks for each detected object
- **Pose Estimation** — YOLOv8n-pose detecting 17 body keypoints (nose, eyes, ears, shoulders, elbows, wrists, hips, knees, ankles)

### Part 6 — Generative AI & Large Language Models

- **Generative vs Discriminative** — discriminative models learn P(Y|X) for classification; generative models learn P(X) to create new content (images, text, audio)
- **Latent Space & Embeddings** — compressed representations where similar concepts cluster together; interpolation between latent codes produces smooth transitions; interactive 2D latent space visualization
- **Stable Diffusion** — forward diffusion (gradually add noise to images) and reverse diffusion (learn to denoise step-by-step for generation)
- **Stable Diffusion Components** — CLIP text encoder (77 tokens × 768 dim), U-Net denoiser (860M–2.6B params, cross-attention for text-to-image conditioning), VAE decoder (64×64×4 latent → 512×512×3 image, 48× compression)
- **Diffusion Parameters** — CFG scale (prompt adherence, sweet spot 7–10), sampling steps (20–30 optimal), sampling methods (PNDM, DDIM, DPM)
- **Transformer Architecture** — self-attention enables parallel processing and long-range dependencies; encoder-only (BERT), decoder-only (GPT/LLaMA), encoder-decoder (T5)
- **Attention Mechanism (Q, K, V)** — Query/Key similarity scores → softmax → weighted Value sum; multi-head attention (8–32 heads) learns diverse patterns (local context, long-range, semantic, syntactic)
- **Tokenization** — BPE/SentencePiece subword tokenization (~50K vocabulary), token IDs → embeddings (768–4096 dim) + positional encoding (sin/cos functions)
- **Autoregressive Generation** — predict one token at a time, append to input, repeat; causal masking ensures only past tokens are visible
- **Sampling Strategies** — greedy (deterministic), temperature (T<1 focused, T>1 random), top-k (filter unlikely tokens), top-p/nucleus (dynamic vocabulary, p=0.9 recommended), repetition penalty (1.1–1.2×); interactive temperature visualization
- **Text-to-Audio Pipeline** — text encoder → acoustic model (→ mel-spectrogram) → vocoder (→ waveform); Bark (transformer, 13 languages, music/SFX) vs MMS-TTS (Meta, 1,100+ languages)
- **Image Super-Resolution** — traditional bicubic (blurry) vs neural SR (learns to hallucinate realistic detail)
- **Real-ESRGAN Architecture (RRDB)** — Residual Dense Blocks with dense connections, local + global residual connections, PixelShuffle upsampling (2×→4×), GAN training for perceptual realism
- **Quality Metrics** — PSNR (pixel accuracy, 32+ dB excellent), SSIM (structural similarity, correlates with human perception)
- **Unified Concepts** — attention mechanisms, transformers, latent representations, and sampling/generation strategies connect Stable Diffusion, LLMs, TTS, and super-resolution

## 🗺️ Learning Path

```
Part 1: ML Fundamentals ──→ Part 2: Regression ──→ Part 3: Classification
                                                            │
Part 4: Deep Learning (Neural Networks, CNNs, RNNs) ◄──────┘
                        │
Part 5: Advanced CNNs, Transfer Learning, YOLO ◄────────────┘
                        │
Part 6: Generative AI, LLMs, Diffusion, TTS, SR ◄──────────┘

```

## ⚙️ Setup

```bash
# Clone the repo
git clone https://github.com/GamithaManawadu/Machine-Learning-Projects.git
cd Machine-Learning-Projects

# Create virtual environment
python -m venv .venv
source .venv/bin/activate        # Linux/Mac
.venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt
```
