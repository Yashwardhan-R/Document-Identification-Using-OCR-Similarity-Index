# Document-Identification-Using-OCR-Similarity-Index

Overview

A Python-based system that identifies handwritten or typed documents through Optical Character Recognition (OCR) and content similarity comparison using multiple techniques. It supports various matching strategies to pinpoint the document identity based on textual content.

Key Features

OCR Extraction: Converts scanned or handwritten documents into text using Tesseract or custom OCR models.

Multi-Strategy Similarity Matching: Supports Jaccard, TF-IDF, BERT, Doc2Vec, and Universal Sentence Encoder (USE) for computing similarity.

Configurable Workflow: Easily swap similarity algorithms via configs.py.

Model Training & Inference: Train custom models or use off-the-shelf for text-based similarity.

Demo Visualization: Includes sample inputs and output samples for quick testing and validation.

Tech Stack

OCR: Tesseract OCR

Text Processing: Python (libraries like NLTK, scikit-learn, or transformers)

Similarity Engines: Jaccard, TF-IDF, Doc2Vec, BERT, USE

Project Structure Management: Python modules (train.py, process_*.py, Main.py)

Configuration: configs.py for easy parameter adjustments

Getting Started
Step 1: Clone the repo
git clone https://github.com/ShaunakGodbole77/Document-Identification-using-OCR-and-Similarity-Index.git
cd Document-Identification-using-OCR-and-Similarity-Index

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Update configuration (configs.py)

Choose similarity method: JACCARD, TFIDF, BERT, DOC2VEC, USE

Set paths to your document templates and input files.

Step 4: Run the main testing script
python Main.py


This will process provided sample documents and output identified matches.

Example Usage
Input Document	Similarity Method	Result
test_paper_1	TF-IDF	Matched to model_ans.txt
Handwritten img	USE	High similarity score; identified correctly

Include your own document/test inputs in the test_ files to evaluate your models with real-world data.

Results

Accurate identification across test samples.

Flexible similarity pipelines to compare effectiveness.

Tools support both printed and handwritten documents.

Screenshots:




Contributing

Contributions are welcome! Feel free to suggest improvements or add new similarity methods.

License

This project is licensed under the GPL-3.0 License
.

Contact

Shaunak Godbole
GitHub: ShaunakGodbole77

Why This Works:

Clarity: Organizes content into intuitive sections.

Guidance: Walks users from setup to running and testing.

Visuals: Screen captures reinforce functionality.

Flexibility: Highlights configurable architecture and multiple algorithms.

Professionalism: Maintains clean formatting and standard README flow.

Let me know if you’d like a similar README for other projects!
