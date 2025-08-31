# Document-Identification-Using-OCR-Similarity-Index

## 📌 Overview
A Python-based system that identifies handwritten or typed documents through **Optical Character Recognition (OCR)** and **content similarity comparison** using multiple techniques.  
It supports various matching strategies to pinpoint the document identity based on textual content.

---

## ✨ Key Features
- **OCR Extraction**: Converts scanned or handwritten documents into text using Tesseract or custom OCR models.  
- **Multi-Strategy Similarity Matching**: Supports **Jaccard, TF-IDF, BERT, Doc2Vec, and Universal Sentence Encoder (USE)** for computing similarity.  
- **Configurable Workflow**: Easily swap similarity algorithms via `configs.py`.  
- **Model Training & Inference**: Train custom models or use off-the-shelf for text-based similarity.  
- **Demo Visualization**: Includes sample inputs and output samples for quick testing and validation.  

---

## 🛠 Tech Stack
- **OCR**: Tesseract OCR  
- **Text Processing**: Python (`NLTK`, `scikit-learn`, `transformers`)  
- **Similarity Engines**: Jaccard, TF-IDF, Doc2Vec, BERT, USE  
- **Project Management**: Modular Python files (`train.py`, `process_*.py`, `Main.py`)  
- **Configuration**: `configs.py` for easy parameter adjustments  

---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/ShaunakGodbole77/Document-Identification-using-OCR-and-Similarity-Index.git
cd Document-Identification-using-OCR-and-Similarity-Index

