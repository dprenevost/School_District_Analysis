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
  *   There were no significant changes noted
    
  * Scores by school spending
  *   There were no significant changes noted

  * Scores by school size
  *   There were no significant changes noted

  * Scores by school type
  *   There were no significant changes noted


## Summary:

The removal of the 9th Grade math and reading scores had no significant impact on the overall passing percentage for the School District when the 9th grade scores were elimated from the calculation.  The overall reading and math scores similarly did not show any meaningful deviation from the original calcualtions.
