# Hawaii-Weather-SQLAlchemy-API
Here, we use SQLAlchemy to fetch Hawaii weather data from a SQLite db, and create a back end Flask app that creates an API to express weather stats such as temp and precip. 

## Path to Code:

 - JoeyForgetabbait/Hawaii-Weather-SQLAlchemy-API/Surfsup/climatefinal.ipynb
 - JoeyForgetabbait/Hawaii-Weather-SQLAlchemy-API/Surfsup/app.py

## Exploratory Analysis...

Begin by importing the dependencies required to relect data from a SQLite db into SQLAlchemy. Once this is completed, queries using traditional SQL syntax are written to collect various weather datas such as average precipitation, to be turned into a pandas data frame. Visualizing the preciptiation of an area in a place like Hawaii can give an indication as to what, where and when the best times to vacation are. 

<img width="706" alt="Screenshot 2024-08-05 at 3 29 31 PM" src="https://github.com/user-attachments/assets/2ab804cc-809b-4231-b057-78bb20c72a3b">

## Designing the App...

Design an app that would be useful to a travel user to execute enjoyable travel planning by dodging bad weather. To do this, they need to have information about the weather, so a Flask app is created with relevant db enpoints (i.e. pertinent weather data) to be visable by the users input. 

<img width="750" alt="Screenshot 2024-08-07 at 6 50 47 PM" src="https://github.com/user-attachments/assets/a2c8a1fb-3ff1-4629-b04f-faf2c225c1b1">

<img width="813" alt="Screenshot 2024-08-07 at 6 50 58 PM" src="https://github.com/user-attachments/assets/bdeecf34-2916-443b-84a8-27af2d5afbce">
