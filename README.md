#### This repository contains the dataset and analysis code for the paper:  
## **Valorizing Organic Waste in Schools: A Thematic-NLP Analysis of Student Experiences with Eco-Enzyme as a Sustainability Practice**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Authors:**  
Desvita Nursayla Putri Cantika, Salwa Asysyifa Khoerunisa, Nazwa Hilda Syafira  
**Affiliation:** Agroindustrial Engineering Study Program, Universitas Linggabuana PGRI Sukabumi, Sukabumi, Indonesia

📍 *Presented at the 2nd International Conference of Innovative Biofrontiers Students, hosted by Faculty of Agricultural Technology - Universitas Brawijaya*

## 🔍 Overview

This study applies Reflexive Thematic Analysis (RTA) complemented with Natural Language Processing (NLP) to analyze students' responses regarding the benefits and potential of eco enzyme as an organic waste management innovation.

## 📁 Folder Structure

- `data/raw/`: Contains the original open-ended questionnaire dataset (`student_responses.csv`)
- `data/processed/`: Cleaned and tokenized responses
- `notebooks/`: Main script to run preprocessing and NLP workflow
- `output/visualization/`: Network graph files (.gexf) and visual maps
- `output/tables/`: Extracted n-gram frequency tables and NLP-to-theme mappings
- `LICENSE`: The MIT License file for the project
- `README.md`: Project documentation (this file)
- `requirements.txt`: Python dependencies used in notebook

## 📜 Methods

1. **Text Cleaning & Tokenization**  
2. **POS-based Bigram & Trigram Extraction**  
3. **Network Mapping (GEXF)**  
4. **Theme Mapping from NLP to RTA**

## 🚀 **Reproducing the Analysis**

To run this analysis on your local machine, please follow the steps below.

#### **1. Prerequisites**
* Python 3.8+
* Git

#### **2. Installation & Setup**

```bash
# 1. Clone this repository to your local machine
git clone https://github.com/junervin12/eco-enzyme-rta-nlp.git
cd eco-enzyme-rta-nlp

# 2. (Highly recommended) Create and activate a virtual environment
#    This will isolate your project's dependencies.
python -m venv venv
source venv/bin/activate  # For macOS/Linux users
# venv\Scripts\activate   # For Windows users

# 3. Install the required libraries
pip install -r requirements.txt
```

#### **3. Running the Analysis**
Once the setup is complete, you can launch the Jupyter Notebook.

```bash
# Launch Jupyter Notebook from your terminal
jupyter notebook notebooks/eco-enzyme-rta-nlp.ipynb
```

## 📄 **Citation**

If you use the code or methods from this study in your research, please cite our work:

**Conference Proceedings**:

```bash
Putri Cantika, D. N., Khoerunisa, S. A., & Syafira, N. H. (2025). Valorizing Organic Waste in Schools: A Thematic-NLP Analysis of Student Experiences with Eco-Enzyme as a Sustainability Practice. In Proceedings of the 2nd International Conference of Innovative Biofrontiers Students. Universitas Brawijaya, Malang, Indonesia.
```

## 🤝 Acknowledgments

This work is part of the student research initiative under the Agroindustrial Engineering Study Program at Universitas Linggabuana PGRI Sukabumi, in collaboration with sustainability-focused education efforts.

## 📬 Contact

For questions or collaborations, please contact:  
📧 tip@unlip.ac.id



