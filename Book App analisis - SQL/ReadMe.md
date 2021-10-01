# Book_App_analisis_SQL
Our company has bought a large subscription book reading service. The analyst's task is to analyze the database. It contains information about books, publishers, authors, as well as user reviews of books. This data will help formulate a value proposition for a new product.  
## Data description:
**Books table**  
Contains data about books:
- book_id - book ID;
- author_id - the author's ID;
- title — the title of the book;
- num_pages — number of pages;
- publication_date — date of publication of the book;
- publisher_id is the ID of the publisher.
  
**authors table**  
- Contains information about the authors:  
- author_id - the author's ID;  
- author — the author's name.  
  
**Publishers table**   
- Contains data about publishers:  
- publisher_id - publisher's ID;  
- publisher — the name of the publisher;  
  
**Ratings table**
- Contains data about user ratings of books:  
- rating_id - rating ID;  
- book_id - book ID;  
- username — the name of the user who left the rating;  
- rating - rating of the book.  
  
**Reviews table**  
- Contains data about user reviews:  
- review_id - review ID;  
- book_id - book ID;  
- username — the name of the review author;  
- text — the text of the review.  
  
## Decomposition of the problem  
1. Calculate how many books were published after January 1, 2000;  
2. For each book, count the number of reviews and the average rating;  
3. Determine the publisher that has released the largest number of books thicker than 50 pages - so you exclude the brochure from the analysis;  
4. Identify the author with the highest average rating of books — consider only books with 50 or more ratings;  
5. Calculate the average number of reviews from users who have given more than 50 ratings.  
