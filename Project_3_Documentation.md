# Project 3 - MERN Stack Implementation
___
___
## **Step 1 BACKEND CONFIGURATION**
___
>### Installing Ubuntu’s package manager ‘apt’

#### To update a list of packages in package manager for Node like apt for Ubuntu the following set of commands are run;
* *`sudo apt update`* - (Updated Ubuntu)
* *`sudo apt upgrade`* - (Upgrades Ubuntu)

![Sudo apt Install](./Project_3_Images/Backend/sudo%20apt%20install.PNG)
![sudo apt Upgrade](./Project_3_Images/Backend/sudo%20apt%20Upgrade.PNG)
![Sudo apt Upgrade](./Project_3_Images/Backend/sudo%20apt%20Upgrade_1.PNG)
![Sudo apt Upgrade](./Project_3_Images/Backend/sudo%20apt%20Upgrade_2.PNG)
#### Installing Node.js Files
* *`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`* - (Gets the location of Node.js software from Ubuntu repositories.)
* *`sudo apt-get install -y nodejs`* - (Install Node.js on the server)
* *`node -v `* - (Checks version of Node)
* *`npm -v`* - (Checks version on NPM. NPM is a package manager for Node like apt for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts.)
![Sudo E-Bash](./Project_3_Images/Backend/Sudo%20E%20Bash.PNG)
![Sudo apt get instal node js](./Project_3_Images/Backend/Sudo%20apt%20get%20install%20nodejs.PNG)
>### Application  Setup
#### Create a new directory for your To-Do project
* *`mkdir Todo`* - (Creates Directory Todo)
* *`cd Todo`* - (Enters into the Ditectory)
* *`npm init`* - ( Initialize the project with a package.json file This file will normally contain information about your application and the dependencies that it needs to run.)
![mkdir Todo](./Project_3_Images/Backend/mkdir%20Todo.PNG)
>### Node Server Setup
#### To run a JavaScript code on the backend, there is need to spin up a server that will compile the code. The following commands were implemented
* *`npm install express`* - (Express helps to define routes of the application based on HTTP methods and URLs)
* *`touch index.js`* - (Create a file index.js)
* *`npm install dotenv`* - (Installs the dotenv module)
* *`node index.js`* - (Starts up the server and displays Server running on port 5000 )
![Install express](./Project_3_Images/Backend/Install%20express%20js.PNG)
![Express](./Project_3_Images/Backend/Welcome%20toexpress.PNG)
>### Creating the routes & defining the models
#### There are three things that the app needs to do
* *`create a task`* 
* *`Display list of all tasks`* 
* *`Delete a completed task`* 
##### To create the Direectories
* *`mkdir routes`* - (create routes that will define various endpoints that the To-do app will depend on)
* *`cd routes`* - (Enters into the Ditectory)
* *`touch api.js`* - (Create a file api.js)
* *`npm install mongoose`* - (create routes that will define various endpoints that the To-do app will depend on)
* *`mkdir models`* - (Creates a model folder that is heart of JavaScript based applications, and it is what makes it interactive.)
* *`touch todo.js`* - (Create a file todo.js)