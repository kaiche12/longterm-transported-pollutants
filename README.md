# longterm-transported-pollutants

The name of paper is **Using Satellite Data on Remote Transportation of Air Pollutants for PM<sub>2.5</sub> Prediction in Northern Taiwan**

In this repository we provide Code files in Python language for capturing longterm transported pollutant(PM<sub>2.5</sub>) and used them to 
improve local prediction of PM<sub>2.5</sub>

The project involve the prediction of PM<sub>2.5</sub> for next 4hour(hr), 8hr,12hr,.. to 72hr. These codes performed prediction 
for next 4hour. The same codes are used from predicting the remaining hours but same changes needed to the 
data shape of input features and output label data.

STRI_fe code with extract middle layer used to extract remote pollutants
STR_p code use the extracted remote pollutants with other features as input for local prediction of PM<sub>2.5</sub>.
RTP composite code used to provide final prediction of PM<sub>2.5</sub> by considering prediction results from STRI_p model with the base model

## INSTALL


- python 3.6
- keras
- numpy
- scipy
- matplotlib

