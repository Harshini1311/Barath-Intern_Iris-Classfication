# Linear Regression on Iris dataset

Iris flower classification using Machine learning, also referred as Hello World for Machine Learning. It is very basic classification problem which helps understand basic concept of Machine Learning for beginners.

Three class for classification are as follows:

 Iris-setosa
Iris-versicolor
 Iris-virginica

## Strategy
The strategy for implementing a solution is to use k-folds cross validation to create k number of bins in the data and then train and test data on each of these bins which will give Beta for each the bins. To reduce the overfitting, we will find the mean of each Beta value generates for each feature as Beta Mean.

## Folders:
**data** - Iris dataset is stored in the folder

Please check if the below mentioned dependencies are met 
(Possibly can run on lower versions as I use very basic methods and functions)

## Dependecies:
1. Python : 3.8.8
2. pandas : 1.2.4
3. numpy : 1.20.1
4. matplotlib : 3.3.4
5. seaborn : 0.11.1
6. sklearn : 0.24.1

## Run Program:
To Run the code, download the folder wherever required.
In command prompt, first navigate to the iris_regression folder. 
Then, input the below mentioned command:
```
python main.py
```

## Data Description
The Iris Data set contains 5 columns – 
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width
5. Species

## Data Distribution based on labels
| Species | Number of Records |
| :---: | :---: |
| Iris Setosa | 50 |
| Iris Virginica | 50 |
| Iris Versicolor | 50 |

## Results

Based on the various train test values, the mean Beta values change.
**Achieved 98% accuracy**
