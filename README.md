# Next-Hikes
# Telco Project: Exploratory Data Analysis and Dimensionality Reduction

## Load Telecom Dataset:
Begin by importing the dataset into a pandas DataFrame and inspect its structure, encompassing variable names and data types.

## Task 1.1: Aggregate User Behavior Information:
Group the data by user, calculating key metrics such as the number of xDR sessions, session duration, total download/upload data, and aggregate data volume for each application. Form a new DataFrame housing the aggregated information.

## Task 1.2: Exploratory Data Analysis:

### Handle Missing Values:
Identify and address missing values by replacing them with the mean of the respective column using the `fillna()` function.

### Analyze Basic Metrics:
Compute descriptive statistics (mean, median, etc.) for relevant variables, shedding light on central tendencies and variations.

### Non-Graphical Univariate Analysis:
Compute dispersion parameters (e.g., standard deviation, range) for each quantitative variable to grasp data spread. Interpret these parameters to glean insights into distribution and variability.

### Graphical Univariate Analysis:
Select appropriate visualization methods (e.g., histograms, box plots) for each variable to portray their distributions. Interpret graphical representations to understand data distribution, skewness, and outlier presence.

### Bivariate Analysis:
Explore the relationship between each application and total download/upload data using scatter plots or correlation matrices. Interpret findings to comprehend the impact of different applications on data usage.

### Variable Transformations:
Segment users into the top five decile classes based on total session duration. Compute total data (DL+UL) per decile class, analyzing the distribution of data usage across these segments.

### Correlation Analysis:
Compute a correlation matrix for variables like Social Media, Google, Email, Youtube, Netflix, Gaming, and Other data. Interpret the matrix to identify relationships and dependencies between variables.

### Dimensionality Reduction:
Implement Principal Component Analysis (PCA) to reduce data dimensions. Interpret results by identifying influential components and understanding their contribution to overall variance.

## Adding the Dataset to SQL:
Incorporate the dataset into a SQL database for enhanced accessibility and querying capabilities.
![image](https://github.com/Rahuldahiya67/Next-Hikes/assets/116004410/46ef694b-4eb8-498d-8667-a22def2418df)
