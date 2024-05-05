
# Instagram User Analysis using SQL & Python

This project involves a comprehensive analysis of Instagram user engagement data. By delving deep into user interactions, content consumption patterns, and audience demographics, the aim is to extract actionable insights. These insights will serve as valuable guidance for various teams including marketing, product development, and user experience.


## 🛠 Tech Stack
Python, Jupyter Notebook, Mysql


## Dataset

https://docs.google.com/document/d/1MhN6A-9a36BHkL6UBVaTGYKdNwdXP-Sa/edit
## Installation & Libraries

```bash
!pip install mysql-connector-python

```
## Libraries
```bash
import mysql.connector          # Importing the MySQL Connector library for connecting to MySQL databases
import pandas as pd             # Importing the pandas library for data manipulation and analysis
import matplotlib.pyplot as plt # Importing the matplotlib library for data visualization
import warnings                 # Importing the warnings module to suppress warnings during code execution
from sqlalchemy import create_engine
%load_ext sql

# Suppressing warnings to avoid cluttering the output
warnings.filterwarnings('ignore')
```

    
## Key Insights Analyzed

A) Marketing Analysis:

1) To identify the five oldest users on Instagram from the provided database.

2) To find the users who have never posted photos on Instagram and encourage them to post.

3) To identify the winner of the contest by determining a user with more likes on a single photo.

4) To Identify and suggest the top 5 most used hashtags on Instagram.

5) To find out on what day of the week most users register on.

B) Investor Analysis:

1) To provide how many times does the average user post on Instagram, also to provide the total number of photos with the total number of users.

2) Determine the users (Potential bots) who have liked every single photo on the site, as this is not typically possible for a normal user.
## Screenshots

![App Screenshot](https://github.com/raghul3/Instagram-User-Analysis-/assets/81759525/e96007ce-423e-4582-8747-6ebaa658f186)

