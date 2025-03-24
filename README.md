# 📰 NewsCred - Classification using LSTM, Bi-Directional LSTM & GRU-LSTM

This project presents a robust **Fake News Detection** system using **deep learning techniques**, leveraging **LSTM**, **Bi-Directional LSTM**, and a **GRU-LSTM architecture**. The focus was on effective text preprocessing (stemming and lemmatization), one-hot encoding, and embedding representation to classify news as **fake or real**.

---

## 📌 Key Features

- 🔠 Text Preprocessing with **Stemming** and **Lemmatization**
- 🧠 Models Used:
  - LSTM
  - Bi-Directional LSTM
  - GRU-LSTM (Hybrid)
- 🧮 **One-hot Encoding** of news titles
- 📚 Vocabulary size: `7000`
- 💡 Embedding Layer with output dimension: `100`
- ⏳ Fixed sequence length: `30` (with **Pre-Padding**)

---

## 📈 Model Performance

### 🔍 Accuracy (Using **Stemming**):

| Model              | Accuracy   |
|-------------------|------------|
| LSTM               | 91.5%      |
| Bi-Directional LSTM| 91.63%     |
| GRU-LSTM           | 89.75%     |

### 🔍 Accuracy (Using **Lemmatization**):

| Model              | Accuracy   |
|-------------------|------------|
| LSTM               | 89.0%      |
| Bi-Directional LSTM| 90.38%     |
| GRU-LSTM           | 89.38%     |

---

## ✅ Conclusion
This project demonstrates the effectiveness of deep learning approaches in tackling the fake news classification problem. Among the tested models, Bi-Directional LSTM consistently performed best, slightly outperforming traditional LSTM and GRU-LSTM architectures. Incorporating text preprocessing techniques like stemming and lemmatization, along with embedding-based representation, significantly enhanced model accuracy. The results underscore the importance of combining proper linguistic preprocessing with advanced sequence models for better classification outcomes. Future improvements can explore attention mechanisms, transformers, or hybrid ensemble methods to push performance further.

## ⚙️ Python Libraries Used

- Python
- TensorFlow / Keras
- NLTK (for stemming and lemmatization)
- NumPy, Pandas
- Seaborn, Matplotlib

## Data source: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data

