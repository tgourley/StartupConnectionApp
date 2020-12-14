# Development Documentation

## Needed Software:

 - [.Net (Version 5.0) ](https://dotnet.microsoft.com/download/dotnet/current/runtime)
 	- Required for the backend API
 - [PostgreSQL (Version 13)](https://www.postgresql.org/download/)
 	- Required for database Control
 - [Node.js (Version 14.15)](https://nodejs.org/en/)
 	- Used to manage packages within the frontend
 - Vue-Cli install through =>   `npm install -g @vue/cli`
	 - Once Node.js is installed you can install this through the command line
	 - Runs the frontend through the Vue framework
 - [Visual Studio Code](https://code.visualstudio.com/) (Recommended)
 	- Requires the [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet) from extensions
	- Recommended so developers may have both frontend and backend open in the same editor.
	

## Important Files/Dir

 ### Choose-up-api
 
 - The 'Controllers' folder will hold any controller which will modify the database directly.
 - The 'Models' folder holds enums, context, and the models of the database. The models and contexts allow
 for a connection to the database.
 
 - The 'appsettings.json' file contains the link connection to allow a developer to login to their Postgres server.
 - 'Program.cs' and  'Startup.cs' initialize the api and set services.
 
 ### Choose-up-ui
 
 - The 'src' folder is where everything involving the application will be stored
 - Inside 'src' there is a 'view' folder which stores all of our .vue components which display html
 - 'Store' holds the functionality to modify states and an indirect connection to the api
 - 'Services' holds all api based functionality that could be replaced if need be.
 - 'Components' hold .vue files that will show up multiple times through different views
 
## Running Developer Environment

### Frontend
To run the frontend, in the command line mentioned above, run the commands in the Choose-Up-UI main folder:
1. `npm install`
	1. Assures necessary files are installed in the project
2. `npm run serve`
	1. Runs the frontend and displays localhost link
3. open localhost link in command line:
	1. Opens the webpage in localhost in your deafult browser

To stop the system, execute CTRL+C or CMD+C in the terminal which terminates the server

### Database

1. To run the PostgresSQL server start up the ‘pgAdmin’ application ( If first time startup perform step two as well )
2. Set a username and password for the local user

### Backend

To run the backend API, perform the following commands:

 1. In ‘appsettings.json', find ‘localhost’ under ‘ConnectionStrings' then change the ‘User Id' and ‘Password’ fields to be the database id and password. Example ‘ConnectionStrings’:
```
"ConnectionStrings": {
    "localhost":"Server=127.0.0.1;Port=5432;Database=ChooseUp;User Id=postgres;Password=admin"
  }
```
2. In the main Choose-Up-API folder, perform the command: ( If using VS)

	1. { PROJECT_PATH } is the folder path of the whole project
```
dotnet run --project "{PROJECT_PATH}\Choose-up-api.csproj"
```
3. The terminal will then state the API is running and where.

## Running Tests

1. To see the tests running perform: npm run test:unit in the main choose-up-ui folder
2. The console will then output a suite of tests that will look like this:

![Test Suite](../Auxiliary%20Files/DevDocPictures/testSuite.png)

3. The top line describes the overall section the tests will cover.
4. Each indented line under will then tell you the exact type of test being run
	1. This will be read as “SearchComponent getters for states for getting search containing 'John’ ”. Each indented line will start with the top line when 	reading what the test is checking
5. At the bottom it will give you information about all the tests, test suites, and the time it took to run. This looks like

![Test Results](../Auxiliary%20Files/DevDocPictures/testResults.png)
