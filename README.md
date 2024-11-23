# Correlation of Movie Dataset

### Project Overview
Explore correlations between variables in a movie dataset (e.g., budget and gross income) to predict trends and analyze factors contributing to a movie's success.

### Tools
Anaconda - Jupyter notebook

### Data cleaning/Prepartion
- Rows with missing data were removed
- Checked the data types to ensure that numerical values are stored as appropriate data types (budget and gross as integers)

### Correlation
The correlation coefficient between budget and gross income to assess their relationship:
```python
y = df['budget']
x = df['gross']
correlation = y.corr(x)
print('Correlation between Budget and Gross:', correlation)
```
### Visualization
Scatter Plot to visualize the correlation between budget and gross income
Generate a correlation matrix between budget and gross income

### Result
Positive Correlation between Budget and Gross: 0.7402465439219624
