Notes from first iteration of data 

# Feature Engineering

- dropped columns with too many missing values 

- changed string/categorical values with `LabelEncoder`

- To go down the data-rabbit hole ('dabbit-hole'), lots of ways of handling missing data. 

- Currently, the best Python package for imputing missing data seems to be [`fancyimpute`]
(https://github.com/iskandr/fancyimpute) Although this seems a bit much. `pd.interpolate()` seems to do the trick. 
The distributions before and after the interpolation look the same, so we didn't change things too much by filling in 
the missing values. 

# Some future directions: 
Implement Megan Risdal's feature engineering nb 
