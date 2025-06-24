## Day 1 - Python Basics

**Environment:**  
Jupyter Notebook

**Setup/Configuration:**  
- Installed Python 3.12.7
- Installed Anaconda Navigation (Windows)

**What I Learned:**  
- Variables, data types, and operators  
- Input/output and basic control flow  
- Wrote and ran Python scripts

**Blockers / Questions:**  
- No blockers

**📂 Files:**  
- ['GitHub'](https://github.com/Vinoth120130/quantlake-internship.git)
 
---

## Day 2 - Python Fundamentals

### Practiced:
- Data Structures: list, tuple, set, dict
- List comprehensions
- Dictionary nesting and lookup

### Functions:
- Factorial calculator
- Prime number checker

### Built-in Modules:
- math
- random
- datetime

### Exceptions:
- Division by zero
- Input validation

### Practice Problems:
- FizzBuzz
- Largest in list
- Reverse string

### Bugs Solved:
- Corrected dictionary key access
- Handled division by zero errors gracefully

### Challenges:
- FizzBuzz logic was easiest
- Nested dictionary access took a bit more effort

---

## Day 3 - Pandas Introduction

### Dataset Used:
- Dummy dataset created using Python dictionary
- Series created from scratch

### Tasks Completed:

#### Task 1: Pandas Basics
- Created a Pandas `Series` and `DataFrame` manually
- Explored structure using:
  - `.head()`, `.tail()`
  - `.shape`, `.columns`, `.index`, `.dtypes`

#### Task 2: Load and View Data *(if done)*
- Used `pd.read_csv()` to load dataset
- Inspected data using `.info()`, `.describe()`, `.isnull().sum()`

#### Task 3: Access & Filter *(if done)*
- Accessed columns with `df['column']` and `df[['col1', 'col2']]`
- Used `df.loc[]` and `df.iloc[]` for row access
- Added new column and dropped one

#### Task 4: Built-in Methods *(if done)*
- Used `.sort_values()`, `.value_counts()`, `.unique()`
- Computed `.mean()`, `.sum()`, `.min()`, `.max()`
- Included comments to explain each line

### Key Learnings:
- Difference between Series and DataFrame
- Quick inspection tools like `.head()` and `.info()`
- Filtering rows/columns using `.loc[]` and `.iloc[]`
- Importance of `.isnull().sum()` in identifying data quality issues

### Observations:
- DataFrames are extremely flexible and powerful for analysis
- Knowing how to filter, sort, and describe data saves a lot of time

