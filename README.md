# Human Protein Data from UniProt

This repository contains a Jupyter Notebook that connects directly to the [UniProt](https://www.uniprot.org/) website to fetch **protein data for humans (Homo sapiens)** using their API.

## 🔍 What This Notebook Does

- Connects to UniProt API using a keyword or gene/protein name.
- Automatically restricts the search to **Homo sapiens (Human)**.
- Downloads data in TSV (tab-separated) format.
- Converts the TSV data to a readable pandas DataFrame.
- Shows key information like:
  - Gene names
  - Protein names
  - Length
  - Sequence
  - Protein existence level
  - Subcellular location
  - Function
  - Entry links (to UniProt page)

## 📁 File

- `UNIPORT.ipynb`: The Jupyter notebook with the full code and example outputs.

## ▶️ How to Run

1. Open the notebook using Jupyter:
```bash
jupyter notebook UNIPORT.ipynb
