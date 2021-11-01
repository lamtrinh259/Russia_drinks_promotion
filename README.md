The notebook can be accessed here (note: this project was submitted as an entry into a competition on Datacamp)
https://www.kaggle.com/lamtrinh259/russia-drink-promo

# Russia drinks promotion

Project synopsis: 
📖 Background
Your company owns a chain of stores across Russia that sell a variety of alcoholic drinks. The company recently ran a wine promotion in Saint Petersburg that was very successful. Due to the cost to the business, it isn’t possible to run the promotion in all regions. The marketing team would like to target 10 other regions that have similar buying habits to Saint Petersburg where they would expect the promotion to be similarly successful.

The data
The marketing team has sourced you with historical sales volumes per capita for several different drinks types.

"year" - year (1998-2016)
"region" - name of a federal subject of Russia. It could be oblast, republic, krai, autonomous okrug, federal city and a single autonomous oblast
"wine" - sale of wine in litres by year per capita
"beer" - sale of beer in litres by year per capita
"vodka" - sale of vodka in litres by year per capita
"champagne" - sale of champagne in litres by year per capita
"brandy" - sale of brandy in litres by year per capita

💪 Competition challenge
Recommend 10 additional regions they should select for the promotion.
Tell the story that supports your recommendations.

# My Methodology: 
We will use two different approaches to figure out the top 10 regions that are most similar to Saing Petersburg. The first method will involve hierarchical clustering, and the 2nd method will involve using similarity criteria such as cosine similarity and Euclidean distances between the regions.

In both cases, we'll only look average sales data across alcoholic beverages from the last 5 years of all regions in order to capture enough of the seasonality and also have enough "recentness" of the data. That is to say, older data (sales of vodka in 1998) will not matter much as a predictor or future sales (e.g., sales of vodka in 2017).

These are the sections of this notebook:

Data overview
Data preprocessing
Exploratory data analysis
Clustering
Collaborative filtering
Conclusion and recommendation
