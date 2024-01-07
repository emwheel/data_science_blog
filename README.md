# What makes up a London house price?
As someone who is looking to buy their next home in London, I was compelled to use my Python skills to analyse the relationship between multiple variables and the price of a property. 
Through Kaggle I was able to find a data set of 2023 house prices in a number of London Boroughs. This dataset contained multiple variables that could be used to determine the value of a house including; the number of bedrooms, the number of bathrooms, proximity to a local station, and the type of ownership available. 
There were both categorical and numerical variables available to analyse. 
The numerical variables were:
- Number of Bedrooms
- Number of Bathrooms
- Miles to the nearest train station
- Price in pounds (This is the variable we are trying to predict)
  
The categorical variables were:
- Has a garden
- Property Tenure (meaning the type of legal ownership available with 3 different options)
- The postcode
- The street
- The name of the nearest train station

For the purpose of this project I narrowed down my research to 3 key questions
1. Does the tenure of a property impact the property price?
2. Do the number of bedrooms or the number of bathrooms have a bigger impact on property price? 
3. How impactful is proximity to the nearest station on property price? 

With a focus on the above questions I removed any columns from the dataset that would not contribute to the analysis. 
I also removed any rows were the predicted variable, house price, was missing. I also removed row with missing data for the other key variables I was assessing the impact of. 
I then moved to reviewing the categorical variable, Property Tenure, and created dummy variables for each of the 3 tenure options so it could be assessed in the model.
