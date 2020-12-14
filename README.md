# School_District_Analysis
Analysis for School Districts

### Method
Python

Pandas

## Background 
Maria, the cheif data scientist for a city school district, is tasked with analyzing data from standardized tests for presentation. Maria has requested my help to uncover performance trends and patterns.  Using Pythonic code and Pandas in the Jupyter environment I was able to organize and analyze data from the csv files Maria has provided. After agregating the data to show the trends and school performance, the data can be used to better inform school budget allotments as well as other priorities. 

## Challlenge
Maria was notified by the school board that there was academic dishonesty surrounding the Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. Maria has therefor requested that I replace the Thomas High School ninth grade scores for math and reading with NaNs.  Doing this will keep the rest of the data intact, the school size and other metrics will stay the same while we exclude the  math and reading scores from the Thomas High School ninth graders. 

## Results

In our original analysis there were several key metrics that were measured

 * District Summary
 * School Summary
 * The Average Math Score
 * The Average Reading Score
 * The Percentage of Passing Students for Math and Reading per School
 * The Top Five and Top Bottom Schools based on performance (the percentage of passing students)
 * Categorizing School Budgets 

Once we replaced the data for the 9th graders at the Thomas High School the data was adjusted and and there were several notable changes. 

## Notable Diferences in Thomas High School post 9th grade adjustments

 * The average reading score for Thomas High School changed
 * The average math score for Thomas high School Changed
 * The overall percentage of sudents passing changed
 * The top 5 schools in the district changed 
 * The district summary changed to reflect a changed percentage of passing studendts
 
 Before The changes made to the 9th grade the average score for reading, the average score for math
 
 
 ![before](https://github.com/Solrys/School_District_Analysis/blob/main/Resources/new%20school/THS_before.png)
 
 with the new code reflecting 9th grade NaNs the following image reflects the new data 
 
 ![after](https://github.com/Solrys/School_District_Analysis/blob/main/Resources/new%20school/THS_after.png) 
 
 The percentage of Passing math has changed, the percentage of passing reading has changed, and the overall percentage of passing students has changed. 
 
 In addition Thomas High School is now #2 on the Top Five Schools List
 
 ![Top 5](https://github.com/Solrys/School_District_Analysis/blob/main/Resources/new%20school/Top5.png)
 
 ## Conclusion
 
After sorting and analyzing the data, and comparing between the charecteristics of the top and bottom schools in the district there are several conclusions that can be made. Charter schools have perfomed significantly better than the district schools. Smaller schools seem to have a better performance as well. Being able to see which schools performed the best may allow us to be able to create tools to model after sucess and implement across the board. 
 
 
 
   
 
 
