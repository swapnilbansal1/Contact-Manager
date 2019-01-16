# Contact-Manager
Contact Management System
Built in PHP, the project also uses HTML, CSS, Bootstrap, JAVASCRIPT, MYSQL, JQUERY, and AJAX. 

How to run:
1. Have MySQL and XAMPP Server install on your pc.
2. Make sure to have the contacts database already extracted in the system. Use the SQL dump file to upload all data and tables into your system.
3. Copy the folder ContactManager onto HTdocs folder inside Xampp folder in C drive.
4. You need to change the connection in all the 3 files to your database server.
	Inside the PHP element in header in each file, change the following.
	$servername = "localhost";
    	$username = "YOUR USERNAME";
    	$password = "YOUR PASSWORD";
    	$dbname = "contacts";

    4.1 Create a database in the server as given in another file "contacts" all the tables
    4.2 Open Search.php file in the browser (localhost/DBProject1/search.php) and this will display a search page with the header to point to the view_all page or home.

5. GUI will be opened to use the functionalities such as search, edit, delete and insert.
