This project is for conducting exploratory data analysis on the the Iris dataset.

Conclusions from EDA on iris dataset :

The iris dataset is a small dataset with only 150 observations and 5 features

The dataset is giving the information about a flowering plant which has 3 different species namely setosa , versicolor and virginica.

The dataset provides the sepal_length , sepal_width , petal_length and petal_width of the sample specimens and also provides the flowering species of the specimens.

The dataset consists of no duplicated observations .
The dataset has no missing values present.
The dataset consist of equal number of specimens for each species class.


The overall distribution of sepal length column irrespective of species is similiar to normal distribution with peak around 5.7 .
The overall distribution of sepal width column irrespective of species is similiar to normal distribution with peak around 3.0 .
Petal length column shows two peaks in the distribution.
Petal width column also shows two peaks in the distribution . 

According to the boxplots , absence of outliers in all the columns majorly.

SEPAL LENGTH :
We see a clear separation in the mean values of sepal length of setosa , versicolor and virginica.
mean values of sepal length for setosa is at 5.0 , for versicolor at 5.8 , and for virginica at 6.5.
There IQR range is also distinguised and can provide a easy prediction of flowering species based on sepal length . 
However lower and upper extreme sepal lengths for each class coincides with the other class . 


SEPAL WIDTH :

IQR of setosa's sepal width is clearly separable from the rest two species . The range of setosa sepal width is around [3.2 , 3.6]  
Though the boundaries of sepal width of setosa and virginica slightly coincides . We can also see presence of two outliers in the sepal width of virginica

PETAL LENGTH AND PETAL WIDTH :

petal length and petal width of setosa and virginica are completely distinguisable from the other two species . 
petal length of setosa is less than 2 even in the extreme values.
virginica has the longest petal lengths. The mean is around 5.6.The IQR range is around [5.1 , 5.8]
for versicolor the petal length IQR range is around [4,4.5]
The petal width IQR of setosa is less than 0.5 , while for versicolor the range is [1.2,1.5] and for virginica it is [1.7,2.3]
 