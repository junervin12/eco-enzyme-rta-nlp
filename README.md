This repository contains the dataset and analysis code for the paper:  
**"Valorizing Organic Waste in Schools: A Thematic-NLP Analysis of Student Experiences with Eco-Enzyme as a Sustainability Practice"**

## 🔍 Overview

This study applies Reflexive Thematic Analysis (RTA) complemented with Natural Language Processing (NLP) to analyze students' responses regarding the benefits and potential of eco enzyme as an organic waste management innovation.

## 📁 Folder Structure

- `data/raw/`: Contains the original open-ended questionnaire dataset (`respon_kuesioner.csv`)
- `data/processed/`: Cleaned and tokenized data, bigram/trigram extraction
- `output/visualization/`: GEXF network graph files for Gephi visualization
- `output/tables/`: RTA initial coding table and NLP-to-theme mappings
- `starter.py`: Main script to run preprocessing and NLP workflow
- `requirements.txt`: Python dependencies

## 📜 Methods

1. **Text Cleaning & Tokenization**  
2. **POS-based Bigram & Trigram Extraction**  
3. **Network Mapping (GEXF)**  
4. **Theme Mapping from NLP to RTA**

## 🔧 How to Run

```bash
# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the main script
python starter.py
