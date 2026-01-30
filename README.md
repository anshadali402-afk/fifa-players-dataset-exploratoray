# fifa-players-dataset-exploratoray

FIFA Players Dataset – Exploratory Data Analysis (EDA)

 Project Description

This project performs Exploratory Data Analysis (EDA) on the FIFA Players dataset using Python and Pandas.
The goal is to analyze player attributes such as nationality, salary, height, club, and preferred foot, and to extract meaningful insights using basic data analysis and visualization techniques.

Dataset

File name: fifa_data.csv

Source: FIFA Players Dataset

Format: CSV (Comma Separated Values)

🛠 Tools & Libraries Used

Python 3

Pandas

Matplotlib

Jupyter Notebook

Objectives / Questions Answered

Which country has the most number of players?

Plot a bar chart of the top 5 countries with the most players.

Which player has the highest salary?

Plot a histogram to get the salary range of the players.

Who is the tallest player in FIFA?

Which club has the most number of players?

Which foot is most preferred by the players? (Bar chart)

 Data Preprocessing

The Wage column was converted from string format (e.g. €200K, €5M) to numeric values.

The Height column was converted from feet–inches format (e.g. 5'11") to centimeters for accurate comparison.

Missing and invalid values were handled safely during conversion.

 Visualizations

Bar charts were used for:

Top 5 countries by player count

Preferred foot distribution

Histogram was used for:

Salary distribution of players



A single country dominates in terms of player count.

Most players earn salaries in the lower range, with a few high-earning outliers.

One player stands out as the tallest in the dataset.

Certain clubs have significantly more players than others.

Right foot is the most preferred foot among players.

 How to Run the Project

Place fifa_data.csv in the project folder.

Open Jupyter Notebook.

Run the cells sequentially.

Ensure Pandas and Matplotlib are installed.

pip install pandas matplotlib

 Conclusion

This EDA provides a clear understanding of
