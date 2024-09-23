<div align="center">

# 🤖 ChatBot Doctor using Fine-Tuning LLMs (FTM) 
### Transforming Healthcare with AI-Powered Medical Expertise

![FTM](https://img.shields.io/badge/LLM-Fine--Tuning-blue)
![Colab](https://img.shields.io/badge/Colab-Optimized-yellow)
![Python](https://img.shields.io/badge/Code-Python-green)

![image](https://github.com/user-attachments/assets/e01d9728-8d9f-4bd8-aa93-0bd0199c8d92)


</div>

---

## 🚀 Project Overview

Harnessing the power of **Large Language Models** (LLMs), this project fine-tunes **LLaMA** to provide intelligent medical insights. With cutting-edge tools such as Hugging Face's **PEFT** and **BitsAndBytes**, the model becomes optimized for high efficiency and deep medical understanding. 

---

## 🛠️ Key Features

- **LLM Fine-Tuning**: Medical-specific term generation with precision using Hugging Face's `SFTTrainer`.
- **Memory-Efficient Training**: Using **LoRA** and 4-bit quantization for fast, efficient model performance.
- **Optimized for Google Colab**: Run directly in Colab with streamlined dependency management.
- **Interactive Medical Chatbot**: Delivers personalized answers to healthcare queries.

---

## 🎯 Tech Stack
<div style="display: flex; align-items: center;">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="60" height="60">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="60" height="60">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/1024px-Google_Colaboratory_SVG_Logo.svg.png" alt="Google Colab" width="60" height="60">
    <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face" width="60" height="60">
</div>

- **Transformers 4.31.0**
- **PEFT 0.4.0**
- **BitsAndBytes 0.40.2**
- **Accelerate 0.21.0**

---

## 💡 Implementation Highlights

1. **Model Loading**: LLaMA model with 4-bit quantization for memory efficiency.
2. **Tokenizer Setup**: Right-padded for consistent data processing.
3. **Supervised Fine-Tuning**: Utilizing `SFTTrainer` for effective task-specific learning.
4. **Interactive Chat**: Answering medical queries in real-time with the fine-tuned model.

---

## 📈 Performance

- **Training Batch Size**: 4
- **Maximum Steps**: 100
- **PEFT Config**: LoRA with `lora_alpha=16` and `lora_dropout=0.1`

---

## ✨ Future Enhancements

- Integrate **Xformers** for memory-efficient attention.
- Expand medical terminology coverage through additional fine-tuning datasets.
  
---

<div align="center">

**Built with ❤️ using Hugging Face & Transformers**

</div>
