# 📚 AI Semantic Plagiarism Checker – Internship Project (Task 1 & Task 2)

This is my submission for the **AI & ML Internship – June 2025**.  
The project detects plagiarism using **semantic sentence comparison** and analyzes the results with **EDA**, all within a single notebook.

---

## ✅ Task 1 – Plagiarism Detection using Sentence-BERT

- Compares two input documents at sentence level using **BERT embeddings**
- Uses **cosine similarity** to measure semantic closeness
- Flags sentences with similarity ≥ 0.75 as potential plagiarism

### 🔹 Input Files:
- `file1.txt`
- `file2.txt`

### 🔹 Output:
- `similarity_output.csv` → Contains matching sentences and similarity scores

---

## 📊 Task 2 – Exploratory Data Analysis (EDA)

This task uses the **same CSV file** (`similarity_output.csv`) generated in Task 1.

### 🔍 EDA Performed:
- Histogram of similarity scores
- Plagiarised vs non-plagiarised count
- Threshold tuning impact (e.g., 0.75 vs 0.6)

### 🧠 Key Insights:
- At 0.75 threshold → 0% plagiarism
- At 0.6 threshold → 100% plagiarism
- Strong paraphrasing detected

---

## 🗂️ Project Files
plagiarismchecker.ipynb # Single notebook for both tasks
├── file1.txt # First input document
├── file2.txt # Second input document
├── similarity_output.csv # Model output used in EDA
├── README.md # This file

yaml
Copy
Edit

---

## 🚀 Tech Stack

- Python
- Sentence-BERT (`sentence-transformers`)
- NLTK
- Pandas, Seaborn, Matplotlib
- Google Colab

---

## 🧠 How to Run

1. Open `plagiarismchecker.ipynb` in Google Colab
2. Upload `file1.txt` and `file2.txt`
3. Run all cells (model + EDA)
4. Review output and visualizations

---

## 👩‍💻 Author

Dhivyadharshini V – AI & ML Intern, June 2025  
🧩 Tasks Completed: Task 1 ✅ | Task 2 ✅  
📅 Using a single notebook to maintain full project continuity

---

## 📌 Status

> ✅ Ready for Task 3 – model deployment or dashboard


