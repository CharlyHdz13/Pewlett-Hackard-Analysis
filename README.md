# Pewlett-Hackard-Analysis
## Overview of the analysis
This analysis was made to obtain the staff that would be retiring from Pewlett-Hackard in the upcoming years. This analysis aids the comapny in designing retirement programs and also look onto upcoming retirees who can be asked to become part of the mentorship program. This program wants to merge new talent with people of huge experience in the company, in order to have the new workforce understand who the company operates.
## Results
- Retrieve the retiring employees from the database
  
  This resulted in a table as follows:
  
  ![image](https://user-images.githubusercontent.com/89402038/139591783-dc2b8282-6f05-4927-a81f-47aa61206c12.png)
  
  From this table there are a total of 90,398 employees who will be retiring in the next five years in the company.
 - Retrieve the titles for each retiring employee

  This is the next step to look into which positions will have more free spaces.
  
  ![image](https://user-images.githubusercontent.com/89402038/139592009-92ffb1ac-715e-4373-ab31-fb2f10d68b20.png)
  
  From this table, we can see that there will be a lot of "Senior" personnel leaving the company, but also there will be a big amount of positions free where there new talent does not require many years of expirience to fulfill the roles. For example "Staff" or "Assistant Engineer".
  - Obtain the candidates for the mentorship program

  The table for the mentorship program candidates is made out of all the employees who were born in 1965 and still work at PH.
  
  ![image](https://user-images.githubusercontent.com/89402038/139592468-41ce2de5-4d82-4610-9d37-86e541935553.png)
  
  The count of total candidates available for the mentorship program is of 1549.
  
  - Obtain the unique titles for the candidates for the mentorship program.
  
  ![image](https://user-images.githubusercontent.com/89402038/139592639-ecfced86-e012-4a5c-a912-641d99baf5cf.png)
  
  From this table we can see that 1/3 of the candidates have the "Engineer" title and there are very few "Senior Engineer". From the retiring titles table most of the retiring titles will be "Senior Engineer", therefore many of the candidates of the program should be suggested for a promotion.
## Summary
  - How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    
    The company will have to make up for 90,398 positions in the next five years as showed in the first bullet point in the results. Many of the which are senior roles which demand a lot of expirience in the industry and company. Therefore the company should start to promote and train their new seniors for these important roles.
  - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    
    Here a quick query was made to see which department would have the most retirements in the following years.
    
    ![image](https://user-images.githubusercontent.com/89402038/139695900-fb3bca53-1203-4dfe-bd88-1f0fff49f527.png)
    
    And if we group by departments the candidates for the mentorship program we obtain the following:
    
    ![image](https://user-images.githubusercontent.com/89402038/139696819-8f094a0a-68f4-4340-9e51-4f5ccd3052a9.png)
    
    As the tables show there is not enough people to be able to mentor the new generation inside the company. Therefore, I recommend to encourage the retiring people to take part in this mentorship programs as part of their retirement plan. Otherwise, the new generation will not understand fully how the company works.
