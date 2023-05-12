# Adult Census 
This report provides an overview of the code and its outputs for the GitHub readme file. The code focuses on manipulating and analyzing the adult census dataset using the Pandas library in Python. The dataset contains information about individuals' demographics, employment, education, marital status, and income.

Firstly, the necessary libraries, including Pandas, Matplotlib, Seaborn, and NumPy, are imported. Then, the dataset is loaded into a Pandas DataFrame using the pd.read_csv() function, and its contents are printed to the console using the print(df) statement.

Next, the DataFrame is filtered to include specific criteria: State-Gov, Bachelors, Never-Married, Adm-Clerical, Not-in-family, White, Male, United States, and <=50K. This is achieved by selecting the relevant columns using indexing or the .loc function. The filtered DataFrame is assigned to df2.

To enhance the readability of the DataFrame, the column names are renamed based on the provided instructions. The rename() function is used to map the existing column names to the new names. The renamed DataFrame is assigned to adult_df.

To analyze the job roles present in the dataset, a bar chart is created. The code groups the data by the 'Job-Role' column, counts the unique occurrences of each job role, and sorts them in ascending order. The resulting counts are visualized using a bar chart created with Matplotlib. The chart shows the count of unique jobs per job group in the 'Job-Role' column.

Further analysis focuses on individuals with a High School Graduate diploma and their earnings in the United States. Two separate bar plots are created to display the count of individuals earning <=50K and >50K. The data is filtered based on the 'Degree Status' column, selecting only those with 'HS-grad'. Then, the filtered data is divided into two groups: individuals earning <=50K and individuals earning >50K. The counts of job roles within each group are visualized using separate bar plots, providing insights into the distribution of job roles among individuals with a High School Graduate diploma and different income levels.

In conclusion, this GitHub readme report showcases code that manipulates and analyzes the adult census dataset using Pandas in Python. The code filters the dataset based on specific criteria, renames columns for clarity, and provides visualizations of job roles by count and income level. These analyses offer valuable insights into the distribution of job roles and income among individuals in the census dataset.
