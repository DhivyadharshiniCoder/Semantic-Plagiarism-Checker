# 🔍 Semantic Plagiarism Checker using Sentence-BERT

An AI-powered plagiarism detection tool that identifies both exact matches and reworded (paraphrased) content using Sentence-BERT.

---

## ✅ Internship Task 1 Completed

This project satisfies:
- ✔️ Custom dataset usage (`file1.txt`, `file2.txt`)
- ✔️ Text preprocessing (sentence tokenization)
- ✔️ AI model usage (Sentence-BERT)
- ✔️ Outputs matched sentence pairs with similarity scores

---

## 📁 Files
- `plagiarism_checker.ipynb` – Main Google Colab notebook
- `file1.txt`, `file2.txt` – Sample text files to compare
- `requirements.txt` – Required libraries
- `README.md` – Project description

---

## 🔧 Tools Used
- Python 3
- sentence-transformers
- Regex (for sentence splitting)
- Google Colab

---

## ⚙️ How It Works
1. Upload two documents (`.txt`)
2. Break each into sentences
3. Use Sentence-BERT to encode sentences
4. Compare using cosine similarity
5. Display sentence pairs with similarity > 0.75

---

## 📊 Output Example
Text 1: AI is transforming industries.

Text 2: Artificial Intelligence is changing how businesses operate.

Score: 0.82
