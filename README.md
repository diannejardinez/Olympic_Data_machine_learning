# Machine Learning Project: Olympics 1896 - 2020

**Team** : Aastha Arora, Dianne Jardinez, Duong Luu, Ritika Bhansali, and Swarna Latha 


[Presentation](https://docs.google.com/presentation/d/1mj6rhwKhcgTzlXBbm85ND_es7FiVOcvyNoUK_zkgKRw/edit) (Google slides)


**Data Source** : [Kaggle Olympics Dataset](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

**Machine Learning Models** : 
- Linear Regression
- ARIMA
- Logistic Regression

**Project scope** :
- Predicting Gold, Silver, Bronze and Total Medals for USA for Tokyo 2020 Olympics
- Predicting Olympic Medalists in all Olympic Sports in 2020


## GitHub Page for static information

[Olympics Project Website](https://diannejardinez.github.io/Olympic_Data_machine_learning/Flask%20API/templates/index.html)

---


#### Flask API for rendering database

- Prerequisites: 
	- pgAdmin and Postgres installed

- Git clone this Repo 
- Log into pdAdmin and create a database 
- Go into Flask API
- Use `PostgreSQL_schema.sql` inside the directory titled database for creating the schema for the newly created database 
- Use `olympics_data.csv` inside the directory titled database to import in the pdAdmin 4 database
- Update `config_database.py` with own pgAdmin 4 password and database name
- Run in Terminal `$ python app.py`
- Copy Server Flask app pathway provided by the Terminal into a Web browser 