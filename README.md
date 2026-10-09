# Python Learning

A collection of Python practice notebooks, chapter-wise exercises, and data analysis projects documenting my learning journey.

This repository covers Python fundamentals, object-oriented programming, data manipulation with Pandas, and visualization with Matplotlib and Seaborn. It also includes a Superstore exploratory data analysis project with supporting presentation and video files.

## Topics Covered

| Area | Topics |
|---|---|
| Python fundamentals | Strings, conditions, loops, functions, user input, and exception handling |
| Data structures | Lists, tuples, sets, dictionaries, and list comprehensions |
| Functional programming | Lambda expressions, `map()`, `filter()`, and `reduce()` |
| Object-oriented programming | Classes, objects, constructors, encapsulation, inheritance, abstraction, and polymorphism |
| Modules | Creating and importing a custom arithmetic module |
| Data analysis | Reading CSV/TSV files, inspecting data, filtering, sorting, and handling missing values and duplicates |
| Pandas operations | Grouping, aggregation, pivot tables, cross-tabulation, concatenation, merging, and `apply()` |
| Visualization | Histograms, box plots, bar charts, scatter plots, line charts, pie charts, pair plots, and heatmaps |

## Repository Structure

The main learning materials are organized as follows. Dataset and supporting files are grouped with their related notebooks.

```text
Python_Learning/
├── Practice/
│   ├── Python_basics.ipynb
│   ├── Python_Coding_Questions_Part1.ipynb
│   ├── Python_For_DataAnalysis/
│   │   └── Pandas_Crash_Course.ipynb
│   ├── Advanced_Data_Analysis_WithPython/
│   │   └── Advanced_Data_Analysis.ipynb
│   ├── Data Visualization/
│   │   ├── Data Visualization.ipynb
│   │   └── Intermediate Data Visualization.ipynb
│   └── OOPS/
│       ├── OOPS_MASTERCLASS.ipynb
│       ├── Math_Module.py
│       └── import_math_module.ipynb
├── Tasks/
│   ├── Python_Chapter1/
│   │   ├── Task_1.ipynb
│   │   ├── Task_2.ipynb
│   │   ├── Task_3.ipynb
│   │   └── Task_4.ipynb
│   ├── Python_Chapter2/
│   │   ├── Task_1.ipynb
│   │   └── Task_2.ipynb
│   ├── Python_Chapter4/
│   │   ├── Chapter_4.2_Task.ipynb
│   │   └── Chapter_4_06.ipynb
│   ├── Python_Chapter5/
│   │   ├── Superstore_Project.ipynb
│   │   ├── Superstore.csv
│   │   ├── SUPERSTORE DATA ANALYSIS.pptx
│   │   └── SUPERSTORE DATA ANALYSIS.mp4
│   └── Python_Chapter6/
│       └── OOPS_TASK.ipynb
├── Python_Interview_questions.docx
├── Python_Recab_Session_ppt.zip
└── .gitignore
```

## Practice Highlights

### Python Exercises and Games

Build familiarity with Python through string operations, collection methods, control flow, and small interactive games:

- **Number Guessing:** Practice loops, conditions, random numbers, and exception handling.
- **Rock, Paper, Scissors:** Compare user input with a randomly selected computer choice.
- **Word Guessing:** Practice string manipulation, tracking guesses, and input validation.

### Data Analysis with Pandas

Explore restaurant orders, football statistics, employee records, insurance data, and sales transactions.

Exercises include:

- Inspecting data types, missing values, and summary statistics.
- Filtering records and ranking grouped results.
- Calculating revenue and creating derived columns.
- Combining annual sales datasets.
- Practicing joins, pivot tables, and cross-tabulation.

### Data Visualization

Use the `mtcars` dataset and small example datasets to explore distributions, compare categories, and visualize relationships through Matplotlib and Seaborn.

### Object-Oriented Programming

Practice class design through bank account, vehicle, and delivery examples. A separate arithmetic module demonstrates how to organize functions and import them into a notebook.

## Featured Project: Superstore Analysis

[View the Superstore notebook](Tasks/Python_Chapter5/Superstore_Project.ipynb)

This project explores sales and profit using Pandas, Matplotlib, and Seaborn. It includes data inspection, date conversion, grouped summaries, and charts addressing:

- Sales and profit by product category.
- Sales by region.
- Top 10 states by sales.
- Sales contribution by customer segment.
- Top 10 products by sales.

The notebook references the [Superstore dataset on Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).

## Getting Started

### 1. Download the Repository

Clone it using Git:

```bash
git clone https://github.com/sujinoven/Python_Learning.git
cd Python_Learning
```

Alternatively, select **Code → Download ZIP** on GitHub and extract the files.

### 2. Install the Required Packages

With Python 3 and pip available, install Jupyter and the libraries used in the notebooks:

```bash
python -m pip install notebook pandas numpy matplotlib seaborn
```

The repository does not currently include a pinned dependency file.

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open a notebook and run its cells in order. Interactive exercises will prompt for input.

Most data analysis notebooks load datasets using relative filenames. Keep the datasets alongside their notebooks and use the notebook’s folder as the working directory. Keep `Math_Module.py` beside `import_math_module.ipynb` for the custom module example.

## Suggested Learning Order

1. Start with Chapter 1 string and control-flow exercises.
2. Practice collections and DataFrame creation in Chapter 2.
3. Explore the number-guessing notebook and coding questions.
4. Work through the Pandas crash course.
5. Continue with advanced analysis and Chapter 4 exercises.
6. Explore visualization notebooks and the Superstore project.
7. Study OOP examples and complete the Chapter 6 exercises.

## Learning Notes

These notebooks contain learning exercises and exploratory work. Some cells include unfinished expressions or inconsistent column names that need correction before a complete run. Review outputs and interpretations as you work through each notebook.

## Author

**SUJINOVEN**  
[GitHub](https://github.com/sujinoven)
