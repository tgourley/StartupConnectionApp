# Deployment Documentation

## User Auth
To implement Okta as the user authentication use their website at: https://www.okta.com/  
Once you have followed the instructions to start the Okta service, find the clientId and the issuer of your okta service and
place this information inside the given fields at the top of router.js inside the ui project

## Server
Our software uses a combination of PostgreSQL for backend database management, .NET for our business logic and connecting the frontend to the database, and an npm server for the local JavaScript.

 ## Cloning the Repository
 
 ### GitLab
 
 To get the projects code, issue the command git clone in the terminal of Visual Studio code with the following links when in a 'Choose Up' folder to store both repositories:
 
 Choose-up-api: https://gitlab.com/Cjbucker/choose-up-api.git  
 Choose-up-ui: https://gitlab.com/Cjbucker/choose-up-ui.git

## Running the system
###  Frontend
To run the frontend, in the command line mentioned above, run the commands in the Choose-Up-UI main folder:

1. npm run build

    a. Assures necessary files are installed in the project.

2. npm run serve

    a. Runs the frontend and displays localhost link.

3. Open localhost link in command line:

    a. Opens the webpage in localhost in your default browser.

To stop the system, execute CTRL+C or CMD+C in the terminal which terminates the server.

### Database

1. To run the PostgresSQL server start up the ‘pgAdmin’ application ( If first time startup perform step two as well ).
2. Set a username and password for the local user.
3. The backend will create the database based on the backend models. This will result in a schema being created called 'Users'.

## Backend

To run the backend api, perform the following commands:

1. In ‘appsettings.json', find ‘localhost’ under ‘ConnectionStrings' then change the ‘User Id' and ‘Password’ fields to be the database id and password. Example ‘ConnectionStrings’:

```
"ConnectionStrings": {
    "localhost":"Server=127.0.0.1;Port=5432;Database=ChooseUp;User Id=postgres;Password=admin"
  }
```
2. In the main Choose-Up-API folder got to src then perform the command:
```
dotnet run 
```
3. The terminal will then state the API is running and where.

## Troubleshooting
If you have issues, check the console for errors.

## Source of Errors
Errors are found in the command console where the npm run serve is running.

## Critical Fails
* Critical fails occur when initially running the server; any uninstalled libraries can cause failures.

* If the User Id and Password for the API to connect to the database is not correct, the backend will not run and throw errors.
