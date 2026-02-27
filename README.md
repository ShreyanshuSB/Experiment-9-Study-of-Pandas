# Experiment-9-Study-of-Pandas

# Name: Shreyanshu Behera

# PRN: 25070123149

# Batch: ENTC A1

# Title

Study and Implementation of the Pandas Library in Python

# Aim

To study and implement the Pandas library in Python for efficient data handling, manipulation, analysis, and cleaning using Series and DataFrame data structures.

# Objectives

To understand the fundamental data structures of Pandas: Series and DataFrame.

To perform basic operations such as data creation, access, and modification.

To apply data manipulation techniques including adding and removing columns.

To perform conditional filtering and basic statistical analysis on datasets.

To understand metadata attributes such as shape, size, and dimensions for dataset analysis.

# Theory

Pandas is a powerful open-source Python library designed for data analysis and manipulation. Built on top of NumPy, it provides efficient and flexible data structures that simplify working with structured or labeled data. It is widely used for data preparation and analysis in modern Python workflows.

Core Data Structures

Series:
A one-dimensional labeled array capable of storing multiple data types such as integers, strings, and floating-point values.

DataFrame:
A two-dimensional, mutable, and heterogeneous tabular structure that organizes data into rows and columns. A DataFrame can be viewed as a collection of multiple Series sharing a common index.

Metadata Attributes

Pandas offers several attributes that help understand dataset structure:

Shape: Represents the number of rows and columns in a dataset (e.g., (3, 2)).

Dimensions (ndim): Indicates the number of axes; Series are 1D while DataFrames are 2D.

Size: Total number of elements present in the dataset.

Columns: Returns the labels of columns, enabling easy data selection and manipulation.

Data Operations
Updating and Modifying Data

DataFrames are mutable, allowing changes to data after creation:

Accessing and Updating: Values can be modified using label-based indexing such as .loc[].

Adding Columns: New columns can be added by assigning lists or Series to a new column name.

Dropping Columns: The drop() method removes unwanted data; using axis=1 targets columns, and inplace=True updates the original DataFrame.

Filtering Data

Filtering is performed using Boolean indexing:

Conditional Selection: Logical conditions (e.g., values greater than a specific number) generate a Boolean mask to select matching rows.

Applications: Useful for extracting specific records, identifying top performers, or detecting outliers.

Statistical Analysis

Pandas provides optimized built-in statistical functions such as mean(), max(), and min(). These vectorized operations allow quick analysis of numerical data without writing manual loops.

Applications of Pandas

Data cleaning and handling missing values (NaN).

Financial data analysis and trend evaluation.

Data preprocessing for Machine Learning models.

Managing and analyzing records obtained from databases.

# Conclusion

The study of the Pandas library highlights its effectiveness in managing structured data through Series and DataFrames. Metadata attributes help in understanding data structure, while filtering and modification operations enable efficient data handling. Its built-in statistical functions make Pandas significantly more powerful and efficient than standard Python data structures for analytical tasks.
