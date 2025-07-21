
# 🚀 TASK 1 — BERT Tokenization

## 📌 Objective
To demonstrate the use of the BERT tokenizer for natural language preprocessing using the Huggingface Transformers library. This task includes tokenizing sample input text, converting it into input IDs, and understanding how BERT prepares text for model consumption.

---

## 🧾 Files in This Folder

```
TASK1/
├── Task1_BERT_Tokenization.ipynb   # Jupyter notebook containing the implementation
├── requirement.txt                 # Python dependencies required for this task
├── saved_model/                    # Folder to store any saved models/tokenizers (if applicable)
└── README.md                       # This documentation file
```

---

## ⚙️ How to Run

### 1. Clone the repository (from root, once pushed to GitHub)
```bash
git clone https://github.com/your-username/nullclassproj.git
cd nullclassproj/TASK1
```

### 2. Install dependencies
```bash
pip install -r requirement.txt
```

### 3. Open and run the notebook
Launch Jupyter or use any IDE (VSCode, Colab, etc.) to open `Task1_BERT_Tokenization.ipynb`.

---

## 📌 What’s Covered in the Notebook?

- Load and initialize the BERT tokenizer
- Tokenize input text
- Convert tokens to input IDs
- Handle padding/truncation
- Visualize tokenized outputs

---

## ✅ Sample Output

The tokenizer converts sentences like:
```
"Transformers are amazing!"
```
into:
- Tokens: `[CLS]`, `transformers`, `are`, `amazing`, `!`, `[SEP]`
- Input IDs: `[101, 19081, 2024, 6429, 999, 102]`

---

## 📦 Dependencies

Listed in `requirement.txt`:
```
transformers
torch
```

You may add:
```
notebook
```
if running via Jupyter locally.

---

## ✍️ Author

This task is a part of the Nullclass Internship Project Submission.

---
