# Pewlett-Hackard-Analysis
Using SQL

# Purpose of our project
The purpose of this project is to review employment data to determine the number of retiring employees per title. We also identified employees who are eligible to participate in a mentorship program. This information will help the manager of the Pewlett-Hackard company prepare for the "silver tsunami" as many current employees reach retirement age.

# The Results
- The *retirment_titles* table provided a list of every employee currently eligible for retirement, a list of titles held at the company, and the dates they were in each title.

![retirement_titles](https://github.com/CorinneBean/Pewlett-Hackard-Analysis/blob/8f1b241ceb8b2909ba1c39df2f8525c4665e021b/Resources/retirement_titles.png)

- Since some employees held multiple titles over the course of their career, the unique titles table remove duplicate names and provided a list of the most recent title for employees of retirment age.

![unique_titles](https://github.com/CorinneBean/Pewlett-Hackard-Analysis/blob/8f1b241ceb8b2909ba1c39df2f8525c4665e021b/Resources/unique_titles.png)

- We next evaluated which titles would see the most retirements. When evaluating the *retiring_titles* table it was clear to see that the titles which will see the greated effect of the "silver tsunami" will be the Senior Engineer and Senior Staff positions. The Senior Enigneer title will see an estimated 25,916 retirements, and the Senior Staff position will see approximately 24,926 retirements. 

![retiring_titles](https://github.com/CorinneBean/Pewlett-Hackard-Analysis/blob/8f1b241ceb8b2909ba1c39df2f8525c4665e021b/Resources/retiring_titles.png)

- The final step of our analysis evaluated *mentorship_eligibility*, this analysis revealed that there is a large group of eligible employees who can participate in the mentorship program. A majority of the employees who are elgible also hold senior titles.

![mentorship_eligibility](https://github.com/CorinneBean/Pewlett-Hackard-Analysis/blob/8f1b241ceb8b2909ba1c39df2f8525c4665e021b/Resources/mentorship_eligibilty.png)

# Conclusion

There is over half of the current workforce who are elgible for retirement. There is also a large group of eligible employees who can participate in the mentorship program who old senior level titles. My recommendation that HR and hiring manager proactively start training current employees who are eligible for mentorship in anticipation for the mass exodus they will experience as their employees reach their retirement date.

