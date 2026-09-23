# IMDB Movie Reviews - Information Retrieval

This project implements Text Preprocessing, TF-IDF Feature Extraction, and Sparse Matrix Dimension Table generation for sentiment analysis using the **IMDB Dataset of 50K Movie Reviews**.

## Dataset Source

- **Dataset Name**: IMDB Dataset of 50K Movie Reviews
- **Source**: [Kaggle - Lakshmi 25 Npathi](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data)

---

## 🚀 Getting Started & Execution Guide

Follow these steps to set up your local environment and run the notebooks from scratch.

### 1. Clone or Open the Project

Open your terminal inside the project root directory.

### 2. Create a Virtual Environment (`venv`)

Run the following command to create a virtual environment named `.venv`:

```bash
python -m venv .venv
```

### 3. Activate the Virtual Environment

- **Windows**:

```bash
.venv\Scripts\activate
```

- **macOS/Linux**:

```bash
source .venv/bin/activate
```

or if you are using **Git Bash** on Windows:

```bash
source .venv/Scripts/activate
```

### 4. Install Required Dependencies

Run the following command to install the required dependencies:

```bash
pip install -r requirements.in
```

## Project Structure

The project main script files are located in the `src` folder, while the dataset and output files are stored in the `data` folder.

```
  ├── src
  ├── data
```

## Project Pipeline Overview

The project consists of the following main steps:

- `preprocessing.ipynb`: Handles text cleaning, tokenization, stop-word removal, and generates the processed dataset containing processed_text and processed_tokens.
- `weighting.ipynb`: Applies TfidfVectorizer (with unigrams and bigrams), converts the output into an optimized sparse matrix DataFrame, and performs feature validation.
