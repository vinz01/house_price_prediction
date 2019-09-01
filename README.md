# house_price_prediction
In this project, I have predicted Housing sales price prices for King County, USA which includes Seattle. It includes prices of houses sold between May 2014 and May 2015.

Data :
kc_house_data.csv dataset in the project contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It has 19 house features plus the price and the id columns, along with 21613 observations.

Features :
The description for the 20 features is given below: 

1. id :- It is the unique numeric number assigned to each house being sold. 
2. date :- It is the date on which the house was sold out. 
3. bedrooms :- It determines number of bedrooms in a house. 
4. bathrooms :- It determines number of bathrooms in a bedroom of a house. 
5. sqft_living :- It is the measurement variable which determines the measurement of house in square foot. 
6. sqft_lot : It is also the measurement variable which determines square foot of the lot. 
7. floors: It determines total floors means levels of house. 
8. waterfront : This feature determines whether a house has a view to waterfront 0 means no 1 means yes. 
9. view : This feature determines whether a house has been viewed or not 0 means no 1 means yes. 
10. condition : It determines the overall condition of a house on a scale of 1 to 5. 
11. grade : It determines the overall grade given to the housing unit, based on King County grading system on a scale of 1 to 11. 
12. sqft_above : It determines square footage of house apart from basement. 
13. sqft_basement : It determines square footage of the basement of the house. 
14. yr_built : It detrmines the date of building of the house. 
15. yr_renovated : It detrmines year of renovation of house. 
16. zipcode : It determines the zipcode of the location of the house. 
17. lat : It determines the latitude of the location of the house. 
18. long : It determines the longitude of the location of the house. 
19. sqft_living15 : Living room area in 2015(implies-- some renovations) 
20. sqft_lot15 : lotSize area in 2015(implies-- some renovations) 

Target Variable :
price:- It is the price of house which we have to predict and this is our target variable. 

Model Evaluation :
I have done model evaluation based on following sklearn metric.

  [R2 Score] (http://statisticsbyjim.com/regression/interpret-r-squared-regression/)
  [Explained Variance Score] (https://en.wikipedia.org/wiki/Explained_variation)
  [Mean Squared Error] (https://www.statisticshowto.datasciencecentral.com/mean-squared-error/)
  Model score
