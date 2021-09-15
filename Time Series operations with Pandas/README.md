•	PandA-Z Algo  - Time series basic Operations
o	Learning to use pandas library
o	Importing time series data from csv files using pd.read_csv()
o	Using the df.head() and df.info() methods to get a snapshot of dataframe
o	Parsing datetime and making it as index column parse_dates, index_col
o	Finding an object at a particular location in the dataframe iloc[,]
o	Checking datatype type()
o	Converting strings to datetime objects pd.to_datetime()
o	Setting datetime column as index using set_index()
•	A-Z Algo  - Financial Data Analysis with Pandas
o	Importing price data from yahoo finance and saving it in a pandas dataframe, using yfinance library
o	Choosing stock ticker symbols, and downloading close price, adjusted close price, open price, and volume data for each ticker and for a particular time period using yf.download()
o	Exporting the stock prices dataframe to a csv file using df.to_csv()
o	Using header to redefine multi-index positions, resetting date as index column, and parsing it as datetime index
o	Flattening (or converting to a tuple) the multi-index columns using df.columns.to_flat_index()
o	Converting tuple index to multi-index using pd.MultiIndex.from_tuples()
o	Swapping column levels from inner to outer using df.swaplevel(), and then sorting index using df.sort_index()
o	Finding basic descriptive statistics for the dataframe using df.describe()
o	Creating a new dataframe from columns in existing dataframe by copying contents using new_df = df.loc[:, ''].copy()
o	Visualising closing stock prices using plot style seaborn from matplotlib library
o	Normalising a time series to 100
o	Using shift() method to calculate absolute and relative change in stock price over previous period (last week to this week, yesterday to today etc.)
o	Creating and adding new columns to a dataframe
o	Calculating Absolute and Relative changes in time series using diff() and pct_change() methods
o	Comparing contents of two columns using equals()
o	Resampling data into monthly, weekly, quarterly or annual periods using resample()
o	Measuring stock performance with MEAN Return and STD of Returns
o	Visualising returns using a histogram plot
o	
•	A-Z Algo  -  Advanced Financial Data Analysis
•	A-Z Algo  - Datetime Index Methods, Timezones and NA values
o	A closer look at Datetime index
o	Finding and inserting name of the day, quarter number, week number columns in a dataframe
o	Filling NA values with backfill (bfill), forwardfill (ffill) and interpolation. When we resample, reindex or merge time series, we might end up with NA or empty rows. We can handle such situations using these methods
o	Reindexing Datetime index
o	Interpolating missing entries using adjacent values
o	Localising datetime index to various time zones
o	Converting from one time zone to another
o	Concatenating data from various time zones
o	Importing and analysing time zone module pytz
