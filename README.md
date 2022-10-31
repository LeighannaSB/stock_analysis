# VBA Stock Analysis

## Overview of Project: Explain the purpose of this analysis.

The purpose of the analysis was to refactor the VBA code to make it more efficient. Deliverables include:
-  Refactor VBA code and measure performance
-  A written analysis of your results (README.md)

## Results: comparing the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

-Refactored Code Analysis for 2017
  - code ran in .109 seconds
  - All possible investments showed positive returns except for TERP which showed a loss of -7.2%
  - DQ and ENPH showed the highest returns
  
  ![image](https://user-images.githubusercontent.com/107161421/198919389-d1e30e77-94ea-4118-8d11-e211bf6d2579.png)

- Refactored Code Analysis for 2018
  - code ran in .109 seconds
  - All possible investments showed a negative return except for ENPH and RUN
  - All returns lower than previous year
  
  ![image](https://user-images.githubusercontent.com/107161421/198919564-4aea0dc9-93f8-43e3-8cb1-e3f06234a2c4.png)

- The original code ran in .5 seconds for 2017 and .5 seconds for 2018

![image](https://user-images.githubusercontent.com/107161421/198920522-4d199347-75bc-4177-b74e-c097b2f6060d.png)
![image](https://user-images.githubusercontent.com/107161421/198920568-399e3972-ba5f-4633-a996-5c4de5e9530b.png)

  - Original Code:
  ![image](https://user-images.githubusercontent.com/107161421/198920720-7c9f34ae-0e3b-4dd8-9bcd-07dd0f53c928.png)
  ![image](https://user-images.githubusercontent.com/107161421/198920766-ea8f8b9a-3279-470b-be5c-29c36090d281.png)

  - Refactored Code:
  ![image](https://user-images.githubusercontent.com/107161421/198920892-4c46f3e5-bbb4-469c-8ab6-1f7abfa81c5c.png)
  ![image](https://user-images.githubusercontent.com/107161421/198920936-8401cc30-e7b6-444a-9d91-8f4539c6a529.png)
  

## Summary
  
  As shown above above both the original and refactored code were able to come determine the returns for the possible investments. The difference being how quickly they were able to do so- the refactored code was significantly quicker. Writing the code was a bit more time consuming on the front end but if the analysis is going to be ran frequently or using large amounts of data the extra time up front will be made up for by the time difference in how quickly the refactored code runs. 
