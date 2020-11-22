Development Documentation

## Needed Software:

 - [.Net Core (Version 3.1) ](https://dotnet.microsoft.com/download/dotnet-core)
 - [PostgreSQL (Version 13)](https://www.postgresql.org/download/)
 - [Node.js (Version 14.15)](https://nodejs.org/en/)
 - Vue-Cli install through =>   `npm install -g @vue/cli` 
	 - Once Node.js is installed you can install this through the command line

 - [Visual Studio Code](https://code.visualstudio.com/) (Recommended)

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
 
## Running Test
 - Currently no automated tests can be run 



