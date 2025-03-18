# IMDB Movie Review Sentiment Analysis with Simple RNN

This project implements a **Sentiment Analysis** model using a **Simple Recurrent Neural Network (RNN)** to classify IMDB movie reviews as either **positive** or **negative**. The model is designed to analyze user-submitted reviews and predict their sentiment with impressive accuracy.

The application is deployed using **Streamlit**, providing a clean and interactive interface where users can submit reviews and instantly receive a sentiment prediction. The underlying model has been trained on the widely recognized **IMDB Movie Review** dataset, ensuring its performance is well-suited for movie review sentiment analysis.

---

## 🚀 Features

- **Simple yet effective RNN architecture** designed for text data analysis.
- **Streamlit-based web app** for an intuitive and user-friendly experience.
- **Real-time sentiment prediction** for user-submitted reviews.
- Trained on the **IMDB Movie Review** dataset to ensure accuracy and reliability.

---

## 🛠️ Setup and Installation

To get started with the project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/NickBwalley/Simple-RNN-Sentiment-Analysis.git
cd Deep-Learning-For-NLP/Simple-RNN
```

### 2. Create a New Conda Environment

To maintain a clean environment for dependencies, it's recommended to create a new Conda environment:

```bash
conda create -n imdb_sentiment_env python=3.11.11
conda activate imdb_sentiment_env
```

### 3. Install Dependencies

All required libraries are listed in the `requirements.txt` file. Install them using the following command:

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

Once everything is set up, you can launch the Streamlit application with this command:

```bash
streamlit run main.py
```

---

## 📋 Usage Instructions

1. Open your browser and navigate to the displayed **localhost** URL (e.g., `http://localhost:8501`).
2. Enter your movie review in the provided text box.
3. Click the **"Classify"** button.
4. The app will classify your review as either `Sentiment`: **positive** or **negative** and the **Prediction score**.

---

## 🧠 Model Overview

- The model architecture is based on a **Simple RNN** with embedding layers to process text data efficiently.
- Trained using the **IMDB Movie Review** dataset, containing labeled movie reviews.
- The model is designed to handle typical sentiment-based language patterns found in movie reviews.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, please submit a pull request or open an issue.

---

## 📧 Contact

For questions or collaboration opportunities, please reach out at **[nickbiiybwalley@gmail.com](mailto:nickbiiybwalley@gmail.com)**.
