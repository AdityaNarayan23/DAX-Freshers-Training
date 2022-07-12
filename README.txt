Initial Setup
-------------

1. Create a directory on your Desktop - DAX-DS-Assignment-2022-Aditya_Narayan
This directory will be used to push into GIT repo

2. Create sub-folders inside this directory
	1. SQL - files with answer to SQL questions will be posted here
	2. Data_Analytics - files with answer to Analytics questions will be posted here
	3. Machine_Learning - files with answer to ML questions will be posted here


<NOT NEEDED> SQLite Setup:
------------
1. Use the sqlite-tools-win32-x86-3390000.zip and unzip onto Desktop
2. Set the path of unzipped file into Environment variables -> System Variables -> Edit Path -> Add New -> Paste the path of sqlite unzipped file.
3. Open cmd and type sqlite3 -> Your SQLite server is ready
4. Change directory into Assignment folder -> cd C:\Users\aditya\OneDrive\Desktop\DAX-DS-Assignment-2022-Aditya_Narayan\SQL
5. Create a database -> sqlite3 mydb.db
6. Show databases -> .databases
7. Create Student Table -> create table STUDENTS (id INT PRIMARY KEY);
8. Show tables -> .tables
9. Show Schema for a table -> .schema STUDENTS 
10. Quit SQLite3 -> .quit
11. reopen database -> .open mydb.db
12. Insert into table -> INSERT INTO STUDENTS (id) VALUES (1);
13. Select from table -> SELECT * FROM STUDENTS;

SQLiteStudio on Windows:
-----------------------
1. Use the sqlitestudio-3.3.3.zip from the package and unzip onto Desktop
2. Open the unzip file and double click on SQLiteStudio.exe to open the SQLiteStudio IDE. 
3. Click on Add a database and browse file to chinook.db provided in the package.
4. Connect to the database "chinook.db" and you will find list of tables present. 
5. Answer the Queries from Assignment and save it in the DAX-DS-Assignment-2022-Aditya_Narayan/SQL
6. git push

Jupyter Notebook on Windows:
---------------------------
1. Pre-requisites - python installed on the machine. Check by cmd: python -V
2. Check jupyter_notebook\venv folder present in the package
3. Open cmd prompt
3. Activate virtual environment -> 'path-to-package'\jupyter_notebook\venv\Scripts\activate
4. It will prompt 'venv' in the terminal (it means virtual environment is activated)
5. type cmd -> jupyter notebook (it will open the jupyter notebook on the web browser)
6. On the right top, click on new and create a python 3 notebook and rename it as 'data_analytics_assignment' and save it in DAX-DS-Assignment-2022-Aditya_Narayan\Data_Analytics.
7. Once completed, save the python 3 notebook. 
8. Close the browser and go to cmd prompt and press Ctrl C to shutdown jupyter notebook 
9. Deactivate the virtual environment -> deactivate