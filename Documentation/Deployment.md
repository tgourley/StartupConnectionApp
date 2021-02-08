# Deployment Documentation
## Server
Our software uses a combination of PostgreSQL for backend database management, .NET for our business logic and connecting the frontend to the database, and an npm server for the local JavaScript. Currently, only npm is implemented in this iteration due to not having a fully connected backend.

## File format
The file for our project (choose-up-ui) can be downloaded and placed anywhere you have admin rights. Once you have the file saved, open it up in the command line (path should be /"path name"/choose-up-ui)

## Running the system
###  Frontend
To run the frontend, in the command line mentioned above, run the commands in the Choose-Up-UI main folder:

1. npm install

    a. Assures necessary files are installed in the project.

2. npm run serve

    a. Runs the frontend and displays localhost link.

3. Open localhost link in command line:

    a. Opens the webpage in localhost in your default browser.

To stop the system, execute CTRL+C or CMD+C in the terminal which terminates the server.

## Backend

To run the backend api, perform the following commands:

1. In ‘appsettings.json', find ‘localhost’ under ‘ConnectionStrings' then change the ‘User Id' and ‘Password’ fields to be the database id and password. Example ‘ConnectionStrings’:

```
"ConnectionStrings": {
    "localhost":"Server=127.0.0.1;Port=5432;Database=ChooseUp;User Id=postgres;Password=admin"
  }
```
2. In the main Choose-Up-API folder, perform the command:
```
dotnet run --project "{PROJECT_PATH}\Choose-up-api.csproj"
```
3. The terminal will then state the API is running and where.

## Troubleshooting
If you have issues, check the console for errors.

## Source of Errors
Errors are found in the command console where the npm run serve is running.

## Critical Fails
* Critical fails occur when initially running the server; any uninstalled libraries can cause failures.

* If the User Id and Password for the API to connect to the database is not correct, the backend will not run and throw errors.
