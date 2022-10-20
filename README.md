# Chatbot


## Getting Started
---

## Project Structure
---
The project files and folders are organized as follows:
```
Final Project                   (project root folder)
+-- inserting-data              (the main folder that holds the CSV data files, the Python script to add those to the database, and the database)    
  +-- game.csv                  (holds the games we chose with a description, rating, publisher, developer, genre, and special category all listed)
  +-- genre.csv                 (holds the description and the genre of the games)
  +-- load_data_to_steam_db.py  (the Python script that adds all of the information from the CSV files to the database)
  +-- review.csv                (holds game name, user name, if the review is verfied, review description, and if the user recommends the game)
  +-- special_category.csv      (holds the special category and a description)
  +-- steamschema.mwb           (the database, which once the script is ran, holds all the data in tables created in the ERD in the MySQL file)
  +-- user.csv                  (holds name, email, password, and display name)
  +-- user_has_game.csv         (holds user name and game name)
README.md                       (general information about project)
```

## Required Technologies
---

## Author
---
*  Mason Schenk:    sch19013@byui.edu

## References
* [sqlalchemy.exc.ArgumentError when creating chatbot](https://stackoverflow.com/questions/67811041/sqlalchemy-exc-argumenterror-when-creating-chatbot)


want to run
```{python}
pip install sugaroid-chatterbot
python3 -m spacy download en_core_web_sm
pip install Mako==1.1.2
pip install SQLAlchemy==1.3.6
```
