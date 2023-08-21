# UsersService
Console application for managing users in a database
The application scope is to apply CRUD operations for User class.
Before running the application there are some steps to be done. 
I am using an external jdbc library to create the connection for an SQLite database.
At the link bellow you can find the external library:
https://jar-download.com/artifacts/org.xerial/sqlite-jdbc?fbclid=IwAR3-t4bM1UZPzr3am7cFHtU4Je2QrHnCx1BrvUpbXbf7CXzgZ-cb7AGjXyg
I am using Intellij IDEA as a development environment, so i will explain to you the steps that have to be done in this ide:
- go to File tab from menu;
- go to Project Structure;
- from the inner menu, select Libraries;
- select that little + sign, browse for the jar file you downloaded from the link above.
In the main folder can be found two packages:
1.The main folder which will be described bellow;
2.The test folder.
The main folder is structured in three sub-folders and Main Class:
1. Dto - where can be found the class User 
2. Service - where can be found the services for creating the Db connection and the table used in application
3. ConsoleUi where can be found the main logic used in the application.
4. Main Class from where the application can be started.
The test folder contains some specific tests using a temporary test db.

The project uses the main knowledge acquired from the Java course at ItFactory.

