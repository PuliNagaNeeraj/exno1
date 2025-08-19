# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

```
import pandas as pd
df  = pd.read_csv("Data_set.csv")
df
```

<img width="1195" height="383" alt="image" src="https://github.com/user-attachments/assets/a3a311d2-2608-415a-b9a6-167e77a9d4ae" />

```
df.describe()
```

<img width="760" height="262" alt="Screenshot 2025-08-19 105128" src="https://github.com/user-attachments/assets/09c26c84-5dbe-498f-9203-16cac512b590" />

```
df.info()
```

<img width="515" height="318" alt="Screenshot 2025-08-19 105227" src="https://github.com/user-attachments/assets/2878fceb-e947-47d4-b90f-5110d0e5d7f1" />

```
df.head(4)
```

<img width="1179" height="159" alt="Screenshot 2025-08-19 105312" src="https://github.com/user-attachments/assets/26787dca-100e-49c8-ba84-ee6d2d92f11d" />
          

# Result
          <<include your Result here>>
