# SIM2025Q2-Techbuilders
Group Project of CSIT314 Techbuilders
This is a GitHub monorepo containing the code for our CSIT314 Group Project.


# Project Contributors:
Poon Jason


Aung Sithu Phyoe

Goh Jeng Yee

Macgyver Smith

Chau Kang Jing

Kho Li Ming

# Project Resource


# Project Planning



📌[Taiga Backlogs/Sprint board and Progress Timeline](https://tree.taiga.io/project/pj0327-sim2025q2-techbuilders/timeline)

📝Documentation(Our final Document)

[Google Documents](https://docs.google.com/document/d/1g8Iu8pVzcl_8_sMqifEEP0aguCscYYEf_VA_5GLP7UA/edit?tab=t.0)



💻 Source Code

[Github Repository](https://github.com/jajhg/CSIT314---Techbuilders-T05-.git)


Unsure what to do before/after downloading? no worries we are guiding you below:

# Pre-requisites:

Please be ensure that your device contains below softwares to run this program 
1. Python(Suggested version above 3.0)
2. [XAMPP controller](https://www.apachefriends.org/download.html)(This is for handling the SQL database inside local phpmyadmin)
3. A Coding Software provider which supports Flask and Xampp operation( Visual Studio Code is the most reccomended)


# Procedures:

1. Download the code to your device(local- Download zip) and unzip it on your local coding software
2. Run below commands 
<br>pip install flask
<br>pip install mysql.connector
<br>pip install flask_sqlalchemy
<br>pip install openpyxl
<br>pip install pandas

3. To connect to phpmyadmin please ensure you have started the Apcahe and MySQL inside the XAMPP controller and Access to http://localhost/phpmyadmin/ in any browsers. 

4. Click (new) the menu , create a database named "c2c_freelance_home_cleaners_db" ,keep utf8mb4_general_ci	and create the table 

5. Import the file "c2c_freelance_home_cleaners_db.sql" into this database folder


6. Run python app.py , a fixed port will be generated, access to the port and the program will start.

# Reminders while running this program:
1. Please be ensure that the Apcahe and MySQl the XAMPP controller has to be constantly starting/running while running the program, please restart the program when your Apcahe and MySQl was turned off unauthorised inside the XAMPP controller.