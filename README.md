# VideoStreamingProject

### Setup:
This project analyzes a total of 25,445 tv shows and movies (often referred to collectively as "titles") across 6 major streaming services.

### Potential questions:
1. What titles were available to stream in May 2022?
2. What were the top 10 titles by Imdb rating?
3. What countries produce titles with the highest average Imdb rating and where are the majority of titles produced?
4. How do ratings, votes, and popularity scores compare across streaming services?
5. How do streaming services differ when it comes to release years and runtime distribution of their content?
6. Which streaming services carry the most titles in each genre?
7. What genres stood the test of time and how did their distribution change?
8. What actors and directors have the most credits in the last 20 years?
...and more!


### Proposed dataset:
One Kaggle user, Victor Soeiro, has scraped data from https://www.justwatch.com/us for multiple video streaming services. Data is from May of 2022. Each dataset is a separate service and includes two files with the titles (titles.csv) and the cast (credits.csv) for the title. The title info includes ratings data from IMDB and TMDB as well as things like length, genres, number of seasons, etc. The credits connect actors and directors to the title data. I plan to use some or all of the following sets: Hulu, Amazon Prime, HBO Max, Paramount, Disney+, Netflix. If possible, I'd like to create one overarching titles dataset and credits dataset to look at trends across all the platforms to use for Tableau (collectively they come to 27 mb of data, well within the 50 mb limit). 


#### Dataset links:
https://www.kaggle.com/datasets/victorsoeiro/hulu-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/amazon-prime-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/hbo-max-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/paramount-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/disney-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies


Data size: Hulu - 2.6 mb; Amazon - 9.8 mb; HBO - 4.7 mb; Paramount - 3.1 mb; Disney - 2 mb; Netflix - 5 mb

Data updated as of: May 2022

License: CCO: Public Domain
