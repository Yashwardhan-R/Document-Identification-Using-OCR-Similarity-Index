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

git clone https://github.com/ShaunakGodbole77/Document-Identification-using-OCR-and-Similarity-Index.git
cd Document-Identification-using-OCR-and-Similarity-Index


2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Update configuration (configs.py)

Choose similarity method: JACCARD, TFIDF, BERT, DOC2VEC, USE

Set paths to your document templates and input files

4️⃣ Run the main script
python Main.py


This will process provided sample documents and output identified matches.

📊 Example Usage
Input Document	Similarity Method	Result
test_paper_1	TF-IDF	Matched to model_ans.txt
Handwritten img	USE	High similarity, identified ✔

You can include your own document/test inputs in the test_ files to evaluate with real-world data.

🏆 Results

Accurate identification across multiple test samples

Flexible similarity pipelines to compare effectiveness

Supports both printed and handwritten documents


🤝 Contributing

Contributions are welcome!
Feel free to open an issue or submit a pull request to improve this project.

📜 License

This project is licensed under the GPL-3.0 License
.

📬 Contact

Yashwardhan Ramchaware
🔗 GitHub: Yashwardhan-R

