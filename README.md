# Generative-AI-Text-Generator
Developed a Generative AI model using GPT-2 via Hugging Face Transformers to produce human-like text. Implemented tokenization, fine-tuned the model on a custom text dataset, and generated coherent paragraphs based on user prompts. Demonstrated applications in creative writing and content generation.

# 📝 Fine-Tuned Generative AI Text Generator

This project fine-tunes **GPT-2** on a custom dataset using Hugging Face Transformers to generate human-like, domain-specific text.


## 📌 Project Overview
- **Model:** GPT-2 (fine-tuned)
- **Dataset:** Wikitext-2 (can be replaced with any custom dataset)
- **Goal:** Generate unique and context-aware text


## 🚀 Features
- Fine-tunes GPT-2 for better domain adaptation
- Generates creative and coherent paragraphs
- Uses Hugging Face `Trainer` API for industry-standard training


## 📊 Example Output
**Prompt:** "The future of artificial intelligence"  
**Generated:**  
"The future of artificial intelligence lies in creating systems that can adapt to human needs, learning from context and experience to provide truly personalized assistance..."


## 🛠 Tools Used
- Python
- Hugging Face Transformers
- PyTorch
- Datasets library


## 📜 How to Run
1. Open in Google Colab
2. Upload your dataset or use `wikitext`
3. Run all cells
4. Enter your own prompt to generate text


## 📈 Future Improvements
- Use larger models like GPT-neo or GPT-J
- Train for more epochs on domain-specific data
- Deploy as an API with FastAPI or Streamlit
