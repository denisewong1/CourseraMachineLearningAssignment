## Machine Learning Assignment
This repository contains my assignment for the JHU Coursera Machine Learning module.

## Executive Summary  
Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 
The goal of this machine learning project is to use a training data set from accelerometers on the belt, forearm, arm, and dumbell of 6 participants to predict quality of barbell lifts for a separate unseen test data set. 
More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

## Overview of the Training Dataset  
Six young health participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E).  
Class A corresponds to the specified execution of the exercise, while the other 4 classes correspond to common mistakes. Participants were supervised by an experienced weight lifter to make sure the execution complied to the manner they were supposed to simulate. The exercises were performed by six male participants aged between 20-28 years, with little weight lifting experience. We made sure that all participants could easily simulate the mistakes in a safe and controlled manner by using a relatively light dumbbell (1.25kg). 

## Data
The data for this project comes from this source: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har. 

The machine learning algorithms used were  
1/ linear discriminant analysis - 69.1% accuracy on training set, 68.1% accuracy on test set  
2/ gradient boosting model - 99.2% accuracy on the training set, 98.8% accuracy on the test set  
The GBM model was used to generate the predictions on the unseen data set for the quiz.  
