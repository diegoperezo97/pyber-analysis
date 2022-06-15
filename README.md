# MODULE 5: PyBer with Matplotlib

To analyze data, combine data sets, execute computations, and build data series and data frames in this module, I'll use a Jupyter Notebooks and Pandas. The two-dimensional graphing package for Python, Matplotlib, will also be covered. I'll use Matplotlib to create publication-quality figures of various data series so that I can use the data to create a visual narrative.

Presenting complicated findings in a way that is educational and interesting to all stakeholders is accomplished by constructing a visual story from the data. Data visualizations make it easier for my audience to understand information and spot patterns, trends, correlations, and outliers that are typically hard to display in a table with hundreds of entries. Sharing visualizations with various teams can aid in project planning and serve as a catalyst for commercial choices.

Let's discover how to utilize Matplotlib to design simple to complicated visualizations.

## Overview of the Analysis
In this module, I landed a job as a data analyst for PyBer, a Python based ride-sharing app company. My first assignment will be to perform an exploratory analysis on data in some very large csv files. To aid this process, I will create several types of visualizations to tell a compelling story about the data. I will write Python scripts using Panda’s libraries, the Jupyter notebook, and Matplotlib to create a variety of charts that showcase the relationship between the type of city, and the number of drivers and riders, as well as the percentage of total fares, riders and rivers by type of city.

### Purpose
* Help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Results of the Analysis
1. KPI analysis as a function of city type:

From Table 2.1. PyBer Summary Percentage Change we can conclude that our business is highly concentrated in urban areas, being ~68% of our business and ~80% of our drivers, bringing ~63% of our revenue, despite having more public transport options and distances being smaller (thus the lowest average fare per ride). We have managed to settle on urban are as (demonstrated by the lowest average fare per ride), reaching economies of scale. 

**Table 2.1. PyBer Summary Percentage Change**

![Captura de Pantalla 2022-02-06 a la(s) 21 22 04](https://user-images.githubusercontent.com/65054637/152722981-b70f6f28-e40f-4abb-8b26-41f74ce31329.png)

2. Fare analysis as a function of time:

From Image 2.1. Summary of Fares by City Type as a Function of Time we can conclude that the trend more or less remains equal no matter the city type. Peaks, and valleys are more noticeable in urban cities and less noticeable in rural cities. Speaking of our original purpose, affordability PyBer hasn’t been necessarily successful at making it’s services cheaper, as there is no clear downwards trend. Nevertheless, it has been successful to remain “constant” with the prices it offers.

**Image 2.1. Summary of Fares by City Type as a Function of Time**

![PyBer_fare_summary](https://user-images.githubusercontent.com/65054637/152722904-f80e7d1e-23d7-4d73-8b44-bda38dd935e7.png)


## Summary of the Analysis

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types:

With the obtained results, it seems to me that our past strategy has been focused on urban areas. Nevertheless, if we want to improve access to ride-sharing services and improve affordability for underserved neighborhoods I would suggest our CEO to:
1. Determine cost per kilometer in three city types to determine whether or not we are aligned with our original purpose to offer cheap services to underserved communities. Average fare in rural areas is the highest but because distances tend to be longer.
2. There is a great potential to tackle suburban and rural areas where our business has not matured in these geographies. With 20% of urban drivers, suburban drivers generate half of the revenue, which may suggest that there is still unexploited potential in this market.
3. . There may also be potential in rural areas as there are less public transport options and distances tend to be further apart (which brings higher revenue). I would consider the market size in some of these rural areas and incentivize drivers to jump into our platform, thus assessing our ride-sharing access concerns.
