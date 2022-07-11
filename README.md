<br>
<br>

# School District Analysis
<br>

## Overview of Project
### ***A representational analysis on a school district's funding and the corrilations to its schools student performance scores on standardized reading and math tests.*** 



<br>

## Purpose

1.  The purpose of this project was to learn the fundamentals of setting up an 
 Anaconda enviroment * to run Jupyter Notebook and import, read, create and manipulate a csv file (containing over 35,000 lines) on Pandas. In order to answer the inital question of: 
            
    'What has the most impact on a schools' student performance on standardized tests?'

<br>

2.  Additionally this project demeonstrates the drastic or not so drastic impact of falsified data and how to efficiently render that data to NaN; utlitizing Pandas and Numpy.

<br>

 #### ***_   * Establishing this sort of enviroment allows for a discreet way of accessing and sharing senitive/ data.***


<br>

# Results 

 Information came to light that suggested that the test results of both math and reading, for the 9th grade class of Thomas High School had been altered. Therefore sections of the inital analysis needed to be revised and the altered data to be rendered NaN. While maintaining the rest of the students information. To perserve as much as the data possible. 

- ### How is the district summary affected?<br>

***District Summary***

 The image below shows the district summary data frame. The differences without the voided test scores were negligible and therefore dont change the combined results.     

![District Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20district%20summary%20DataFrame.png)


- ### How is the school summary affected?

At first glance the results of the school summary are drastic. The second image reveals that if Thomas HS had to carry the results of the replaced scores( based on the overall school population ) they would rank amoung one of the lowest performing schools in the distric.

However, as the 'Revised Results' image shows, with the results of the 9th grade class of Thomas High school's deducted from the school population and the avg's recalculated accordingly. Thomas HS remains second in overall performance. Leaving the differnces between the original and revised analysis results negligable.   

***Initial Results***

![Org School Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Original%20Analysis%20images/Per_School_Summary_OG.png)

***At First Glance***

![Org School Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Before%20Avg_Snipit.png)


***Revised Results***

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/School%20Summary_Snippit.png)






Math and reading scores by grade<br>


![Updated Math](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20average%20math%20score%20for%20each%20grade%20level%20from%20each%20school%20.png)


![Updated Reading](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20average%20reading%20score%20for%20each%20grade%20level%20from%20each%20school%20.png)

Scores by school spending<br>


![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20spending%20per%20student.png)

Scores by school size<br>


![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20size.png)

Scores by school type<br>


![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20type.png)


