# Principal Component Analysis (PCA)

## Project Objective:

The purpose for the first two parts of this project is to conduct principal component analysis (PCA) using the data describing students working through online math problems. The purpose of the third part of the project is to perform PCA on data about people's sense of humour.  

## Datasets:

  * Assistment-confidence.csv
  
The data comes from the Assistments online intelligent tutoring system (https://www.assistments.org/). It describes students working through online math problems. Each student has the following data associated with them:

- id
- prior_prob_count: How many problems a student has answered in the system prior to this session
- prior_percent_correct: The percentage of problems a student has answered correctly prior to this session
- problems_attempted: The number of problems the student has attempted in the current session
- mean_correct: The average number of correct answers a student made on their first attempt at problems in the current session
- mean_hint: The average number of hints a student asked for in the current session
- mean_attempt: The average number of attempts a student took to answer a problem in the current session
- mean_confidence: The average confidence each student has in their ability to answer the problems in the current session

  * humor_data.csv
  * humor_codebook.txt

## Results:

### Part I and Part II:

    * Biplot of PCA showing which variables going together:
    ![graph](https://github.com/lizarova777/assignment4/blob/master/Biplot.png)
    
When it comes to PC1, it accounts for the most variance in the three following variables: mean_hint, mean_attempt, and problems_attempted. As in, it contributes the most to these variance. It accounts for 30.22% of variance in the average number of hints a student asked for in the current session, 25.86% of variance in the average number of attempts a student took to answer a problem in the current session, and 21.74% of variance in the number of problems the student has attempted in the current session. PC2 contributes the most to prior_prob_count, prior_percent_correct, and problems_attempted. It accounts for 25.08% of variance in how many problems a student has answered in the system prior to this session, 44.68% of variance in the percentage of problems a student has answered correctly prior to this session, and 17.34% of variance in the number of problems the student has attempted in the current session. PC3 contributes the most to prior_prob_count, problems_attempted, and mean_confidence. It accounts for 22.10% of variance in how many problems a student has answered in the system prior to this session, 20.06% of variance in the number of problems the student has attempted in the current session, and 45.79% of variance in the average confidence each student has in their ability to answer the problems in the current session, which is substantial. PC4 contributes the most only to prior_prob_count and mean_confidence. It accounts for 31.52% of variance in how many problems a student has answered in the system prior to this session. and 22.61% of variance in he average confidence each student has in their ability to answer the problems in the current session. PC5 contributes the most only to problems_attempted and mean_attempt. It accounts for 30.39% of variance in the number of problems the student has attempted in the current session, and 35.77% of variance in the average number of attempts a student took to answer a problem in the current session. PC6 only contributes the most to mean_hint. As in, it accounts for 35.61% of variance in the average number of hints a student asked for in the current session. 

### Part III:

    * Biplot of PCA showing which variables going together:
    ![graph](https://github.com/lizarova777/assignment4/blob/master/Biplot2.png)
    
The biplot displays a pattern that greatly resembles the four scale scores of the Humor Styles Questionnaire (HSQ). First, it shows that the variables go in four directions. Second, the pattern of variables that "go together" is similar as to how the variables are grouped into four scale scores of the HSQ, which are affiliative, self-enhancing, aggressive, and self-defeating. In other words, they represent the same construct. However, there are some exceptions such as Q16 (I don't often say funny things to put myself down.). Each of the groups points towards a particular direction. 
