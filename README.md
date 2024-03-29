# stock-analysis

## Overview of Project

### Purpose
The purpose of this analysis is to find the trend for multiple stocks based on:
1. The amount/quantity of stocks sold throughout the year.
2. Fluctuation of stock price over whole year. 

## Results

### Results based on performance of stock in year 2017 and 2018 with original and refactored code
1. The number of stocks sold or the volume of stocks was way higher in 2018 than 2017 but by looking at the Return 
   it concludes that the stock overall did not perform well. 
2. Majority number of stock's prices fell throughout the year for 2018
   - Quantity of stocks and return for FY2017
   ![](./Resources/Year2017.PNG)  
   - Quantity of stocks and return for FY2018
   ![](./Resources/Year2018.PNG)  
3. To have a proper understanding of which stock performed better, it is good to take in consideration the *opening* and 
   *closing* amount for each stock for every month.
4. By refactoring the code we were able to analyze the whole data in only around 0.1 second. As the number of rows 
   are same for both 2017 and 2018, the time taken to traverse is almost same for both the years using refactored code. 
   - Time taken to traverse FY2017 data using refactored code
   ![](./Resources/2017_TimeTaken.PNG)  
   - Time taken to traverse FY2018 data using refactored code
   ![](./Resources/2018_Timetaken.PNG)  
5. By using non refactored code, were are traversing the whole data almost 12 times which increases the time to almost 
   0.6 seconds. 
   - Time taken to traverse FY2017 data *by not* using refactored code
   ![](./Resources/NonRefactored_2017.PNG)
   
   - Time taken to traverse FY2018 data *by not* using refactored code
   ![](./Resources/NonRefactored2018.PNG)  
   
   



## Summary

1. What are the advantages or disadvantages of refactoring code in general?
   - Advantage : By refactoring the code we can improve the space or time complexity.
   - Disadvantage : The code needs to be written pertaining to the data available.  
   
1. What are the advantages or disadvantages of refactoring code(VBA)?
   
   Advantages :
   - By refactoring the code we improved the time complexity for the program. 
     The refactored code was able to traverse through 3000 rows in only 0.1 seconds which is almost less than qaurter time 
	 than non refactored code. 
   Disadvantages : 
   - For the refactored code to work the data needs to be sorted. 

2. What are the advantages or disadvantages of non refactored code(VBA)?

   Advantages :
   - Code can be applied for any kind of unstructured data. 
   Disadvantage : 
   - Code can become long and complex. 



