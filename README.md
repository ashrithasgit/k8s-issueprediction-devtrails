# Kubernetes Failure Prediction Model for DEVTRAILS by Guidewire

## Overview
This is our submission for the DEVTRAILS hackathon conducted by Guidewire. We are currently studying in 6th semester at Dayanad Sagar University. We aim to predict 6 issues that are faced in k8 clusters. We used different algorithms like LighGMB and Random forest but XGBoost had the highest accuracy.

## Failure Categories
The model predicts the following Kubernetes issues:
1. Node or pod failures
2. Resource exhaustion (CPU, memory, disk)
3. Network or connectivity issues
4. Service disruptions based on logs and events
5. Security anomalies
6. Application-level failures

## Dataset
- The dataset contains labeled instances of failures.
- Features include system metrics, logs, network data, and resource usage.

## Model
- Algorithm: XGBoost
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score
- Preprocessing: Missing value handling, feature scaling, and balancing

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, lightgbm

## Installation
```sh
pip install pandas numpy scikit-learn lightgbm
```

## Training the Model
Run the following script to train the model:
```sh
python train_model.py
```

## Evaluation
To evaluate the trained model:
```sh
python evaluate_model.py
```

## Future Improvements
- Hyperparameter tuning
- Anomaly detection using deep learning
- Real-time failure prediction integration

##Demo Video 
https://github.com/ashrithasgit/k8s-issueprediction-devtrails


## Contact us:
Ashritha Arunkumar - arunkumarashrithaa@gmail.com
B Dhivya - dhivyabalakumar28@gmail.com
Manasvini V -
Pranati Biswal - pranatibiswal1108@gmail.com



