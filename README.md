# C-login-with-HWID-API
Project .NET C# with api for login and it's check if HWID match with a API


Thanks for using my API login with HWID :p

Step 1
Place the folder API on your website with filezilla.

Step 2
Edit the file connection.php for connect it with your database.

Step 3 
In the folder Database Table Users, import the id11198133_bb57 (1).sql on your database

All API is done.




Step 4

Create a new account on your database use this api:

http://nameofyourwebsite.com/API/execute.php?action=registerUser&userName=USERNAME&password=PASSWORD&repassword=PASSWORD&registerKey=N0QxoXM

Change USERNAME and PASSWORD only and press enter it's will say OK::DONE
Now come back on your database and you can see your account in apipremium

Step 5

In the folder Application Login, use Visual Studio for edit / build the project but first you need add api
in the form "Login.cs" change https://yourwebsite.com/API/ to your link for it's work !

When it's done, build the project and try login with account you have make.

In database controls users:
For give access to user, change IsPremium to "PREMIUM"
for ban user, change IsPremium to "BANNED"
for remove access to a user, change IsPremium to "FREE"
for reset HWID user, change whitelist to "RESET"


Now all is done, you can edit it if you want !

Made By Misaki Dev

