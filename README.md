# VideoStreamingProject

### Setup:

This project is my proposed final project for the LaunchCode data analysis bootcamp. I'd look at movie and tv data from streaming services to examine ratings data against a variety of factors and see what performs both across platforms and within them.

### Potential business questions:

1. What genres perform well across different streaming platforms? Is there variability in which genres are popular by streaming service?
2. What directors or cast members seem to draw high reviews across the different streaming services?
3. How much does length of a tv show benefit or handicap it in ratings? Does this differ by genre?

### Proposed dataset:

One Kaggle user, Victor Soeiro, has scraped data from https://www.justwatch.com/us for multiple video streaming services. Data is from May of 2022. Each dataset is a separate service and includes two files with the titles (titles.csv) and the cast (credits.csv) for the title. The title info includes ratings data from IMDB and TMDB as well as things like length, genres, number of seasons, etc. The credits connect actors and directors to the title data. I plan to use some or all of the following sets: Hulu, Amazon Prime, HBO Max, Paramount, Disney+, Netflix. If possible, I'd like to create one overarching titles dataset and credits dataset to look at trends across all the platforms to use for Tableau (collectively they come to 27 mb of data, well within the 50 mb limit). I'd also probably run functions on each individually where that makes more sense.

#### Dataset links:

https://www.kaggle.com/datasets/victorsoeiro/hulu-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/amazon-prime-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/hbo-max-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/paramount-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/disney-tv-shows-and-movies; https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies


Data size: Hulu - 2.6 mb; Amazon - 9.8 mb; HBO - 4.7 mb; Paramount - 3.1 mb; Disney - 2 mb; Netflix - 5 mb

Data updated as of: May 2022

License: CCO: Public Domain
