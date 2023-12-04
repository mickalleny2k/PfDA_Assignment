# PfDA_Assignment
Programming for Data Analysis Assignment

# Installation
- Change directory to PfDA_Assignment directory
- Run the Jupyter Notebook in Visual Studio Code terminal or cmder terminal
- Open the notebook PfDA_Assignment.ipynb
  
![Screenshot](./files/installation.PNG)
![Screenshot](./files/installation1.PNG)
![Screenshot](./files/installation2.PNG)
![Screenshot](./files/installation3.PNG)

# INTRODUCTION
As a golf enthusiast myself I picked the real-world phenomenon of the performance of golfers playing professionally on the PGA TOUR and DP World Tour. After some research, I decide that the most important variable is the Average Score of each player calculated over the 2022/2023 season. This is one of my variables (Average Score). The other variables are rank, strokes, rounds, driving distance and TOUR. The variable types are as follows :

- RANK is a non-zero integer
- Average Score is a non-negative real number with two decimal places
- Strokes is a non-zero integer
- Rounds is a non-zero integer
- Driving Distance is a non-zero integer
- TOUR is a categorical variable with 2 possible values : PGA TOUR or PGA/DP.

# CONCLUSION
THe main conclusion you can draw from this notebook is that you can model golf performance accurately and you can synthesize data accurately. RANK follows a uniform distribution. The other variables follow a normal or poisson distribution. The correlation beween RANK and performance is very, very strong as the players who perform the best are generally ranked the highest. We can draw a number of conclusions from the pairplots above:

- There is a linear relationship between AVG and RANK which means the correlation is very strong. Close to 1.
- There is a linear relationship between Total Drives and Total Distance which means the correlation is very strong.
- Total Drives is distributed normally.
- Total Distance is distributed normally.
- AVG is distributed normally.
- The scatter plot of the relaionship between RANK and Total Drives is very scattered which means the correlation is very weak. Close to 0.
- The scatter plot of the relaionship between AVG and Total Drives is quite scattered which means the correlation is weak.
- TOUR is a categorical variable. The results for the PGA Tour and DP World Tour are very similiar. We can see this clearly in the pairplots. I used groupby to group the data according to TOUR. And because the colours of both Tours are different in the pairplots, we can easily compare them. The results are very similiar indeed.

