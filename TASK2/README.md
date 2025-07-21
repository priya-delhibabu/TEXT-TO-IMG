
# Task 2 – Text Embedding for Text-to-Image Generation

This project demonstrates how to preprocess text descriptions using Hugging Face's Transformers library. The tokenized and encoded representations (embeddings) of the input text are generated to serve as accurate inputs for a downstream **text-to-image** model.

## 🚀 Objective

To develop a software module that takes **textual descriptions** as input and transforms them into meaningful **tokenized and encoded embeddings**, ready to be fed into any **text-to-image model** for generating visuals.

## 📂 Folder Structure

```
Task2/
├── Task2_Embedding.ipynb   # Main Jupyter notebook for text preprocessing
├── requirements.txt                   # Required libraries
├── README.md                          # Project documentation
├── saved_model/                       # Tokenizer and model saved locally
│   ├── config.json
│   ├── tokenizer_config.json
│   ├── tokenizer.json
│   └── vocab.txt
```

## 🧠 Tools & Libraries Used

- Python
- Transformers (Hugging Face)
- Pre-trained model: distilbert-base-uncased
- Jupyter Notebook

## 🔧 How It Works

1. **Input**: User provides a sentence or a batch of sentences.
2. **Tokenization**: Text is split into tokens using a pre-trained tokenizer.
3. **Encoding**: Tokens are converted into numerical format suitable for model input.
4. **Embedding Output**: These numerical embeddings are printed and saved.
5. **Saving**: Tokenizer and model configuration are saved to `saved_model/`.

## 🛠️ Setup Instructions

1. Clone the repository or copy files to your local system.
2. Create and activate a virtual environment (optional but recommended).
3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the cells in `Task2_Embedding.ipynb`.

## ✅ Sample Output

```python
Tokenized Input:
{'input_ids': tensor([[101, 2023, 2003, 1037, 3435, 6251, 102]]), ...}

Encoded Representation Shape:
torch.Size([1, 7, 768])
```

## 📁 Model Saving

After execution, you will find the model and tokenizer saved under the `saved_model/` folder. These can be reused or integrated with any text-to-image generation system.

## 💡 Future Scope

- Integration with models like Stable Diffusion for full text-to-image synthesis.
- Adding a front-end for input and visual output.
- Batch processing of text inputs.

## 👤 Author

Created as part of the AI/ML Internship program under Task 2.
