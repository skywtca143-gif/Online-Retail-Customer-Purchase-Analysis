# Online-Retail-Customer-Purchase-Analysis

# Online Retail Customer Purchase Dataset

## 1. Project Overview
This project is based on an Online Retail Customer Purchase Dataset using Python. It reads customer purchase data from a CSV file and displays basic information about the dataset.

The project uses the Pandas library to load and display the dataset.

## 2. Objectives
- To read customer purchase data from a CSV file.
- To display the first 10 records.
- To count the total number of records.
- To display dataset column names.
- To check dataset information.
- To understand the structure of retail customer data.

## 3. Technologies Used
- **Programming Language:** Python
- **Library:** Pandas
- **File Format:** CSV
- **IDE:** VS Code / PyCharm / Jupyter Notebook

## 4. Software Development Life Cycle (SDLC)

### Phase 1: Planning
The main goal of this project is to read and display online retail customer purchase data using Python.

### Phase 2: Requirement Analysis
Requirements:
- Python must be installed.
- Pandas library is required.
- CSV dataset file is required.
- A Python IDE or code editor is needed.

### Phase 3: System Design
The project follows a simple process:

1. Import the Pandas library.
2. Load the CSV dataset.
3. Display the first 10 rows.
4. Count total records.
5. Display column names.
6. Display dataset information.
7. Show successful completion message.

### Phase 4: Implementation
The project is implemented using Python and Pandas.

```python
import pandas as pd

df = pd.read_csv("online_retail_customer_purchase_dataset (1).csv")

print("Online Retail Customer Purchase Data")
print(df.head(10))

print("\nTotal Records:", len(df))

print("\nDataset Columns:")
print(df.columns)

print("\nDataset Information:")
print(df.info())

print("\nProject Completed Successfully!")
```

### Phase 5: Testing
The following tests are performed:

- Check whether the CSV file loads successfully.
- Verify that the first 10 records are displayed.
- Check the total number of records.
- Verify column names.
- Check dataset information.

### Phase 6: Deployment
The project can be executed using:
- VS Code
- PyCharm
- Jupyter Notebook
- Python IDLE

### Phase 7: Maintenance
Future improvements may include:
- Adding data cleaning.
- Adding customer purchase analysis.
- Creating graphs and charts.
- Generating reports.
- Adding a graphical user interface.

## 5. Installation and Execution

### Step 1: Install Python
Download Python from https://www.python.org/

### Step 2: Install Pandas
```bash
pip install pandas
```

### Step 3: Keep Files Together
Place these two files in the same folder:
- `main.py`
- `online_retail_customer_purchase_dataset (1).csv`

### Step 4: Run the Project
```bash
python main.py
```

## 6. Expected Output
- First 10 rows of the dataset.
- Total number of records.
- Dataset column names.
- Dataset information.
- Project completion message.

## 7. Conclusion
This project demonstrates how Python and Pandas can be used to read and display online retail customer purchase data. It provides basic knowledge of CSV file handling and dataset exploration.

## 8. Author
**Project Name:** Online Retail Customer Purchase Dataset  
**Language:** Python  
**Project Type:** Mini Project

Author Sanjeet kumar Yadav
