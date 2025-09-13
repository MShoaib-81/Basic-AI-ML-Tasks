# Spam vs Ham Text Classification

This project classifies SMS messages into **Spam** or **Ham** using three approaches:

1. TF-IDF + Logistic Regression  
2. Bag of Words (BoW) + Naive Bayes  
3. Deep Learning (LSTM + Embeddings)

---

## Dataset
The dataset used is the **SMS Spam Collection Dataset**, containing labeled SMS messages.

---

## Results

- **TF-IDF + Logistic Regression**: Accuracy ~96%  
- **BoW + Naive Bayes**: Accuracy ~98% (best performance)  
- **LSTM + Embeddings**: Accuracy ~87%, struggled with spam detection  

---

## Insights
- Naive Bayes with BoW worked best on this dataset.  
- Logistic Regression with TF-IDF was also reliable.  
- LSTM underperformed due to limited dataset size.  
- Word clouds showed spam-heavy words (*win, free, urgent*) vs casual ham words (*ok, see, later*).

---

## Future Work
- Try advanced models like **BERT / Transformers**.  
- Deploy as a **web app (Streamlit/Flask)**.  
- Use larger datasets for better LSTM performance.

---

## How to Run
1. Install requirements:
   ```bash
   pip install -r requirements.txt
