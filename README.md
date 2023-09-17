# Asphalt Pavements Performance Prediction Using Tree Ensemble Models
Repository containing code and data from the article presented at TRA 2024.

## TLDR
Predict the performance of flexible pavements, specifically the International Roughness Index (IRI), using various Tree Ensemble models.

## Overview:
This notebook contains the code used to train and compare five Tree Ensemble models, namely Random Forest, Gradient Boosting Decision Tree, XGBoost, LightGBM, and CatBoost, for predicting asphalt pavement performance (using IRI as a target). The models are trained using the Long-Term Pavement Performance (LTPP) program data.

**Raw Data:** [Available Here](https://infopave.fhwa.dot.gov/DownloadTracker/Bucket/114229)

**Citation:**  
Tamagusko, T. & Ferreira, A. (2024). *Asphalt Pavements Performance Prediction Using Tree Ensemble Models*. Transport Research Arena. Dublin, Ireland.

```bibtex
@article{Tamagusko-Ferreira2023-predict-iri-ensemble,
   author = {Tiago Tamagusko, Adelino Ferreira},
   title = {Asphalt Pavements Performance Prediction Using Tree Ensemble Models},
   journal = {Transport Research Arena},
   year = 2024,
   address = {Dublin, Ireland}
}
```

**Setup:**
1. `python -m venv venv`
2. Windows: `venv\Scripts\activate` | Linux/Mac: `source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `jupyter notebook main.ipynb`

**License:** [CC-BY-NC-ND-4.0](LICENSE) © 2023 [Tiago Tamagusko](https://github.com/tamagusko)
