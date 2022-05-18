Steps to follow:

1: Install Xampp -> start xampp server -> 

	Part A: start Apache and MySQL server

	Part B: if mysql workbench is already installed then in xampp control panel 
	click on config of MySQL and edit port from 3306 to 3307 at two places and
	uncomment password by removing # ,just above port and 
	enter MySQL workbench password then open 
	xampp folder -> phpMyAdmin -> config.inc file -> here on line 21 
	enter MySQL workbench password and save file and run MySQL server from Xampp.

2: Move this folder to xampp -> htdocs

3: open connection.php from connection folder and if by using part A,
xampp started then just comment the line in which password is filled 
and uncomment the blank password line.
if followed part B, then vise versa fill the MySQL workbench.

4: Now, open chrome and enter localhost/chillin/ and press enter site will start.