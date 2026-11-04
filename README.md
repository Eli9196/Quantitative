# MScFE 600 – Group Work Project #1
## Financial Data: Alternative Data & Stock Market Prediction

[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository contains the deliverables for **GWP1** of *MScFE 600 Financial Data*.

### 📚 Part 1 – Assessing Models with Alternative Data
A critical analysis and replication of:

> Sagaceta-Mejia, A. R., Sánchez-Gutiérrez, M. E., & Fresán-Figueroa, J. A. (2024).
> *An Intelligent Approach for Predicting Stock Market Movements in Emerging Markets
> Using Optimized Technical Indicators and Neural Networks.*
> Economics, 18, 20220073. https://doi.org/10.1515/econ-2022-0073

**Q1–Q5 + Financial Problem + Application** → [`part1/`](part1/)
**Replication (ECH ETF, Dispersion Ratio, 10-fold CV)** → [`part1/replication/`](part1/replication/)

### 📊 Part 2 – Alternative Data User Guide
A user guide for **Social Media Data** (Behavioral Data), based on:

> Sun, Y., Liu, L., Xu, Y., Zeng, X., Shi, Y., Hu, H., Jiang, J., & Abraham, A. (2024).
> *Alternative data in finance and business: emerging applications and theory analysis (review).*
> Financial Innovation, 10, 127. https://doi.org/10.1186/s40854-024-00652-0

**Guide + Python EDA** → [`part2/`](part2/)

### 🚀 Quick Start

```bash
# 1. Clone
git clone https://github.com/<your-username>/gwp1-financial-data.git
cd gwp1-financial-data

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run replication
cd part1/replication
python ech_replication.py

# 4. (Optional) Build the Jupyter notebook
python build_notebook.py
# then open ech_replication.ipynb in Jupyter/Colab

# 5. Run Part 2 EDA
cd ../../part2/code
python social_media_eda.py   # requires Reddit API credentials
