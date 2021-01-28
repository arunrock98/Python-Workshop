# Python Workshop


Let us help the chocolate firm chocoBury in its marketing efforts. 

Henry is the experienced Marketing Manager and Mark is the smart software developer responsible for answering Henry’s queries.

Q1. Chocolate firm chocoBury wants to do smart advertisement for their newly launched chocolate brand across Germany in 2019 and target right aged customers. They have collected the years of birth of all of the customers and want to calculate their respective age.

Given below is a list of 10 customers with year of birth, however, the list can be as large as several thousands of customers.

[1999, 1995, 2005, 2010, 2007, 2006, 1994, 1996, 1979, 2008]

The task is to write a function that returns the age of customers.

Sample input:   [1999, 1995, 2005, 2010, 2007, 2006, 1994, 1996, 1979, 2008]
Sample output: [20, 24, 14, 9, 12, 13, 25, 23, 40, 11

Q2. It costs much for the chocolate firm chocoBury to do marketing for wide range of customers. To save money, they want to narrow down the range of ages obtained in previous list.
    
Also, the oldest person and youngest person do not truly represent the targeted group for marketing campaign and they can be considered as outliers.


The task is to write a function that removes the outliers (the oldest and youngest person’s age) and return the new list with age of 8 persons (in this case which contains data for 10 customers initially).
    
Sample input: [20, 24, 14, 9, 12, 13, 25, 23, 40, 11]
Sample output: [20, 24, 14, 12, 13, 25, 23, 11]

Q3. The chocolate firm chocoBury did the survey of customers in Berlin and Munich separately and came up with the following lists of the age of customers.

berlin = [15, 13, 16, 18, 19, 10, 12 ]
munich = [7, 13, 15, 20, 19, 18, 10, 16]

However, marketing manager Henry thinks that a single list would be better to look at rather than having different lists from these 2 cities. So, Henry wants to have a common list from these 2 cities.

The task is to write a function that takes these 2 lists as input and returns the common age values.

Sample input: [15, 13, 16, 18, 19, 10, 12 ], [7, 13, 15, 20, 19, 18, 10, 16]

Sample output: [15,13,16,18,19,10]

Q4. After careful investigation of the common age list, Henry, the marketing manager of the chocolate firm chocoBury, found out that many of the customer ages are simply duplicate values.  So, he asked Mark, the only software developer in the Chocolate company chocoBury, to give him the list with no redundant age values.

The task is to write a function that takes the list with duplicate values as input and return the list with unique age values. 

Sample input: [15,13,16,18,19,15,10]
Sample output: [15,13,16,18,19,10]

Q5. Henry generally asks software developer Mark if a certain age value is present in the list of customer ages or not. However, Henry, a busy manager, often forgets what Mark replies and asks the same question sometimes multiple times.

Mark, a smart guy, thinks it is too boring for him and hence, he thinks why not he creates a function which will listen to Henry’s query and read through the age list & finally reply back to Henry if that age is present or not in the list.
   
The task is to write a function that takes an input list and value of age to find as input and return true or false if the age value is present or not.
            
Sample input: [15,13,16,18,19,15,10], 15
Sample output: True

Sample input: [15,13,16,18,19,15,10], 28
Sample output: False

