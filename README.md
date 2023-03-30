# Pima-Indians-Diabetes-Dataset

Given the Pima Indians Diabetes Database as a csv file. This data-set is originally
from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to
predict based on diagnostic measurements whether a patient has diabetes. Several constraints
were placed on the selection of these instances from a larger database. In particular, all patients
here are females with at least 21 years old of Pima Indian heritage.  

It contains following 9 attributes.
* pregs: Number of times pregnant
* plas: Plasma glucose concentration 2 hours in an oral glucose tolerance test*
* pres: Diastolic blood pressure (mm Hg)
* skin: Triceps skin fold thickness (mm)
* test: 2-Hour serum insulin (mu U/mL)
* BMI: Body mass index (weight in kg/(height in m)^2)
* pedi: Diabetes pedigree function
* Age: Age (years)
* class: Class variable (0 or 1)


The Data_Visualization code:
* Loads the csv file into the Spyder Enviornment.
* Calculates and print the various statistical features of each attribute like Mean, Median, Mode etc.
* Calculates and print the correlation cofficient between the target attribute and various columns
* Plots the scatter plot between 2 different attributes.


The Data_Preprocessing code:
* Imports PCA from sklearn.
* Loads the csv file into the Spyder Enviornment.
* Normalization and standarization of each and every attribute except the target class.
* Then generates a syntheic data inoder to perform Eigenvalue and EigenVector decomposition.
* Applys PCA on the given Dataset in oder to reduce the dimensions of the data.
* Caluculates and print the covarience matrix after dimensionality reduction.



# Input Dataset

https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

# Output

