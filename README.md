# Machine-Learning-Final-Project---Spearing-Rachel

Database used: vegetable pulses 2021

Database link:

https://www.ers.usda.gov/data-products/vegetables-and-pulses-data/vegetables-and-pulses-yearbook-tables/



My target column to predict is pricing for these vegetables. This can be related to over time, the type of vegetable, and the quantity of these vegetables.

Analyze: the relationship between the value of the vegetables is directly correlated to the type of vegetable, which is stored in ‘Commodity’. It also relates to year,  end use, category, unit, which is the size. the size of the order can affect the price, obviously. the time of year can affect the order. Geographic and Location don’t seem to affect it much.





1.	Graph of prices over time, separated by the vegetable types:


df = df.sort_values(by='Year', axis=0)
df.groupby(by='Year')
sns.lineplot(data=df, x=df['Year'], y=df['PublishValue'], hue=df['Commodity']  )


Graph:
1.	Graph of prices over time, separated by the vegetable types:
<img width="468" alt="GraphOne" src="https://user-images.githubusercontent.com/95445097/165222004-a60f11ca-4cef-410d-ae19-1f908befb4b8.png">

graph2 .Graph of units for each vegetable with rising years.
![Graph2](https://user-images.githubusercontent.com/95445097/165222063-411cf677-ce70-4dcf-9554-ea86da06ae2b.png)

3.	a pair plot showing the relationship of asparagus to the decade, years, commodity, endues, category, item, unit, country, state,location, and published value. 
![Graph3](https://user-images.githubusercontent.com/95445097/165222127-ce72c63d-7d98-4865-aebe-a93bc19994ee.png)



I’ve found that the price is related the type of vegetable and the year significantly. I think it is also possible to relate to units, if units was converted to a number and could be used in a regplot. I would train a dataset on to be able to predict the prices of different types of vegetables based on past years’ prices.
