## 🧠 Machine Learning Experience Overview

### 📘 Strong ML Foundations – Self-driven Learning

#### <ins>Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow – Aurélien Géron</ins>
Completed the entire book, including all exercises.

Gained a deeper understanding of the ML concepts and tools to get me started.
The work on exercises proved to be challenging enough to teach me some of the more advanced concepts.

[📖 Goodreads](https://www.goodreads.com/book/show/40363665-hands-on-machine-learning-with-scikit-learn-keras-and-tensorflow)

#### <ins>IBM AI Engineering (Coursera)</ins>
5/13 courses completed

Solid introductory coverage of ML and DL topics.
Transitioned to a more in-depth approach via Géron's book for hands-on experience and deeper understanding.

[🎓 Coursera](https://www.coursera.org/professional-certificates/ai-engineer)

---

### 🧪 ML Projects – Practical Implementation

#### <ins>Titanic (Kaggle Challenge)</ins>
- The biggest focus was on feature engineering (decision trees helped me to evaluate which features are important)
- Hyperparameter tuning (different models and parameters were compared)
- `Scikit-Learn, DecisionTree, RandomForest`

[Kaggle](https://www.kaggle.com/competitions/titanic) | [GitHub](https://github.com/MartinRajniak/Kaggle-Projects/tree/main/Titanic)

#### <ins>Beans Disease Classification (Computer Vision)</ins>
- Small dataset was a challenge - had to find the right data augmentation to create good representative samples,
- For the same reason, I used transfer learning - the challenge was to find the right model for the right balance of time vs performance,
- Had to make training deterministic to be able to assess improvements,
- `Keras, Tensorflow, Computer Vision, TFDS, Data Pipelines, HuggingFace`

[GitHub](https://github.com/MartinRajniak/hands-on-ml-exercises/blob/main/14_deep_computer_vision_with_cnns/tensorflow_datasets/tfds_beans_disease_classification_transfer_learning.ipynb) | [🤖 Hugging Face](https://huggingface.co/martin-rajniak/beans_disease_classification_transfer_learning)

#### <ins>Sudoku Solver with Deep CNNs</ins>
- Working with big data was a challenge - used TFRecords to speed up loading and preprocessing,
- Used curriculum(progressive) learning to train the model on easier puzzles first,
- Created custom loss function and adapted model architecture to adhere to Sudoku rules,
- Future work: test Auto-Encoder architecture, speed up training by using multiple GPUs,
- `Keras, Tensorflow, TFRecords, Deep CNNs`

[GitHub](https://github.com/MartinRajniak/Sudoku-Solver)

#### <ins>Variational Autoencoders (MNIST)</ins>
- Built a model to reconstruct and generate new images for the MNIST dataset,
- Visualised the latent space of VAEs for debugging,
- Had to find the correct metrics so I wouldn't have to rely purely on human feedback during testing,
- Read papers and consulted LLMs to try different approaches (e.g. Beta-VAE),
- future work: testing a more structured latent space

[GitHub](https://github.com/MartinRajniak/hands-on-ml-exercises/blob/main/17_autoencoders_gans_and_diffusion_models/11_variational_autoencoder_basic.ipynb)

---

### ☁️ Cloud Engineering (Google Cloud Platform)

Hands-on experience with cloud-native development, Firebase integration, and serverless applications.  

#### <ins>Developing Applications with Google Cloud – Coursera Specialisation</ins>
Completed full specialisation.

[🎓 Coursera](https://www.coursera.org/specializations/developing-apps-gcp)

#### <ins>Projects:</ins>
- Developed Slack app ("Kudos Bot") using Cloud Functions
- Implemented referral system using Cloud Functions
- As a mobile developer I used Firebase(GCP) for analytics, A/B testing, and remote config

---

### 📱 Product & Team Leadership in ML Context

- **12 years** of experience building mobile applications and leading engineering teams
- Collaborated with ML researchers as a domain expert and customer to design a **mobile release prediction model**
  - ML-assisted decision-making tool for release readiness based on streaming analytics
  - End-to-end involvement: data extraction → feature engineering → deployment
  
