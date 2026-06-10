# Formative Assignment: Advanced Linear Algebra (PCA)

**ALU FA**

Principal Component Analysis from scratch on Rwanda rainfall data (HDX HAPI).

## What it does

- Loads and preprocesses rainfall data (imputation, encoding, standardization)
- Computes covariance matrix and eigendecomposition
- Selects principal components via cumulative variance threshold (90%)
- Projects data into lower-dimensional space
- Compares covariance+eigh vs SVD approaches for stability and performance

## Files

| File | Description |
|------|-------------|
| `rainfall.ipynb` | Full PCA implementation and analysis |
| `hdx_hapi_rainfall_rwa.csv` | Rwanda rainfall observations |
| `task_sheet.pdf` | Assignment brief |
