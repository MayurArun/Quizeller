# Quizeller
A quiz Management System

# About System
This Online Quiz Site is in PHP, CSS, JavaScript, and bootstrap. Talking about the features of the Online Quiz site, it just contains both the admin section and the user section. The user can log in to give the exam, while the admin can view all users, their rankings and manage questions. 

# How To Run The Project?
To run this project, you must have installed a virtual server i.e XAMPP on your PC (for Windows).<br />
 After Starting Apache and MySQL in XAMPP, follow the following steps.<br />

1st Step: Copy the main project folder<br />
2nd Step: Paste in xampp/htdocs/ <br />
3rd Step: Open a browser and go to URL “http://localhost/phpmyadmin/” <br />
4th Step: Then, click on the databases tab<br />
5th Step: Create a database naming “quiz” and then click on the import tab<br />
6th Step: Click on browse file and select “quiz.sql” file which is inside the “Quizeller” folder<br />
7th Step: Click on go.<br />
After Creating Database,<br />
8th Step: Open a browser and go to URL “http://localhost/ Quizeller /”<br />

Note: For admin login, username: quiz and password: quiz <br />

# How to Use

1. Use the Admin Panel to set up quiz. Quiz won't be enabled unless you click the "Enable" button. Click on the same to enable an added quiz.
2. Scores are updated realtime on the server, however the leaderboard will be updated only when the user finishes the quiz, or there is a time out or the admin ends the quiz by clicking on "Disable" button.
3. Once the admin clicks on the disable button, the quiz ends for all the users taking that quiz, irrespective of their active or inactive state (whether logged in or left the quiz in the middle only). The leaderboard will be updated either when a user "Finishes" his /her quiz and when the admin "disables" the quiz. 
4. Once the quiz is disabled, the quiz becomes inaccessible. If the quiz is enabled again later, only those user who have not already taken the quiz can take the quiz.
5. It is recommended that you Enable the quiz when all the users are ready and disable the quiz when all the users have completed the quiz or time limit of taking the quiz has exceeded
