# 📝 Case Deduplication using NLP

This project is a simple experiment to detect **duplicate cases** in text data using **Natural Language Processing (NLP)** techniques.  
It applies **TF-IDF** for feature extraction and **Cosine Similarity** to measure similarity between cases.

---

## 📂 Project Structure
- **CaseDuplicate.ipynb** → Main Jupyter Notebook with code and results.  
- **cases_expanded.csv** → Sample dataset used in the project.  
- **requirements.txt** → List of required Python libraries.  

---

## ⚙️ How it Works
1. **Data Preprocessing** → Clean Arabic text (remove diacritics, symbols, etc.)  
2. **Feature Extraction** → Convert text to numerical vectors using TF-IDF.  
3. **Similarity Calculation** → Compute similarity scores with Cosine Similarity.  
4. **Duplicate Detection** → Flag cases as duplicates if similarity > threshold.  
5. **Evaluation** → Precision@K and Recall@K to evaluate performance.  

---

## 🚀 How to Run
Clone this repo and install the requirements:
```bash
git clone https://github.com/Reemax990/case-duplication-nlp.git
cd case-duplication-nlp
pip install -r requirements.txt
