![image](https://github.com/user-attachments/assets/5f1c732a-11c5-4149-b270-320814603b5f)

Aim
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

![image](https://github.com/user-attachments/assets/fa119ca5-f0d1-4294-b35b-5a1215ebfe2e)


How to use?
Clone the repository
Install the required packages in "requirements.txt" file.
Some packages are:

numpy
pandas
scikit-learn
Run the "application.py" file And you are good to go.
Description
What this project does?
This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10.

![image](https://github.com/user-attachments/assets/fa7e7245-eed1-4cd9-a99a-254f9856f1b6)

How this project does?
First of all the data was scraped from Quikr.com (https://quikr.com) Link for data: https://github.com/rajtilakls2510/car_price_predictor/blob/master/quikr_car.csv

The data was cleaned (it was super unclean :( ) and analysed.

Then a Linear Regression model was built on top of it which had 0.92 R2_score.

Link for notebook: https://github.com/rajtilakls2510/car_price_predictor/blob/master/Quikr%20Analysis.ipynb

This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.
