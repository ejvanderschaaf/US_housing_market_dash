# US_housing_market_dash
This is a dashboard originally designed in Tableau and then recreated using Plotly to analyze trends in US housing market data.

### Background

This dataset concerns the US housing market. I found it on Kaggle (US Housing Trends, 2024) but it’s sourced from Zillow. The data spans from 2018 – 2024 and provides measures of home value, time on the market, and price cuts to the property.

This data set caught my eye because of the reputation of the housing market. Housing prices and availability are only becoming more of an issue. I thought this data set might provide some insight into the situation.
The audience for the dashboards I’ve designed is anyone interested in the US housing market. It may be of especial interest to those involved in the buying and selling of homes. These people may have some prior knowledge of the market but be unaware of some of the recent trends. They may also be people who are interested in drilling down further into a particular geographic area. They may want to know more about how to set an appropriate price for a home or when might be a good time to sell.

The story I want to tell is about the relationship between home value, time on the market, and price cuts. Across the continental US, the period of 2021 – 2022 was a somewhat dramatic one for housing. This may also be tied in with the COVID pandemic, though that isn’t explored directly here. In 2021 and 2022 the average time a home was on the market before it went into pending status was only 32 days. This coincided with a rapid rise in home values. Home price cuts also peaked in 2022. These trends are starting to stabilize. This would be important for those involved in the buying and selling of homes to take into account.

The big idea for these dashboards is that although there has been some extreme housing market behavior in recent years, these trends are starting to stabilize – homes may take longer to sell and be less marked down.
Because this data set contains three key metrics (home value, days until pending, and price cut) I wanted to showcase the relationship between them. One dashboard focused on the relationship between average days until pending and average price cut. These metrics can be compared side-by-side in two shaded maps of the US and also below in a combo bar and line graph. Clicking on one of the states in either map filters the dashboard, allowing the user to explore the data further. The source of the data is included in a link at the bottom. A button at the top right moves the user to the second dashboard, which concerns the relationship between average home value and average price cut. This includes a map of the US detailing average home values, which can be filtered by year. Also, clicking on one of the states will filter the dashboard by state. In this way, the user can get a picture of the change in home prices across regions and time and see how price cuts are related as well. I wanted to create an interactive dashboard so that the users could investigate the data themselves. Info buttons are included on both dashboards to provide some guidance.

### Reference

*US housing trends: Values, time & price cuts.* (2024, July 1). Kaggle. (https://www.kaggle.com/datasets/clovisdalmolinvieira/us-housing-trends-values-time-and-price-cuts?resource=download)
