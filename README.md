# Openclassroom-projet3

## Description : 

The “Santé publique France” agency has launched a call for projects to find innovative ideas for food-related applications. You want to participate and propose an idea for an application.
I decided to create an application that calculates the sugar level of different products for diabetics.
This second notebook will explore the data.

## Environnement :

Two notebook.

jeu de données : https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip

## Content:

#### I – Data cleaning

###### First analysis of the dataframe
###### Application idea
Application based on the calculation of the sugar level of foods. I took all the sugars and their derivatives as well as the different information that could be useful for the consumer and the nutriscore. 
###### Treatment of outliers
Drop all the values : above 100 and below 0 for sugar, this derivatives and proteins, above 3000 and below 0 for energy and above -15 and below 40 for nutriscore. 
###### Treatment of missing values
I select all the produits that are buy in France. I deal with missing values by imputing with median or 0. For the nutriscore, I use KNN algorithm.


#### II – Exploratory analysis

###### Univariate analysis.
Describes, piechart, hisgramm, boxplot.
###### Bivariate analysis.
Pairplot, correlation matrix, boxplot.
###### Multivariate analysis.
ACP, ANOVA.
