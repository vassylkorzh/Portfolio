# Portfolio
My Data Science Portfolio
## [Project 1 - Titanic Data set](https://github.com/vassylkorzh/Project-Titanic-Data-Set)
Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck
![](/img/Age&Gender.png)
![](/img/ModelResults.png)

## [Project 2 - "Oscar" Data Base (Oracle & MS)](https://github.com/vassylkorzh/Project-SQL-Oscar-DB)
Entity-relationship diagram for the database for collecting information on the Oscar Film Academy Award

![](/img/Oscar_model.png)

## [Project 3 - ML from scratch in python](https://github.com/vassylkorzh/ML-from-scratch-in-Python)
KNN,Perceptron & "Single-layer neural network" for language classification

## [Project 4 - ETL-Vachicle-Service](https://github.com/vassylkorzh/ETL-Project-Vachicle-Service)
* There are 5 errors in the data. Find them

The CustomerID field does not contain duplicate records.

Suggest explanations how each of the errors could have occurred 
and what you think is the best way to fix each one.

You know that the total projected revenue for 2016 equals: $419,896,187.87. 
You need the uploaded data to match this value (this means that every row is important).

### First step 

Using Visual Studio with ssdt-bi I automatically excluded  
![](/img/VisualStudio.PNG)

The condition to split the data into bad and good records was 

`if len(column6)>0 & len(2016E)==0 it all bad raws due to there error `

"CustomerID" | "CustomerSince"| "Vehicle" | "2014" | "2015" | "2016E" | "Column 6"|
-------------|----------------|-----------|--------|--------|---------|-----------|
  2738818    |  2014-01-01    |2009 Chevrolet Traverse|118|01|122.55|725.89
 
 1. 2738818;2014-01-01;2009 Chevrolet Traverse;118;01;122.55;725.89 - error due to 118;01; as for me here it should be 118.01
 * [continuation](https://github.com/vassylkorzh/ETL-Project-Vachicle-Service)

## [Project 5 - Customer_Segmentation](https://github.com/vassylkorzh/Customer_Segmentation)
### Using Machine Learning to segment customers in Python&Tableau
  
   Customer Segmentation is one of the most important applications of unsupervised learning. Using clustering techniques, companies can identify several segments of customers allowing them to target the potential user base.
  
![](/img/clusters.png)
