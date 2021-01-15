# School District Analysis

## Overview

A city's school district requested an analysis on standardized testing data for the district schools. In addition to the analysis, the district wants a report and presentation to help inform decisions regarding the district's budget. Two CSV files, one with data regarding the schools and the other with students' math and reading test data were provided for the analysis, reporting, and presentation to the board. After performing the initial analysis, it was discovered that the scores of one of the schools, Thomas High School (THS), were altered for the school's 9th grade students. The school board now needs THS's 9th grade scores removed and the anaylsis re-completed, as well as a summary of the changes caused by the altered data.

## Results

The anaysis consisted of a district summary, summary by school, and average scores based on grade level, spending per student, school size, and type of school (charter or district). 

  * **Effect on the District Summary**
  
       Below is the original analysis performed on the entire district, which showed the average scores to be 79.0 for math and 81.9 for reading.
      
      
      <img src="https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/district_summary_original.png">
      
      Removing the scores of 9th graders at THS had very litte effect on the overall district average, which were recalculated at 78.9 and 81.9 - nearly identical to those found in the original analysis. The entire district analysis with the cleaned data is shown below.
      
      <img src="https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/district_summary_revised.png">
  
  * **Effect on the THS's School Summary**
  
      The two summaries presented below of the THS student data both before and after the removal of the 9th graders' scores shows that the scores' removal had very little effect on the overall percentages that the school achieved. The percent of students passing both categories, as well as the overall percentage of students passing from THS all changed by less than half of a percent. Overall, the school ranked second in the district (in terms of percentage of students passing both subjects) both before and after the 9th graders' data was removed. 
      
      ###### THS summary with the 9th graders' data
      
      <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/ths_summary_original.png'>
      
      ###### THS summary without the 9th graders' data
      
      <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/ths_summary_revised.png'>
      
  * **Effect on THS's Scores Relavtive to Other Schools**
  
      As previously mentioned, THS ranked second both before and after the 9th graders' scores were removed. The top five schools are listed below both before and after the data was cleaned.
      
      ###### Top 5 Performing Schools (prior to removing THS 9th graders' data)
      
      <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/top_5_original.png'>      
      
      ###### Top 5 Performing Schools (after to removing THS 9th graders' data)
      
      <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/top_5_revised.png'>
      
  * **Effect on Other Metrics:**
  
      * _Math and reading scores by grade_
      
          * Math and reading scores for the district's 9th graders were 80.4% and 82.5%, respectively, before THS's data was removed. THS's average 9th grade math and reading scores were both above the average at 83.6% and 83.1%, which indicated the district's average would decrease once THS's data was removed. The district's averages both dropped slightly THS's data was removed, with the revised values coming in at 80.1% and 82.4%. Average scores of 10th-12th graders were unaffected, as there were no changes made to scores from those grade levels. 
      
      * _Scores by school spending_
      
          * At $638 per student, THS ranks as the fifth highest budget per student in the district and falls into the second highest spending bin ($631-$645). The impact of removing THS's 9th graders' scores was not felt on the results versus school spending, as demonstrated in the before and after tables below.
        
        ###### Average Scores Grouped by Spending per Student (prior to removing THS data)
        
        <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/spending_per_student_original.png'>
        
        ###### Average Scores Grouped by Spending per Student (after removing THS data)
      
        <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/spending_per_student_revised.png'>
      
      * _Scores by school size_
      
        Similar to the average scores based on school spending range, the averages based on school size was uneffected by the removal of THS's 9th grade data. At 1635 total students, THS falls into the medium range, which has average math and reading scores of 83.4% and 83.9%. THS's scores are nearly identical to the average at 83.35% and 83.90%, which is the reason they have very little impact on the average when removed.
        
        ###### Average Scores Grouped by School Size (before and after - data remained unchanged)
        
        <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/school_size_revised.png'>
        
      * _Scores by school type_

        As with the scores by school size and per student budget, the scores grouped by school type (charter or district) were not effected in a noticable way. THS is a charter school, so the only possible effect was on the charter school group, however, as shown below, the group averages were not changed following the removal of the data.
        
        ###### Average Scores Grouped by School Type (before removing THS data)
        
        <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/type_original.png'>
        
        ###### Average Scores Grouped by School Type (after removing THS data)
        
        <img src='https://github.com/bradydwilton/School_District_Analysis/blob/main/Resources/type_revised.png'>
        
## Summary
In general, the data remained largely unchanged from the removal of THS's 9th grade math and reading scores. The four largest changes are summarized below:

   1. The percentage of students passing math, reading, and both dropped slightly (drops ranged from 0.1%-0.4%)
   2. The number of students in the THS analysis dropped by 461 students, from 1635 to 1174
   3. The district's average math score, which dropped by 0.1% from 79.0% to 78.9%
   4. The number of students in the analysis dropped from 39.170 to 38,709
