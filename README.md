# fundamentals-of-aiml

# AI Resume Screening & Job Recommendation System

## Overview

An NLP-based application that uses Transfer Learning
and pre-trained transformer models to analyze resumes
and recommend suitable job positions.

## Features

- Resume PDF upload
- Text extraction
- NLP-based semantic analysis
- Pre-trained transformer model
- Job recommendation
- Similarity scoring
- Interactive Streamlit interface

## Technologies

- Python
- NLP
- Sentence Transformers
- Scikit-learn
- Streamlit
- PyMuPDF

## Architecture

Resume
↓
PDF Text Extraction
↓
Preprocessing
↓
Pre-trained Transformer
↓
Embeddings
↓
Cosine Similarity
↓
Job Ranking
↓
Recommendations

## Installation

```bash
git clone <your-repository-url>

cd ai-resume-job-recommender

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt
