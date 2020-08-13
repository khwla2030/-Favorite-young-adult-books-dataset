# Project 4: Adults Book 


# Problem Statement:

* Sites and libraries are full of adult-oriented books, but adults find it difficult to choose the right choice for their passion.The recommendation system helped adults to  find the best authers  and books in their passion based on several things 
so lets Find how ?

### Dataset Description 

* This data was acquired from goodreads website.and the dataset from  Kaggel

kaggel :
https://www.kaggle.com/rawanalmalki/goodreads-dataset.

## Data dictionary 

|Feature|Type|Description|
|---|---|---|
|title_book|object|The column contains the title of the book series|
|titleseriesbook|object|The author's name for the books|
|author_name|object|The author's name for the books.|
|has_series|bool|The column shows if the book has a series or not.|
|series_number|int64|The number of series books.|
|avg_rating|float64|The number of votes for each rating (1 star, 2 stars, 3 stars, 4 stars, 5 stars) and gives you the mean rating.|
|total_rating|int64|The number of all votes for each rating.|
|voters|int64|The number of voters who add the book in their books list's on the website.|
|score|int64| The book's score based on multiple factors, including the number of voters who have voted for it and how highly those voters ranked the book in their books list's on the website, which they can rank the books in order of 1 to 100 on their list.|


# Executive Summary:

* At first I looked at the data and I think there is a strong correlation between the high rating and the  series of the book.
But after I cleaned the data and made some correction and visualization in order to see the relationships between the properties.
I found that there is a relationship between the number of voters and the Evaluation rate. The higher the number of voters, the higher the Evaluation rate(Positive relationship)

* Then, i found top 10 authors with most books for adults.
* Back to what I thought about the relationship of  Evaluation rate  and  if the book has series. The number of the book has series shows a slight increase from books that do not contain a series.


# Recomendation system

* Recommending books and author name.
* Recommendation of five authors with their most famous books based on the highest evaluation.