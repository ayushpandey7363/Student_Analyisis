# Students Data Analysis

## 📌 Project Overview

This project demonstrates basic **student data analysis using Python and Pandas**. A student dataset is created using a Python dictionary and converted into a Pandas DataFrame.

The notebook focuses on selecting columns, viewing rows, filtering students, and applying multiple conditions.

## 🛠️ Technologies Used

- Python
- Pandas
- Jupyter Notebook

## 📊 Dataset

The dataset contains **8 students** with the following columns:

- RollNo
- Name
- Course
- City
- Age
- Marks

### Courses Included

- Python
- Java
- Fullstuck

### Cities Included

- Delhi
- Mumbai
- Pune
- Lucknow
- Gujrat

## 🔍 Analysis Performed

The notebook covers the following operations:

1. **Create a DataFrame**
   - Creates student data using a dictionary.
   - Converts the dictionary into a Pandas DataFrame.

2. **Select Columns**
   - Displays only the `Name` column.
   - Displays both `Name` and `Marks`.

3. **Display First Five Rows**
   - Uses `head()` to display the first five rows.

4. **Display First Row**
   - Uses `head(1)` to display the first row.

5. **Filter Students by Marks**
   - Displays students whose marks are greater than 80.

6. **Filter Students by Age**
   - Displays students whose age is greater than 21.

7. **Filter by Course**
   - Displays students enrolled in the Python course.

8. **Filter by City**
   - Displays students from Delhi.

9. **Apply Multiple Conditions**
   - Displays students whose marks are greater than 80 and age is greater than 20.

10. **Filter Multiple Courses**
    - Displays students from either Python or Java using `isin()`.

## 💻 Key Pandas Concepts

The project demonstrates:

```python
df["Name"]
df[["Name", "Marks"]]
df.head()
df.head(1)
df[df["Marks"] > 80]
df[df["Course"] == "Python"]
df[df["City"] == "Delhi"]
df[(df["Marks"] > 80) & (df["Age"] > 20)]
df[df["Course"].isin(["Python", "Java"])]
```

## 📁 Project Structure

```text
Students-Data-Analysis/
│
├── Students_Data_Analysis.ipynb
└── README.md
```

## 🎯 Project Objective

The objective of this project is to practice fundamental **Pandas DataFrame operations and conditional filtering** using student data.

## 📚 Learning Outcomes

After completing this project, you can understand:

- How to create a Pandas DataFrame
- How to select one or multiple columns
- How to view the first rows of a DataFrame
- How to filter data using conditions
- How to use `&` for multiple conditions
- How to use `isin()` for multiple values
- How to analyze structured student data with Pandas

## ▶️ How to Run

1. Install Python.
2. Install Pandas:

```bash
pip install pandas
```

3. Open `Students_Data_Analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells to perform the analysis.

## 👨‍💻 Project

**Students Data Analysis**  
Built with Python and Pandas for data analysis practice.
