# 🧠 Advanced Data Augmentation & Keras Customization – Colab Series

Welcome to the official GitHub repository for my multi-part deep learning assignment. This project demonstrates:

- A variety of **data augmentation and regularization techniques** across domains.
- Implementation of **advanced Keras constructs**, from custom losses to optimizers.
- Each section is structured into multiple Colab notebooks.
- All code is **original** (not copied from hint notebooks) and carefully explained in the walkthrough videos.

---


## 🎥 Video Walkthroughs

Each Colab has been executed, explained, and narrated in a video walkthrough:

- 🔗 **[Part 1: Data Augmentation Walkthrough](https://youtu.be/dVxGXS4hH2o)**
- 🔗 **[Part 2: Advanced Keras Constructs Walkthrough](https://youtu.be/ojFC_MxTGEs)**

---

## ✅ Part 1: Data Augmentation & Generalization Techniques

### 📘 [1_regularization_and_callbacks.ipynb](https://colab.research.google.com/drive/1GdYzRRjaWEe6bOaesdKfE1JIN0ZeBNp5?usp=sharing)
> **Focus**: Fundamental regularization strategies and training callbacks.

- Implemented L1, L2 regularization
- Applied Dropout and Batch Normalization
- Used EarlyStopping and TensorBoard callbacks
- Showcased Monte Carlo Dropout for uncertainty estimation
- Demonstrated custom dropout and regularizer functions

---

### 📘 [2_image_augmentation_with_keras_cv.ipynb](https://colab.research.google.com/drive/1jLcn3uSHjHGraWmF4vngVohaU0Zo1eK6?usp=sharing)
> **Focus**: Modern image augmentation using KerasCV.

- Introduced KerasCV's `keras_cv.layers.*` augmentation layers
- Compared augmentations via A/B training performance
- Combined multiple augmentation layers for pipelines
- Visualized before/after augmentation examples
- Tracked training impact via TensorBoard

---

### 📘[3_multimodal_data_augmentation.ipynb](https://colab.research.google.com/drive/1W02Nq7yzWw1xN7Na3vkxQMFPfsigHdU1?usp=sharing)
> **Focus**: Augmenting diverse data types using modern libraries.

- **Image**: Used `AugLy` and custom image transformations
- **Text**: Demonstrated NLP augmentation with `nlpaug`
- **Time Series**: Added noise, scaling, and jittering
- **Tabular**: Feature perturbation and SMOTE-like strategies
- **Speech**: Applied tempo and pitch modifications
- **Document Images**: Distortions and geometric transformations

---

### 📘 [4_fastai_augmentation_demo.ipynb](https://colab.research.google.com/drive/1rNwnjC4QUmgg3vYyD5bHFjyD5VnLRw-8?usp=sharing)
> **Focus**: Leveraging FastAI's rich augmentation ecosystem.

- Showcased FastAI DataBlock API with built-in transforms
- Used `aug_transforms`, `resize`, and test-time augmentation (TTA)
- Compared results from training with and without augmentation
- Visualized live image augmentations and analyzed effects

---

## 🧪 Part 2: Advanced Keras Deep Learning Constructs

### 📘 [1_custom_layers_losses_metrics.ipynb](https://colab.research.google.com/drive/1Y4RrLLppCNAtYjlAgyb63Y-DQmNQl8lS?usp=sharing)
> **Focus**: Hands-on with custom objects in Keras.

- Built a **custom learning rate scheduler**
- Developed **custom dropout (MCAlphaDropout)** and **normalization**
- Created **custom loss function (HuberLoss)** and **custom metric (HuberMetric)**
- Applied **custom activation, initializer, regularizer, kernel constraint**
- Logged all metrics using TensorBoard

---

### 📘 [2_custom_models_optimizers_training_loop.ipynb](https://colab.research.google.com/drive/1ANo673I19A7KNk9L-l_MDkvsrz6xC1yG?usp=sharing)
> **Focus**: Full control with custom layers, models, and training logic.

- Built custom layers: `ExponentialLayer`, `MyDense`, `AddGaussianNoise`
- Implemented custom model blocks: `ResidualBlock`, `ResidualRegressor`
- Designed a **custom optimizer** (MyMomentumOptimizer)
- Wrote a **custom training loop** (eager execution with loss/grad tracking)
- Applied it all to **Fashion MNIST** and visualized progress with TensorBoard

---


## 📚 Resources & References

- [KerasCV Docs](https://keras.io/keras_cv/)
- [AugLy by Facebook Research](https://github.com/facebookresearch/AugLy)
- [FastAI Augmentations](https://github.com/fastai/fastbook)
- [nlpaug for Text Augmentation](https://github.com/makcedward/nlpaug)
- [TensorFlow Official Tutorials](https://www.tensorflow.org/tutorials)
- Inspiration: Aurelien Geron’s *Hands-On Machine Learning*

---
