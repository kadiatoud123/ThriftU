# ThriftU


# Project Overview
Deployment URL: https://thriftu-jgg9.onrender.com/

GitHub Repo (linked to my univeristy email (kdiallo6)): https://github.com/ljbrown4/ThriftU

ThriftU is a university-focused marketplace platform that enables students to list items, message buyers and sellers, manage pickups, and browse a clean, intuitive feed. The system is built following strong software engineering practices, including modular design, layered architecture, and comprehensive testing. Team Contributions Our team worked collaboratively throughout the project using Agile Scrum methodology:

Scrum Master and Developer: Leigh

Product Owner and Developer: Kadiatou

Developers: Yawavi and Zoie

# Installation / Deployment

MacOS:

python3 -m venv venv

source venv/bin/activate

python3 pip install -r requirements.txt

export FLASK_APP=app.py

flask run


Windows:

python3 -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

set FLASK_APP=app.py

flask run

# Testing
** Please run the application first and then run tests. As tests clear the MongoDB database to ensure accuracy **

python3 -m pytest --cov=. --cov-report=term-missing
