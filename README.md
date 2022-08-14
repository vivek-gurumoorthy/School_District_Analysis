# School_District_Analysis

## Overview of the Analysis
 The purpose of this analysis is to examine school and student performance across a school district in a city. Performance is measured according to standardized test scores in both math as well as reading. To further categorize each school across the district, information is available about the grade in which each included student is currently enrolled, as well as school type, size, and budget details. 

 First, the analysis was performed on all high school students from all schools in the district. Then, once it had been discovered that there was evidence of academic dishonesty within the scores for Thomas High School in the 9th grade, the data used for the analysis was modified accordingly and the analysis was performed again to get a more realistic idea of student performance. 

## Results
How is the district summary affected?
District Summary DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184417994-afe4eada-b7ad-474a-91af-7174f9ac0b43.png)


District Summary DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419269-710a3bf3-1b6e-4717-bf9f-85c24f83b790.png)

* The district summary, while somewhat altered by the removal of Thomas High School's 9th grade scores, did not change all that much between each iteration of the analysis. The average math and reading scores across the district were nearly identical. The percentage of students passing math, the percentage of students passing reading, and the percentage of students passing both subjects all declined, by 0.1%, 0.1%, and 0.2%, respectively. Overall, performing the analysis again without Thomas High School's 9th grade scores did not greatly affect average performance across the district.

How is the school summary affected?
School Summary DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418376-b1201f6c-6fb5-4396-946a-611d0c0be0e8.png)
 

School Summary DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419334-fa8f30b5-8a86-4470-af87-5755a438ed9c.png)


* The school summary also did not change much between each iteration of the analysis. In fact, the only changes that occurred to this particular DataFrame were localized to the row concerning Thomas High School, as all other school metrics were unaffected. For Thomas High School, the average math and reading scores decreased by approximately 0.1. The passing percentages for math, reading, and overall also declined, by 0.1, 0.3, and 0.3% respectively. Clearly, Thomas High School's performance appeared better with the inclusion of scores that may have been a result of academic dishonesty. Still, the overall metrics for the school were not drastically decreased by the exclusion of this information. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Top Schools DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418440-bd8e9c45-5bc2-49d9-9d09-c6eb4fc9d2e5.png)


Top Schools DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419399-4180550b-180d-4de8-921c-cfb8a53d3b4d.png)

* The performance of Thomas High School relative to the other schools was also largely unaffected by the exclusion of scores by its 9th graders. While, as previously detailed, average math and reading scores as well as passing percentages in each individual subject and both subjects together were lower with the exclusion of the 9th grade scores, clearly Thomas High School still performed well in relation to the other schools. In ranking all 15 schools in descending order by overall passing percentage, Thomas High School still comes 2nd out of the 15 schools in both iterations of the analysis. While the overall passing percentage is 0.3% lower in the subsequent analysis, Thomas High School still outperforms the vast majority of other insitutions. 

How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade

Math Prior to THS 9th Grade Score Removal           |  Reading Prior to THS 9th Grade Score Removal
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418490-e245fa57-0db0-4fdc-b60e-49ef84773ae6.png)|  ![image](https://user-images.githubusercontent.com/108832056/184418540-32844a61-39c3-4640-8ad6-ea7fa3c468e4.png)


Math After THS 9th Grade Score Removal           |  Reading After THS 9th Grade Score Removal
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419463-9019c73e-48bf-4275-abce-d6ff83fc50d1.png)|  ![image](https://user-images.githubusercontent.com/108832056/184419524-fdd83e02-dd10-41b4-abef-0b61ca44937e.png)

* The scores broken up by grade for each school by subject are perhaps the DataFrames most substantially affected by the exclusion of Thomas High School's 9th grade scores. This is clear from the fact that in the second analysis, both the Thomas High School reading and math scores read as "nan", also meaning "not a number". This demonstrates that these scores were effectively voided in the second analysis and were not factored into averages or other metrics. All other scores, including those for students in Thomas High School in other grades, were unaffected. For all schools in this analysis, scores do not seem to vary greatly across each grade level.

* Scores by school spending

School Spending DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418629-616be9f4-56b2-4d6e-95e1-55f82a34c067.png)
 

School Spending DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419576-8d498014-454c-45be-a736-8faedd999c62.png)

* School performance by school spending was completely unaffected by removal of Thomas High School's 9th grade scores. From this DataFrame, it appears that schools that budgeted less per student actually observed better student standardized test performance. Some data that leads to this insight is that those schools that spent the least (< $586) per student actually saw on average the highest average math and reading scores as well as the highest passing percentages in each individual subject as well as both subjects cumulatively. This trend appears to hold true for the other spending bins, as performance for the higher spending bins actually appears to decline. 

* Scores by school size

School Size DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418698-43a14631-dcf1-4bac-854e-3f4f3ad7903a.png)


School Size DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419618-c53f0c33-332c-4339-9810-39af8416efb7.png)

* School performance by school size was also completely unaffected by removal of Thomas High School's 9th grade scores. It appears from the information displayed in this DataFrame that both Small and Medium schools appear to, on average, demonstrate superior student performance in comparison with Large schools. Further, Medium schools appear to slightly outperform Small schools on average, having the highest overall passing percentage and reading passing percentage. Small schools, having the highest math score on average, also tied with Medium schools in the metrics of average reading score, percentage passing math, and percentage passing reading. While the difference between Small and Medium schools is difficult to assess, it appears that both of these schools greatly outperform Large schools on average, as Large schools recorded the lowest score for all metrics. 

* Scores by school type

School Type DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418744-fba0d743-529a-4761-a7df-d834765002c0.png)


School Type DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419645-697e5fe6-df0b-4efc-bdfc-819801d8ea7d.png)

* School performance by school type was also unaffected by the removal of Thomas High School's 9th grade scores. From this DataFrame, Charter schools appear to substantially outperform District schools on average, with large observed differences in all metrics and a 36% different in overall passing percentage (90% for Charter and 54% for District). 

## Summary
* Overall, the results of the performed analysis were not significantly altered by the removal of scores from Thomas High School that may have resulted from academic dishonesty. Thomas High School still performed very well relative to other schools in both iterations of the analysis.
* From comparing performance by spending, size, and type of school, better student performance may be likely in schools that spend less per student, schools that are either small or middle size, and schools that are charter schools rather than district schools. 
