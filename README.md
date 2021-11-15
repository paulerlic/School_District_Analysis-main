_______________________________________________________________________________________________________________________
# School_District_Analysis

## Project Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We have been tasked with replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we've done this we are going to run the analysis again, and compare the results between the two analyses to how the replacing the data affected our results.    

## Analysis 
The following section describes how sections of our code were affected by removing 9th grade math and reading scores at Thomas High School.

### District Summary 
The district summary changed slightly, the average math score decreased by .04% from 78.985% to 78.931%. The average reading score decreased from 81.878% to 81.856%. There was a minor decrease in percentage of students who passed math , 74.98% of students had passed math before refactoring data, after removing the 9th grade THS students 74.76% passed math. The percentae of students who passed reading had a slight decrease from 85.81% passing to 85.66%. The overall percentage of students who were passing both math or reading declined from 65.17% to 64.86%

**All scores included
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/district%20summary%20all%20scores%20included1.png)


**9th grade scores removed
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/district%20summary%209th%20grade%20scores%20removed2.png)

### School Summary
School summary results paint a different picture roughly one fourth of Thomas High School students test grades had to be converted to null values, while only a minute portion of the district's total number of student test scores.

Avg math scores for Thomas went from 83.42% to 83.35%. Average reading scores had slight increase from 83.85% to 83.90%. While the average scores saw little change with the removal of the 9th graders at Thomas, there was a significant change with the percentage of students passing math, reading, and overall pass rates. When all students were included in the dataframe at Thomas, 93.27% were passing math, 97.31% were passing reading, and 90.95% of students were passing both. However, once we removed the 9th graders from the data, the scores dropped sharply to 66.91%, 69.66%, and 65.08%. 

**With all scores included
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/School%20summary%20all%20scores3.png)

**With 9th grade scores removed
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/school%20summary%209th%20grade%20scores%20removed%204.png)

### Thomas High School Performance
Before removing the 9th grade scores, Thomas High School ranked 2nd in pass percentage with 90.95% of students passing reading and math. Thomas's overall percentage of overall students passing dropped sharply after removing the 9th grade scores with 65.08% of all 10th - 12th graders passing. 
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Thomas%20High%20School%20Performance5.png)

### Score Statistics
* Reading and Math Scores by Grade
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Math%20%26%20Reading%20Scores%20by%20Grade%20Figueroa6.png)
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Math%20%26%20Reading%20Scores%20by%20Grade%20Figueroa7.png)
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Math%20%26%20Reading%20Scores%20by%20Grade%20Figueroa8.png)
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Math%20%26%20Reading%20Scores%20by%20Grade%20Figueroa9.png)

The only real difference in the math and reading scores by grade is with the refactored code, we see null values instead of the scores for both sections at Thomas because we removed their scores from the data. 

* Scores by spending
Only minor changes in spending scores were seen in the $630-644 bin. Before removing the 9th graders at Thomas scores, 73.48% were passing math, 84.39% were passing reading, and 62.86% were passing both. After the removal, the scores became 73.46%, 84.32%, and 62.78%. 

![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/SpendingRanges10.png)
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/SpendingRanges11.png)


* Scores by size
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Scores%20by%20school%20size%2012.png)
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Scores%20by%20school%20size%2013.png)

Changes in the school size data were marginal, the only bin affected was the Medium (1000-2000) bin.



* Scores by school type
*9th grade scores at Thomas removed
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Charter-district12.png)

* All scores
![image](https://raw.githubusercontent.com/paulerlic/School_District_Analysis-main/main/Charter-district13.png)

Since Thmoas is a charter school its reasonable that we would see a change in the bings for them since the data was only lightly impacted with the removal of scores.


## Summary
### Changes in the data due to the removal of Thomas High School 9th Grade Reading & Math Scores
1) Thomas did not perform as well compared to other the high schools,  in regards to the overall passing percentage when the scores of the 9th graders were removed.
2) The percentage of students passing, math, reading, and overall pass percentages dropped by a very small margin when the scores were removed.
3) Performance based on school spending showed a minor dip for scores that were in the $630-644 bin.  
4) Performance based on school size saw a relativley similar minor decrease in scoring among medium sized schools. 

