# Resume Parser — Rule-based and LLM Extraction

This repository contains a complete resume parsing pipeline (Resume_Parser.ipynb) that extracts structured information such as name, email, and skills from resumes in both PDF and Word (.docx) formats.  
It demonstrates two complementary approaches — a rule-based NLP method and a Large Language Model (LLM)-based extraction using OpenAI's API.  
The notebook also includes data generation, preprocessing, parsing, evaluation, and reproducibility setup.

---

## Features

- Supports PDF and Word (.docx) formats
- Extracts name, email, and skills into structured JSON
- Implements two approaches:
  - Rule-based extraction using regular expressions and pattern matching
  - LLM-based extraction using OpenAI’s GPT model
- Hybrid mode that combines both results for higher accuracy
- Includes precision, recall, and F1 evaluation metrics
- Fully executable Jupyter notebook with documented steps

---

## Project Structure

policy_reporter/
│
├── Resume_Parser.ipynb # Main notebook with full workflow
├── requirements.txt # Python dependencies
└── data/
└── resumes_dataset/
├── ground_truth.json # Labeled dataset for evaluation
├── sample_resume_1.pdf
├── sample_resume_2.pdf
└── ...
