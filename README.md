<image src="images/title_image.PNG" width="900" height="500">[^1]

### COMPANY QUERY: 
  Amazing Prime is a video platform for streaming movies and TV shows. Develop an algorithm to predict which low-budget movies being released will become popular so that they can buy the streaming rights at a bargain.

### COMPANY SOLUTION: 
  Host a ~ PREDICT THE POPULAR PICTURES ~ HACKATHON

# MY PART: Create the datasets for the Hackathon.

### Start Data
-	[Scrape of Wikipedia for all movies released since 1990 (JSON)](wikipedia-movies.json)
-	[Rating data from Movielines website (Kaggle data)](resources/wikipedia-movies.json)
- [Ratings CSV](resources/ratings.csv)

  <image src="images/source_data_screenshot.PNG" width="1100" height="600">

### Prep Work: Module Activities
[Steps 1-3 code](Mod_8_code.ipynb)
1.	Extract data from each source
2.	Transform (clean & structure)  it into 1 clean dataset
3.	Load that dataset into a SQL table

### CHALLENGE: Refactor steps 1-3 so that the data can be updated daily. 
4. Extract [ETL_function_test.ipynb](ETL_function_test.ipynb)
5. Transform [ETL_clean_wiki_movies.ipynb](ETL_clean_wiki_movies.ipynb)
6. Transform [ETL_clean_kaggle_data.ipynb](ETL_clean_kaggle_data.ipynb)
7. Load [ETL_create_database.ipynb](ETL_create_database.ipynb)

### Results
    
  [Ratings Table](resources/ratings_query.PNG)
    
  <image src="resources/ratings_query.PNG" width="900" height="280">
  
  [Movies Table](resources/movies_query.PNG)
  
  <image src="resources/movies_query.PNG" width="900" height="900">
    
[^1]: [Movie Theatre photo by Felix Mooneeram](https://unsplash.com/s/photos/movie). Published on March 15, 2017. Accessed Jan. 22, 2022.
