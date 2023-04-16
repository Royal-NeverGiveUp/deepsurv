# DeepSurv-based model for predicting survival of primary gastrointestinal lymphoma based on a surveillance, epidemiology, and end results analysis

Model construction, hyperparameters tuning and evaluation are handled with [pysurvival](https://github.com/square/pysurvival), [scikit-learn](https://github.com/scikit-learn/scikit-learn) and [lifelines](https://github.com/CamDavidsonPilon/lifelines) packages: [ModelDevelopment.ipynb](ModelDevelopment.ipynb)

Web application based on [streamlit](https://github.com/streamlit/streamlit) package: [app.py](app.py)

To reproduce this study, first run the following codes to install packages:
```
git clone https://github.com/Royal-NeverGiveUp/deepsurv.git
pip install -r requirements.txt
```

Run ```streamlit run app.py``` in terminal to open the web application locally.

[Online web application](https://royal-nevergiveup-deepsurv-app-7tnpnh.streamlit.app/)

[Paper link](https://pubmed.ncbi.nlm.nih.gov/)
