# SQL

# Background

 In this particular task is to do a research project about people whom the company Pewlett Hackard (a fictional comapny) employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, have designed the tables to hold the data from the CSV files, import the CSV files into a SQL database, 
and then answer questions about the data through data modeling, data engineering, and data analysis, respectively.

To begin with have created a  local Git repository, with a folder name "EmployeeSQL".


This task is divided into three parts: data modeling, data engineering, and data analysis.

# 1. DATA MODELLING

For this  the CSV files given are inspected, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, i have used tool 
"QuickDBD".By using this technique six employee database entities or tables are identified, these entities are employees, departments, salaries, titles, department managers, and department employees. The attribute or the data type of the entities also presented. At last, the ER diagram was drawn to visualize the relationships between entities/objects (primary key or foreign keys in a database). To read the detailed description of the employee database click the following link and download the PDF file."https://app.quickdatabasediagrams.com/#/d/fo6Uey"   

The ER diagram looks like the following.

<img width="982" alt="image" src="https://user-images.githubusercontent.com/116701851/218334711-1d251cea-d9e3-474c-80fe-4884b47dc5b8.png">

# 2. DATA ENGINEERING

Using the provided information created a table schema for each of the six CSV files sith specified data types, primary keys, foreign keys, and other constraints.Note to import each CSV file into the corresponding SQL table the order strictly should be followed to avoid errors.

Click the following link to see the actual schema file  https://github.com/MeerKar/SQL/blob/main/CREATE%20TABLE%20%22departments%22%20(.sql


### 3.DATA ANALYSIS

After importing the CSV files given, a query anlysis is done with the following : The full query is done with this https://github.com/MeerKar/SQL/blob/main/--DATA%20ANALYSIS.sql


1. List the employee number, last name, first name, sex, and salary of each employee.


<img width="388" alt="image" src="https://user-images.githubusercontent.com/116701851/218335771-b8b7409a-f34e-4f3b-aa8e-a555b065eaba.png">


2.  List the first name, last name, and hire date for the employees who were hired in 1986.

 <img width="500" alt="image" src="https://user-images.githubusercontent.com/116701851/218335833-5b367e3f-ed43-4b45-82c0-0ee68a878977.png"> 
 

3.  List the manager of each department along with their department number, department name, employee number, last name, and first name.

<img width="428" alt="image" src="https://user-images.githubusercontent.com/116701851/218335892-bef80e06-e771-4200-9609-6c39044caa40.png">


4.  List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

<img width="432" alt="image" src="https://user-images.githubusercontent.com/116701851/218335937-295a19b4-0909-4988-a2f6-b699ff8db46e.png">


5.  List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

<img width="278" alt="image" src="https://user-images.githubusercontent.com/116701851/218335986-87f76f11-a48c-47a5-859d-dd1068ec8538.png">


6. List each employee in the Sales department, including their employee number, last name, and first name.

<img width="398" alt="image" src="https://user-images.githubusercontent.com/116701851/218336011-08a26fa4-53ff-464f-9819-337f9e9a9704.png">


7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

<img width="425" alt="image" src="https://user-images.githubusercontent.com/116701851/218336066-f8f4a717-dc9f-4fa9-95ee-93acfb35d041.png">

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

<img width="301" alt="image" src="https://user-images.githubusercontent.com/116701851/218336086-b04b2beb-2ca3-410b-b864-6c7cb10db3c2.png">











