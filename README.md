![image](https://github.com/Bmdhia/Rating_Predictions/assets/136000177/5740a9fc-f9e3-456a-a6c8-c207ab9bb76c)


# Rating_Predictions

Dhia Ben marzouk

## Context

The number of restaurants in New York is increasing day by day. Many people are eager to dine out, and checking restaurant ratings is an excellent option for them. It ensures they find delicious food tailored to their tastes. We will offer suggestions for multiple restaurants through our rating system.

## Background and motivation

####  This project will be a Rating prediction for Food Ordering and Delivery

Data Source :

Click [here](https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset) to download the data

#### Data Description : 
The data contains the different data related to a food order. The detailed data dictionary is given below.

#### Data Dictionary

* order_id: Unique ID of the order
* customer_id: ID of the customer who ordered the food
* restaurant_name: Name of the restaurant
*  cuisine_type: Cuisine ordered by the customer
* cost: Cost of the order
* day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
* rating: Rating given by the customer out of 5
* food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the 
* delivery person's pick-up confirmation.
* delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up 
 confirmation and drop-off information

The DataFrame has 9 columns, as mentioned in the Data Dictionary, and it contains 1898 rows corresponding to customer orders.

## Exploratory Data Analysis:

![image](https://github.com/Bmdhia/Rating_Predictions/assets/136000177/9c73ec6b-6632-48fe-a986-02f1a24b9c72)

Above is the top ten popular restaurants , in order, are Shake Shack, The Meatball Shop, and Blue Ribbon Sushi.

![image](https://github.com/Bmdhia/Rating_Predictions/assets/136000177/de32c050-c342-4519-91dd-2f1cb77604f6)

Ratings in the dataset are limited to three discrete values (3, 4, and 5 stars), with the majority of customers giving 5-star ratings, and the minimum possible rating being 3 stars.

## Maching Learning Using the Following Models:

* RandomForestClassifier
* XGBoost
* KNN

## Deep learning Using the Following Model:

* Sequential

## Models Evaluated & Results:

* RandomForestClassifier:
  
  Accuracy : 0.52063

* XGBoost:
  
  Accuracy : 0.43174

* KNN:
 
  Accuracy : 0.48571

* Sequential ( Deep Learning ):
  
  Accuracy : 0.39  

#### The selected final model is a RandomForestClassifier that has been fine-tuned with the following hyperparameters: 'max_depth' set to 5, 'min_samples_leaf' set to 4, 'min_samples_split' set to 10, and 'n_estimators' set to 50.

## Recommendations:

* I recommend making changes to the input features, adjusting model settings, or trying different methods for predicting ratings in food ordering and delivery to improve the accuracy and reliability of your predictions.

## Limitations & Next Steps:

* Our challenge is the limited size of our training data, which may affect our model's accuracy; to address this, we will employ data augmentation techniques to expand the training dataset, thereby improving our model's predictive capabilities.

### For Further Information:

For any additional questions, please contact:

Dhia Ben Marzouk

adresse.de.dhia@gmail.com
