# Welcome to my Tidy Data Project!

### Project Overview
This project aims to clean up analyze, and visually represent a dataset using tidy data principles. My goal was to transform raw data from the Olympics dataset into a structured format that is easy to manipulate. The tidy data principles that guided my work are as follows:
- Each variable has its own column.
- Each observation is in its own row.
- Each type of observational unit fors a separate table.

I adhered to these principles to ensure consistency, efficiency, and simplicity in my data analysis. 

### Instructions to Run the Notebook 💻
Follow the steps below to run the notebook:
1. Download (or clone) this repository to your local machine.
2. Make sure you have installed Python!
3. Run the following command in your terminal: pip install pandas matplotlib seaborn
4. Open the Jupyter notebook environment and find the project directory.
5. Run the notebook cells in sequential order to clean, analyse, and visualize the data in my project! 😊

### Dataset Description 🏅
The Olympics dataset I used orignates from the 2008 Summer Olympics dataset by EDJNet (European Data Journalism Network), and contains information about Olympic medalists, their respective sports, and the type of medals they won. 

I used the following pre-processing steps:
1. I melted the dataset. More specifically, I reformatted the wide-form dataset into long-form with the melt() function.
2. I cleaned the strings by removing any unwanted characters using .str.replace(), and separated any combined columns using .str.split()
3. Assigned unique identifiers (IDs) to each medalist and sport using .groupby().ngroup()
4. Finally, I handled the numerous missing values by using .dropna() to remove incompelte entries.

### References 📖
Please see the [Tidy Data Paper](https://vita.had.co.nz/papers/tidy-data.pdf)  by Hadley Wickham and the [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)  for more reading on tidy data and data wrangling. 

### Some Visual Examples from My Project
1. Medal Count by Sport:
   
![image](https://github.com/user-attachments/assets/0f579052-09de-4007-a9a5-ff1e1d31492f)

2. Type of Medal by Gender:
   
![image](https://github.com/user-attachments/assets/bf2ec66b-3305-41f7-b364-96d829a6d2e2)



