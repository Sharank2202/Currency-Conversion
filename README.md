Web Development

1)Clone or download the zip file into your htdocs folder in xampp with a suitable name.

2)Create a database with the name "registration".

3)Create a table with the name "users" and it should contain 4 columns (id,username,email,password).

                                      (or)
                                      
  Run the code below in your sql shell for creation of table:
  
                  CREATE TABLE `users` (
                  `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
                  `username` varchar(100) NOT NULL,
                  `email` varchar(100) NOT NULL,
                  `password` varchar(100) NOT NULL
                ) ENGINE=InnoDB DEFAULT CHARSET=latin1;
   The structure of the table looks as follows :
   
   <img src="images/Capture.PNG">
   
   The login page :
   
   <img src="images/1.png">
   
   If the user is new,by clicking on the Sign up button,the page will be redirected to registration page wherein the user can fill their details :
   
   <img src="images/3.png">
   
   After filling the appropriate details,the details of the user are stored into the database and the after the newly registered user is logged in,he/she is redirected to the following page wherein the user can do the conversion from USD to INR or vice-versa:
   
   <img src="images/6.png">
   
   If the already existing user tries to register with the same name ,the following prompt shows up :
   
   <img src="images/7.png">
   
   If the username/password entered are incorrect,the following prompt shows up :
   
   <img src="images/8.png">
   
   If the user doesn't enter his username during login,the following prompt shows up:
   
   <img src="images/11.png">

   If the user doesn't enter his password during login,the following prompt shows up:
   
   <img src="images/9.png">
   
