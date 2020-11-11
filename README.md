# Data Representing Ground-Truth Explanations

Due to size constraints, only the code  is being attached in the repository and not the dataset. The dataset can be downloaded from the links provided below.

The code for the entire project is split 3 essential parts:

1) Loan Data - ![Link to Loan Dataset](https://drive.google.com/drive/folders/1_7hbPb8FQ488faesZVQDpWo9mxJrG5h4?usp=sharing)
- GTE with 5 num_samples
- GTE with 25 num_samples
- GTE with 50 num_samples
- NN1 coefficients from LIME-Loan
- NN2 coefficients from LIME-Loan
 
 **To run the code ensure that file "Loan_Data.csv" has the same path as the Jupyter notebook "Loan_Data-Lime-explanations"**

2) Time Data - ![Link to Time dataset](https://drive.google.com/drive/folders/1_7hbPb8FQ488faesZVQDpWo9mxJrG5h4?usp=sharing)
- Time 10000 Evaluation Instances Correct with labels.csv
- GTE with 1000 num_samples
- NN1 coefficients from LIME-Time
- NN2 coefficients from LIME-Time


3) Distance Data - ![Link to Distance dataset](https://drive.google.com/drive/folders/1CUPRlrwuGYfecG1TToUX8AdHq-YjaYIe?usp=sharing)
- Distance 50000 Evaluation Instances Correct with labels.csv
- GTE with 5000 num_samples
- NN1 coefficients from LIME-Distance

  **Run the Visualization.py notebook to replicate the charts 
  
  **Note: For Distance and Time dataset, due to the sheer size of the dataset, we already have trained models and evaluation instances ready in NN Models folder and Dataset folder respectively. Please ensure the corresponding jupyter notebooks are linked to the said files.**  
