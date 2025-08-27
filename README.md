# what_is-_lora
# 🤖 GEMMA & DistilBERT Fine-Tuning with LoRA

This repository demonstrates fine-tuning large language models and transformers using **LoRA** for efficient parameter-efficient training. The project includes:

- Text generation with GEMMA-2B-IT  
- Instruction-following and chat functionality  
- Sentiment analysis using DistilBERT  

## 📌 Project Overview

1. **GEMMA-2B-IT Causal LM**
   - Tokenization using Hugging Face `AutoTokenizer`  
   - Model loaded in 4-bit precision using `bitsandbytes`  
   - LoRA adapters applied for efficient fine-tuning  
   - Training on Alpaca-cleaned dataset (instruction-following)  
   - Generate responses with custom `chat()` function  

2. **DistilBERT Sentiment Classification**
   - Dataset: IMDB reviews  
   - Tokenization and preprocessing  
   - LoRA applied to DistilBERT for sequence classification  
   - Training with `Trainer` from Hugging Face Transformers  
   - Predict sentiment: Positive / Negative  




