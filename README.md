### Table of Contents
<b> </b>
- [Project Motivation](#[Project Motivation)
- [Questions answered](#Questions answered)
- [Libraries used](#Libraries used)
- [Files in the Repository](#Files in the Repository)
- [Blog Post Link](#Blog Post Link)
- [Summary of Analysis](#) - Does price have any impact on review scores in Seattle and Boston? - How do Seattle and Boston homeowners describe their houses? Is there a difference in   the way top reviewed houses are described? - What are the best neighbourhoods to stay in Seattle and Boston?
- [Acknowledgements](#Acknowledgements)

### Project Motivation
This project is being done as a part of the Udacity's Data Scientist Nano Degree program Term 2. The project is later used to convey the results using a Blog post.

The questions I intended to answer does not need any Data science models to be explored and hence, I've left them out for this particular project. The emphasis has been laid upon presenting the data as clearly and meaningfully as possible. While, there have been others who worked on the same data, I have purposefully, avoided to answer regular questions and tried to look at unusual questions.

### Questions answered
We will explore the Airbnb Seattle and Boston data and answer 3 major questions
<b></b>
- Does price have any impact on review scores in Seattle and Boston?
- How do Seattle and Boston homeowners describe their houses? Is there a difference in the way top reviewed houses are described?
- What are the best neighbourhoods to stay in Seattle and Boston?

#### Libraries used:
<b></b>
- Numpy
- Pandas
- Matplotlib.pyplot
- Seaborn
- PIL.Image
- wordcloud

#### Files in the Repository
- Seattle_listings.csv - Raw Seattle listings data as of February 09, 2019 provided by Inside Airbnb team. Data can be found here
- Boston_listings.csv - Raw Boston listings data as of February 09, 2019 provided by Inside Airbnb team. Data can be found here
- Seattle_cleaned.csv - Cleaned csv file generated after few modifications done on the original data set of Seattle listings.
- Boston_cleaned.csv - Cleaned csv file generated after few modifications done on the original data set of Boston listings.
- Airbnb Listings for Seattle and Boston.ipynb - Jupyter notebook containing all the data exploration and analysis done for the 3 questions I intended to answer.
- Airbnb Listings for Seattle and Boston.html - The HTML file of the jupyter notebook. It is always advisable to save your work as HTML for future reference and to share with those who do not     have jupyter notebook running in their systems.

#### Blog Post Link
<b></b>
- https://medium.com/@lella.sundeep/be-it-boston-or-seattle-airbnb-has-got-your-back-991fb3046013

#### Summary of Analysis
<b></b>
## Does price have any impact on review scores in Seattle and Boston?
As the prices go up, the review ratings also remain high.

This implies that at higher prices, listings generally are able to satisfy the higher demands and expectations of the travelers staying in the rooms.

## How do Seattle and Boston homeowners describe their houses? Is there a difference in the way top reviewed houses are described?
Seattle Discussion At an aggregate level for overall listings within Seattle, the summaries seem to have the following words at a higher frequency: beautiful, comfortable, private home, being near downtown, things being available at walking distance. Capitol Hill area also seems to be very popular.

When you compare it against the top 25 percentile homes in Seattle (75th percentile for review ratings in Seattle is 99), majority of the words are similar. However, there are few interesting words which had higher frequency amongst those with high ratings. These are neighborhood, kitchen, large, and downtown.

Boston Discussion At an aggregate level for overall listings within Boston, the summaries seem to have the following words at a higher frequency: downtown, Back bay location, beautiful, park, South end, private home, and park.

When you compare it against the top 25 percentile homes in Boston (75th percentile for review ratings in Boston is 98), majority of the words are similar. However, there are few interesting words which had higher frequency amongst those with high ratings. These are neighbourhood, located, being near restaurant, and close. Being close to happening places, seem to be the major driver behind getting higher ratings in Boston as per the word cloud.

## What are the best neighbourhoods to stay in Seattle and Boston?
In Seattle, Southeast Magnolia is the best neighborhood for Airbnb rooms.

Unlike Seattle, in Boston, there is no clear one neighbourhood but rather few choices depending on what one wants. The balanced choices are between Jamaica Plain and South Boston Waterfront which have relatively high number of listings and high review ratings. However if one wants to go purely by highest review rating scores, then he/she has to look at Roslindale and West Roxbury neighbourhoods.

#### Acknowledgements
<b></b>
- Inside Airbnb for providing us the data.
- Udacity for giving the direction and scope of the project
