# Recs on Recs
#### a recommendation engine using NLP
#### of reviews from leafly.com
---
The requirements for this project were to use unsupervised learning and natural language processing techniques on text data. Additionally, all data was to be stored in a Mongo database.

## Project Motivation
---
My intent with this project was to provide a starting point for building out a recommender system for retail marijuana. Due to project requirements, I limited the scope to using reviews (text only) of popular strains in order to determine what strains are most similar. 

While a marketable product would contain a recommendation system based on user purchases, one could also integrate this NLP model to help consumers find products that others find have similar affects. Consumers who have medical needs may find this particularly useful.

## Findings
---
Within the most recent reviews (~100 each) of some of the most popular strains listed on [leafly.com](https://www.leafly.com/explore), I found 4 general topics:
1. Daytime use, helps with anxeity and depression.
2. Nighttime use, helps with insomnia.
3. Relaxation, helps with nerve pain.
4. Uplifting, creativity, helps with chronic pain.
![](~/Downloads/plot.png?raw=true)

For a visual representation of these topics within a 3-D space, please [click here](https://plot.ly/~n8pk/88/).
