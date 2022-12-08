# Step 1

1. Run data_cleaning.ipynb
2. Run lr_model.ipynb

Then we obtain *processed.csv* in data folder, which can then be uploaded to http://aequitas.dssg.io/ for auditing. 

> Remember to select only desired columns.

# Step 2

1. Change sensitive_features in Cell 3 to the desired sensitive features to correct
2. Run fair_lr_model.ipynb

Then we obtain *fair_processed_[sensitive_features].csv* in data folder, which can then be uploaded to http://aequitas.dssg.io/ for auditing.

> Remember to select only desired columns. Also, remember that the algorithm would try to correct bias in one column if it was set as one of the sensitive_features in Cell 3.
