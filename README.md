# Projects

A collection of data science, engineering, and research projects by **Megan Millet**.

---

## 📂 Table of Contents

| Project | Topics | Type |
|---|---|---|
| [Amazon Co-Product Purchasing Network Analysis](#-amazon-co-product-purchasing-network-analysis) | Graph Theory, Network Science, Python | Data Science |
| [Amazon India Discount Analysis](#-amazon-india-discount-analysis) | Statistics, Regression, Hypothesis Testing, Python | Data Science |
| [The Google PageRank Score](#-the-google-pagerank-score) | Graph Algorithms, Linear Algebra | Research Paper |
| [Aerobear — Vertical Flight Society](#️-aerobear--vertical-flight-society) | Aerospace Engineering, VTOL Design | Engineering |
| [Batches — BioCase Competition](#-batches--biocase-competition) | Biology, Computational Methods | Competition |

---

## 🛒 Amazon Co-Product Purchasing Network Analysis

**Tools:** Python · NetworkX · Matplotlib · Quarto

An exploration of Amazon's co-purchasing behavior using graph theory. The dataset, sourced from the [Stanford SNAP collection](https://snap.stanford.edu/data/amazon-meta.html), covers 548,552 products and nearly 1.8 million co-purchasing edges collected in 2006.

Due to computational constraints, the analysis works on a reproducible random sample of 5,000 edges (seed = 2026) using Bernoulli sampling; parsing the full file without loading it into memory.

**Key analyses:**
- Network construction and visualization of the largest connected component
- **Degree Centrality** — identifies the most directly connected products
- **Eigenvector Centrality** — weights connections by neighbor importance
- **PageRank** — ranks products by global influence in the network
- **Katz Centrality** — measures influence through all paths, discounting longer ones

**Highlight:** PageRank results aligned closely with degree centrality, while Katz centrality tracked eigenvector centrality, which is a behavior explained by the mathematical definitions of each measure.

---

## 📊 Amazon India Discount Analysis

**Tools:** Python · pandas · scipy · statsmodels

A statistical investigation into whether larger discounts on Amazon India product listings correlate with higher customer ratings. The dataset contains ~1,465 products scraped in 2023 from [Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset).

**Methods used:**
- Confidence Interval (CI) Testing
- One-way ANOVA
- Ordinary Least Squares (OLS) Regression

---

## 📐 The Google PageRank Score

**Deliverables:** Research paper · Presentation slides

A deep dive into the mathematical foundations of Google's PageRank algorithm: the algorithm that originally powered Google Search. Covers the linear algebra and graph theory underpinning the ranking model, including the random surfer model and power iteration convergence.

---

## ✈️ Aerobear — Vertical Flight Society

**Deliverables:** VTOL design proposal · Competition attestation

A vertical takeoff and landing (VTOL) aircraft design proposal submitted as part of the Vertical Flight Society student competition. Includes the full engineering design document and the official competition attestation.

---

## 🧬 Batches — BioCase Competition

**Deliverables:** Competition proposal · Certificate of participation

A research proposal submitted for the BioCase 2022 competition. Includes the full proposal document and a certificate of achievement.

---

*More projects coming soon.*
