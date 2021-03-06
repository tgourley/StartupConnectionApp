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
 - [Docker](https://www.docker.com/)
 	- Needed for dev environment
	

 ## Cloning the Repository
 
 ### GitLab
 
 To get the projects code, issue the command git clone in the terminal of Visual Studio code with the following links when in a 'Choose Up' folder to store all repositories:
 
 Choose-up-api: https://gitlab.com/Cjbucker/choose-up-api.git  
 Choose-up-ui: https://gitlab.com/Cjbucker/choose-up-ui.git  
 Choose-up-docker: https://gitlab.com/Cjbucker/choose-up-docker.git  

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

### Choose-up-Docker
 - Docker-compose.yml is used for creating and running the images for the ui, api, and db
 
## Running Developer Environment

1. Within the docker folder run the command to get the database image for postgresql
```
docker-compose pull db
```
2. Run the command to build the images for the ui and api
```
docker-compose build
```
3. Run the command to put the images into containers. The '-d' keeps the terminal open for other uses.
```
docker-compose up -d
```

All three modules should now be running in Docker, this can be checked within the Docker application.  
Go to 'localhost:8081' to view the website.

If given a connection error, stop and start the api, through the docker app, to assure it is connected to the db.

## Running Tests

### Frontend
1. To see the tests running perform this command in the main choose-up-ui folder: 
```
npm run test:unit 
```
2. The console will then output a suite of tests that will look like this:

![Test Suite](../Auxiliary%20Files/DevDocPictures/testSuite.png)

3. The top line describes the overall section the tests will cover.
4. Each indented line under will then tell you the exact type of test being run
	1. This will be read as “SearchComponent getters for states for getting search containing 'John’ ”. Each indented line will start with the top line when 	reading what the test is checking
5. At the bottom it will give you information about all the tests, test suites, and the time it took to run. This looks like

![Test Results](../Auxiliary%20Files/DevDocPictures/testResults.png)

### Backend

1. Inside the Choose-Up-Api folder cd into tests then cd into UnitTests
2. Once inside the UnitTests folder run the command
```
dotnet test
```
3. This will result in a output that looks like this:

![Test Results](../Auxiliary%20Files/DevDocPictures/backendTestResults.png)

4. The number to the right of each word is how many fullfilled that condition
