# Module-4_-School_District_Analysis

## (1) Overview of the school district analysis


## (2) Results
There has been evidence showing issues with the math andreading grades of Thomas High School ninth graders. In order to resolve thediscrepancy, we have taken the following steps.  To avoid the grades from Thomas High School ninth graderswere being counted, we first replaced all their grades to “NaN”. 

Subsequently, we created new dataframes that excluded the ThomasHigh School ninth graders’ grades and redid the calculation. The total counts and passing percentages were needed to beredone. With the removal of the ninth graders, all these numbers would be affected. This would also affect the results when looking at the school size, district,or spending ranges levels. 

1. <ins>The district summary DataFrame<ins> 
- *The replacement of “NaN” on Thomas High School ninth graders,would cause their grades cannot be counted, as the entries have been updated toa non- integer format.*  

2. <ins>The school summary DataFrame<ins> 
- *Similar to the above, the replacement of “NaN” on ThomasHigh School ninth graders, would cause their grades cannot be counted, as theentries have been updated to a non- integer format.*  

3. <ins>The top 5 performing schools, based on the overall passingrate<ins>
- *The exclusion of Thomas High School ninth graders, wouldaffect the overall student count at Thomas High School, which would directlyaffect its overall passing rate result and this would affect the ranking ofThomas High School on the list.* 

4. <ins>The bottom 5 performing schools, based on the overall passing rate<ins>
 - *Same as the above, the exclusion of Thomas High School ninth graders, would affect the overall student count at Thomas High School, which would directly affect its overall passing rate result and this would affect the ranking of Thomas High School on the list.*

5. <ins>The average math score for each grade level from each school<ins>
- *The calculation of average scores is divided by the total number of students. The removal of ninth grades would change the average count result as the total number of students has shortened.*

6. <ins>The average reading score for each grade level from each school<ins>
- *Same as the above, the calculation of average scores is divided by the total number of students. The removal of ninth grades would change the average count result as the total number of students has shortened.*

7. <ins>The scores by school spending per student<ins>
- *The bucketing would not be affected. As the spending is a fixed amount per school per student. Thus, this would not affect how we bucket on the spending rangers level. The only effect that the removal of the ninth graders would be the score results and the reason has been explained above.*

8. <ins>The scores by school size<ins>
- *Similar to the above, the bucketing would not be affected. Because the school size is fixed per each school. Thus, this would not affect how we bucket on the school size level. The only effect that the removal of the ninth graders would be the score results and the reason has been explained above.*

9. <ins>The scores by school type<ins> 
- *Similar to the above, the bucketing would not be affected. Because the school type is fixed per each school. Thus, this would not affect how we bucket on the school type level. The only effect that the removal of the ninth graders would be the score results and the reason has been explained above.*

## (3) Summary
The replacement of the new math and reading scores of Thomas High School would have the following effects.

1. Clear out all discrepancy data from the ninth graders.

2. affect its ranking on all levels.

3. Affect the results when Tomas High School results are needed to be combined with other schools’, such as when showing the overall results by school type or district

Asides from the effects list above. The replacement of these scores would not affect the grades of the Thomas High School students on an individual level. 
