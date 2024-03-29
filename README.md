# Master's in Data Science
## Illinois Institute of Technology, Chicago, IL
<p align="justify">
Seeing the slow life in a small desert town of Rajasthan to a fast-paced life of Chicago, I realized how
divergent worlds can co-exist in the era of the global village.</p><p align="justify">My journey, cultural shocks and learning from
various institutes and teachers made me discern, there is so much to learn, unlearn and relearn; and it can be
done wisely, with a comprehensive understanding of information. Here are a few projects that I got inspired to work on during my Master's degree at IIT, Chicago.</p>

# [Project 1: Cryptocurrency Dataset - Project Overview](https://github.com/Shivi15/crytpcurrency-test_data)
* Verified the speculation, whether regulatory incidents drive time-based cryptocurrency data.
* Gathered, arranged and cleaned data using Pandas libraries to improve research quality and accuracy by 20%.
* Identified the highly correlated cryptocurrencies (near to +1 or -1).
* Aligned the team to analyze the Price Trend exhibited by the positively correlated Cryptocurrencies.

<p align="justify">
The analysis revealed that Bitcoin is the first and most dominant cryptocurrency. Despite the rise in Altcoins,  Bitcoins will have the advantage of being widely recognized, operating as the primary  trading pair for all other Altcoins. As Bitcoin rises to $10k and potentially beyond, it  can be expected that Ethereum and other Altcoins follow suit.
</p>


![CryptocurrencyPrices](/Cryptocurrency/CryptocurrencyPrices.jpeg)
<p align="justify">
Let’s compare the heat-map outcomes for the years, 2016, 2017, and 2018. As we  can see in the below picture, the correlation has increased like a burning fire across  all the cryptocurrencies. And it occurred all in just a short period.
</p>

![heatmaps](/Cryptocurrency/heatmaps.jpeg)
<p align="justify">
Since the cryptocurrency market is the only market which isn’t under the control of  the government. The Bitcoins drastic rise at the end of December 2017, was  greatly driven by Chinese transactions, as they contributed the greatest to Bitcoin  transactions. Hence, directly or indirectly cryptocurrency market is affected by the  events happening around the world. It would be interesting to notice if any such  correlation exists. 
</p>

# [Project 2: Covid-19 Spread in US counties - Project Overview](https://github.com/Shivi15/Covid19_Spread_in_US)
* Analyzed the spread and gradual shift of Covid-19-prone counties in the US.
* Found out the counties with the most COVID-19-positive cases and the highest infection rate.
* Cleaned and performed an inner merge on the two datasets, i.e. Population of each county and COVID-19 cases of these counties.
* Using Tableau's racing bar charts and animation found out, that only 1.04% of LA counties are infected, 3.3% of Arizona counties are infected, and New York had an alarming infection rate of 13.5%.

Let’s look more closely at the top 10 counties by number of cases.

![Counties_ranked_by_Cumulative_cases_and_deaths](/Covid19_Spread_images/Counties_ranked_by_Cumulative_cases_and_deaths.gif)
<p align="justify">
Percentage of Population infected by County over time.
</p>
![Percentage of the population infected over time](/Covid19_Spread_images/Percentage_of_population_infected_over_time.gif)
<p align="justify">
The clustering of dark red counties seems to shift dramatically away from major metropolitan areas and into rural areas with lower population density. Suddenly, Los Angeles County looks fairly under control, while Arizona, Mississippi, and a smattering of counties in the Midwest look devastated.
</p>
To put numbers to this:

1. Only 1.05% of LA County is infected, whereas Maricopa County in Arizona (home to the state capital of Phoenix) has an infection rate of 3.3%.
2. New York County (Manhattan) is still alarming with an infection rate of 13.52%!
3. Trousdale County in Tennessee, with a population of only 7816, has an infection rate of 13.2%. It would be impossible to live here and not know at least one person who’s been infected.

# [Project 3: Movie Recommendation System - Project Overview](https://github.com/Shivi15/Movie_Rec_System)
* Developed a Collaborative Filtering Recommender System, considering only user preferences into account, and if the two users share the same interests.
* Using one-hot encoding, extracted and created a search for a movie by genre.
* Performed data cleaning before learning about the distribution of rating data.
* Implemented two modelling techniques, IBCF and UBCF. Evaluating the ROC curve and Precision-Recall curve, UBCF became the top model with 88.2% accuracy.

Output for the User ID 364 (picked just for example), the following movies are recommended:

![Output](/Movie_Recommendation_System/Output.png)

# [Project 4: Airbnb Data Analysis - Project Overview](https://github.com/LohithChowdary/Airbnb_Data_Analysis)
* Analyzed Airbnb listings in New York City to understand if nonstandard amenities can be added to increase revenue.
* Cleaned and performed Exploratory Data Analysis, by implementing techniques like a word cloud and term generation matrix, visualizing neighbourhoods with high Airbnb listings using tableau on a map and carrying out a sentimental analysis on reviews dataset to draw insights.
* Created features from Amenities by performing feature engineering.
* Finally, evaluated 5 different models, and found out that XGBoost showed maximum accuracy in predicting Airbnb listings' prices.
<p align="justify">
EDA on the price variable was one of the crucial steps in the complete EDA process. It was found that Manhattan’s average price was greater than the rest of the neighborhood groups. Brooklyn also has higher prices and is mostly because it's closer to Manhattan. Staten Island has higher prices because it's near to the central park.
</p>
![Amenities_Wordcloud](/Airbnb_Data_Analysis/Tableau_Images/Amenities_Wordcloud.png)
<p align="justify">
Now, in the image below, you can see that Average price is high for Manhattan. Since, Brooklyn neighbourhoods are close to Manhattan, they tend to have higher average prices. And in Staten Island areas close to state park tend to have higher prices.
</p>
![Neighbourhoods_with high prices](/Airbnb_Data_Analysis/Neighbourhoods_with_high_prices.png)
<p align="justify">
A review dataset is taken to derive more insights about the amenities. Customer reviews can provide a wealth of information if mined properly. 

A term document matrix has been created which uses the Airbnb customer reviews to find word associations, given a word it gives back closest words in reviews. Keywords like near, close, around, great, place, transit, store are used to find word associations. Finding associations has revealed some interesting insights. New amenities that interest Airbnb customers are found. These are the amenities that are missing in the primary dataset. As this information is missing in our primary dataset, we relied on foursquare API to get information about nearby amenities.
</p>
![Tweets](/Airbnb_Data_Analysis/Tweets.png)

|                       Contact                       |                      Email-ID                    |                     Linkedin                          |
| --------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------   |
|                    (312)-825-9224                   |           shivimalhotra115@gmail.com             | https://www.linkedin.com/in/shivi-malhotra-535443186/ |
