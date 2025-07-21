# Task 3
This project generates images from text prompts using a text-to-image model.
Objective
To develop a complete pipeline that generates images from text using:

Pretrained NLP models (like BERT) for text embeddings

GAN-based architecture for image generation

Components
Text Preprocessing – Tokenizing and encoding text

Embedding Generation – Using Hugging Face Transformers to convert text to embeddings

Image Generation – Feeding embeddings into a GAN model to generate images

Pipeline Integration – Combined preprocessing and generation into one smooth workflow

Folder Structure
bash
Copy
Edit
Task3/
├── text_to_image.ipynb       # Jupyter Notebook with full code  
├── requirements.txt                   # Dependencies  
├── README.md                          # This file  
How to Run
Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Open the notebook:
text_to_image.ipynb

Run all cells to process text and generate image outputs
Note: This project uses a simplified text-to-image generation approach that maps text embeddings to static images instead of training a full GAN model, due to storage and resource constraints.