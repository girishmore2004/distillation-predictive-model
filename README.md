# Predictive Modeling of Distillation Column Performance Using Sensor Data

## Project Overview
This project develops a **predictive model** for forecasting the performance of a distillation column using **sensor data**. The focus is on predicting key performance indicators, such as the mole fractions of TX and HX components, using **machine learning (ML)** techniques. The study leverages synthetic data generated with **Aspen HYSYS**, simulating real-time operating conditions.

## Key Work Done
1. **Data Simulation**: Synthetic data representing temperature, pressure, and component concentrations was generated using Aspen HYSYS.
2. **Data Preprocessing**: 
   - Cleaned and normalized data.
   - Handled missing values using imputation techniques.
3. **Model Development**:
   - Evaluated multiple ML models.
   - Selected **Random Forest** for its accuracy in handling non-linear relationships.
4. **Training and Validation**:
   - Trained the model on synthetic data.
   - Validated performance using metrics like RMSE and accuracy.
5. **Outcome**:
   - Achieved prediction accuracy of **90.52%** for MoleFractionTX and **90.50%** for MoleFractionHX.
   - Demonstrated the model's potential for improving process control and operational efficiency.

## Technologies Used
- Python (TensorFlow, Scikit-learn)
- Aspen HYSYS
- Data Visualization (Matplotlib, Seaborn)

---
 
