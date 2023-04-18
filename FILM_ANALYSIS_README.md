# Microsoft Film Analysis

**Author**: Andre Layton

## Overview

Microsoft has decided to create a new movie studio and requires more insight into which types of films are best to begin creating. This project uses descriptive statistical analysis on data gathered from both the Internet Movie Database (IMDb) and The Numbers websites to gain insight into which genres produced the best returns on investment (ROI), both domestically and globally. Two seperate datasets were used for this analysis to gain insight into which genres of movies yielded the best median ROI on both levels, as well as which genres are most prevalent. The results of the top 3 genres show that Comedy and Drama movies generate high ROIs and are popular in number. My recommendation for which type of film to produce would be Comedy or Drama. 

## Business Problem

Microsoft has created a movie studio; however, the executives are stuck on what type of content to begin creating and investing in. In order to compete with companies like Apple and Amazon, who have been dominating the space thus far, I am looking at the film genres that provide the highest return on investment (ROI), both domestically and globally, in order to recommend the best genres for Microsoft to begin creating. The significance in selecting a genre with a high ROI lies in the impact it could have on future films - if the genre we recommend produces a high ROI for Microsoft, it encourages further film production and assures the executives that Microsoft can compete in this space/industry.


***

## Data & Methods

The data analysed came from both the IMDb and The Numbers websites. IMDb is a popular worldwide online database of infomation relating to all movies, television programs, video games and streaming content online. The Numbers, on the other hand, is a popular website that displays financial information related to films such as budget, domestic gross, worldwide gross, and etc. I used 1 file from IMDb and 1 file from The Numbers to answer the question of which genres were most successful, mainly focusing on the Domestic and Worldwide Gross sales along with budget.

After cleaning the information on each table such as column names and missing data, I joined the two datasets with a shared field, budgets_df3 and movie_basics_df together using the 'Movie Name' column as it was a unique identifier creating a new dataframe called final_df. However, I created a final_df2 and final_df3 where median ROIs for both domestic and worldwide levels, respectively, are filtered and refined for plotting. 
***

## Results

According to the first plot depicting the Genre Counts, Drama, Action, and Comedy make up the majority of records in our dataset, and the top movies based on budget. Two of the plots - Median Domestic ROI and Median Worldwide ROI - clearly show that Comedy and Drama are the best films to begin creating among the top three mentioned earlier, with Drama appearing in the top three in all categories measured in this analysis. 

There is a 4th graph in this analysis - a scatter plot of each record plotted by genre - which is included to fully depict the thought process and workflow process behind this project.

To improve confidence in the results next time I would:

Include the movie ratings and refine to include multiple genre characterizations in order to give a clear, more comprehensive picture of the dataset. In addition, research other companies and their initial content to measure similar potential success. 

***



## Conclusions

This analysis leads to three recommendations regarding types of movies that are best to begin creating:

Focus on the genres with low margins of error. While Musical and War movies have the highest returns on investment (ROIs), they are both in the bottom five in value counts, as well. As such, their margins of error are high - meaning that type of success may not be as consistent, or proven, as the plot shows. The genres with low error margins provide a better picture and potentially have more confidence in their results - primarily the top 7 with over 200 records.

Stick with the top 3 genres. Horror movies would not be a bad place to start; however, with the top 3 genres - and the majority of our data - being Drama, Action, and Comedy movies, I would focus my energy and resources on those genres that are popular in number and high in ROI, domestically and globally.

Start with a Comedy or Drama, depending on your goals. Comedy movies are shown to not only be popular in number, but also also produce high ROIs, and would be a great place to start. However, if the goal is to also get nominated for accolades and compete for awards, Dramas are generally the best route to go. Dramas, fortunately, fall in the top 3 in both ROIs, assuming we focus on the low error margins. In either route, I would also recommend casting high-profile actors/actresses to further promote the film and promote a high return on investment.

***





## Repository Contents
***
Below is a list of the contents of this repository.

```
├── FILM_ANALYSIS_README.md             
├── Microsoft Film Analysis - Notebook.ipynb
├── Film Analysis.pdf         
├── data                               
└── images                           
```
