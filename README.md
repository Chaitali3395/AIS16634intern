Task 1:
1]Variable declaration rule: studied the rules for declaration of variables
2]Operators: Studied various operators in python namely Arithematic,logical,assignment,identity,bitwise,membership,comparison etc
3]List: Studied the datatype list and its methods like append remove insert pop  sort count,accessing,copy reverse and its properties(mutable)
4]Tuples:-studied how to declare tuple its methods like count index etc  properties like immutable unorders etc
5]Set: set declaration,properties like mutable,orderd,etc
6]Dictionary:- declation of dict,methods like copy index pop and use of for loop for accessing
7]string: declaration and use of functions like upper lower split strip replace ect
8]Numeric:- subtpes like int float and complex

TASK 2:
1]if stmt:- use of if statement to check a single condition in vaious examples like to check whther a number is positive negative even or not within a range or not etc
2]if else stmt: used to check two conditions in examples like checking a number is odd or even, greater or smaller,negative or positive whether a person and vote or not and other similar examples
3] if elif else:- to test multiple conditions at a time if the above condition  false then the next one to it is tested.Studied examples like to check whether a num is positive negative or zero result of a student and other similar examples
4] For loop: used for accessinng the elemnts in a list tuple and its methods 
5] while loop: use of while loop to print a sequence of number print tables checking a number is palimdrome or not armstron or not etc and other statements like break continue pass

Task 3:
1]break stmt: usedto control the sequence of the loop. Suppose you want to terminate a loop and skip to the next code after the loop; break will help you do that.
#With the break statement we can stop the loop before it has looped through all the items:
2]pass stmt:has no-operation statement, meaning it does nothing when executed. Its primary uses are:
#Placeholder for Future Code: It allows you to write syntactically correct code when you have not yet implemented the functionality but need to leave a placeholder.
3] continue stmt: used to continue the loop as like break stmt it does not terminate when the condition is met but it continue escaping the condition that is met
3]statistical user defined functuions: created function to find mean variance median mode skewness rane etc
5]logical user defined functions: created functions to sole logical problems like finding theeven or odd number,palimdrome armstrong suare of number area of circl etc

Task 4:
1] numpy 1: studied what is NumPy,different methods and functions of numpy like creading 1d 2d 3d arrays indexing slicing shape reshape datatypes in numpy view copy join spliting of arrays iterating search sort and filtering arrays
2] numpy 2: studied the random function used in numpy data distribution seaborn module random permutation noram chisquare binomial poisson logistic multinomial distributions .thir distribution plots using matpotlib and seaborn .generating randon numbers etc.studied ufunc(universal function) like add subtract multiply diff product sin costan antisin anticos anti tan radian to degree and vise versa,,lcd,gcd,hypothenius etc


Task 5 -
In task 5 we studied the pandas library in python.
#we see creation of series and their operation .A Pandas Series is like a column in a table. It is a one-
dimensional array holding data of any type.
#Then we see the data frame creation using dictionary and matrix ,and how to to read data in csv and
xlsx file in panda library in python.
#Data frame operation -
In data frame operation different methods of operation like value count , apply, unique,
nunique,describe,merge,sort etc
#selection-
In selection we see that how to select data frame column and row by using (loc,iloc) function .
#In pandas, selecting data from a DataFrame involves specifying which columns and/or rows you want
to work with.
#we can use several methods for selection, including .loc, .iloc, and boolean indexing.
Also conditional selection with how to add , delete and update column in the data frame .Also seen that
indexing and removing indexing by set reset function.
Operation between two columns like addition , substraction, multiplication and division are carried out .
#missing values
In missing values we studied checking missing values, how to drop missing values by row and by column
and also filling missing values by mean ,median etc.By using function
#Using isnull(): This method returns a DataFrame of the same shape with boolean values indicating
whether the data is missing (True) or not (False).
#we can drop rows that contain any missing values using dropna(axis=0):
#we can fill missing values with a specific value using fillna(value):

