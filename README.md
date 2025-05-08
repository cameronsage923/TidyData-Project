
# 📊 Tidy Data Project – Olympic Medalist Analysis
Welcome! This is a data cleaning and analysis project built using Python and Pandas, focused on applying tidy data principles to transform and visualize Olympic medalist data from the 2008 Summer Games.

## 📊 Project Overview
This project demonstrates how raw data can be reshaped, cleaned, and analyzed using the core principles of tidy data:

- Each variable is in its own column

- Each observation is in its own row

- Each type of observational unit forms a separate table

The dataset—originally messy and wide-form—was transformed into a clean, long-form structure for analysis. The end result is a well-organized dataset ready for insightful visualizations and exploratory analysis.

## 🧠 Skills & Technologies Used
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook
- Data wrangling & tidy data theory

## 📸 Project Visuals
Medal Count by Sport:
1. Medal Count by Sport:
   
![image](https://github.com/user-attachments/assets/0f579052-09de-4007-a9a5-ff1e1d31492f)

2. Type of Medal by Gender:
   
![image](https://github.com/user-attachments/assets/bf2ec66b-3305-41f7-b364-96d829a6d2e2)

##🚀 Run the Project Locally
First, ensure you have Python 3.8+ and Jupyter Notebook installed. Then:

```bash
    Copy code
    pip install pandas matplotlib seaborn
```
Next:

1. Clone this repository or download the .ipynb file

2. Open the notebook in Jupyter

3. Run the cells sequentially to clean, transform, and visualize the dataset

## 📄 Dataset Details
This project uses a dataset from the 2008 Summer Olympics, made available by the European Data Journalism Network (EDJNet). The dataset includes:

- Medalists and their sports
- Country, gender, and medal type
- Additional attributes like event and discipline

## 🛠 Key Cleaning Steps
- Used melt() to reshape wide-form data into tidy long-form

- Cleaned strings and split combined values with .str.replace() and .str.split()

- Created unique IDs using groupby().ngroup()

- Removed incomplete rows using .dropna()

## 📚 References
- Tidy Data – Hadley Wickham
- Pandas Cheat Sheet







   

