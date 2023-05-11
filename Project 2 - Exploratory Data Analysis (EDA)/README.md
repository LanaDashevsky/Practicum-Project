## Project 2 - Factors affecting the price of a car

**Technologies and Tools** - Python, Jupyter, Pandas, Numpy, Seaborn, Matplotlib, Plotly

**Goal:** Compare the music preferences of the cities of Springfield and Shelbyville.

**Project Description**

You're an analyst at Crankshaft List. Hundreds of free advertisements for used vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.

## Tasks
1. Study the following parameters: price, vehicle's age when the ad was placed, mileage, number of cylinders, and condition. 
2. Study how many days advertisements were displayed (days_listed). Describe the typical lifetime of an ad. Determine when ads were removed quickly, and when they were listed for an abnormally long time.
3. Analyze the number of ads and the average price for each type of vehicle.
4. What factors impact the price most? Take each of the popular types you detected at the previous stage and study whether the price depends on age, mileage, condition, transmission type, and color. 

## Overall Conclusion

- We have seen that the typical lifetime of advertisements is between 19 and 53 days, and those that last more than 105 days we can consider as anomalously long.
- For short ads, which were only 5 days old, we made an assumption that these were cars in excellent condition for a lower price and they quickly sold out, but this was not confirmed.
- The factor that most influences the price is the age of the car. Pearson correlation coefficient for SUVs - 0.58, for sedans - 0.61.
- The three most popular type featured in ads are SUVs, sedans and trucks - 11380, 11264 and 11055.
- For SUVs, cars in black color and manual transmission cars were more expensive.
- For sedans, black and white cars were almost equally expensive, with silver being the most popular color - 1880. 
- Cars with an automatic transmission were listed as more expensive than a manual transmission.

LINK: [Detailed Project](Project_2_Exploratory_Data_Analysis.ipynb)
