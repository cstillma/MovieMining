# MovieMining
Group project for CU Boulder CSPB4502 Data Mining class

## Group Members ##
- Caleb Stillman - cast9172@colorado.edu
- Graydon Sinclair - grsi7978@colorado.edu
- Stephen Tynan - stty1424@colorado.edu

## Description ##
The goal of this data mining project is to discover trends in film runtime such that the findings can be applied in the film industry to produce more successful movies. Our dataset, which can be found below, contains information on over 950,000 films. We will be mining this information to look at the runtime feature's impact on other features and vice versa. Among our goals in determining what relationships exist here are to identify the ideal film length associated with high ratings. 

## Summary of Findings ##
### Questions Sought ##
- Is it possible to predict the runtime of a film based on its genre?
- Is it possible to predict the runtime of a film based on its country of origin?
- Is it possible to predict the runtime of a film based on its date of release?
- Can an ideal film length (may be a range) be identified which corresponds to high ratings from viewers?

### Discoveries ### 
Multiple model types showed that it is possible to predict the runtime feature using various other independent variables such as genre and rating. Some models were more effective than others, with the linear and forest regression models showing some of the best results. Bayesian Belief Networks could also prove promising with an alternate encoding of the dataset. While modeling efforts gave useful and usable results, all models showed room for improvement, suggesting that further work on this project could yield more precise predictions and therefore greater utility in filmmaking applications.

## Application of Insights ##
One of the primary insights from our mining is the discovery that filmmakers could start to tailor their film runtimes to achieve targeted ratings, which could help commercial success and box office take. An additional insight from the BBN model illuminated cultural preferences, again allowing for an application in which the film industry can craft films to target runtimes that are more likely to be engaging and successful to an expected or desired market of filmgoers. 

## Video Demo and Final Paper ##
Link to video demo: 

Link to final project paper: 

## Dataset ##
Original: https://www.kaggle.com/datasets/gsimonx37/letterboxd/data

Working: https://github.com/cstillma/MovieMining/blob/main/Deliverables%20-%20Raw/encoded_df.csv
