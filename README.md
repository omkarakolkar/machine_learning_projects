# Machine Learning Projects

Welcome! 👋 This repository is a collection of small machine learning projects I'm building as I learn machine learning on my own. Each project includes a Google collab notebook with code, explanations, and results. The goal is to document my progress, practice key ML concepts, and gradually build a strong portfolio.

---

## 📂 Projects

### 1.Rock Mine prediction
- **Goal**: Predict weather it's a Rock or Mine based on sonar fequencies data.
- **Tech**: Logistic Regression
- **Dataset**: [UCI Sonar Dataset](https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks)

### 2.House price prediction
- **Goal**: Predict house prices based on various housing features like number of rooms, location, area, etc. 
- **Tech**: XGBRegressor, Mean Absolute Error (MAE), R2 score 
- **Dataset**: [Boston data set](http://lib.stat.cmu.edu/datasets/boston)

### 3. Fake News Detection
- **Goal:** Classify news articles as real or fake based on their title, source domain, and social media engagement (tweet count).
- **Tech:** Logistic Regression, TF-IDF Vectorization, OneHot Encoding, Stemming (NLTK), StandardScaler
- **Dataset** [FakeNewsNet dataset from Kaggle](https://www.kaggle.com/datasets/algord/fake-news)

### 4. Wine Quality Prediction
- **Goal:** Predict whether a red wine is of good quality (quality ≥ 7) based on physicochemical features.
- **Tech:** Random Forest Classifier
- **Dataset** [Wine quality red dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

### 5.Face Mask Detection  
- **Goal:** Classify images of people with and without face masks using a Convolutional Neural Network (CNN). 
- **Data Preprocessing:** Resized images to 224×224, normalized pixel values
- **Model:** Transfer learning with VGG16 (ImageNet). Replaced final layer with a sigmoid Dense layer for binary classification; froze convolutional layers.
- **Training:** Optimizer: Adam, Loss: Binary Crossentropy, Metrics: Accuracy, Epochs: 5, Batch size: 32.
- **Evaluation:** Monitored training and validation accuracy/loss curves. 
- **Tech:** TensorFlow/Keras, OpenCV
- **Dataset:** Dataset extracted from Kaggle face mask dataset 
---

## 🚧 In Progress

I'm still learning and improving. More projects and improvements will be added over time!

