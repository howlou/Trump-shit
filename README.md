# Trump-shit

Notebook project for analyzing Trump speech transcripts.

## Open in VS Code

Open this folder (`Group Project/Trump-shit`) in VS Code. The workspace uses the local `.venv` interpreter.

## Set up Python

From this folder, create the environment and install the notebook dependencies:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

Open `trump shit.ipynb` and select the `.venv` Python environment as its kernel if VS Code does not select it automatically.

## Add the dataset

The notebook expects `Trump_Labeled_Combined_Rev_Speeches_Final_9-24-2024.json` inside `data/`. The dataset is kept locally and excluded from Git. Download `Trump_Labeled_Combined_Rev_Speeches_Final_9-24-2024.json` from [Kaggle](https://www.kaggle.com/datasets/tangtaidje/donald-trump-rev-com-speech-transcripts-dataset) and place it in `data/` before running the analysis cells.
