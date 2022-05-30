# Classifying Cryptocurrencies with PCA and K-means Clustering

## Summary

This experiment involves preprocessing and clustering cryptocurrencies using [data provided by CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist).

Principal Component Analysis is used to reduce the dimensions of features in the dataset. After PCA conversion, K-means clustering is applied to the data to identify groupings of crpytocurrency data.

## Usage

### Environment

Requires an [Anaconda](https://www.anaconda.com/products/distribution) virtual environment running Python >= 3.8.

Activate your Anaconda virtual environment.
```sh
conda activate <env>
```

### Dependencies

These installations are required to run the analysis. Newer package versions can be used, but be aware that library updates may cause code errors in the notebook.

```sh
pip install numpy==1.20.3
pip install pandas==1.3.4
pip install matplotlib==3.4.3
pip install hvplot==0.7.3
pip install scikit-learn==0.24.2
```

### Run

Use Jupyter Lab, Google Colab, or any other Jupyter Notebook editor to run the code.