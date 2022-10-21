# “I scream. You scream.  We all scream for Beach Cream”

## Overview of Project:
This analysis helps examine the risk of opening a business that needs to function year round, year after year. What better way to gain insight than looking at the extremes: Mid Summer-June and Mid Winter-December for every year within the data.   

### Results: 
- Using 1700 observations, we see that June temperatures average 74.9 degrees.  It never drops below 64 degrees and it never exceeds 85 degrees:
       <br>
 ![alt text](https://github.com/VinoSarran/surfs_up/blob/main/June.PNG?raw=true)
        <br>
- Using 1517 observations, we see that December temperatures average 71.0 degrees.  It never drops below 56 degrees and it never exceeds 83 degrees:        
  ![alt text](https://github.com/VinoSarran/surfs_up/blob/main/Dec.PNG?raw=true)
         <br>
- 50% of all June observations show a range of 73 to 77 degrees.    While December can get into the 50s, 50% of all observations show a range of 69 to 74 degrees.  

  
  
  
 
### Summary:
- Based on these findings, these months are very similiar and (barring a few chillier December days), beach goers should be around all year and in the mood for ice cream and surfing.  The data shows good evidence that and ice cream shop in this location could be successful year round.  However 2 additional queries can be added to this analysis to confirm this theory: 
- We should examine precipitation using results=engine.execute("SELECT prcp FROM Measurement where date like ('%-06-%')").fetchall().  Inconsistent or bad weather despite the temperature could impact number of beach goers and therefore ice cream sales.  
- We should also review the data grouped by station and rely more on the data closest to the proposed location of our store.  This will allow us to zero in on exact conditions of the local area: results=engine.execute("SELECT avg(tobs),station FROM Measurement where date like ('%-06-%') group by station").fetchall()  
