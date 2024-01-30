# Crankshaft_List

As an analyst at Crankshaft List, where hundreds of free vehicle advertisements are posted on the website daily, the task at hand involves delving into a dataset spanning several years to discern the factors influencing vehicle prices.

## Goals

In this project, the primary goal is to unravel the key determinants of vehicle prices over the past few years. The journey begins with data preprocessing, followed by a meticulous examination of data quality and transformation processes. The project culminates in a comprehensive data analysis, drawing insights from the discoveries made during the data processing stages.

## Steps

The dataset containing information about car advertisement is stored in file /datasets/vehicles_us.csv. This project will consist of few steps:

1. **Data Review:**
   - Examine the quality of the dataset and address any anomalies.
   - Process the data to ensure it aligns with the analytical goals.

2. **Data Transformation:**
   - Apply necessary transformations to enhance the dataset for analysis.

3. **Data Analysis:**
   - Conduct a thorough analysis to uncover trends and patterns in vehicle pricing.

## Conclusion

Before delving into the analysis of available data, a comprehensive data preprocessing phase was executed. This involved addressing missing values, handling duplicate entries, and managing outliers to ensure the integrity of the dataset. Subsequently, an exploration of factors influencing car prices was conducted, revealing insights into the impact of vehicle type, color, transmission, age, and mileage. Each aspect is detailed below:

1. **Data Preprocessing:**
   - **Handling Missing Values:**
     - Identified and addressed missing values in the dataset to enhance data completeness.
   - **Duplicate Data:**
     - Checked for and removed duplicate entries to ensure accurate analysis.
   - **Outlier Treatment:**
     - Detected and managed outliers using removal or adjustment strategies based on their nature and impact.

2. **Factors Influencing Car Prices:**
   - **Vehicle Type:**
     - Larger vehicles like buses, trucks, and pickups exhibit the highest average selling prices, likely due to their size and utility.
     - Luxury cars such as coupes and convertibles follow with competitive pricing, reflecting their premium features.
     - Hatchback cars, in contrast, tend to have the lowest average prices, possibly due to their compact design and general affordability.

   - **Color of the Car:**
     - White and black cars are more prevalent and command higher prices, suggesting a preference for classic and neutral colors in the market.
     - Notably, SUVs in the color orange hold a higher value, indicating a potential market preference for distinctive colors in this vehicle category.

   - **Transmission Type:**
     - In city cars like sedans, manual transmission variants are priced lower than automatic counterparts, reflecting consumer preferences and demand.
     - This trend does not hold for SUVs, where manual transmission variants tend to be more expensive than automatic ones. The reasoning behind this could be explored further.

   - **Age and Mileage:**
     - The age and mileage of a car are inversely proportional to its price, suggesting that older cars with higher mileage generally have lower market value.
     - This aligns with the expected higher maintenance costs associated with older cars, influencing pricing decisions in the used car market.
    
## Future Work

While this analysis has shed light on key factors influencing car prices, there are avenues for further exploration and refinement:

1. **Market Trends:**
   - Investigate broader market trends and economic factors influencing car prices over time.

2. **Detailed Transmission Analysis:**
   - Delve deeper into the nuanced relationship between transmission types and car prices, especially in SUVs.

3. **Color Psychology:**
   - Explore the psychological impact of car colors on consumer preferences, potentially influencing pricing dynamics.

4. **Predictive Modeling:**
   - Develop predictive models to forecast future car prices based on identified factors, providing valuable insights for both sellers and buyers.

5. **Customer Surveys:**
   - Conduct surveys or gather customer feedback to understand preferences and expectations, contributing to a more comprehensive analysis.

These potential areas of exploration can enhance the depth and accuracy of insights derived from the dataset, offering a more nuanced understanding of the factors shaping the car sales landscape.
