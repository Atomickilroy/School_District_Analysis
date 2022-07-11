<br>
<br>

# <center>School District Analysis
<br>

## <center>Overview of Project
#### - *A representational analysis on a school district's funding and the corrilations to its schools student performance scores on standardized reading and math tests.* 



<br>

## <center>Purpose

1.  The purpose of this project was to learn the fundamentals of setting up an 
 Anaconda enviroment * to run Jupyter Notebook and import, read, create and manipulate a csv file (containing over 35,000 lines) on Pandas. In order to answer the inital question of: 
            
    'What has the most impact on a schools' student performance on standardized tests?'

<br>

2.  Additionally this project demeonstrates the drastic or not so drastic impact of falsified data and how to efficiently render that data to NaN; utlitizing Pandas and Numpy.

<br>

 #### ****Establishing this sort of enviroment allows for a discreet way of accessing and sharing senitive data.***


<br>

# <center>Results 

 ### **Section 1**<br> 
 
 Information came to light that suggested that the test results of both math and reading, for the 9th grade class of Thomas High School had been altered. Therefore sections of the inital analysis needed to be revised and the altered data to be rendered NaN. While maintaining the rest of the students information; to perserve as much of the data as possible. 
  

 ### ***<center>How is the district summary affected?***

 <br>

***District Summary***<br>

 *The image below shows the district summary data frame. The differences with the replaced test scores were negligible and therefore dont change the combined of the district results.*     

![District Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20district%20summary%20DataFrame.png)


### ***<center>How is the school summary affected?***<br>

At first glance the results of the school summary are drastic. The second image reveals that if Thomas HS had to carry the results of the replaced scores( based on the overall school population ) they would rank amoung one of the lowest performing schools in the district**.

However, as the 'Revised Results' image shows, with the results of the 9th grade class deducted from the school population and the avg's recalculated accordingly. Thomas HS remains second in overall performance**. Leaving the differnces between the original and revised analysis results negligable. 


<br>

***Initial Results***

![Org School Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Original%20Analysis%20images/Per_School_Summary_OG.png)

***At First Glance***

![Org School Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Before%20Avg_Snipit.png)


***Revised Results***

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/School%20Summary_Snippit.png)

<br>

#### *****Please See - 'Additional Data Frames'***

<br>


### **Section 2**:  
- What has the most impact on a schools' student performance on standardized tests?


---
<br>

These two charts above represent the core of the analysis. 

<br>


***Scores by school size*** 
<br>

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20size.png)
<br>

***Scores by school spending***<br>

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20spending%20per%20student.png)

<br>

- The first shows that Larger Schools'Students (2000-5000) pass 32% less students and only 58% of students pass. 

- The second chart when crossed with the school summary ( [Org School Summary](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Original%20Analysis%20images/Per_School_Summary_OG.png) ) in addition to the school size chart above, shows that dispite Larger schools having among the highest amount of money spent per student, it ultimately comes down to school size not money spent per student.  


----

## <center>Conclusion

----
<br>

The impact of the results above could lead to an enumerable number of discussions into the 'Why' of it all. Potientally leading to not just increased test scores but offering the students of those schools a better educational-enviroment to learn in. Or leading to future projects where you evaluate different metrics.

Such as the cost per student ratio and new school construstion.

- By dividing the larger schools into two you decreasing the cost per student per student by ~$150.
- For one school of 4000 it could potientally save ~$600,000 per year 
- Ultimately being more cost efficient over a decade or so?


***Just an example additional data needed . . .**

<br>


----

## <center>Additonal Data Frames

----
<br>


***Top 5 Schools***

![Top](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20top%205%20performing%20schools%2C%20based%20on%20the%20overall%20passing%20rate.png)


***Bottom 5 Schools***

![Bottom](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20bottom%205%20performing%20schools%2C%20based%20on%20the%20overall%20passing%20rate.png)


***Math scores by grade***<br>

![Updated Math](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20average%20math%20score%20for%20each%20grade%20level%20from%20each%20school%20.png)


***Reading scores by grade***<br>

![Updated Reading](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20average%20reading%20score%20for%20each%20grade%20level%20from%20each%20school%20.png)


***Scores by school spending***<br>

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20spending%20per%20student.png)


***Scores by school size***<br>

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20size.png)


***Scores by school type***<br>

![Updated](https://github.com/Atomickilroy/School_District_Analysis/blob/main/Deliverable%20images/The%20scores%20by%20school%20type.png)


___ 
***TBD***  : Although the question still remains as to why Thomas HS's 9th grade scores were falsified. One could speculate it was just an attempt to claim the higher "Overall Passing" average and 'beat Cabrera HS to claim the number in the district. ***
