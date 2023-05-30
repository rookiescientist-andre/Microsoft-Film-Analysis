# Microsoft Film Analysis

**Author**: Andre Layton


## Overview

  Microsoft is creating a new movie studio division in an effort to compete with other big companies, like Apple and Amazon, that have been successfully putting out diverse media content. This project aims to analyze movie data from various sources and recommend the best type of film to create for the studio's initial content. The main focus behind the analysis is seeing which films are best to begin creating by calculating and comparing both the Domestic and Worldwide returns on investment (ROI), both measured in percentages. During the course of the analysis, the comparison shifted from ROIs to average ROIs from the datasets due to outliers. The results showed that while a majority of the movies from Box Office Mojo's movie budget dataset fell under Action, Comedy, Drama, or Adventure genres, which are the four most frequent genres in order, War and Mystery movies yielded the highest average ROI, both domestically and worldwide. However, those genres were lacking enough records to draw conclusions from, shown through the high error bars in both visuals for each genre; as such, if we focus on the genres with low error margins (like the top four mentioned earlier), our results recommend Adventure as the best genre to begin with for both domestic and global success and profit. Adventure films, on average, require a $75 million budget, but I am suggesting $100 million, at minimum, upwards to approximately $170 million, for both domestic and foreign success. 
  
## Business Problem

Microsoft has created a movie studio; however, the executives are stuck on what type of content to begin creating and investing in. In order to compete with companies who have been dominating the space thus far, I am looking at the film genres that provide the highest return on investment (ROI), both domestically and globally, in order to recommend the best type of film for Microsoft to begin creating. The significance in selecting a genre with a high ROI lies in the impact it could have on future films - if the genre we recommend produces a high ROI for Microsoft, it encourages investors and invites conversations for further film production. It also assures the executives that Microsoft can compete in this space/industry.

***

## Data & Methods

The data analysed came from both the IMDb and The Numbers websites. IMDb is a popular worldwide online database of infomation relating to all movies, television programs, video games and streaming content online. The Numbers, on the other hand, is a popular website that displays financial information related to films such as budget, domestic gross, worldwide gross, and etc. I used 1 file from IMDb and 1 file from The Numbers to answer the question of which genres were most successful, mainly focusing on the Domestic and Worldwide Gross sales along with budget.

After cleaning the information on each table such as column names and missing data, I joined the two datasets with a shared field, budgets_df3 and movie_basics_df together using the 'Movie Name' column as it was a unique identifier creating a new dataframe called final_df. However, I created a final_df2 and final_df3 where median ROIs for both domestic and worldwide levels, respectively, are filtered and refined for plotting. 
***

## Results

The first three plots depict the median and average Domestic ROI as well as the median Worldwide ROI by genre. Two of the plots - Median Domestic ROI and Median Worldwide ROI - clearly show that Adventure films are the best type to begin creating among the top four mentioned earlier, with Comedy coming in second, despite having the higher average Domestic ROI, as measured in this analysis. 

The next few visuals - the boxplot and multiple regression plots - exhibit how production budgets vary among the top four genres, and the bar chart shows that the Adventure films in the dataset required $75 million for production, on average. However, I am suggesting a production budget between $100-170 million, based on gross sale estimates, both domestically and worldwide, in order to cover investment costs and even generate potential profit. 

To improve confidence in the results next time I would:

Include the movie ratings and refine to include multiple genre characterizations in order to give a clear, more comprehensive picture of the dataset. In addition, research other companies and their initial content to measure similar potential success. 

***



## Conclusions

This analysis leads to three recommendations regarding types of movies that are best to begin creating:

1. START WITH ADVENTURE FILMS. Adventure films generated the highest median domestic and worldwide returns on investment, among the top four genres. We focused our analysis to those four genres due to outliers skewing the results (e.g., low budget films that found major success), and a lack of records for the other genres to confidently include them in the analysis. As such, Adventure films were the best choice to begin with, and is estimated to produce the highest median returns, as well as an average domestic ROI of approximately 130% - suggesting the film will make enough to cover production costs and even generate profit. 

2. A MINIUMUM BUDGET OF $100 MILLION. According to the average budget model above, prepare to spend a minimum of $75-80 million on this film. Despite the median budget being $55 million for Adventure films, according to the boxplot above, the visuals that follow suggest the higher budget range will generate enough revenue, domestically, to break even on production costs, or more than double the investment, worldwide. However, the budget minimum I am suggesting is $100 million - where the 75th percentile of films lie, as shown in the boxplot above. This is estimated to gross well over the initial investment, and generate profit, both domestically and globally.

3. A MAXIMUM BUDGET OF $170 MILLION. I am suggesting a maximum budget of approximately $170 million for the Adventure film. According to the models above, in order to break $200 million in domestic gross, an estimated budget of about $170 million will be required. That same estimated budget will far exceed the $400 million mark, globally, and thus lead to commercial success. 

***





## Repository Contents
***
Below is a list of the contents of this repository.

```
├── FILM_ANALYSIS_README.md             
├── Microsoft Film Analysis - Notebook.ipynb
├── Microsoft Film Analysis.pdf         
├── .gitignore                               
└── images                           
```
