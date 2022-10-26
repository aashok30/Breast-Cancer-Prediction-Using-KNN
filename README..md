
# Breast Cancer Prediction 
Breast cancer is one of the most common cancers among women in the world. Early detection of breast cancer is essential in reducing their life losses. Build a predictive model using machine learning algorithms to predict whether the tumor is benign or malignant. 


## Data Description 

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius. 
1.	ID number 
2.	Diagnosis (M = malignant, B = benign) 
3-32) 

Ten real-valued features are computed for each cell nucleus: 
a)	radius (mean of distances from center to points on the perimeter) 
b)	texture (standard deviation of gray-scale values) 
c)	perimeter 
d)	area 
e)	smoothness (local variation in radius lengths) 
f)	compactness (perimeter^2 / area - 1.0) 
g)	concavity (severity of concave portions of the contour) 
h)	concave points (number of concave portions of the contour) 
i)	symmetry 
j)	fractal dimension ("coastline approximation" - 1) 


## Tools Used

Python - Jupyter Notebook


## Libraries Used 

Pandas

Numpy

Matplotlib

Seaborn

## Roadmap To The Project

### Data Preprocessing

As I can see that there is no missing value in the data.

I have decided to opted for Label Encoding for dependent variable.


### Model Building

Before building the model I have splited our data into train and test by the ratio of 80:20 and Scaled the data.

I have used KNN MLA to building our model also check with differnet n_neighbors and decided to choose n_neighbors as 5 which fit for the model and avoid overfitting.

### Model Accuracy & Performance

I have got 94% of by KNN.


Note: 
This repository includes the information of a project which I had completed during my Data Science Prodegree Program.


