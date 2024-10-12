What did I do in this project, step by step:
1- I created Frontend and Backend folders. Apart from these folders, I installed npm for the entire project.
2- (npm i express mongoose dotenv) I ran it in terminal. 
- Express.js: Used for handling server-side operations and managing API routes.
- Mongoose: Used for connecting to MongoDB and defining data models for the database.
- Dotenv: Used for managing environment variables and securely loading them into the project.
- If you want to learn which versions of the libraries installed and whether they were actually installed,
go to the package.json file.
3- I created server.js folder to determine the entry point for our API. It may also be named like app.js/index.js/main.js in the other projects.
4- If we go into package.json folder and change "scripts" -> "dev" as "node backend/server.js" we can run the app when print "npm run dev"
- But if we want application to upload itself, we should install nodemon.js .
- Nodemon is a development tool that automatically restarts your Node.js application when file changes are detected in the directory. 
- After print "npm i nodemon -D" to console and install the tool files, it is going to work. And actually pressing "ctrl+s" will be enough to run your project.
