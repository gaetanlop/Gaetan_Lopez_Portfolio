[Link to my github profile](https://github.com/gaetanlop)

## [Paris Real Estate Price Prediction](https://github.com/gaetanlop/Apartments_Paris)
**Final Product Hosted On Heroku:** [https://house-price-prediction-paris.herokuapp.com/](https://house-price-prediction-paris.herokuapp.com/)

I created a web app that estimates the Price of an apartment In Paris in 2020. Such a tool can be used to help people finding the best price to sold or buy an apartment. It also can be used by real estate companies to give an estimation of the price of an apartment of one of their clients without sending an expert to check the apartment.

*   Created a web app that estimates the price of an apartment in Paris in 2020 (MAE ~ € 74 K).
*   Scraped more than 4000 sell announcements of apartments in Paris from LogicImmo website using python and selenium.
*   Engineered features from the text of each announcements description to get the different caracteristics of an apartment in Paris such as balcony, patio, cellar, parking, floor of the apartment, floor of the building.
*   Optimized Linear, Lasso, Ridge, Random Forest Regressors and XGBoost Regressors using RandomizedSearchCV to reach the best model.
*   Built a client facing API using flask.
*   Used HTML, CSS, JS for the UI.
*   Deployed the model on AWS EC2 instance and on Heroku.

[![](/image/Paris_apartment_demo.PNG)](https://house-price-prediction-paris.herokuapp.com/)

## [Pneumonia-Detection](https://github.com/gaetanlop/Pneumonia-Detection)
**Final Product Hosted On Heroku:** [https://pneumonia-detection-appli.herokuapp.com/](https://pneumonia-detection-appli.herokuapp.com/)

I created a tool that classifies pediatric chest X-rays to detect pneumonia. One way to depict Penumonia is by using chest X-ray images. They are obtain easily but the problem is in radiologic interpretation of images which are not always available. Therefore, such a tool could be use to predict fast and automatically whether or not someone have pneumonia. 

*   Project done using the Fast.ai Library.
*   I created a tool that classifies pediatric chest X-rays to detect pneumonia.
*   Performed Data preprocessing and Augmentation.
*   Used transfer learning (pretrained resnet34). 
*   Used the learning rate finder to find the best learning rate to update the weights. 
*   Fine-tuned the model.
*   Built a client facing API using Flask.
*   Deployed the model on Heroku.

[![](/image/pneumonia_detector.png)](https://pneumonia-detection-appli.herokuapp.com/)

## [Hotel Booking Cancelation](https://github.com/gaetanlop/Hotel_Booking_Cancelation)

In this project, I created a tool that predict whether or not a Booking will be cancelled. Such a tool can help hotels in their Overbooking Strategy. Indeed, this tool can be used to predict with a high accuracy the number of rooms that will be cancelled and therefore put the room for rent again. Such a strategy can help to maximize the total capacity and increase the overall revenue of the hotel.

* Created a tool that predict whether or not a Booking will be cancelled (Recall ~ 86.60%) to help hotel maximize their profits.
* Data collection on Kaggle Website: https://www.kaggle.com/jessemostipak/hotel-booking-demand
* Cleaned the Data and Removed sources of Data Leakage (four features where present in the dataset, but could not be used to make predictions since we would not have these informations at the time we make the prediction).
* Generated one other feature and Used SelectKMean for Feature Selection.
* Choose Recall over the different metrics of classification problems because I wanted to minimize False Negative Rate (the number of bookings that we will predict canceled but that will not be).
* Optimized Logistic, Random Forest Classifier and XGBoost Classifier using GridSearchCV to reach the best model.
* Stacked three different models using Voting Classifier of Scikit Learn.

## [Clothing_Classification](https://github.com/gaetanlop/Clothing_Classification)
**Final Product Hosted On Heroku:** [https://clothing-classification.herokuapp.com/](https://clothing-classification.herokuapp.com/)

I created a tool that classify images of clothes into their corresponding categories (t-shirts,shirts,jeans...). Such a tool can be used by e-commerce websites to automatically create the different keywords for each of their articles. For example, for each new items it will tell directly in which category the new item belongs. 

*   Project done using the Fast.ai Library.
*   I created a tool that classify images of clothes into their corresponding categories. 
*   Scraped more than 1000  images of clothes from Google Image.
*   Cleaned Data based on the predictions of a simple convolutional neural net.  
*   Used transfer learning (pretrained resnet34). 
*   Used the learning rate finder to find the best learning rate to update the weights. 
*   Fine-tuned the model
*   Built a client facing API using Voila.
*   Deployed the model on Heroku.

[![](/image/Data_clothing.png)](https://clothing-classification.herokuapp.com/)

## [Malaria-Detection](https://github.com/gaetanlop/Malaria_Detection)
**Final Product Hosted On Heroku:** [https://malaria-detectorv1.herokuapp.com/](https://malaria-detectorv1.herokuapp.com/)

I created a tool that classifies images of blood cells to detect Malaria. The best way to depict Penumonia is by performing a microscopic examination of blood cells. The problem is in the interpretation of these microscopic images.They are not always experts available to interpret them. Therefore, such a tool could be use to predict fast and automatically whether or not someone has Malaria. 

*   Project done using Pytorch Library.
*   I created a tool that classifies images of blood cells to detect Malaria.
*   Performed Data preprocessing and Augmentation.
*   Used transfer learning (pretrained resnet34). 
*   Fine-tuned the model.
*   Built a client facing API using Flask.
*   Deployed the model on Heroku.

[![](/image/malaria_detector.png)](https://malaria-detectorv1.herokuapp.com/)

[Link to my github profile](https://github.com/gaetanlop)
