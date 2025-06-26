A machine learning web application that predicts the risk of forest fires based on environmental conditions such as temperature, humidity, wind speed, and other forest fire indices. Built with Flask, scikit-learn, and deployed on Render.
Features-:
a)Predict forest fire risk based on 9 input features
b)Trained ML model using Linear Regression
c)Flask-based web interface
d)Styled frontend with HTML + CSS
e)Deployment on Render

Input Features:-
This app takes the following 9 input parameters:
1)Temperature (°C)
2)Relative Humidity (%)
3)Wind Speed (km/h)
4)Rain (mm)
5)FFMC (Fine Fuel Moisture Code)
6)DMC (Duff Moisture Code)
7)DC (Drought Code)
8)ISI (Initial Spread Index)
9)BUI (Build-Up Index)

Model: Linear Regression  #
Preprocessing: StandardScaler #
Libraries Used: sklearn, numpy, pandas, flask, gunicorn

Future Improvements:-
1)Add login/user authentication
2)Display fire risk in visual levels (Low/Medium/High)
3)Map-based display of forest areas
