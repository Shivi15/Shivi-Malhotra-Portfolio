# Shivi-Malhotra-Portfolio

Data Science Portfolio

# [Project 1: Covid-19 Spread in US - Project Overview](https://github.com/Shivi15/Covid-19-Spread-in-US)
* Analyzed the spread and gradual shift of Covid-19 prone counties in the US.
* Found out the counties with most covid positive cases, and the highest infection rate.
* Cleaned and performed an inner merge on the two datasets, i.e. Population of each county and Covid-19 cases of these counties.
* Using tableau's racing bar charts and animation found out, only 1.04% of LA counties are infected, 3.3% of Arizona counties are infected, and New York had an alarming infection rate of 13.5%.

Let’s look more closely at the top 10 counties by number of cases.


![](/Covid-19 Spread images/Counties ranked by Cumulative cases and deaths.gif)

  
Percentage of Population infected by County over time.

![](/Covid-19 Spread images/Percentage of population infected over time.gif)

The clustering of dark red counties seems to shift dramatically away from major metropolitan areas and into rural areas with lower population density. Suddenly, Los Angeles County looks fairly under control, while Arizona, Mississippi, and a smattering of counties in the Midwest look devastated.

To put numbers to this:

1. Only 1.05% of LA County is infected, whereas Maricopa County in Arizona (home to the state capital of Phoenix) has an infection rate of 3.3%.
2. New York County (Manhattan) is still alarming with an infection rate of 13.52%!
3. Trousdale County in Tennessee, with a population of only 7816, has an infection rate of 13.2%. It would be impossible to live here and not know at least one person who’s been infected.

# [Project 2: Movie Recommendation System](https://github.com/Shivi15/Movie-Rec_System)
* Developed a Collaborative Filtering Recommender System. Considering only user preferences into account, and if the two users share the same interests.
* Using one-hot encoding, extracted and created a search for a movie by genres.
* Performed data cleaning before learning about the distribution of rating data.
* Implemented two modelling techniques, IBCF and UBCF. Evaluating the ROC curve and Precision-Recall curve, UBCF became the top model with 88.2% accuracy.

Output for the User ID 364 (picked just for example), the following movies are recommended:

![](/Movie Recommendation System/Output.png)

