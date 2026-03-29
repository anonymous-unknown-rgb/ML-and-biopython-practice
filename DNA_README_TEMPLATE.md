# 🧬 DNA Sequence Analyzer & Viral Classifier

## Overview
This repository contains a full-stack bioinformatics pipeline and web application designed to classify raw DNA sequences into viral strains. The project bridges classical Machine Learning and computational biology, featuring a live, interactive user interface.

## 🚀 Live Demo
**[Replace this with your Streamlit URL]**

## Features
- **Sequence Parsing:** Native integration with `BioPython.SeqIO` to read `.fasta` files.
- **Biochemical Feature Extraction:** Algorithmic calculation of biological parameters (e.g., GC-content) from raw nucleotide strings `(A, T, G, C)`.
- **Machine Learning Inference:** Predicts viral behavior with a serialized `RandomForestClassifier` (`virus_brain.pkl`) trained on genomic data.
- **Live UI/UX:** Front-end built with Streamlit handling live string validation and rapid model unpickling.

## Tech Stack
- **Language:** Python
- **Bioinformatics:** BioPython (`SeqUtils`)
- **Machine Learning:** Scikit-learn
- **Data Pipeline:** Pandas, Numpy
- **Deployment:** Streamlit

## Getting Started

### Installation
```bash
pip install -r requirements.txt
```

### Running Locally
```bash
streamlit run app.py
```

*Note: This data is synthesized for educational/portfolio purposes.*
