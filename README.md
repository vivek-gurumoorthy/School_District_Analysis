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


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Top Schools DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418440-bd8e9c45-5bc2-49d9-9d09-c6eb4fc9d2e5.png)


Top Schools DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419399-4180550b-180d-4de8-921c-cfb8a53d3b4d.png)


How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade

Math Prior to THS 9th Grade Score Removal           |  Reading Prior to THS 9th Grade Score Removal
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418490-e245fa57-0db0-4fdc-b60e-49ef84773ae6.png)|  ![image](https://user-images.githubusercontent.com/108832056/184418540-32844a61-39c3-4640-8ad6-ea7fa3c468e4.png)


Math After THS 9th Grade Score Removal           |  Reading After THS 9th Grade Score Removal
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419463-9019c73e-48bf-4275-abce-d6ff83fc50d1.png)|  ![image](https://user-images.githubusercontent.com/108832056/184419524-fdd83e02-dd10-41b4-abef-0b61ca44937e.png)


* Scores by school spending

School Spending DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418629-616be9f4-56b2-4d6e-95e1-55f82a34c067.png)
 

School Spending DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419576-8d498014-454c-45be-a736-8faedd999c62.png)


* Scores by school size

School Size DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418698-43a14631-dcf1-4bac-854e-3f4f3ad7903a.png)


School Size DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419618-c53f0c33-332c-4339-9810-39af8416efb7.png)

* Scores by school type

School Type DataFrame Prior to Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184418744-fba0d743-529a-4761-a7df-d834765002c0.png)


School Type DataFrame After Removal of Thomas High School 9th Grade Scores            |  
:-------------------------:
![image](https://user-images.githubusercontent.com/108832056/184419645-697e5fe6-df0b-4efc-bdfc-819801d8ea7d.png)


## Summary

