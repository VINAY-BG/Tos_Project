# Tos_Project
Here is the description of the files and their functionality! config.php - Configure database login.php - Allows user to login register.php - Allows user to login welcome.php - If user was able to login redirect him to welcome page logout.php - Allows user to logout

In register.php, the code is written such that the input is as Username(Email), Password, Confirm Password, Phone Number. And there is 
a Sign-in button, by pressing it it accepts and store the Username(email), Password, Phone Number in mysql server in php_my_admin.

In the mysql, the table is created where the column name are id(primary key)=INT , username=VARCHAR(50), password=VARCHAR(256), phone number=INT
and created at=DATETIME. Whenever we input the data in register.php it automatically gets stored in the table in mysql.

In login.php, the code is written such that the input taken is Firstname, lastname, Password and the role(editor/writer) and there is a submit button to 

In welcome.php, the code is written such that the page displays the post and comment section. In the post section the users can write about the post title,
post content and then the user can create the post. In the comment section the users can post their comments and alo read them below.

In config.php, the code is written such that it configure the database.

In logout.php, the code is written such that it allows the user to logout.
