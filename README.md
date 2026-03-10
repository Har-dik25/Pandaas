# Pandas Revision & Sandbox 🐼

A collection of Python scripts designed as a practical reference and learning guide for the **Pandas** data manipulation library. These files cover everything from initializing DataFrames to advanced data transformation and reshaping techniques.

## 🚀 Topics Covered

### 1. DataFrame Creation (`Pandas1.py`, `Pandas2.py`)
- Initializing DataFrames from basic Python structures like **Lists** and **Dictionaries**.
- Converting **NumPy Arrays** directly into DataFrames.
- Loading data from external files (e.g., `pd.read_csv('data.csv')`).

### 2. Data Inspection & Attributes (`Pandas1.py`, `Pandas2.py`)
Understanding the shape and content of your data using common attributes and functions:
- `.head()` and `.tail()` to preview rows.
- `.shape` to understand dimensionality.
- `.columns` and `.dtypes` to get column names and data types.
- `.info()` for a concise summary of the DataFrame including memory usage.
- `.describe()` for quick statistical summaries (mean, std, min, max, quartiles).

### 3. Data Manipulation & Transformation (`Pandas1.py`, `Pandas3.py`)
- **Indexing & Slicing:** Selecting specific rows, columns, or sub-matrices using label-based `.loc[]` and integer-based `.iloc[]`.
- **Filtering:** Selecting rows conditionally (e.g., `df[df['Age'] > 30]`).
- **Sorting:** Ordering data using `.sort_values()`.
- **Modifying Columns:** Adding computed columns or dropping existing ones (`.drop()`).
- **Handling Missing Data:** Filling `NaN` values using `.fillna()`.

### 4. Data Reshaping (`Pandas3.py`)
Advanced techniques for changing the layout of DataFrames:
- **Melting:** Converting "wide" format data to "long" format (`pd.melt()`).
- **Pivoting:** Converting "long" format back to "wide" format (`.pivot()`).
- **Stacking & Unstacking:** Pivotting the innermost column index into the innermost row index, and vice versa.

## 🛠 Prerequisites

To run these scripts, you need Python installed, along with `pandas` and `numpy`.

```bash
pip install pandas numpy
```

## 📝 Running the Scripts

Navigate into the repository and execute the scripts using your terminal:

```bash
python Pandas1.py
```
*(Note: Some scripts reference a local `data.csv`. Ensure you have dummy data available if testing CSV loading functionality).*