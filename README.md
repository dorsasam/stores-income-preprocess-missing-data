# Department Store Data Missing Value Analysis
## Project Description
This project focuses on handling missing data in a dataset containing information on department stores worldwide. 
In a previous [project](https://github.com/dorsasam/stores-income-data-preprocessing), we preprocessed the dataset by standardising the country names. 
This time, our goal is to identify, analyze, and address the missing data in the dataset.

## Installation
- Clone the repository:
```bash

git clone https://github.com/yourusername/department-store-missing-data-analysis.git
```
- Navigate to the project directory:
```bash
cd department-store-missing-data-analysis
```
- Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
- Install the required dependencies:
```bash
pip install -r requirements.txt
```
## Data Description
The dataset contains the following columns:

- **id**: Unique identifier for each department store.
- **store_name**: Name of the department store.
- **store_email**: Email address of the department store.
- **country**: Country where the department store is located (contains inconsistent country names).
- **income**: Income of the department store.
- **date_measured**: The date and time of the income measurement.

## Methodology
- Identifying Missing Data
We begin by identifying the missing data in the dataset:
1. Count the number of missing values in each column.
2. Generate a summary report indicating the columns with missing data and the extent of missingness.
3. Analysing Missing Data

- For columns with missing data, we investigate the underlying distribution:
    - Determine the pattern of missing data to classify it as MAR (Missing At Random), MNAR (Missing Not At Random), or MCAR (Missing Completely At Random).
    - Visualise the distribution of data to aid in understanding the nature of the missing values.

- Handling Missing Data
Based on the analysis, we decide on the best approach to handle the missing data:
   - Impute missing values using appropriate methods (mean, median, mode, regression, etc.).
   - Discuss the rationale behind the chosen method for each column with missing data.





