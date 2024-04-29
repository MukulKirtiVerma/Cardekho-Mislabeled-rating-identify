# Mislabel Identification in Car Rating Data

This project identifies potentially mislabeled data points in a car rating dataset using a machine learning model.

## Description
The provided Python script uses a RandomForest classifier to predict car ratings based on various features and identifies discrepancies between the predicted ratings and the actual labels. These discrepancies may indicate potential mislabelings in the dataset.
it consist followings:
1. Remove Col having 99% nan values
2. Remove Non related col linek appointmentId
3. Remove the clsses having les then 20 % of max class count
4. Then identify Mis labeled datapoint with RandomForest
5. Remove those outliers
6. Then Feature selection
7. Then train the model for better rating prediction

## Installation
To run this project, you need to have Python installed on your system. The dependencies are listed in `requirements.txt`. Install them using pip:

```bash
pip install -r requirements.txt
# Cardekho-Mislabeled-rating-identify
