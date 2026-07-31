# AI-ML Projects Repository

This repository contains **9 Artificial Intelligence and Machine Learning projects** developed as part of my AI-ML assignments and learning journey.

The projects cover a variety of concepts including **classification, deep learning, computer vision, reinforcement learning, recommendation systems, deployment, and Retrieval-Augmented Generation (RAG)**.

## 📚 Projects

| No. | Project                                  | Main Technique                     |
| --- | ---------------------------------------- | ---------------------------------- |
| 1   | Adult Census Income Classification       | Machine Learning Classification    |
| 2   | CIFAR-10 Image Classification using CNN  | Convolutional Neural Network       |
| 3   | Face Recognition using CNN (LFW Dataset) | CNN / Computer Vision              |
| 4   | Cancer Detection using MRI Images        | CNN / Medical Image Classification |
| 5   | Cart-Pole Reinforcement Learning         | Reinforcement Learning             |
| 6   | Lunar Lander Reinforcement Learning      | Reinforcement Learning             |
| 7   | Movie Recommendation System              | Recommendation System              |
| 8   | End-to-End Render Deployment Project     | Web App Deployment                 |
| 9   | RAG Chatbot (Capstone Project)           | NLP / RAG / Generative AI          |

---

# 1. Adult Census Income Classification

## 📌 Objective

The objective of this project is to predict whether a person's annual income is **greater than $50K or less than or equal to $50K** using demographic and employment-related information.

## 📊 Dataset

**Adult Census Income Dataset**

The dataset contains information such as:

* Age
* Workclass
* Education
* Marital Status
* Occupation
* Relationship
* Race
* Gender
* Capital Gain
* Capital Loss
* Hours Per Week
* Native Country

## 🤖 Machine Learning

This project uses a classification approach to predict the income category.

## 🔧 Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 📈 Output

The trained model predicts whether an individual belongs to:

* `<=50K`
* `>50K`

## 📂 Project Folder

`01_Adult_Census_Income_Classification`

---

# 2. CIFAR-10 Image Classification using CNN

## 📌 Objective

The objective of this project is to classify images into different object categories using a **Convolutional Neural Network (CNN)**.

## 📊 Dataset

**CIFAR-10 Dataset**

The dataset contains 10 classes:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

## 🤖 Model

**Convolutional Neural Network (CNN)**

## 🔧 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

## 📈 Output

The trained CNN predicts the category of an image from the 10 CIFAR-10 classes.

## 📂 Project Folder

`02_CIFAR10_Image_Classification_CNN`

---

# 3. Face Recognition using CNN (LFW Dataset)

## 📌 Objective

The objective of this project is to perform face recognition/classification using facial images from the **Labeled Faces in the Wild (LFW)** dataset.

## 📊 Dataset

**LFW (Labeled Faces in the Wild) Dataset**

The dataset contains facial images of different people.

## 🤖 Model

**Convolutional Neural Network (CNN)**

## 🔧 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 📈 Output

The CNN learns facial features from the images and predicts the corresponding person/class.

## 📂 Project Folder

`03_Face_Recognition_CNN_LFW`

---

# 4. Cancer Detection using MRI Images

## 📌 Objective

The objective of this project is to classify MRI images using deep learning techniques.

## 📊 Dataset

**MRI Cancer Image Dataset**

The dataset contains MRI images divided into training and testing data.

## 🤖 Model

**Convolutional Neural Network (CNN)**

## 🔧 Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* PIL
* Google Colab

## 📈 Output

The CNN learns visual patterns from MRI images and predicts the corresponding image class.

> **Note:** This project is developed for educational purposes and should not be used as a medical diagnostic system.

## 📂 Project Folder

`04_Cancer_Detection_MRI`

---

# 5. Cart-Pole Reinforcement Learning

## 📌 Objective

The objective of this project is to train a reinforcement learning agent to balance a pole on a moving cart.

## 🎮 Environment

**CartPole environment**

The agent interacts with the environment and learns by receiving rewards for maintaining the pole in a balanced position.

## 🤖 Technique

**Reinforcement Learning**

The project demonstrates:

* Environment interaction
* State observation
* Action selection
* Reward collection
* Learning through repeated episodes

## 🔧 Technologies

* Python
* Gymnasium
* NumPy
* Matplotlib
* Google Colab

## 📈 Output

The trained agent learns a policy that allows it to keep the pole balanced for as long as possible.

## 📂 Project Folder

`05_CartPole_Reinforcement_Learning`

---

# 6. Lunar Lander Reinforcement Learning

## 📌 Objective

The objective of this project is to train an agent to safely land a lunar lander in the target landing area.

## 🎮 Environment

**LunarLander environment**

The agent learns how to control the lander's movements using reinforcement learning.

## 🤖 Technique

**Reinforcement Learning**

The agent learns through:

* States
* Actions
* Rewards
* Episodes
* Environment interaction

## 🔧 Technologies

* Python
* Gymnasium
* Box2D
* NumPy
* Matplotlib
* Google Colab

## 📈 Output

The trained agent attempts to control the lander and achieve a successful landing.

## 📂 Project Folder

`06_Lunar_Lander_Reinforcement_Learning`

---

