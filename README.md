# EDA project on King County Housing data

This is an EDA based on the King County Housing dataset.

Please first have a look at the [assignment](assignment.md) and also at the [workflow](workflow.md).

The actual EDA can be found here: [EDA](EDA.ipynb)

And here is the final project presentation: [EDA project presentation](EDA-project-presentation.pdf)

## Data

The data is not included in this repository and can be found on kaggle:
https://www.kaggle.com/harlfoxem/housesalesprediction

## Requirements

- pyenv
- python==3.9.4

## Setup

For this purpose you use following commands:

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Unit testing (Optional)

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.
