# Netflix-Recommender-Systems
This python notebook provides an introduction to building movie recommender systems using data from the famous 2006 Netflix Prize Competition. Netflix offered a prize of one million dollars for the first algorithm that could beat its own recommendation system by 10%. The prize was finally won in 2009, by a team of researchers called “Bellkor’s Pragmatic Chaos,” after over three years of competition. More details [here](https://en.wikipedia.org/wiki/Netflix_Prize). 

Only a sample of the competition has been used in this notebook (to speed up processing time). Kaggle have made the full data available [here](https://www.kaggle.com/netflix-inc/netflix-prize-data).

## Main Goal
We'll be building and evaluating automated recommendation engines capable of telling us: *What are the top movies a user would most like to watch (which they haven't done already)?*

We'll be doing this using two different methods, **Content-Based Filtering** and **Collaborative Filtering**.

## Analysis Tasks
This notebook will be made up of the following high level steps:
1. Load in data
2. Basic EDA
3. Build Content-Based filtering system
4. Build and Evaluate Collaborative filtering systems
