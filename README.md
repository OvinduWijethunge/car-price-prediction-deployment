# Price prediction of cars - Deployment
<p align=left>
<img src="https://img.shields.io/badge/Type-Regression-blue"/> 
<img src="https://img.shields.io/badge/Python-3.7-brightgreen"/>
<img src="https://img.shields.io/badge/DataSet-Kaggle-brightgreen"/> 
<p/>
<br>
<p align=center>
<img src="https://media.giphy.com/media/WnBbhOLj5v1LW6NK1R/giphy.gif" width="500px" height="300px">
</p>
<br>
<br>
• This project predicts current car price of the market in particular cars by considering below factors
<br>
      
      1. Year <br>
      2. Show room price <br>
      3. How much kilo meters already driven <br>
      4. how many owners previously had <br>
      5. Fuel type <br>
      6. current owner type ( individual or buyer ) <br>
      7. Transmission type <br>
 
• This repository consists of files required to deploy a ___WEB APPLICATION___ created with ___Flask___ on ___Heroku___ platform.

• Data set got from kaggle, if you want to inspect it just click this link _https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho_

• You can see deployed model in heroku , use below link for reach to deployed model:<br />
Heroku: _https://car-price-prediction-v-1.herokuapp.com/_

• If you want to check the algorithems ,models which used for implemented the model and see the accuracy matrix just Click the link mentioned below:<br />
Link: _https://github.com/OvinduWijethunge/Machine_Learning_Projects/tree/master/car-price-prediction_

<hr>


### If you are willing to check project in flask API


### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

### Project Structure
This project has four major parts :
1. random_forest_regression_model.pkl - This is our built model for predict values.
2. app.py - This contains Flask APIs that receives car details through GUI or API calls, computes the precited value based on our model and returns it.
3. static - This uses for store css files and some gifs for while presenting.
4. templates - This folder contains the HTML template to allow user to enter required detail and displays the predicted car price.


### Running the project in flask API
type python app.py for start your server 
then copy the given url and paste it in your browser
then input valid inputs and predict car price.

