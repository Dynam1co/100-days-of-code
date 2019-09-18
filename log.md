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

### Day 6: September 2, 2019
##### Show recipes in main page. Fav icon added.

**Today's Progress**: I added fav icon to base html this way you only have to do it once. The recipes are already shown on the main page.

**Thoughts:** Tomorrow, I will show the recipes ordered from the last to the first, I'll also limit the number of recipes shown. I would also like to add some style to the recipes on the home page.

**Link(s) to work**
1. [Git repo My Project "MacarronesConTomatico"](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 7: September 3, 2019
##### Added delay in scraping. The scraped data are saved in a CSV.

**Today's Progress**: Today I will change project to continue learning Scrapy and Python I have to do it if I do not want to be overwhelmed to deliver next week's practice for BootCamp.

**Thoughts:** Tomorrow, I will have to download the final data, so far it was a small data set. The next step will be to create a cluster in Hadoop.

**Link(s) to work**
1. [Git repo My Project "Scrapy Python web El Tenedor vs dataset Airbnb"](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)

### Day 8: September 4, 2019
##### Solved another problem with virtualenv in Scrapy project. Waste of time creating docker with hadoop.

**Today's Progress**: Today I solved a problem with virtualenv in Scrapy project, also I created a guide to show how to use an existing virtualenv in PyCharm. I tried many times to create hadoop cluster docker, unsuccessfully.

**Thoughts:** Tomorrow I will continue trying to create the cluster

**Link(s) to work**
1. [Git repo My Project "Scrapy Python web El Tenedor vs dataset Airbnb"](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)
2. [Git repo Use existing virtualenv in PyCharm](https://github.com/Dynam1co/Add_existing_venv_python)

### Day 9: September 5, 2019
##### Ciao Docker, hello Hadoop in Google Cloud Platform.

**Today's Progress**: I give up with Docker, I've wasted too much time and I haven't come to learn docker. Today I created the Hadoop cluster in Google Cloud Platform with the free account. I've been learning the use of MapReduce and I have practiced with PyHIVE. I created a PyCharm project to connect to Hive in Google Cloud Platform using PyHive.

**Thoughts:** Tomorrow I have to think about the next steps for the Big Data Architecture exercise that I will submit on Sunday 15.

**Link(s) to work**
1. [Git repo to connect local PyCharm project to Hive in Google Cloud Platform](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)

### Day 10: September 6, 2019
##### Outline exercise performed. I begin to document the PyHIVE project.

**Today's Progress**: Today I have done the outline of the Big Data Architecture exercise to know at all times what I have to do. I have also started to document the project in which I use the PyHIVE library explaining its operation.

**Thoughts:** Tomorrow I will finish documenting the PyHIVE project and I will go to Google Draw the complete exercise scheme.

**Link(s) to work**
1. [Git repo to connect local PyCharm project to Hive in Google Cloud Platform](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)

### Day 11: September 7, 2019
##### Documentantion day.

**Today's Progress**: Today I have continued to document the project that will connect to the Hadoop cluster.

**Thoughts:** I have to keep thinking if the csv will be sent to Google Storage from the Pycharm project or from the PyHive project.

**Link(s) to work**
1. [Git repo to connect local PyCharm project to Hive in Google Cloud Platform](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)

### Day 12: September 8, 2019
##### I have taken a step back.

**Today's Progress**: Today I found a problem in the Scrapy project. The crawler does not work inside a loop.

**Thoughts:** Tomorrow I will have to fix the crawler problem if I want to arrive on time for the delivery of the exercise.

**Link(s) to work**
1. [Git Repo Scrapy el Tenedor](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)

### Day 13: September 9, 2019
##### Problem solved. I continue with the exercise.

**Today's Progress**: Today I solved a problem in the Scrapy project. The crawler runs correctly. I created a menu to allow to use scrapy or upload files to Google Storage and this part is also finished.

**Thoughts:** Tomorrow I will record a video to show how it works.

**Link(s) to work**
1. [Git Repo Scrapy el Tenedor](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)

### Day 14: September 10, 2019
##### Diagram created. Main repository created.

**Today's Progress**: Today I created the exercise diagram and main repository in Git Hub for present it.

**Thoughts:** Tomorrow I will made a change in scrapy project to generate Airbnb csv without irrelevant data.

**Link(s) to work**
1. [Git Repo Main project exercise](https://github.com/Dynam1co/kc_ej_bdarchitecture)

### Day 15: September 11, 2019
##### Finished documentation in main project.

**Today's Progress**: Today I finished the documentation of main repository that explains how to I made all parts of the exercise.

**Thoughts:** Tomorrow I will record a video to show how it works what I have done.

**Link(s) to work**
1. [Git Repo Main project exercise](https://github.com/Dynam1co/kc_ej_bdarchitecture)

### Day 16: September 12, 2019
##### Installed Django in PyHive project.

**Today's Progress**: Because of work and floods today I could only install Django.

**Thoughts:** This weekend I have to work hard to arrive on time for the deadline.

**Link(s) to work**
1. [Git Repo PyHive project](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)

### Day 17: September 13, 2019
##### I recorded video demonstration of Scrapy project.

**Today's Progress**: As I am using the free Google Cloud option for the Hadoop cluster, I have to remove it every time I finish using it so that I don't use credit. Tomorrow I will take the opportunity to finish the PyHive part and not have to recreate another cluster.

**Thoughts:** The most lazy part is going to be the demo video edition.

**Link(s) to work**
1. [Git Repo Scrapy project](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)

### Day 18: September 14, 2019
##### I discovered git revert command

**Today's Progress**: I realized that using Django was not necessary, but I already had it installed in the project, so I used the **git revert** command to undo some commits. I have finished the data visualization part and the communication with Hive.

**Thoughts:** I have already recorded the videos on how the exercise works. Tomorrow I will edit them and upload youtube to attach them to the main repository.

**Link(s) to work**
1. [Git Repo PyHive project](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)

### Day 19: September 15, 2019
##### Video editing and exercise documentation

**Today's Progress**: I edited video demonstration of the exercise and I completed the documentation.

**Thoughts:** Tomorrow I can return to work on my side project.

**Link(s) to work**
1. [Git Repo Main project](https://github.com/Dynam1co/kc_ej_bdarchitecture)
2. [Youtube Video](https://www.youtube.com/watch?v=3wt1vzeaNXQ)

### Day 20: September 16, 2019
##### Continue with my side project. Learning bootstrap.

**Today's Progress**: I changed main page, now I sort recipes by creation date and only shows last 25 recipes. I'm creating cards in bootstrap to show recipes in main page.

**Thoughts:** Tomorrow I will continue with bootstrap cards.

**Link(s) to work**
1. [Git Repo Macarrones con tomatico](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 21: September 17, 2019
##### Change css class in buttons in bootstrap. Learning algebra for Big Data.

**Today's Progress**: Modified css class of recipe card button in bootstrap. Learning algebra of propositions with python.

**Thoughts:** Tomorrow I will continue with bootstrap cards and login page.

**Link(s) to work**
1. [Git Repo Macarrones con tomatico](https://github.com/Dynam1co/MacarronesConTomatico)

### Day 22: September 18, 2019
##### Start with algebra for big data exercise. Exercise 1 Collatz Conjecture

**Today's Progress**: I finished the first part of algebra exercise for Big Data & Machine Learning BootCamp.

**Thoughts:** Tomorrow I will continue with the exercise to finish it as soon as possible

**Link(s) to work**
1. [Git Repo Algebra for Big Data exercise](https://github.com/Dynam1co/kc_ej_algebra_big_data)

