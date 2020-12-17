# shap-values-titanic-xyonix-blog
SHAP values are used to explain model outcomes predicting passenger survival on the RMS Titanic

# installation
```
# create an environment, install packages, register Jupyter kernel and launch notebook
python3 -m venv xyonix_titanic && source xyonix_titanic/bin/activate
pip install --upgrade pip setuptools wheel
pip install ipykernel shap xgboost matplotlib seaborn Jinja2 ipywidgets
jupyter nbextension enable --py widgetsnbextension --sys-prefix
python -m ipykernel install --user --name xyonix_titanic
jupyter notebook
```

Once the Jupyter notebook navigator loads:

1. Select `shap_values_titanic_xyonix_blog.ipynb` to open notebook 
2. Select `Kernel >> Change kernel >> xyonix_titanic` from pulldown menu

# Juyter notebook

The [Jupyter Notebook](https://github.com/xyonix/shap-values-titanic-xyonix-blog/blob/master/shap_values_titanic_xyonix_blog.ipynb) corresponds to the [UPDATE LINK AND TITLE ONCE ARTICLE IS ON SITE! Explaining a passenger survival model for the RMS Titanic](https://www.xyonix.com/blog/inside-black-box-developing-explainable-ai-models) XYONIX article. Run the cells in the notebook in order to produce the plots shown in the article, such as the SHAP force layout plots shown below.

![shap value force layout plots for select passengers](https://github.com/xyonix/shap-values-titanic-xyonix-blog/blob/master/shap_titanic_force_layout.png?raw=true)

```