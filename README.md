# School_District_Analysis
The objective of this project is to analyze the district school’s data to assess the student’s performance in math and reading exams and its correlation with the school type, size and spending budget. 
## Data clean up 
It was realized that the reading and math grades for Thomas High School ninth graders have been altered and therefore should be excluded from the analysis. The reading and math scores for those students were replaced by NaN as shown below. 

![image](https://user-images.githubusercontent.com/103223944/166982683-b1e41895-5ffa-48e3-9028-c5aca2a91002.png)

##  School District Analysis
To assess the performance of the district and each school in the district, the following metrics are evaluated:

•	The district summary (total budget, average math and reading scores, passing percentages)

•	The school summary (total budget, average math and reading scores, passing percentages, top and bottom performing schools)

•	The average math and reading scores by grades

•	The average math and reading scores by school spending per student

•	The average math and reading scores by school size

•	The average math and reading scores by school type

### District Summary
The school district summary includes the district total number of schools and students, total budget, average math and reading scores as well as the corresponding passing percentages as shown below. The total number of students is calculated by subtracting the number of ninth-grade students in Thomas High School from the total student count. Therefore, the average scores and passing percentages do not include the data from those students.

![image](https://user-images.githubusercontent.com/103223944/166982797-43f65cd1-74d3-4f4f-a29b-03e2155b6953.png)

If the scores from the 9th grader of Thomas High School were included, then the average and passing percentages would be slightly higher:

![image](https://user-images.githubusercontent.com/103223944/166982820-290fb202-1198-4f27-85ec-7a973a476381.png)

### School Summary
Tables below summarizes the average scores, passing percentages and the spending budget per student for each school. The schools have been categorized into small, large, and medium based on the number of students as shown in the last column.  Additionally, different ranges for the spending budget per student have been defined as shown in the second column to the last. The last row shows the data for the Thomas High School. 

![image](https://user-images.githubusercontent.com/103223944/166982860-1cb23a75-dd38-43f5-aae8-1e6f17f827e0.png)

If the scores from the 9th grader of Thomas High School were included, then the average scores and passing percentages would be slightly different as can be seen in the last row of the table below:

![image](https://user-images.githubusercontent.com/103223944/166982897-8c7a5d8f-1171-48f1-9f29-5d55aea5227d.png)

The schools with the highest and lowest performances are shown in tables below. Th ranking is based on the overall passing percentages.

![image](https://user-images.githubusercontent.com/103223944/166982931-592175fa-af85-4903-8af5-7f3f40ef9704.png)
![image](https://user-images.githubusercontent.com/103223944/166982965-fb1b61cc-544a-43d7-af85-24b3ddc2cb66.png)

### Average math and reading scores by grade
For each school, the average math and reading scores by grade are shown below (math: left, reading: right). As expected, the average scores for 9th graders of Thomas High School have not been calculated. The average math and reading scores of those students were among the top schools (as shown in the second set of tables below) but had to be removed due to the evidence of academic dishonesty.

![image](https://user-images.githubusercontent.com/103223944/166983061-30747df2-a02a-4917-9f3e-33db18a75430.png)
![image](https://user-images.githubusercontent.com/103223944/166983127-9c543595-60a7-45f6-b45c-3480ca244dca.png)

### Average math and reading scores by spending budgets
Table below shows the average scores and passing percentages based on the spending budget per student. Interestingly, the student’s performance has been much better for the schools with lower budgets. It should be noted the average scores and passing percentages do not change much by excluding the scores for 9th graders of Thomas High School as those were only a small subset of the data.

![image](https://user-images.githubusercontent.com/103223944/166983188-2ecc6069-881d-44fa-b038-aa5daabbb612.png)

### Average math and reading scores by school size
Table below shows the average scores and passing percentages based on the school size. As expected, the student’s performance has been much better for the smaller schools. It should be noted the average scores and passing percentages do not change much by excluding the scores for 9th graders of Thomas High School as those were only a small subset of the data.

![image](https://user-images.githubusercontent.com/103223944/166983231-9b6d7b3e-112c-4383-bd11-23aa797dffca.png)

### Average math and reading scores by school type
Table below shows the average scores and passing percentages based on the school type. The student’s performance has been much better for the charter schools. It should be noted the average scores and passing percentages do not change much by excluding the scores for 9th graders of Thomas High School as those were only a small subset of the data.

![image](https://user-images.githubusercontent.com/103223944/166983256-81c82dbb-223c-44c1-a296-5c9d929003e0.png)

