# netflix-data-analysis-with-python
Analysis of Netflix data.

This project seeks to answer certain questions. Many pandas functions such as data cleaning, transformation and visualization are used to answer the questions.

* Q. 1) For 'House of Cards', what is the Show Id and Who is the Director of this show ?
* Q. 2) In which year the highest number of the TV Shows & Movies were released ? Show with Bar Graph.*
* Q. 3) How many Movies & TV Shows are in the dataset ? Show with Bar Graph.
* Q. 4) Show all the Movies that were released in year 2000.
* Q. 5) Show only the Titles of all TV Shows that were released in India only.
* Q. 6) Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix ?
* Q. 7) Show all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom".
* Q. 8) In how many movies/shows, Tom Cruise was cast ?


*head() - It shows the first N rows in the data (by default, N=5).
* tail () - It shows the last N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe.
* size - To show No. of total values(elements) in the dataset.
* columns - To show each Column Name.
* dtypes - To show the data-type of each column.
* info() - To show indexes, columns, data-types of each column, memory at once.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* unique() - It shows the all unique values of the series.
* nunique() - It shows the total no. of unique values in the series.
* duplicated( ) - To check row wise and detect the Duplicate rows.
* isnull( ) - To show where Null value is present.
* dropna( ) - It drops the rows that contains all missing values.
* isin( ) - To show all records including particular elements.
* str.contains( ) - To get all records that contains a given string.
* str.split( ) - It splits a column's string into different columns.
* to_datetime( ) - Converts the data-type of Date-Time Column into datetime[ns] datatype.
* dt.year.value_counts( ) - It counts the occurrence of all individual years in Time column.
* groupby( ) - Groupby is used to split the data into groups based on some criteria.
* sns.countplot(df['Col_name']) - To show the count of all unique values of any column in the form of bar graph.
* max( ), min( ) - It shows the maximum/minimum value of the series.
* mean( ) - It shows the mean value of the series.
