# Machine-Learning-Final-Project---Spearing-Rachel
Link to data set used: https://catalog.data.gov/dataset/mypyramid-food-raw-data
Attribution
Linke: https://catalog.data.gov/dataset/mypyramid-food-raw-data#sec-dates
Publisher: Food and Nutrition Service, Department of Agriculture
Maintainer Angela Leone
Metadata: created Date November 10,2020
Metadat updated data November 13, 2020

My Pyramid Food Raw Data

Food and Nutrotion Service DNS USDa


Target Column: Calories


Calories seems to have an interesting relationship with Saturated Fats, I would expect it to increase over time, but it doesn’t always, it is quite jerky. I don’t expect Food Code, Display Name,  or Portion display name eto have an impact on calories. I don’t know what Factor or Increment, or Multiplier means in this dataset.

Portion amount almost seems to have a negative relationship to calroies. A huge cluster is at the beginning with smaller portions relating to high calories. 

Factor doesn’t seem to have strong relationship to calories. Increment seems to have a small relationship.
Multiplier doesn’t seem to have a strong relationship to it. 

As expected, Grains has a strong relationship to calories. Whole_Grains, less so. Vegetables has a very slight correlation. Orange_Vegetables, Dark Green vegetables have almost no or a weak relationship. Starchy vegetables seems to have a little more. Other Vegetables, almost none. Fruits, very little. Milk has a stronger relationship, as well Dry Bean Peas. Oils has some relationship to calories. Solid fats has a strong relationship. Added Sugars has a slight relationship. Alcohol has very little to go off on. saturated fats appears to have a strong relationship.

For the rest of the food columns, it seems likely that if you increase the number of them in it, Calories will also increase. Determining the precise amount of correlation is left up to the future work.



First relationship:
The relationship between saturated fats and calories. It seems that drawing a line of best fit, that calories does increase while saturated fats increases alongside it.
![Picture1Import](https://user-images.githubusercontent.com/95445097/165677137-d41d1230-d210-4e38-8ef2-9f33a8289ff4.png)

Second was oils versus calories. It appears if you add more oils, your calories will go up, though not drastically.
![oilsgraphImport](https://user-images.githubusercontent.com/95445097/165677369-e84b9372-a48f-405e-befe-64b8d5c8955e.png)

Third The mean of calories plotted against the portion amount, set to one cup to make things fair in a scatter plot.

![Picture3Import](https://user-images.githubusercontent.com/95445097/165677384-b9d8fe62-7bdc-4bcc-8511-651b13ae41f8.png)
