# Drug_action_prediction

## About Dataset
This dataset can be used to predict the presence of medicinal compound based on DNA analysis in cells.

The 79 cell specimens, were analyzed in an effort to
determine if certain chemical characteristics of the drug might be related to the
formation of DNA-drug complex.
The six chemical characteristics of the drug are: 
(1) specific gravity, the density of the drug given relative to water; 
(2) pH, the negative logarithm of the hydrogen ion; 
(3) osmolarity (mOsm), a unit used in biology and medicine but not in physical chemistry.
(4) conductivity (mMho milliMho). One Mho is one reciprocal Ohm.
(5) alanine concentration in millimoles per litre; and 
(6) metal concentration (MET) in millimolesllitre.

### Performing Basic EDA and training

To explore the dataset, I have performed basic EDA by loading the dataset into Python's Pandas library. I have checked for missing values, computed summary statistics, and created visualizations of the data. This EDA helps in understanding the dataset and identifying potential issues that need to be addressed before training models.

Several machine learning algorithms were used to train, test and evaluate the model, including:
- Logistic Regression
- Random Forest
- XGBoost 

### Conclusion :

This project demonstrates the effectiveness of machine learning algorithms for predicting the presence of drug molecules in cell. The results suggest that the Logistic Regression algorithm can be a valuable tool for healthcare professionals in developing strategies for better docking of drug molecules to DNA iside the cell. Also the data available was too less to train any powerful ML, DL algorithms.


> [!CAUTION]
> ***The required dataset was provided by a Children's Research Hospital and belongs to them. Entire data is edited to maintain privacy of patients. Any attempt to copy or recreate data is subject to lawsuit.***
