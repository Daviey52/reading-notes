# Class Twelve

[Home](https://daviey52.github.io/reading-notes/)

## Pandas

Normally, we import pandas as “import pandas as pd”

We can create a Series by passing a list of values and letting pandas create a default integer index. For instance IN [3]:  s = pd.Series([1, 3, 5, np.nan, 6, 8])

We can create a Dataframe by passing a Numpy array, with a datetime index and labeled columns
IN [5] :  dates = pd.date_range("20130101", periods=6)

We can view data using df.head() and df.tail(). 5 is the default number of rows to be included by both methods.

We can display index and columns using df.index()

Df.to_numpy() gives a Numpy representation of the underlying data. It is important to note that NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column.

Df. Describe () shows a quick statistic summary of the data, including mean, SD, confidence levels.

We can sort by axis using df.sort_index(axis=1, ascending=False)

We can sort by values using df.sort_values(by="B")

We can select a single column using df.A

We can select by labels by using df.loc[] e.g df.loc[dates[0]]

We can select using position by df.iloc[3]

isIn can be used to filter given a given circumstance.

Pandas use np.nan to represent missing data

Reading from csv (pd.read_csv)

Writing to csv(df.to_csv)
