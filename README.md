## Wallmart Sales Forecast

### Introduction

Walmart is one of the largest retailers in the world and it is very important for them
to have accurate forecasts for their sales in various departments. Since there can be
many factors that can affect the sales for every department, it becomes imperative
that we identify the key factors that play a part in driving the sales and use them to
develop a model that can help in forecasting the sales with some accuracy.

### Objective

To predict the weekly sales for 99 departments at 45 Walmart stores located in
different regions.

### Dataset Description

The data collected ranges from 2010 to 2012, where 45 Walmart stores across the
country were included in this analysis. Each store contains several departments.
Dataset contains information about the stores, departments, temperature,
unemployment, CPI, isHoliday, and Markdowns.

**1) Stores:**
  - **Store:** The store number. Range from 1–45.
  - **Type:** Three types of stores ‘A’, ‘B’ or ‘C’.
  - **Size:** Sets the size of a Store would be calculated by the no. of products available in the particular         store ranging from 34,000 to 210,000.

**2) Features:**
  - **Temperature :** Temperature of the region during that week.
  - **Fuel_Price :** Fuel Price in that region during that week.
  - **MarkDown1:5 :** Represents the Type of markdown and what quantity was available during that week.
  - **CPI:** Consumer Price Index during that week.
  - **Unemployment:** The unemployment rate during that week in the region of the store.

**3) Sales:**
  - **Date:** The date of the week where this observation was taken.Weekly Sales: The sales recorded during that          Week.
  - **Dept:** One of 1–99 that shows the department.
  - **IsHoliday:** A Boolean value representing a holiday week or not.
  
**Dataset Link :** https://www.kaggle.com/fernandol/cracking-the-walmart-sales-forecasting-challenge

### Prediction Result

![alt text](/images/image1.png)

### Conclusion

We find that Random Forest Regression gives best acuracy on this dataset.
