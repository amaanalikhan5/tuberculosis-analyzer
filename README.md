# Tuberculosis Analyzer

BTech major project (2024): a Streamlit web app that classifies chest X-rays as **Normal** or **Tuberculosis** using a deep-learning model, with supporting ML analysis (ResNet, Decision Tree, Random Forest).

- Live app (may be asleep): https://tuberculosis-analyzer.streamlit.app
- Report, research paper and presentation: [`docs/`](docs)
- Training notebook: `tuberculosis-classification-f1-score-99-3.ipynb`

## Run locally
Requires Python 3.9+.
```bash
git clone https://github.com/amaanalikhan5/tuberculosis-analyzer.git
cd tuberculosis-analyzer
pip install -r requirements.txt
streamlit run main.py
```

## Dataset
Not included in this repo (≈700 MB). Download the **Tuberculosis (TB) Chest X-ray Database** from Kaggle:
https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset

## Credits
The Streamlit app structure is adapted from the open-source analyzer template by
[MainakRepositor](https://github.com/MainakRepositor).
