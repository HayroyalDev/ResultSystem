N.B: Google chrome is the recomended browser, XAMPP with Cpanel version 3.2.1 is the recomended server and Notepad++ is the recomended editor :)
=============================================================================================================
1. Install XAMPP Server/WAMP Server/PHP and MySQL
=============================================================================================================
2. Run the server you installed, (Xampp in this case), run xampp, start apache, mysql, filezilla
=============================================================================================================
3. To confirm your server is successfully installed and running, open any browser and type localhost, you should see "Welcome to XAMPP server" and there, you can check the version of php, mysql, apache installed in the side menu you have in your view.
=============================================================================================================
4. Copy the project folder name "AUResult" in your drive in this path (C:/Xampp/htdocs) The path actually depends on where you have installed your server, if you installed in C or any other drive. You may as well check C:/program files/Xampp. It actually depends
=============================================================================================================
5.Once Copied, you access the project via localhost/AUResult (since "AUResult" is the name of the project folder). The project should have errors since you dont have a database yet
=============================================================================================================

To Create the database, the sql is already in the project folder (AUResult/TRSystem.sql) We are going to import this to create the database.

1. Open your browser and type in localhost/phpmyadmin (This will only run if your "localhost" had ran earlier!) otherwise go to step 1 above
=============================================================================================================
2. If phpmyadmin opened; In the menu at the top, locate the "import" link, click import. We are going to import that sql file you located earlier. click "choose file" and navigate to your AUResult folder again to find the TRSystem.sql file, choose it. Leave other fields as they are and click "Go" link at the bottom. Wait for the file to import, once imported, your database has been created.
=============================================================================================================
3. Once imported, open a new tab for your browser again and type "localhost/AUResult" in your address bar. You should see the landing page of the AUResult web application with the login and register links.
=============================================================================================================



For Admin to register use localhost/AUResult/admin/signup

For Admin to login use localhost/AUResult/admin/signin

For student to register use localhost/AUResult/signin

Note that Admin will have to create the students so there is no link for student signup.




The app is so easy to use for easy defense all the best