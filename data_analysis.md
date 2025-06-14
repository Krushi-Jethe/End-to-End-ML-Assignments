# Data Analysis


The aim of the assignment is to familiarize you with exploratory data analysis. Through this assignment you should be able to get a good understanding of how to approach a given problem statement and analyze the data for a given use case.   

While having good data science skills is important it is also necessary to be able to write clean and self explanatory code which is reusable and follows the PEP-8 coding standards. For code formatting use black formatter and for linting python scripts use pylint. To use black formatter in your notebooks in the first block of code execute `%load_ext jupyter_black`. Formatting and linting of python scripts will be discussed in the upcoming assignments. 

Please use the following template to make your notebook clean:
```
# 1. Imports

[1] `%load_ext jupyter_black`

# 2. Data loading and cleaning

# 3. Data Analysis

## 3.1
### 3.1.1
### 3.1.2

## 3.2

# Conclusion
<your conclusion here>
```


## Exploration of pandas, matplotlib and seaborn library

*Note: These are just a few commonly used commands. Feel free to explore and try out more as you learn.*

#### Commands to explore
##### Pandas:
- `pd.pivot`
- `pd.melt`
- `pd.cut`
- `pd.merge`
- `pd.concat`
- `pd.get_dummies`
- `pd.unique`
- `pd.nunique`
- `pd.describe`
- `value_counts()` - also check for normalize option. When numbers are large %'s would give a good idea
- `isna` or `isnull`
- `notna` or `notnull`
- `isin`
- `to_datetime` - also check how to extract date time features. For e.g., `df["date"].dt.month` would return a pandas series containing the information about month.
- `groupby`
- `agg` - this could be utilized to obtain sum, min, max etc.
- `pipe`
- `quantile`
- `explode`
- `empty`
- `plot`
- `iterrows`
- `read_excel`, `read_csv`, `to_excel`, `to_csv`
  
*For more refer [here](https://pandas.pydata.org/docs/reference/index.html)*

##### Matplotlib & Seaborn:
- Learn how to make proper graphs by adjusting the settings for colors, linewidth, xticks/yticks, xlabels/ylables, title, creating neat grids
- Suggestion: When creating grids say you have to create 23 plots, to create a neat plot flatten the axes and iterate over these to plot since it would be easier to handle one dimension rather than two. Also ensure you delete the last two empty figures. Since the grid would be 5x5 which means 25 figures.

##### Ipython.display & HTML
- Try using HTML and display feature to display your tables or any type of content neatly. For example if you have 8 tables to display instead of displaying them one below the other create a 4x4 grid using HTML. Feel free to use AI tools for generating code for you.
- Optional: Get familiar with simple html commands `<h1>, <h2>, <code>, <u>, <table> etc.`

