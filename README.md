\# Supply Chain Delivery ETA Prediction Pipeline (Machine Learning)

&nbsp;

\#\# Executive Summary

This project implements an end-to-end Machine Learning pipeline designed to predict real-world shipment delivery durations (\`actual\_delivery\_days\`) across global logistics routes using order, warehouse, carrier, and environmental metadata.

&nbsp;

\#\# Key Results

\- \*\*Model Architecture:\*\* Random Forest Regressor (100 estimators)

\- \*\*Mean Absolute Error (MAE):\*\* 0.787 days (\~18.8 hours average error window)

\- \*\*Variance Explained (${R}^{2}$ Score):\*\* 0.948

\- \*\*Data Volume:\*\* 50,000 historical shipment events

&nbsp;

\#\# Technical Stack

\- \*\*Language:\*\* Python 3.10+

\- \*\*Data Manipulation:\*\* Pandas, NumPy

\- \*\*Machine Learning & Metrics:\*\* Scikit-Learn (RandomForestRegressor, Train/Test Split, Regression Metrics)

\- \*\*Model Persistence:\*\* Joblib

&nbsp;

\#\# Features Included at Dispatch Time

\- Physical Attributes: \`product\_weight\_kg\`, \`package\_size\`, \`order\_value\_usd\`

\- Spatial & Temporal Vectors: \`distance\_km\`, \`promised\_delivery\_days\`, \`warehouse\_processing\_hours\`

\- Operational & External Variables: \`shipping\_method\`, \`carrier\`, \`order\_priority\`, \`weather\_condition\`

&nbsp;

\#\# How to Run

1\. Clone the repository:

&nbsp;&nbsp;&nbsp;\`\`\`bash

&nbsp;&nbsp;&nbsp;git clone \[https\://github.com/KassianoLK/logistics-eta-prediction-ml.git\](https\://github.com/KassianoLK/logistics-eta-prediction-ml.git)

&nbsp;