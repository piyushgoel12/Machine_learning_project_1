Introduction
-----------------
This is my first Machine learning project. Here, I took the Amazon's Top 50 Bestselling Books from the year 2009 to. 2022 and analyzed it to draw required conclusions from it. 

Dataset
-----------------
The data that I'll be using for this machine learning project is "Amazon Top 50 Bestselling Books 2009 - 2022". The dataset is available on Kaggle and can be downlaoded from the link below:
https://www.kaggle.com/datasets/chriskachmar/amazon-top-50-bestselling-books-2009-2022

The  dataset contains 700 books in total which are further classified into Fictions and Non-fictions.
Along with 700 books there are 7 columns pertaning to the relevant information such as: 
1. Name: Name implies the title of the book.
2. Author: This column represents the author of the book in context. 
3. User rating: This represnts the ratings (out of 5 stars) alloted to the book by the user.
4. Reviews: This represents the total number of reviews listed for book. 
5. Price: Price of the book. The price available here is rounded for easy calculations. 
6. Year: The specific year in which the book was published. 
7. Genre: The book type. 
So, these were 7 columns of the dataset and their relevence for the anazlyzing of the data. 

Data_Alteration
------------------
Here, I have altered the data and renamed some columns like User rating to user_rating. Along with this I corrected some spelling mistakes in the dataset. 

Data analysis using Python. 
-------------------
In the dataset, the genre feature or column plays an important role as it helped me anazlyze the type of book that is much popular among the folks for better understanding of the dataset. 
Here we can see the districution, Non-Fiction books occupies 53.51% of the total volume of books while Fiction books occupy 46.49% of the total number of books. Hence, we can say that Non-fiction is much popular genre than fiction. (This is the first outcome of our analysis.)

The second observation that we can derive is that the highest number of Non-Fiction books were sold in 2015 and the same year was the lowest for the Fiction books. The highest number of Fiction books were sold in the year 2021 i.e. 50% while that was the lowest for the Non-fiction books. Now I tried to visulaize the data using Piechart.

