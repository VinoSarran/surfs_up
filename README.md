# “I scream. You scream.  We all scream for Beach Cream”

## Overview of Project:
This analysis helps examine the risk of opening a business that needs to function year round, year after year. What better way to gain insight than looking at the extremes: Mid Summer-June and Mid Winter-December for every year within the data.   

### Results: 
- Running a distinct count on the table housing retired employees and their titles shows that more than 90,000 employees could be retiring of the 300,000 in the employee table:
       <br>
 ![alt text](https://github.com/VinoSarran/surfs_up/blob/main/June.PNG?raw=true)
        <br>
- Further inspection shows a need to clean data further.  Some of the employees have had numerous titles.  Restricting the table to only show current titles will remove duplicates and shows that more than 72,000 employees could be retiring of the 300,000 in the employee table:        
  ![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/70Kstillworking.PNG?raw=true)
         <br>
- Unfortunately, when broken out by Title, we see that over 50,000 of those 72,000 retiring hold Senior Engineering or Senior Staff roles.  Roles difficult to recruit and hire for:        
  ![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/titlesbreakout.PNG?raw=true)
         <br>
- To soften the blow, Pewlett-Hackard has identified 1,549 employees who are still roughly 10 years from retirement that can become mentees to those eligible for retirement.  Their titles range but still cover the fields needed in this knowledge sharing effort.        
  ![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/Mentee.PNG?raw=true)
  
  
  
 
### Summary:
- 72,458 roles will need to be filled as a result of the "silver tsunami"
- Even with minimal participation, there should be more than enough retirement-ready employees to train the 1,549 mentorship-eligible employees.  These 2 tables show tremendous overlap in titles between the 2 populations.  
![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/Mentee.PNG?raw=true)![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/titlesbreakout.PNG?raw=true)

- Finally, not all retirement ready employees should be considered mentors.  There is a population of 5,315 soon to be retired employees who started with the company much later in their careers and have low tenure.  DOB 1955 but started  at 40+ years of age after 1996.  While they may have skills to share, there are 1,422 mentees that would have been at Pewlette Hackard for longer:  
![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/RetireLowTenure.PNG?raw=true)![alt text](https://github.com/VinoSarran/Pewlett-Hackard-Analysis/blob/main/Resources/MenteeHighTenure.PNG?raw=true)

