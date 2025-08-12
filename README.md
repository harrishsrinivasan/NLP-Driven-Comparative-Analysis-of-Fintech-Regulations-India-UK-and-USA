##  Overview
FinRegNLP is a Natural Language Processing (NLP) project that analyzes and compares fintech-related regulations across three major jurisdictions:
- **India** – The Payment and Settlement Systems Act, 2007  
- **UK** – Directive (EU) 2015/2366 (Payment Services Directive 2 - PSD2)  
- **USA** – Dodd-Frank Wall Street Reform and Consumer Protection Act  

This project uses NLP techniques to extract, preprocess, and analyze key similarities, differences, and themes in payment system regulations, consumer protection laws, and financial stability measures.

---

##  Features
- **Text Preprocessing** – Cleaning, tokenization, stopword removal, lemmatization.
- **Similarity Analysis** – TF-IDF vectorization + cosine similarity to measure regulatory text similarity.
- **Sentiment Analysis** – VADER sentiment scoring for tone assessment.
- **Topic Modeling** – LDA topic modeling to identify major thematic areas.
- **Visualization** – Graphs and plots to present similarity, sentiment, and topic trends.

---

##  Methodology
1. **Data Extraction** – Collected regulation texts in PDF format and extracted raw text.
2. **Preprocessing** – Standard NLP cleaning pipeline:  
   - Lowercasing  
   - Removing punctuation/numbers  
   - Tokenization  
   - Stopword removal  
   - Lemmatization  
3. **Similarity Analysis** – TF-IDF vectorization + cosine similarity to compare regulatory texts.  
4. **Sentiment Analysis** – Applied VADER to identify tone and stance in regulation text.  
5. **Topic Modeling** – Used Latent Dirichlet Allocation (LDA) to extract thematic clusters.  
6. **Visualization** – Created plots to visualize similarity scores, sentiment distribution, and topic frequency.

---

##  How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/FinRegNLP.git
