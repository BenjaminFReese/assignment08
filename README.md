# assignment08
This is Benjamin Reese's repo for assignment08
The assignment08.html file contains the final result of the analysis and assignment08.qmd contains the code that generates assignment08.html. 
Before running the code, be sure to include a data folder in your working directory with the four required datasets as mentioned in assignment08.html. 
The code executes four individual exercises that ranges from machine learning and text analysis to data visualization. The first exercise runs a principal
component analysis model on Senate votes from the 103rd Congress. The percent variance and percent cumulative variance for the principal components are calculated
and the PCs are visualized showing voting behavior color coded by both party and US region. The second exercise performs cluster analysis on the same data, 
finds the optimal number of clusters, creates a function that allows users to input the number of clusters manually, and visualizes the results. The third exercise 
uses text analysis methods to analyze bi-grams in presidential executive orders. The code creates the bi-grams, visualizes the most common bi-grams, and further 
calculates the most common bi-gram frequencies, using TF-IDF, for each president included in the dataset. A visualization of the bi-grams frequencies for each president
is also included. Finally, the fourth exercise estimates a logistic regression predictive model based on a text description of bills to predict if a bill will pass or not.
The code loads in the bill description dataset, splits the data into training and testing, creates a recipe removing stopwords and custom stopwords, as well as other
pre-processing decisions, estimates the model and calculates the model's quality based on the following metrics: accuracy, precision, recall, the ROC Curve, and the AUC.
The final model was highly accurate, about .96, and had a good ROC curve and AUC metric, but suffered from low recall and precision. Assignment08.html ends with a
discussion of how to improve the model.
