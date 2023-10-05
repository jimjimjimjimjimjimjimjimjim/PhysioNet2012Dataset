
# PhysioNet2012 Dataset

You can do the following commands to get the `csv` file.
```bash

# You need "gdown" to download the dataset. If you have no this package, you can follow the command below to install the package.
# (Optional)
pip install gdown

# (Necessary)
gdown https://drive.google.com/uc\?id\=1hg-zZ2Eo3lcLK4CNWhWjwnIfvFyHjn-_

```

This document will briefly introduce the PhysioNet2012 dataset. This dataset collects 11988 patients' first 48 hours of ICU records starting from their hospitalization. The default task for the dataset is to predict whether the patient will die after 48 hours.  

There are three `csv` files: one for training data (`physionet_2012_train.csv`), one for validation data (`physionet_2012_val.csv`), and the other for testing data (`physionet_2012_test.csv`).

Each row is a log for the patient at the same timestamp and includes 41 features. Each `csv` file contains the following columns:

* **'pid'**: The id number of the sample.
* **'timestamp'**: the recorded time of the corresponding row.
* **'target'**: To indicate if the patient dies after the first 48 hours. "1" means the patient died and "0" represents the patient survived.
* **'Weight'**
* **'ALP'**
* **'ALT'**
* **'AST'**
* **'Albumin'**
* **'BUN'**
* **'Bilirubin'**
* **'Cholesterol'**
* **'Creatinine'**
* **'DiasABP'**
* **'FiO2'**
* **'GCS'**
* **'Glucose'**
* **'HCO3'**
* **'HCT'**
* **'HR'**
* **'K'**
* **'Lactate'**
* **'MAP'**
* **'MechVent'**
* **'Mg'**
* **'NIDiasABP'**
* **'NIMAP'**
* **'NISysABP'**
* **'Na'**
* **'PaCO2'**
* **'PaO2'**
* **'Platelets'**
* **'RespRate'**
* **'SaO2'**
* **'SysABP'**
* **'Temp'**
* **'TroponinI'**
* **'TroponinT'**
* **'Urine'**
* **'WBC'**
* **'pH'**
* **'Age'**
* **'Gender'**
* **'Height'**
* **'ICUType'**

## Reference
