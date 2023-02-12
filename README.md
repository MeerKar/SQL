# SQL

# Background

 In this particular task is to do a research project about people whom the company Pewlett Hackard (a fictional comapny) employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, have designed the tables to hold the data from the CSV files, import the CSV files into a SQL database, 
and then answer questions about the data through data modeling, data engineering, and data analysis, respectively.

To begin with have created a  local Git repository, with a folder name "EmployeeSQL".


This task is divided into three parts: data modeling, data engineering, and data analysis.

# 1. DATA MODELLING

For this  the CSV files given are inspected, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, i have used tool 
"QuickDBD".By using this technique six employee database entities or tables are identified, these entities are employees, departments, salaries, titles, department managers, and department employees. The attribute or the data type of the entities also presented. At last, the ER diagram was drawn to visualize the relationships between entities/objects (primary key or foreign keys in a database). To read the detailed description of the employee database click the following link and download the PDF file."https://app.quickdatabasediagrams.com/#/d/fo6Uey"   "QuickDBD-Free Diagram.pdf"

The ER diagram looks like the following.

<img width="982" alt="image" src="https://user-images.githubusercontent.com/116701851/218334711-1d251cea-d9e3-474c-80fe-4884b47dc5b8.png">

# 2. DATA ENGINEERING

Using the provided information created a table schema for each of the six CSV files sith specified data types, primary keys, foreign keys, and other constraints.Note to import each CSV file into the corresponding SQL table the order strictly should be followed to avoid errors.

Click the following link to see the actual schema file  https://github.com/MeerKar/SQL/blob/main/CREATE%20TABLE%20%22departments%22%20(.sql


