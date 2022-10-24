# Chatbot
This is a very basic starting point to build a chatbot in Python. Within this project, you will use the Chatterbot library, with Chatterbot-Corpus used if you would like. My purpose of creating this project is to help others create their own chatbots and train them to do what they want, and to also help others get their feet wet in the world of machine learning.

Included in the Python file of this project titled 'chatbot.py', you will find three imports that you can use. You will definetly need to use the first, but you can choose whether to use List Trainer or Chatterbot Corpus. I will let you figure out which you would like to use

Look to the links in [References](#References) titled Chatterbot Documenation and Chatterbot-Corpus Libraries to learn how to train your bot.

Feel free to fork this repository and use it as a starting place for your very own chatbot. 

## Getting Started
---
You are going to want to go the first link in [References](#References) and download Python 3.9.13. You may not need to do this, but for my configuration, it worked. After downloading Python 3.9.13, you are going to want to run these commands in the terminal
```{python}
pip install sugaroid-chatterbot
pip install sugaroid-chatterbot-corpus
python3 -m spacy download en_core_web_sm
pip install Mako==1.1.2
pip install SQLAlchemy==1.3.6
```
After this, you should be able to make a chatbot up to the specifications that you want!

## Project Structure
---
The project files and folders are organized as follows:
```
chatbot                             (project folder)
+-- .gitignore                      (ignore file for any files that don't need to be pushed to GitHub)
+-- README.md                       (general information about project)
+-- chatbot.py                      (file where the chatbot will reside)
```

## Required Technologies
---
* An IDE like VSCode
* Python 3.9.13
* Chatterbot
* Chatterbot-Corpus

## References
---
* [Python 3.9.13](https://www.python.org/downloads/release/python-3913/)
* [Chatterbot Documenation](https://chatterbot.readthedocs.io/en/stable/index.html)
* [Chatterbot-Corpus Libraries](https://github.com/gunthercox/chatterbot-corpus)
* [How to Make a Chatbot in Python Step By Step [Python Chatterbox Guide]](https://www.upgrad.com/blog/how-to-make-chatbot-in-python/)
* [sugaroid-chatterBot](https://openbase.com/python/sugaroid-chatterBot)
* [sqlalchemy.exc.ArgumentError when creating chatbot](https://stackoverflow.com/questions/67811041/sqlalchemy-exc-argumenterror-when-creating-chatbot)
* [OSError: [E050] Can't find model 'en'](https://stackoverflow.com/questions/58057021/oserror-e050-cant-find-model-en)
* [Python Do While – Loop Example](https://www.freecodecamp.org/news/python-do-while-loop-example/)

## Author
---
*  Mason Schenk:    sch19013@byui.edu
