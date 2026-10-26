# Logistics Predictive Modeling: Shipment Delay Prediction

## Project Overview
This project demonstrates how supervised machine learning can be used to predict shipment delays in logistics operations using Python and a Decision Tree Classifier.

## Objectives
- Build a model to classify shipments as delayed or not delayed.
- Prepare data for machine learning.
- Train and test a Decision Tree model.
- Evaluate predictions using accuracy, a classification report, and a confusion matrix.
- Visualize feature importance to understand which inputs the model uses most.

## Dataset
The project uses **200 simulated shipments** with these features:
- `Distance_km` — shipment distance
- `Order_Units` — number of units in the order
- `Warehouse_Load` — warehouse workload
- `Shipping_Method` — Standard or Express
- `Delayed` — target variable (1 = delayed, 0 = not delayed)

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## Methodology
1. Create and inspect the simulated dataset.
2. Convert the categorical shipping method into numerical features.
3. Split the data into 80% training and 20% testing sets.
4. Train a Decision Tree Classifier.
5. Generate predictions on the test set.
6. Evaluate model performance and visualize results.

## Project Files
- `Logistics_Predictive_Modeling.ipynb` — notebook containing the analysis and model.
- `shipment_prediction_results.csv` — actual and predicted test outcomes.
- `confusion_matrix.png` — visualization of classification results.
- `feature_importance.png` — visualization of model feature importance.
- `Business_Insights_Report.txt` — summary of findings and recommendations.

## Business Applications
A validated shipment-delay model could help logistics teams identify shipments that may need closer monitoring and investigate potential operational risks.

## Limitations
The dataset is simulated, and the delay labels are generated using predefined rules. Model performance on this dataset does not demonstrate real-world accuracy. Historical operational data and further validation would be required before operational use.

## Author
Created as a hands-on learning project in logistics analytics and machine learning.
