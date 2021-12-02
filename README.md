### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python.<br>
The code should run with no issues using Python versions 3.*.<br>
Word Cloud: https://github.com/amueller/word_cloud

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing Seattle Airbnb Open Data.
Specifically, I looked at the following questions:

1. Which words are used most in postive ratings?
2. Which neighbourhood and which month of the year to choose for economic reasons?
3. What are better price indicators: neighbourhood or property type and furnishing?

## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `Project_Writing_A_Data_Science_Blog_Post.ipynb` - a notebook of the analysis performed following the CRISP-DM process
* `calendar.csv`: including listing id and the price and availability for that day
* `listings.csv`: including full descriptions and average review score
* `reviews.csv`: including unique id for each reviewer and detailed comments
* `price_per_month.png`: bar chart of price analysis
* `price_per_neighbourhood.png`: bar chart of price analysis
* `top5_indicators.png`: horizontal bar chart price indicator coefficients
* `wordcloud_blurred.png`: world cloud chart of review comments with some blurred words
* `wordcloud_good_rating.png`: world cloud chart of review comments

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@matleib/can-you-guess-what-is-most-important-for-a-good-airbnb-rating-74781d37d178).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Airbnb and Kaggle for the data.
You can find the Licensing for the data and other descriptive information for the [Seattle data](https://www.kaggle.com/airbnb/seattle/data).  
