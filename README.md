# Lead Scoring Project
Author - Adithya Ramachar 

This project aims to predict the likelihood of a lead being converted into a customer using machine learning techniques.

## Dataset

The dataset used in this project is sourced from Kaggle:

[Leads Dataset](https://www.kaggle.com/datasets/ravichan76/leadscore)

To use this dataset, you'll need to:

1. Create a Kaggle account if you don't have one
2. Download the dataset from the link above
3. Place the downloaded CSV file in the `data` directory of this project

## Project Structure

```
lead-scoring/
│
├── data/
│   └── Leads.csv
│
├── notebooks/
│   └── lead-score.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   └── model.py
│
├── README.md
├── requirements.txt
└── main.py
```

## Setup

1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`

## Usage

1. Run data preprocessing: `python src/data_preprocessing.py`
2. Perform feature engineering: `python src/feature_engineering.py`
3. Train and evaluate the model: `python src/model.py`
4. For an end-to-end pipeline, run: `python main.py`

## Results

The logistic regression model achieved an accuracy of **78%** on the test set. Key features influencing lead conversion include total time spent on the website, total visits, and lead origin.

## Future Work

- Experiment with more advanced models like Random Forest or XGBoost
- Implement cross-validation for more robust model evaluation
- Deploy the model as a web service for real-time predictions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

