
# 📝 Text Summarization

## 📌 Objective
Create a system that summarizes lengthy articles, blogs, or news into concise summaries using both extractive and abstractive methods.

---

## 🗂 Dataset
- **CNN/Daily Mail Dataset**

---

## ⚙️ Steps Performed

### 1. Text Preprocessing
- Cleaned and tokenized input text.
- Removed unwanted characters and normalized formatting for accurate summarization.

### 2. Extractive Summarization
- Used **spaCy** to identify and extract the most relevant sentences.
- Generated summaries by selecting key parts of the text based on linguistic features.

### 3. Abstractive Summarization
- Loaded pre-trained models (like **BART**, **T5**) from HuggingFace Transformers.
- Generated concise summaries that rephrased the original content in a human-like way.

### 4. Real-World Testing
- Applied the summarization system to actual articles and blog posts.
- Evaluated summaries for readability, coherence, and informativeness.

---

## ✅ Outcome
- Developed a functional summarization system capable of producing:
  - **Extractive Summaries** (selecting key sentences)
  - **Abstractive Summaries** (generating human-like language)

---

## 🛠 Tools & Libraries Used
- Python
- spaCy
- HuggingFace Transformers
- Google Colab
- PyTorch

---

## 🏁 How to Run
1. Open the notebook in Google Colab.
2. Paste or load your article or text input.
3. Run extractive and abstractive summarization steps.
4. Review the generated summaries.
