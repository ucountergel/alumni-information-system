# alumni-information-system
Alumni Information System of Balay sa Alumni in CTU-AC

Alumni's Home Page -- [ http://localhost/alumni-information-system ]
![Capture](https://user-images.githubusercontent.com/55085932/152482930-c5374d22-10c4-4494-aee8-f620eb3f38cc.PNG)

Admin's Login Page -- [ http://localhost/alumni-information-system/admin ]
![Capture1](https://user-images.githubusercontent.com/55085932/152483179-7859d49d-af89-4285-850c-7430f267fd4d.PNG)


Setting up to run the source codes:

1. Download the source code and extract the zip file or clone this repository link using Git Bash using the command, ( git clone https://github.com/ucountergel5/alumni-information-system.git ).

2. Download or install any local web server that runs PHP script such as Apache Xampp, which is used to test this system. Copy and paste the alumni-information-system folder to the location where your local web server have access to your local projects. Example in Xampp, go to your drive C, like this: ( C:\xampp\htdocs ).

3. Open your browser, access the web-server database by typing [ http://localhost/phpmyadmin ], create a new database, name it: alumni_db. Import the alumni_db.zip file located in the database folder of the alumni-information-system folder.

4. Turn on the internet connection, since Login or Create account page for Alumni user won't appear if not connected to the internet. Finally, open a new tab in your browser, and type in the url tab to the location of the project:
 [ http://localhost/alumni-information-system ] for the Alumni user; and
 [ http://localhost/alumni-information-system/admin ] to access the Admin user's dashboard.


Admin credentials to login:

username: admin || 
password: admin123

recommendations: can add forgot password feature to all the users (alumni and admin) if needed

#
Based on the project of [sourcecodester](https://www.sourcecodester.com/php/14524/alumni-management-system-using-phpmysql-source-code.html)
