# FIFA-22-Player-Management-Sysytem

**DESCRIPTION OF FSM:**

This project consists of player details which include the likes of player’s age and nationality. It also consists of player statistics which include players technical skills. It also consists of tables containing information such as player earnings, club, and preferred position to play. It also provides a strong search, update, delete, and insert operations delivered with a user-friendly web-based UI. The project also helps the users to keep track of the player details in a computerized way without any trouble. The project contains 7 stored procedures and 3 triggers per table. Stored procedures are used in search engine. Every time the user searches through the database, a procedure is called, and the results is collected and displayed for the user in a structured manner. It also has 3 triggers namely “Insert, Delete and Update” triggers assigned separately to each table. Whenever operations such as insert or delete or update is performed on any table, these triggers are automatically called, and the logs are captured into 3 separate tables, individually for each trigger. Hence use of triggers provides users to trace back all the latest as well as the oldest changes into any table at any point of time.

**INSTALLATION AND EXECUTION PROCEDURE**

Install wamp [Download wamp from here ](https://sourceforge.net/projects/wampserver/files/latest/download) and update Google Chrome [Update Latest chrome from here](https://www.google.com/chrome) 

After installing wamp (Default directory : c:/wamp64/) , download the project and paste it in directory : (c:/wamp64/www/).

Set your wamp username to root and no password.

Start wampServer64 from the desktop icon and open google chrome and type the following url without quotes: "http://localhost/phpmyadmin/" and enter root as username and press Go.

Now first you have to Load the database in your local server and then you can run the project.

**To load the database :**

 - Click on +New on the left hand column
 - Give database name as "fifa" (without quotes and small case) and set character encoding to "utf8mb4_unicode_ci"
 - After creating the database successfully, on the upper main menu panel, click on Import and then click "choose file" from file to import menu. Now browse to directory where you saved the project (expected directory: c://wamp/www/your_project_name/db/fifa.sql) and click on fifa.sql and then go down and click Go (Do not change any other settings).
 - After importing successfully, loading the database is complete.

  **Run the project :**
   - Open a new tab in chrome
   - type the following url:[http://localhost/your_project_name_inside_www_directory/index.html]
   - enjoy.

#### For further queries :Drop me mail at hamzashahnawaz3440@gmail.com 
