# Deployment Documentation
## Server
Our software uses a combination of PostgreSQL for backend database management, .NET for our business logic and connecting the frontend to the database, and an npm server for the local javascript. Currently, there is only npm implemented in this iteration due to not having a fully connected backend.

## File format
The file for our project (choose-up-ui) can be downloaded and placed anywhere that you have admin rights. once you have the file saved, open it up in the command line (path should be /"path name"/choose-up-ui)

## Running the system
To run the system, in the command line mentioned above, run the command "npm install" to ensure all the necessary files are installed. Then run the command "npm run serve". Once the serve has completed (assuming all code is correct), you will get a localhost link. open that link in your browser to get the website up.

To stop the system, CTRL+C or CMD+C in the terminal to terminate the server.

## Troubleshooting
if you have issues running "npm run serve", you might be missing a library. if so, the errors will give you a command for you to run to install a library. if it is not a library, then you will find a piece of code.

## Source of errors
errors are found in the command console where the npm run serve is running.

## critical fails
the biggest fails occur when initally running the server, any uninstalled libraries can cause failures.
