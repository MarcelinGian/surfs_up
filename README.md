# surfs_up
## Data Storage & Retrieval using SQLite, SQLAlchemy, and Flask

### Overview
#### An investor want to learn more about weather patterns in Oahu, Hawaii before commiting their money into an Ice Cream & Surfboard shop because the store's success or failure will depend on good weather, ie- warm days with no rain. To support my business plan and better inform the investors decision, I will be analyzing precipitation & temperature patterns in a SQLite weather database using SQLAlchemy. Matplotlib was used to visualize the data.

***
### Results
#### June Summary Statistics (2010 - 2017)
![01JuneSummary](https://user-images.githubusercontent.com/105818879/194726981-9ced677c-7a16-4918-928b-9a9e106ed1f6.png)

#### December Summary Statistics (2010 - 2017)
![02DecSummary](https://user-images.githubusercontent.com/105818879/194726986-2c4a6108-046e-48fa-80e2-ed3296892677.png)

#### June Temperature Histogram
![03JuneTempPlot](https://user-images.githubusercontent.com/105818879/194726996-be2b462d-3a5e-4d26-8852-722e2f42413c.png)

#### December Temperature Histogram
![04DecTempPlot](https://user-images.githubusercontent.com/105818879/194727005-a58332a4-4e7f-4655-917c-d1bf979820fe.png)

### Observations
- June is warmer
  - At 75 degrees, June's average temperature is higher than December's- which is 71 degrees
- December temperatures have larger variations from the mean compared to June
  - Though the average December temperature is just 4 degrees less than June's, with a max recorded temp being only 2 degrees less than June (83 vs. 85), December's lowest recorded temperature of 56 degrees is significantly lower than June's lowest temp of 64 degrees. 
  - This observation is supported by December's comparatively larger standard deviation
- December is wetter
  - December's average precipitation of .22 inches is higher than June's .14 inch average

*** 
### Summary
#### To summarize, the data shows that both December and June have temperatures warm enough to support foot traffic and sales at an ice cream  & surf board retail establishment. In adding precipitation data to my analysis, I have also observed that both months are low in rainy days. Precipitation was a major point of concern for the potential investor so this additional analysis should be very helpful.
