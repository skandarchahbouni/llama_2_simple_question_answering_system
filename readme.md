# 📚 Llama 2 Simple Question Answering System

## ✨ Project Overview

This project implements a simple question-answering system using the Llama 2 model, allowing users to query information from PDF documents. The system leverages natural language processing to provide answers based on the content of the uploaded PDFs.

## 📦 Usage

1. **Install Necessary Packages**  
   Run the following command to install the required packages listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

2. **Download the Quantized Llama 2 Model**  
   📥 **Download Link:** [Llama 2 Model](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML)  
   (Note: This is a very large file, over 7 GB, so please ensure you have sufficient storage.)

3. **Add Your PDF File**  
   📂 Place your PDF file in the `pdf` folder.

## ⚠️ Limitations

- 🐢 **Performance**: This code is running on a CPU, which may lead to longer response times for each question (up to 3 minutes).
- ❓ **Accuracy**: Sometimes, the answers generated may not be accurate.
 
