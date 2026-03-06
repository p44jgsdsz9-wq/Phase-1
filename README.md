Data Cleaning for Ames Housing Dataset

This code loads, explores, and cleans the Ames Housing dataset using Python. The dataset is first read from the file AmesHousing.csv and stored in a pandas DataFrame. After loading the data, basic exploration is performed to display the column names, dataset shape, and general information about each column.

The code then checks for missing values and duplicate rows to identify potential data quality issues. Columns with more than 50% missing values are removed, since they may not provide useful information. For the remaining data, missing values in numerical columns are filled using the median, while categorical columns are filled with the label "Unknown".

Duplicate rows are removed to ensure the dataset contains only unique records. Finally, a set of checks is performed to confirm that there are no missing values left and that all values in the SalePrice column are greater than zero. This process prepares the dataset for further analysis or machine learning tasks.
