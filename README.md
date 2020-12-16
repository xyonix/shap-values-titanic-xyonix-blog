# shap-values-titanic-xyonix-blog
SHAP values are used to explain model outcomes predicting passenger survival on the RMS Titanic

# installation
```
# create an environment, install packages, register Jupyter kernel and launch notebook
python3 -m venv xyonix_titanic && source xyonix_titanic/bin/activate
pip install --upgrade pip setuptools wheel
pip install ipykernel shap xgboost matplotlib seaborn
python -m ipykernel install --user --name xyonix_titanic
jupyter notebook
```

Once the Jupyter notebook navigator loads:

1. Select `shap_values_titanic_xyonix_blog.ipynb` to open notebook 
2. Select `Kernel >> Change kernel >> xyonix_titanic` from pulldown menu

```