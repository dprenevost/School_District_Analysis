# School_District_Analysis

## Overview 

The school board has notified Maria and her supervisor that the 
"students_complete.csv" file shows evidence of academic dishonesty;
specifically, reading and math grades for Thomas High School 9th graders
appear to have been altered.  Although the school board does not know the full 
extent of the academic dishonesty, they want to uphold state-testing standards 
and have turned to Maria for help. She has asked me to replace the math and reading
scores for Thomas High School with NaNs while keeping the rest of the data intact.
Once i’ve replaced the math and reading scores, Maria would like me to repeat the 
school district analysis that I did in this module and write up a report to describe
how these changes affected the overall analysis.

The Data needed to be checked, and corrected for irregularities in several fields, noteably the "student_name" column, as there were several anomolous entries related to name prefixes and suffixes, most likely due to cheeky students with a sense of humor.

### Results:

* District Score summaries:

   * District overall Scores **before** removing THS 9th grade scores:
   * ![Scores_Before](/resources/District_overall_before.PNG)

   * District overall Scores **after** removing THS 9th grade scores:
   * ![Scores_After](/resources/District_overall_after.PNG)

* Analysis of the adjusted data:
  * Removing the alleged compromised 9th grade scores from the overall data appears to have minimal effect to the outcomes.
  * The difference in the total % passing scores for the entire district is less than .2%
  

* How does replacing the 9th graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * ![THS_before_after](/resources/before_after.PNG)
   * As you can see from the above image, the numbers at the top indicate the % passing score is much higher.  This is expected as we removed all of the 9th grade from the dataset.  This however points out another interesting point.  The overall averages for Math and Reading did not deviate from the other schools significantly.
  
* By removing the 9th grade scores, the following observations are made:

  * Math and reading scores by grade
  *   Math scores for THS went from 93.2% down to 69.6% for the whole school
    
  * Scores by school spending

  * Scores by school size

  * Scores by school type


## Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data

    

*Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
