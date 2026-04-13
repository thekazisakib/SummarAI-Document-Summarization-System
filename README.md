# SummarAI – Document Summarization System

A simple NLP system for generating concise summaries from documents.

Built to process unstructured text and produce readable summaries using transformer-based models.

---

## What it does

- generates summaries from input text or documents  
- handles unstructured data with preprocessing  
- supports batch processing for multiple documents  
- improves readability and reduces manual effort  

---

## How it works

1. Load and preprocess text data  
2. Clean and structure input documents  
3. Pass text through a transformer-based model (T5)  
4. Generate concise summaries  
5. Output formatted results  

---

## Tech stack

Python • HuggingFace Transformers • MLflow  

---

## Run locally

```bash
git clone https://github.com/thekazisakib/SummarAI-Document-Summarization-System.git
cd SummarAI-Document-Summarization-System

pip install -r requirements.txt
python app.py
