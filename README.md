# School_District_Analysis_updated
Overview:
The purpose of this analysis is to understand the school performances after removing 9th graders of Thomas High School and analyzing the average scores based on school size and type

- i) First we calculated the percentages of passing math, passing reading and passing overall by removing the math and reading scores for 9th graders studying in Thomas High School which technically means all 9th graders were marked as failed or not graded. 
- This returned a very low percentages - \
  % Passing math = 66.91% \
  % Passing Reading = 69.66% \
  % Overall Passing = 65.07% 

![image](https://user-images.githubusercontent.com/85796900/125201847-e56e6880-e23e-11eb-8484-8fe146333ae2.png)

- ii) Then, we reduced the total count of students studying in Thomas High School by subtracting the count of 9th graders from the total count i.e. we just considered 10th to 12th graders and reperformed our school data analysis
-  This analysis returned a higher percentages which is more accurate- \
      % Passing math = 93.18% \
  % Passing Reading = 97.01% \
  % Overall Passing = 90.63% 
![image](https://user-images.githubusercontent.com/85796900/125204257-5e26f200-e24a-11eb-99b1-c273bde3fe79.png)


iii) With this new calculated score (after removing 9th graders) we compared Thomas High School's performace with other schools and reproduced the top and bottom 5 performing schools -
- Thomas High School is still under top 5 high performing schools list - \
![image](https://user-images.githubusercontent.com/85796900/125204326-ae9e4f80-e24a-11eb-8be5-ddc37050f6c6.png)


We Continued our analysis by creating the DataFrames for Reading and Math scores By Grade which for Thomas High School under 9th was displayed as NaN- 
![image](https://user-images.githubusercontent.com/85796900/125202766-12bd1580-e243-11eb-96bb-0c04612b88e7.png)

![image](https://user-images.githubusercontent.com/85796900/125202803-4ac45880-e243-11eb-890e-0de9f5e263e4.png)

We concluded by calculating the scores by school spending per student, by school size, and by school type - \
First we calculated the spending bins -  \
![image](https://user-images.githubusercontent.com/85796900/125202994-5c5a3000-e244-11eb-982b-c191c8a60731.png)
Thomas High School is under medium bin - \
![image](https://user-images.githubusercontent.com/85796900/125203065-c8d52f00-e244-11eb-969d-b7035c020dbd.png)

Scores by School Size - \
![image](https://user-images.githubusercontent.com/85796900/125203096-ebffde80-e244-11eb-856a-81051c99352b.png)

Scores by School Type - \
![image](https://user-images.githubusercontent.com/85796900/125203113-15b90580-e245-11eb-9dac-5fb6e77c74a7.png)



