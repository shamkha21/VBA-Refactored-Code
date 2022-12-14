# Analysis on VBA-Refactored-Code 
## Overview of Project 
### Purpose and Background 
Steve, a client has multiple stocks that he would like to analyze. With the code from the module conducted it would take a longer time and many steps to analyze. Our purpose is to refactor or edit the existing code so that Steve can efficently analyze stocks and that code should require less steps, and avoiding the nested loops. 
## Results  
#### Code Run Times
The Refactored Code ran faster than the Original code. 

![Refactored Code 2018 Run Time](Refactored2018.png)
 
2018 Refactored 0.03125  
 
![Alt text](Refactored2017.png)
 
2017 Refactored 0.027343  
 
![Alt text](2017originalcode.png)
 
2017 Original Code 0.2261718  
 
![Alt text](2018Originalcode.png)
 
 2018 Original Code 0.2578125 

#### Stock Results  
The stocks preformed overall well in 2017 with all but one a increase in return. The only stock that had a negative return was "TERP". However in 2018 only two stocks "ENPH" and "RUN" had an increase in return while all others were at a loss. 

2017 Stocks Return & Daily Volume 

![Alt text](2017stocks.png)
 
2018 Stocks Return & Daily Volume  

![Alt text](2018stocks.png) 

## Summary  

### Advantages and Disadvantages on Refactoring Code  
There are  many advantages and disadvantages to refactoring code. A few advantages are simplifying the code and as the example shown in the results section, decreases the code run time. Disadvantages of refactoring code are it is time consuming or you can introduce bugs to your code. 
### Advantages and Disadvantages of the Original and Refactored VBA script 
These pros and cons apply to the original and refactored vba script in regards to having the same advantages and disadvantages as I listed above. We avoided nested loops in the refactored VBA which had part in why the run time was faster for the refactored code as well as easier to undertand. The cons were I did have to debug my code a few times which made it time consuming. 
