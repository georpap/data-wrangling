# Pandas data-wrangling project

### 1. Importing of the csv

Imported the csv file using a specific encoding type: 'cp1252'
(If opened with standard encoding encountered error)

### 2. Renaming of column names

Renamed Sex to Gender, Fatal (Y/N) to Fatal and removed space after Species

### 3. Checking for duplicates, missing values and similarities between columns

There were no duplicate rows in the dataframe

There were 2 columns with more than 99% of missing values so they were dropped
'Unnamed: 22', 'Unnamed: 23'

Columns were found that contained information identcal with other ones
Decided to drop them so to keep only one copy of each piece of information

Columns dropped after this procedure:
Case Number', 'Case Number.1', 'Case Number .2', 'href formula', 'href', 'original order'

### 4. Cleaning every column from irrelevant information

Cleaned columns:
'Fatal', 'Gender', 'Type', 'Name'
                                    
### 5. Export of a clean csv called GSAF5_clean.csv

After cleaning file can be opened with regular encoding
Encoding type cp1252 not necessary

