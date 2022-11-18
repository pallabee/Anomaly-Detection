# Predictive Maintenance using Classification 
I solved this problem at Paderborn University as part of an assignment of Data Science in Industrial Applications module.

## Problem
Predict production of faulty parts based on historical data of ball bearing vibrations. Predictive Analysis helps business to:
- Take necessary corrective actions.
- Reduce cost as the parts rejection rate can be reduced.

## Dataset
- Consists of log data from ERP system, machine data (vibration masurements) from MES system. The data distribution of normal and faulty vibrations vary greatly, so the dataset contains unbalanced data.

## Tasks
- Data preprocesssing using Windowing, Fast Fourier Transform, Resampling.
- Feature generation by Spectral Transformation.
- Handle unbalanced data using oversampling the minority class (SMOTE).
- Machine learning modelling using a binary classifier.
