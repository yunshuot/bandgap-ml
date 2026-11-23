# Band gap prediction with a neural network

MASC 520 (Fall 2026) final project by Yunshuo Tian and Shao Jinlin Yang.

We predict the PBE band gap of inorganic semiconductors from CIF files using a small
neural network and 17 composition and nearest-neighbour features. Data are from the
Materials Project (2307 materials, may update depending on the database).

**Result:** MAE = 0.41 eV (grouped 5-fold CV), compared with 0.66 eV for predicting the mean.

## How to run

pip install -r requirements.txt
jupyter notebook

Run the notebooks in order:

1. `1_data_and_features.ipynb`: load the data and compute features
2. `2_train_models.ipynb`: train the models
3. `3_results.ipynb`: make the result figures

data are already included.