# 7. Movie Recommendation System

## 📌 Objective

The objective of this project is to recommend movies to users based on movie similarity and available movie information.

## 📊 Dataset

A movie dataset containing information such as:

* Movie titles
* Genres
* Keywords
* Cast
* Crew
* Other movie-related information

## 🤖 Technique

**Content-Based Recommendation**

The system compares movie features and recommends movies similar to the selected movie.

## 🔧 Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit (if used for interface)
* Google Colab

## 📈 Output

When a user selects a movie, the system recommends similar movies.

## 📂 Project Folder

`07_Movie_Recommendation_System`

---

# 8. End-to-End Render Deployment Project

## 📌 Objective

The objective of this project is to demonstrate the complete process of taking an application from development to deployment on **Render**.

## 🔄 Project Flow

```text
Development
     ↓
Python Application
     ↓
GitHub Repository
     ↓
Requirements File
     ↓
Render Deployment
     ↓
Live Web Application
```

## 🔧 Technologies

* Python
* Flask
* HTML
* CSS
* Git
* GitHub
* Render

## 🚀 Deployment

The application is connected to a GitHub repository and deployed using the Render platform.

## 📈 Output

The final application can be accessed through a live Render deployment URL.

## 📂 Project Folder

`08_End_to_End_Render_Deployment`

---

# 9. RAG Chatbot – Capstone Project

## 📌 Objective

The objective of this project is to build a chatbot that can retrieve information from a provided document and generate an answer using a language model.

## 🧠 What is RAG?

**RAG (Retrieval-Augmented Generation)** combines:

1. Document retrieval
2. Relevant information search
3. Language model generation

Instead of relying only on the model's existing knowledge, the chatbot retrieves relevant information from the provided documents before generating an answer.

## 🔄 Project Flow

```text
Document
   ↓
Text Extraction
   ↓
Text Chunking
   ↓
Embeddings
   ↓
Vector Database / Search
   ↓
Relevant Context
   ↓
Language Model
   ↓
Generated Answer
```

## 🤖 Technologies

* Python
* Transformers
* Sentence Transformers
* FAISS
* PyPDF
* PyTorch
* Google Colab

## 📈 Output

The chatbot answers questions using information retrieved from the uploaded document.

## 📂 Project Folder

`09_RAG_Chatbot_Capstone`

---

# 🛠️ Common Technologies Used

The projects in this repository use the following technologies:

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* PyTorch
* Transformers
* Sentence Transformers
* FAISS
* Gymnasium
* Flask
* GitHub
* Render
* Google Colab

---

# 📖 Machine Learning Concepts Covered

Through these projects, I practiced:

### Machine Learning

* Classification
* Feature preprocessing
* Model training
* Model evaluation

### Deep Learning

* Convolutional Neural Networks
* Image classification
* Face recognition

### Reinforcement Learning

* States
* Actions
* Rewards
* Episodes
* Environment interaction

### Recommendation Systems

* Content-based filtering
* Feature similarity

### NLP and Generative AI

* Text embeddings
* Semantic search
* Document retrieval
* Large Language Models
* Retrieval-Augmented Generation

### Deployment

* GitHub
* Requirements management
* Web application deployment
* Render

---

# ▶️ How to Run

Most of the machine learning and deep learning projects can be run using **Google Colab**.

## Step 1

Open Google Colab:

https://colab.research.google.com/

## Step 2

Open the required `.ipynb` notebook.

## Step 3

Install the required Python packages using:

```bash
pip install -r requirements.txt
```

## Step 4

Upload the required dataset when requested.

## Step 5

Run the notebook cells from top to bottom.

---

# 📂 Repository Structure

```text
AI-ML-Projects/
│
├── README.md
├── requirements.txt
│
├── 01_Adult_Census_Income_Classification/
│   └── project.ipynb
│
├── 02_CIFAR10_Image_Classification_CNN/
│   └── project.ipynb
│
├── 03_Face_Recognition_CNN_LFW/
│   └── project.ipynb
│
├── 04_Cancer_Detection_MRI/
│   └── project.ipynb
│
├── 05_CartPole_Reinforcement_Learning/
│   └── project.ipynb
│
├── 06_Lunar_Lander_Reinforcement_Learning/
│   └── project.ipynb
│
├── 07_Movie_Recommendation_System/
│   └── project.ipynb
│
├── 08_End_to_End_Render_Deployment/
│   └── project files
│
└── 09_RAG_Chatbot_Capstone/
    └── project.ipynb
```

---

# 🎯 Learning Outcomes

These projects helped me gain practical knowledge of:

* Data preprocessing
* Machine learning
* Deep learning
* Computer vision
* Reinforcement learning
* Recommendation systems
* Natural language processing
* Generative AI
* RAG systems
* GitHub
* Cloud deployment

---

# 👩‍💻 Author

**Bhumika**

Int.MTech – Cyber Security

AI-ML Projects – 2026

---

# ⭐ Conclusion

This repository contains nine practical AI-ML projects developed to understand and implement different Artificial Intelligence and Machine Learning concepts.

Each project focuses on a different real-world application, providing hands-on experience with data, models, training, evaluation, deployment, and AI systems.
