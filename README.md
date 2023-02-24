# Bengaluru House Price Prediction of Different Loacalites using Machine Learning Models such as Linear Regression, Decesion Trees, Lassos.

Predicting house prices can be a complex task that involves multiple variables, such as location, property size, age, condition, amenities, and market trends. However, I can provide you with a general idea of the factors that influence house prices in Bengaluru, India, and some strategies you can use to predict them.

**Factors Affecting House Prices in Bengaluru:**

**Location:** Bengaluru is a large city with various neighborhoods that differ in terms of accessibility, connectivity, infrastructure, amenities, and livability. Some of the most expensive areas are Koramangala, Indiranagar, Jayanagar, and MG Road, while some affordable ones are KR Puram, Whitefield, and Electronic City.

**Property size and type:** The size and type of the property, such as apartments, villas, independent houses, and plots, can significantly impact the prices. Generally, larger properties or ones with more rooms and bathrooms will have higher prices.

**Condition and age of the property:** The condition and age of the property can also affect the prices. Newly built or renovated properties with modern amenities and features will command higher prices than older ones that need repairs or maintenance.

**Amenities and facilities:** The availability of amenities and facilities such as parking, security, power backup, elevators, gym, and swimming pool can add value to the property and increase its price.

**Market trends:** The real estate market in Bengaluru is dynamic and influenced by several factors such as economic conditions, job opportunities, infrastructure development, and government policies. Prices can vary significantly depending on the demand and supply of properties in the market.

## Strategies to Predict House Prices in Bengaluru:

**Analyze recent sales data:** You can research the recent sales data of properties in different neighborhoods of Bengaluru to understand the price trends and compare them with the factors mentioned above.

**Consult with a real estate agent:** A local real estate agent can provide you with valuable insights into the market trends, pricing strategies, and negotiation tactics.

**Use online tools:** You can use online tools such as real estate websites and property portals to search for properties, compare prices, and analyze the market trends.

**Consider macroeconomic factors:** You should also consider the macroeconomic factors such as GDP growth, inflation, interest rates, and political stability that can affect the real estate market in Bengaluru.

Remember that predicting house prices is not an exact science and involves uncertainties and risks. You should do your due diligence, research thoroughly, and consult with experts before making any investment decisions.

## Visualization of Bedroom, Hall and Kitechen
![download](https://user-images.githubusercontent.com/90987160/221073271-43b7c838-dbc5-490c-863c-7a71ba020b21.png)

## Visualization of Bathing Area
![download (1)](https://user-images.githubusercontent.com/90987160/221073381-d094c91c-0b04-4374-94ef-8a21fb0fb581.png)

## Price per square feet
![download (2)](https://user-images.githubusercontent.com/90987160/221073509-8d87aa61-b9d1-4b19-8082-5914a1693264.png)

## Rajaji Nagar Area Visuzalization 
![download (3)](https://user-images.githubusercontent.com/90987160/221073604-54e070ab-8806-4f1b-b27e-cf08d6c1bbb9.png)


## Visualization  of Price per Square Foot at Rajaji Nagar
![download (4)](https://user-images.githubusercontent.com/90987160/221073772-ad7f8dbe-0aed-4bde-8de4-1ce210732f01.png)
 
## Number of Bathrooms 2, 3 ,4 and 6 BHK
![download (5)](https://user-images.githubusercontent.com/90987160/221073911-d95c0347-5a31-4d6d-a11f-f34793c5f1c6.png)

## Best Score Model 
|   |  model | best_score  |  best_params |
|---|---|---|---|
| 0  | linear_regression	  |  0.818354	 |  {'normalize': True} |
|  1 |  lasso | 0.687429  | {'alpha': 1, 'selection': 'cyclic'}  |
|  2 | decision_tree  |  0.718892 | {'criterion': 'mse', 'splitter': 'random'}  |


## Price Prediction for '1st Phase JP Nagar':
86.50537337722247

## Price Prediction for '5th Phase JP Nagar':
38.93415026548578

## Price Prediction for 'Indira Nagar':
180.82820686320383
