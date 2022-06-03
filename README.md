# PyBer_Analysis
**Objective:**
PyBer CEO has given you an assignemnt-- Using Python, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. One the analysis is complete, submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


## Deliverable 1:  A Ride-Sharing Summary DataFrame by City Type
>### Results & analysis

**1. The total number of rides for each city type is retrieved.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/Total%20rides.PNG)

**2. The total number of drivers for each city type is retrieved**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.2.PNG)

**3. The sum of the fares for each city type is retrieved.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.3.PNG)

**5. The average fare per driver for each city type is calculated.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.4.PNG)

**4. The average fare per ride for each city type is calculated.**

![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.5.PNG)

**5. A PyBer summary DataFrame is created.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.6.PNG)

### Deliverable 2: A multiple-line chart of total fares for each city type
**1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.1.PNG)

**2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."**
![my imagee](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.2.PNG)

**3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.**

![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.3.PNG)

**4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.**

![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.4.PNG)

**5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.**
![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.5.PNG)

## Deliverable 3: A written report for the PyBer Analysisg:

1. * Explain the purpose of the new analysis:

    > The purpose of this PyBer report is to create a complete summary of the Ride-Sharing data by city type via line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib libraries. We determined the mean, median, and mode using Pandas, NumPy, and SciPy statistics. Our Final Analysis include multiple-line graphs of total weekly fares for each city type.


2. **Results** 

    * The Suburban fares started around $1,000, and the analysis was not profitable, fare dropped in March and in mid-April.  
    * The Rural fares started at around $200, the analysis shows fares increase and dropped till the end of April.  
    * The Urban fares start with an average of $1,800 with a consistent increase around 2,300. 
    
    The PyBer summary DataFrame, 
   ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/1.6.PNG)

     A multiple-line chart of total fares for each city type,
   ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/2.5.PNG)

     PyBer Ride-Sharing Data (2019), 
    ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/Fig1.png)     

3. **Summary** 

    **1)** We can predict that there are good opportunities to expand the business in rural and suburban cities, including hiring drivers to operate and explode business in rural and suburban cities.

    % of Total Drivers by City Type,
    ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/Fig7.png)
     **2)** The Urban cities fare is the highest and consistent, giving us great and new business opportunities to expand rides.  

     % of Total Fares by City Type, 
  ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/Fig5.png)
    
    **3)** The Rural cities fare is the lowest of the other two city types (Urban and Suburban cities), in addition, fares never intersect.  Knowing that all fares never intersect, we can expand fares and increase business financial income to the company without affecting our rate.

     Total Fare by City Type,
  ![my image](https://github.com/SLCunningham21/PyBer_Analysis/blob/main/Resources/Images/PyBer_fare_summary.png)






