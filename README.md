# Task-2--Robot-Arm-Interface-move-base-

This project is done using NetBeans platform, XAMPP, and PhpMyAdmin.

The idea of the project is to create an interface where the user can adjust the degrees values for the six motors which the robot arm will move according to, and move the base (forward, back, left, right and stop) then connect this interface to the database.

The interface contains two parts:
1- The left part contains six sliders, six textboxes for the motors, and two buttons: (Save) to send the values to the database table which called (motorsdegrees), and (play) to move the motors by changing the value 0 (off) in (playmotors) table to 1 (on).
2- The right part contains 5 buttons. 'Forward' button to move the base forward, 'Back' button to move the base back, 'Left' button to move the base left, 'Right' button to move the base right, and 'Stop' to stop the base. When a button is clicked, the suitable value will be inserted in the database.   

The project folder contains 7 files:
1- ControlUserInterface.html -> the program interface.
2- direction.php -> shows the last direction in the database.
3- .htaccess -> to process html file as php file. 
4- robotarm database -> the database where the values are stored.
5- image for robotdirection table. 
6- image for the web page as mobile web view. 
7- the project as ZIP folder.

The database details: 
1- motorsdegrees table contains 7 columns (id, motor1, motor2, motor3, motor4, motor5, motor6):(id) column is auto-increment and the six others columns contain the degrees values.
2- playmotors table conatin 2 columns (id, status): (id) column is auto-increment and (status) coulmn to store whether the motors are on or off.
3- robotdirection table contains 2 columns (id, direction): (id) column is auto-increment and (direction) column to store the base direction (r, l, f, b, s).
(r -> right, l-> left, f -< forward, b -> back, s -> stop).

-------------------------------------------------------Edited by Marya AL-Zoreky---------------------------------------------------------------
