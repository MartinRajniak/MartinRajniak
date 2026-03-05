# 🧠 Machine Learning Experience Overview

## 📘 Strong ML Foundations – Self-driven Learning

### <ins>Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow – Aurélien Géron</ins>
Completed the entire book, including all exercises.

Gained a deeper understanding of ML concepts, tools, and practical patterns. The exercises — especially in deep learning, CNNs, and autoencoders — challenged me to go beyond the surface and develop genuine intuition for the tradeoffs involved.

[📖 Goodreads](https://www.goodreads.com/book/show/40363665-hands-on-machine-learning-with-scikit-learn-keras-and-tensorflow)

### <ins>Neural Network from Scratch – Andrej Karpathy (micrograd)</ins>
Implemented a full neural network and backpropagation engine from scratch following Karpathy's *"The spelled-out intro to neural networks and backpropagation: building micrograd"*.

Building every piece manually — forward pass, backward pass, gradient computation — gave me a foundational understanding of what frameworks like TensorFlow and PyTorch are actually doing under the hood.

[🎥 YouTube](https://www.youtube.com/watch?v=VMj-3S1tku0)

### <ins>IBM AI Engineering (Coursera)</ins>
5/13 courses completed

Solid introductory coverage of ML and DL topics. Transitioned to a more in-depth, hands-on approach via Géron's book and independent projects for deeper understanding.

[🎓 Coursera](https://www.coursera.org/professional-certificates/ai-engineer)

---

## 🧪 ML Projects – Practical Implementation

### <ins>Recall – Socratic AI Learning Tutor (Full-Stack Mobile App)</ins>
A production-grade mobile learning application that uses an LLM to guide users through book comprehension using the Socratic method — asking questions rather than giving answers.

- Engineered a Socratic prompting system for coherent multi-turn teaching conversations
- Implemented book-specific grounding to prevent hallucination and keep responses contextual
- Built a Kotlin Spring Boot REST API backend, deployed to GCP Cloud Run
- Used Supabase for PostgreSQL database and authentication
- Integrated Groq API for fast LLM inference
- Built the Android client in Jetpack Compose (Compose Multiplatform, targeting iOS as well)
- Built a Chrome extension for content extraction and data ingestion
- `Kotlin, Spring Boot, Jetpack Compose, Compose Multiplatform, GCP Cloud Run, Supabase, PostgreSQL, GroqAPI, LLM`

> 🚧 In progress – targeting release as a fully end-to-end shipped product

### <ins>Bean Disease Classification (Computer Vision) – End-to-End</ins>
Full end-to-end pipeline from training to mobile deployment.

- Trained a deep CNN (98% test accuracy) using transfer learning to classify diseases in bean plants
- Used data augmentation to compensate for a small dataset (~1k samples)
- Integrated **MLflow** for experiment tracking and **Apache Airflow** for workflow orchestration
- Deployed an optimised **TFLite** model to an Android app for real-time, offline inference
- Enabled **Dockerized Modal cloud GPU training** for scalable, serverless experimentation
- Built a **Flask REST API** for configurable model training and hyperparameter control
- `Keras, TensorFlow, TFDS, TFLite, MLflow, Airflow, Docker, Flask, HuggingFace, Android`

[GitHub](https://github.com/MartinRajniak/hands-on-ml-exercises/blob/main/14_deep_computer_vision_with_cnns/tensorflow_datasets/tfds_beans_disease_classification_transfer_learning.ipynb) | [🤗 Hugging Face](https://huggingface.co/martin-rajniak/beans_disease_classification_transfer_learning)

### <ins>Air Quality Prediction – Time-Series Forecasting (End-to-End)</ins>
Comparative forecasting study with a full MLOps setup.

- Compared ARIMA, Prophet, XGBoost, and LSTM models (best Willmott Index: 0.84)
- Applied recursive multi-step forecasting with rolling-window cross-validation
- Built a CI/CD pipeline with **GitHub Actions** and **Docker** for automated testing and builds
- `Python, Scikit-Learn, XGBoost, TensorFlow/LSTM, Prophet, statsmodels, Docker, GitHub Actions`

[GitHub](https://github.com/MartinRajniak/air-quality-prediction)

### <ins>Sudoku Solver with Deep CNNs</ins>
- Used **TFRecords** for efficient large-dataset loading and preprocessing
- Applied **curriculum (progressive) learning** — trained on easier puzzles first, gradually increasing difficulty
- Created a **custom loss function** and adapted the model architecture to enforce Sudoku rules
- Future work: Auto-Encoder architecture, multi-GPU training speedup
- `Keras, TensorFlow, TFRecords, Deep CNNs`

[GitHub](https://github.com/MartinRajniak/Sudoku-Solver)

### <ins>Variational Autoencoders (MNIST)</ins>
- Built a VAE to reconstruct and generate new MNIST digits
- Visualised the latent space for debugging and understanding representations
- Experimented with **Beta-VAE** based on paper reading and LLM consultation
- Defined custom metrics to reduce reliance on purely visual feedback during testing
- Future work: more structured latent space exploration
- `Keras, TensorFlow, VAE, Generative Models`

[GitHub](https://github.com/MartinRajniak/hands-on-ml-exercises/blob/main/17_autoencoders_gans_and_diffusion_models/11_variational_autoencoder_basic.ipynb)

### <ins>Audio Emotion Classifier</ins>
- Classified emotional tone from audio samples using spectral features and deep learning
- `TensorFlow, Audio Processing, Deep Learning`

### <ins>Titanic Survival Prediction (Kaggle)</ins>
- Focus on **feature engineering** — used decision trees to evaluate feature importance
- Compared multiple models with hyperparameter tuning
- `Scikit-Learn, DecisionTree, RandomForest`

[Kaggle](https://www.kaggle.com/competitions/titanic) | [GitHub](https://github.com/MartinRajniak/Kaggle-Projects/tree/main/Titanic)

### <ins>Kaggle Exploration</ins>
Occasional deep dives into interesting Kaggle notebooks — running, analysing, and tweaking existing solutions to understand techniques in context.

- *Map charting student math misunderstandings* – explored spatial charting and classification approaches

---

## ☁️ Cloud Engineering (Google Cloud Platform)

Hands-on experience with cloud-native development, Firebase integration, and serverless applications.

### <ins>Developing Applications with Google Cloud – Coursera Specialisation</ins>
Completed full specialisation.

[🎓 Coursera](https://www.coursera.org/specializations/developing-apps-gcp)

### <ins>Projects:</ins>
- Deployed Kotlin Spring Boot backend for **Recall** to **GCP Cloud Run**
- Developed Slack app ("Kudos Bot") using **Cloud Functions**
- Implemented referral system using **Cloud Functions**
- As a mobile developer, used **Firebase** (GCP) for analytics, A/B testing, and remote config

---

## 📱 Product & Team Leadership in ML Context

- **12 years** of experience building mobile applications and leading engineering teams
- Collaborated with ML researchers as a domain expert to design a **mobile release prediction model**
  - ML-assisted decision-making tool for release readiness based on streaming analytics
  - End-to-end involvement: data extraction → feature engineering → deployment
