# credit-card-fraud-detection
Credit Card Fraud Detection using Unsupervised Machine Learning (Isolation Forest).  The system detects anomalous transactions based on behavioral, temporal, and geographic patterns  and generates a fraud risk score (0–100) for decision-based intervention.


# Credit Card Fraud Detection (Unsupervised ML)

## Overview
This project builds an anomaly-based fraud detection system using Isolation Forest.

## Features Engineered
- Transaction amount
- Spending ratio (amount / credit limit)
- Distance from home location
- Night transaction indicator
- Weekend indicator
- Transaction frequency per card

## Model Used
- Isolation Forest (Unsupervised Learning)

## Risk Scoring
Generated a fraud risk score between 0–100 and categorized transactions into:
- Low Risk
- Medium Risk
- High Risk

## Business Logic
- High Risk → Block transaction
- Medium Risk → OTP verification
- Low Risk → Allow transaction

## Results
- ~1.5% transactions flagged as high risk
- Clear separation between normal and anomalous behavior

## Future Improvements
- Add supervised learning with labeled fraud data
- Deploy as API using Flask
- Add real-time scoring system
