# Data Science Notebook

A containerized Jupyter Notebook environment for data science workflows including data analysis, visualization, and machine learning experiments.

## Features
- Pre-installed data science libraries: Pandas, NumPy, Matplotlib, Scikit-learn
- Easy environment setup using Docker
- Supports reproducible workflows and experiments

## Tech Stack
- Python
- Jupyter Notebook
- Docker
- Libraries: Pandas, NumPy, Matplotlib, Scikit-learn

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/WasanaKarunasena/data-science-notebook.git
Build Docker image:


docker build -t ds-notebook .
Run container:


docker run -p 8888:8888 ds-notebook
Open Jupyter Notebook in your browser at http://localhost:8888

Usage
Create and run notebooks for data analysis and machine learning experiments.

Import your datasets into the container for testing.
