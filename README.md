# 🎥Movies Dataset Exploration

## 🔍Project Overview
An exploratory analysis of a movies dataset from the year 2008-2021 to discover insights. The project shows a well-detailed exploratory data analysis (EDA) in Python using markowns/comments.

## 🎞Project Task
1. Data Import & Preparation:
- Load the movie dataset into a Pandas DataFrame using the pd.read_csv() function.
- Explore the DataFrame using df.head(), df.info(), and df.describe().
- Handle any missing values (e.g., using df.fillna()).
- Convert data types as needed (e.g., using pd.to_numeric()).

2. Data Exploration and Analysis:

a. NumPy:
- Calculate the average runtime of movies in each genre using np.mean() and groupby operations.
- Find the movie with the longest runtime using np.argmax().

b. Pandas:
- Create a new column for "movie age" by calculating the difference between the current year and the release year.
- Filter the DataFrame to display movies released in a specific year range.
- Analyze the relationship between runtime and rating using correlation (df.corr()).

c. Matplotlib:
- Create a histogram to visualise the distribution of movie ratings using plt.hist().
- Generate a scatter plot to show the relationship between runtime and rating using plt.scatter().
- Create a bar chart to compare the average rating of movies in different genres using plt.bar().

3. Data Visualization:
- Use Matplotlib to create visualisations that highlight interesting patterns or insights from the data.
- Add titles, labels, and legends to make your visualisations informative.

## 🛠Tools Used
- Python (Pandas, Numpy, Matplotlib), Jupyter Notebook

## 🔎Key Findings
- Found 9 missing values both in runtime and ratings columns which I populated with their mean.
- The movies' runtime and the ratings using correlation shows that there is weak or no linear relationship between the two.
- There's rating of 7 common among the audience, and around 6.3 as the least.
- Generally, the average rating of each genre were in the range of 6.8 - 7.1
- 2021 recorded the highest number of movie release (23) while the least (8) was in 2014.
- All the genres are produced almost at the same rate.

## 🎬Conclusion
From the visualizations so far, I could see that in 2021 there has seen a tremendous amount of effort by movie producers to release more films compared to the previous years. 
Since the ratings and the runtime seem to have a very weak correlation, and the ratings amongst the genres seem to be at close range. I believe more research is needed to understand the reason behind the recent sudden surge of production in the movie industry, or why previous years (especially 2014) were lagging.
