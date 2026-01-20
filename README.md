# Scientific Trend Analytics

A data-driven exploration of scientific research trends using metadata from the arXiv repository.  
This project analyzes publication patterns, keyword frequencies, and topic evolution to understand how scientific fields grow and shift over time.

---

## 📌 Project Overview

This repository contains a Jupyter Notebook that performs:

- Data loading and preprocessing of arXiv metadata  
- Trend analysis across scientific categories  
- Keyword frequency exploration  
- Visualization of long-term publication patterns  
- Identification of emerging and declining research areas  

The goal is to provide a clear, reproducible workflow for analyzing large-scale scientific metadata.

---

## 📂 Repository Structure

```
science_trend_analytics/
│
├── scientific_trend_analysis.ipynb     # Main analysis notebook
├── arxiv-metadata-oai-snapshot.json    # (Ignored locally; too large for GitHub)
├── .gitignore                          # Excludes large data files
├── anaconda_projects/                  # Local environment metadata (ignored)
└── README.md                           # Project documentation
```

**Important:**  
Large dataset files such as `arxiv-metadata-oai-snapshot.json` and `.parquet` files are intentionally excluded from Git history to keep the repository lightweight and GitHub‑compatible.

---

## 🧠 Requirements

To run the notebook locally, install:

- Python 3.9+
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib / seaborn
- pyarrow (if working with Parquet files)

Install dependencies with:

```bash
pip install -r requirements.txt
```

(If you don’t have a `requirements.txt` yet, you can generate one later.)

---

## 🚀 How to Use

1. Download or clone the repository:
   ```bash
   git clone https://github.com/1994Simba/science_trend_analytics.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook scientific_trend_analysis.ipynb
   ```
3. Run the cells to reproduce the analysis.

---

## 📊 Data Source

This project uses metadata from the **arXiv Open Access Initiative**, which provides structured information about millions of scientific papers across physics, mathematics, computer science, and more.

The full metadata file is very large (5GB+), so it is **not included in this repository**.  
You can download it directly from arXiv if needed.

---

## 🛡️ Notes on Large Files

To keep the repository clean and pushable:

- `.parquet` files were removed from Git history  
- `arxiv-metadata-oai-snapshot.json` (5GB) was removed from Git history  
- `.gitignore` prevents large files from being tracked in the future  

This ensures fast cloning and compatibility with GitHub’s 100MB file limit.

---

## 📄 License

This project is released for educational and research purposes.  
Feel free to fork, modify, and build upon it.

---

## ✨ Author

**Integrity Simbarashe Alseti**  
AI & Data Science Student  
Berlin, Germany

---

If you find this project useful, consider starring the repository ⭐