Task 6 -
In task 6 we studied the matplotlib and seaborn library.
Matplotlib is a graph plotting library in python that serves as a visualization utility.
#Pyplot
Most of the Matplotlib utilities lies under the pyplot submodule, and are usually imported under the plt
alias:
#import matplotlib.pyplot as plt
#Plotting x and y points
The plot() function is used to draw points (markers) in a diagram.
In matplotlib we study matplotlib plotting with markers,lines,labels,grid,subplot,scatter plot,bars,
histograms and pie charts .
#seaborn libraray-
Seaborn is a powerful and versatile data visualization library in Python, built on top of the popular
Matplotlib library.
It provides a high-level interface for drawing attractive and informative statistical graphics.
Seaborn is particularly useful for visualizing complex datasets and for creating aesthetically pleasing
visualizations with minimal code.
#import seaborn as sns
#In seaborn library we see different types of plotting of graphs such as distribution plot, box plot, violin
plot, bar plot,scatter pot,
line plot, heatmap, pair plot ,facet grid, regression plot , residual plot.

Task 7
1] Numpy exercise:- solved probles related to array indexing slicing,creating arrays containg zeros ones generating random numbers from normal distribution,using linspace addition of elements in an array calculate mean standard deviation, etc
2]Ecommerce purchase exercise:- studied the dataset and found out the mean purchase price maximum and minimum purchase price,number of people having job title lawyer number of people making the purchase during the AM and how many people made the purchase during PM,5 most common Job Titles,person with the following Credit Card Number: 4926535242672853 ,number of people have American Express as their Credit Card Provider and made a purchase above $95,number of people have a credit card that expires in 2025,top 5 most popular email providers/hosts (e.g. gmail.com, yahoo.com, etc...)
3] Salary exercise:-studied the data read the file and found out average BasePay,the highest amount of OvertimePay in the dataset,job title of JOSEPH DRISCOLL, How much does JOSEPH DRISCOLL make,name of highest paid person,name of lowest paid person,the average (mean) BasePay of all employees per year,number of unique job titles,the top 5 most common jobs,number of  Job Titles were represented by only one person in 2013, people have the word Chief in their job title,there a correlation between length of the Job Title string and Salary

#Case study -
In this case study we download the titanic data from kaggle and import it to jupyter notebook.Then we find the missing values and filled the missing values by its mean ,and droped the variable like cabin,passenger id etc. Then we do label encoding for the categorical variable.
Then Performd the EDA i.e exploratory data analysis on titanic data such as bar plot,scatter plot,joint plot and pie chart .
From the graph it is seen that the females are survived more than males.The passengers who are in class 1st are most survived as compared to class 2nd and 3rd.
In titanic data survival is the dependent variable and other variables like age,sex,fare,sibps,embarked are independent variables.
Then we split data into train test and fit the algorithms like naive bayes,KNN, dicision tree and predict the text data using particular fitted model.
In model evaluation we find accuracy,classification report,confusion matrix,precision and recall for each algorithm .and compare it with each other and we may conclude that 
decision tree is the best model on the basis of prcision , accuracy and recall, Where the values of precision,accuracy and recall for dicision tree are high as compared to knn and naive bayes.

#Dashboard-
In this task we created a dashoard on project data i.e Bike sharing demand data in power bi dashboard.We download the Bike sharing demand data from kaggle. In power bi we get the data from csv file then by using graphs ,sclicers,card and other features we create a dashoard in power bi.

#Project-
In the bike sharing demand data prediction project we download the data from kaggle and import it to jupyter notebook then perform EDA on the data.
Then we cleaned data by handling missing values and outliers to build the various models like - linear regression,ridge regression,elastic net, random forest, decision tree,KNN,SVR9Support vector regressor),PCR(principal component regbressor),PLSR(partial least square regressor),Gradient Boosting and find the root mean square error and R square for all the 10 models.
Then we perform grid search cv on 10 models to find the best parameter once we find the Best parameters then again we build the 10 models with that best parameter, and find the RMSE and R square values after the grid search cv .
Also we find feature importance from decision tree model and find the best parameter i.e Hour , tempreture,solar radiation,humidity,seasons and holiday and fit the all 10 models with these 6 variables.and find the RMSE and R square of all models.
Then plot the bar graphs and joint bar plots of rmse values and r square values. Also compare the rmse and R square values of before and after grid search cv .
