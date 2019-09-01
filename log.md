# 100 Days Of Code - Log

## My Goals:
* code everyday
* continue learning Python + Django: My wife and I like cooking, but we have descentralization of recipes. I'll try to develop a platform like https://cookpad.com/es in Django + Python + REST, making some improvements in the database to have the possibility to analyze the information.

## Project website https://github.com/Dynam1co/MacarronesConTomatico
* Noobs Cook Community

### Resources:

#### Python:
I have a few books and courses and would like to use them:
1. [Python Data Science Handbook: Essential Tools for Working with Data](https://www.amazon.com/Python-Data-Science-Handbook-Essential/dp/1491912057/ref=sr_1_1?crid=1RH3QBDHK6Y2D&keywords=python+data+science+handbook&qid=1566929081&s=gateway&sprefix=python+data%2Caps%2C215&sr=8-1) With this book I learned to work with NumPy library.
2. [Python & Django + REST Course](https://plataforma.keepcoding.io/p/curso-online-python-django-rest) This course was my first contact with Django and I loved it.

### Day 0: August 27, 2019
##### Preparing 100DaysOfCode repo

**Today's Progress**: Forked 100daysOfcode repository. Update my goals. Create repository for my project. Create project with PyCharm, install Django in a virtual envirnoment and push changes to project's GitHub repository.

**Thoughts:** What I see more complicated is the front-end part, in the back-end I usually manage to solve problems better or worse.

**Link(s) to work**
1. [Git repo 100DaysOfCode](https://github.com/Dynam1co/100-days-of-code)
2. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 1: August 28, 2019
##### Preparing the database's EER diagram 

**Today's Progress**: I have tried several EER diagram editors for Mac OS, I have finally made the diagram with MySqlWorkbench and I have attached it to the project. I connected my Django application with new database in PostgreSQL and I deleted default database in SQLlite.

**Thoughts:** I hope has a large volume of data, I discarded SqlLite databasa and I'm using PostgreSQL in localhost. I would have liked to make the models in python, but connecting to the new database in PostgreSQL has taken me more time than expected.

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 2: August 29, 2019
##### Creating models in Django project

**Today's Progress**: I have created database models in a new Django app inside the project. I have also propagated the models to the PostgreSql database

**Thoughts:** I need to add various recipes to the database because the next step will be create main page. I have had problems in my attempt to have the database in Third Normal Form (3NF) because Django not allows more than one filed as primary key, I have tryed to do using <strong>unique_together</strong> property but as the fields are foreing keys it gave me errors. I've finally decided to fix it coding when record will inserted.  

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 3: August 30, 2019
##### Creating nav bar responsive in Django project

**Today's Progress**: I have update database models to add some fields also I updated de [EER_Diagram.png](https://github.com/Dynam1co/MacarronesConTomatico/blob/master/EER_Diagram.png). I have also propagated the models to the PostgreSql database. Finally, I have created a responsive base navigation menu. To all this we must add that I have been without internet all afternoon and I am connected to the internet of the smartphone.

**Thoughts:** I had some problem creating the base template, when I entered the home (which was inside the app "recipes" I could not find the html base file where the footer is and the navigation menu). I created the base html file in the main app because it will be common to the apps that the project contains. Tomorrow I hope to finish the real navigation menu.  

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 4: August 31, 2019
##### Finished nav bar responsive in Django project. Bootstrap added. Created all pages of nav menu.

**Today's Progress**: I have changed nav menu colors with the final design, also I have imported bootstrap library and I finished responsive nav menu and its buttons already redirect to the corresponding pages.

**Thoughts:** I thought it would be difficult to show what menu page you are in, but thanks to Django it has been very easy Tomorrow I'll create some recipes to display in main page. If I have time, I will also add the fav icon

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 5: September 1, 2019
##### Change some models. Added Categories, recipe types. Added one recipe with steps and ingredients.

**Today's Progress**: I could not display the recipes on the main page because I had several problems with the database when inserting data from DataGrip directly. That has forced me to delete the database and recreate it.

**Thoughts:** I realized that in a table the fields had not been created. After much reviewing the problem, I realized that it was a code error, but the program compiled 🤔

Tomorrow I hope to create some recipes and display in main page. If I have time, I will also add the fav icon

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)
