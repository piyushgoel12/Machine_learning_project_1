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

The second observation that we can derive is that the highest number of Non-Fiction books were sold in 2015 and the same year was the lowest for the Fiction books. The highest number of Fiction books were sold in the year 2021 i.e. 50% while that was the lowest for the Non-fiction books. Now I visulaized the data using Piechart, here I represented them according to every year and drew necessary insights from it. 

Then I drew conclusion to collect the bestselling author based on their appearences in the top 50 bestsellign books from the year 2009-2022. Now I'll notice top 10 bestselling authors from both the genres i.e. Fiction and Non-fictions. I've used 'fivethirtyeight' style from the matplotlib for the comparison and representation of the authors. 

Now we can see that there are many recurring books and we don't want duplicates so I've used drop_duplicates function to remove all the rows with duplicate bok names, and now we have the refined data. I've systematically represented the total number appearences of the same author and uniwue appearences in the very next column, and total number of reviews in another one. 

Conclusion
--------------
Now I anayzed the data and one could easily draw essential conclusions from this visulaization, for instance I can conclude that the author with most appearences in the unique books column is Jeff Kinney. We can conclude further things depending on the requirements from the client. 
Now that we have analyzed the data, we can perform certain things on this processed data, for instance we can perform sentiment analysis on the reviews of the books by many authors and can see which author has the best audience support and which one has to work with their audience. 

So, that was it from my side, I hope you liked it. 
You can follow me on Linkedin by clicking on the given link: https://www.linkedin.com/in/piyush-goel-6974b4203/
