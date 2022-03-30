# A Todo Web Application for productivity built with Python Flask**
![Todo App Custom Canva Banner](https://user-images.githubusercontent.com/49600021/160913625-73100fd3-7ca6-4d55-9742-d3f8f140206f.png)

## Table of Contents

- [Demo](#Demo)
- [Technologies](#Technologies)
- [What's unique in this Project](#whats-unique-in-this-project)
- [Screenshots](#screenshots)
- [Developer Instructions](#developer-instructions)
  1. [Initial Setup Instructions](#initial-setup-instructions)
  2. [Running Server](#running-server)

---

## Demo
![Todo App Custom  Project Demo](https://user-images.githubusercontent.com/49600021/160914467-15183409-a2a1-4f40-be62-163e27eb917d.gif)

---

## Technologies
## Technologies

![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
&nbsp;
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
&nbsp;
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
&nbsp;
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
&nbsp;

---

## What's unique in this Project

- The to-do web app is a dynamic and responsive web application that manages the tasks for the users
- Users can add their to-do tasks using the textbox
- Then, users can mark each task as completed using a button provided for each task or can also remove the tasks using the X button
- This application uses flask web framework to manage the CRUD (Create, Read, Update and Delete) operations
- The data is handled using SQLite connected seamlessly with the flask REST API.

---

## Screenshots

![Todo Web App Screenshot 1](https://user-images.githubusercontent.com/49600021/160915002-96a5418d-433d-4e2b-b956-81586e5dbadc.png)


![Todo Web App Screenshot 2](https://user-images.githubusercontent.com/49600021/160915030-54ed85cd-3e8e-45bd-aa4d-a806edf3e491.png)


![Todo Web App Screenshot 3](https://user-images.githubusercontent.com/49600021/160915425-743a8d21-e8b8-421e-9200-099fc225270e.png)


![Todo Web App Screenshot 4](https://user-images.githubusercontent.com/49600021/160915460-3c90604a-6969-4ede-8bb6-6b39beff16b3.png)

---

## Developer Instructions

## Initial Setup Instructions

### Setup Python Virtual Environment
```buildoutcfg
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```
## Running Server
### Cheatsheet
```buildoutcfg
sqlite3 todo.db <---- creates db and runs sqlite3 terminal
.tables <---- saves db in sqlite3 terminal
.exit <------ closes sqlite3 terminal
python / python3 <---- run python terminal
from app  import  db <----- import db from our flask app inside python terminal
db.create_all() <---- creates tables
exit() <----- exit from terminal
python app.py <---- run our app
```
### Go and check `http://127.0.0.1:5000`

---

[**🔼 Back to Top**](#todo-web-app)
1. [Running Server](#running-server)

