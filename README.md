# alumni-information-system
Alumni Information System of Balay sa Alumni in CTU-AC

Setting up to run the source codes:

1. Download the source code in the G-drive and extract the zip file. Or clone the repository link of the system from GitHub using Git Bash using the command, ( git clone https://github.com/amnesiagel/alumni-information-system.git ).

2. Download or install any local web server that runs PHP script such as Apache Xampp, which is used to test this system. Copy and paste the alumni-information-system folder to the location where your local web server have access to your local projects. Example in Xampp, go to your drive C, like this: ( C:\xampp\htdocs ).

3. Open your browser, access the web-server database by typing [ http://localhost/phpmyadmin ], create a new database, name it: alumni_db. Import the alumni_db.zip file located in the database folder of the alumni-information-system folder.

4. Open a new tab in your browser, and type in the url tab to the location of the project:
 [ http://localhost/alumni-information-system ] for the Alumni user; and
 [ http://localhost/alumni-information-system/admin ] to access the Admin user's dashboard.


Admin credentials to login:

username: admin || 
password: admin123

recommendations: can add forgot password feature to all the users (alumni and admin)if needed
