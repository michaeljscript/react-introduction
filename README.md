# Building web applications with React

## Introduction

[React](https://reactjs.org/) is a widely used tool by large tech companies to build scalable web applications or websites. React allows you to handle click events, manage the state of the application, and render different components based on the user inputs.

Examples of companies or projects using React: [Starbucks](https://app.starbucks.com/), [Discord](https://discord.com/), [Asana](https://app.asana.com/), [GitHub Desktop](https://desktop.github.com/)

## Creating a simple React application

Requirements: git, [NodeJS](https://nodejs.org/en/) (make sure you’re running version 14 or newer - `node -v` will print the node version you’re running), npm

To create a simple React application project, the following commands need to be executed in a command line

1. `npm install -g create-react-app` 
    1. This command will install a tool for bootstrapping a simple react application.
    2. [create-react-app](https://create-react-app.dev/) is a small command line tool for bootstrapping react applications used in almost every company which works with React. It may be needed for software developers to know about this tool if they’re applying for a Front-End React position. 
2. `create-react-app my-react-application` 
    1. Running this command will create a new directory called `my-react-application` and will create all the necessary project files and configurations
3. `cd my-react-application`
4. `npm start`
    1. It should run the project in development mode. It should open a new web browser window with a React logo spinning. If you’ve managed to get this done successfully, you’re ready to develop your first react application! Just open this folder in your favourite editor and as you make changes to the files, you should see the changes being updated automatically in your web browser.

Please do not make any changes to the `node_modules` folder, as this folder is intended to have internal project files which should not be edited. You can always ignore this folder. Please have a look at the `src/App.js` file, as this is the root file which you can edit and where you can develop your solution. Feel free to split the application logic into multiple files if needed.

## Task - Creating a simple Todo application in React

[Here is an example](https://todomvc.com/examples/react/#/)  of a simple web application built in React to track your “Todo” items. Todo application is a productivity application, so people don’t have to keep all the tasks in their head. Todo application lets you create new todo item, lets you mark your todo item as completed, or allows you to delete your todo items. Please try to develop a similar application in the code you’ve created in the section earlier and feel free to add any styles to make the application look unique, but no need to spend too much time on this.

A good Todo application 

- Should allow the user to write any input longer than 0 characters, but shorter than 256 characters
- Show allow the user to create a todo item based on the text user input (eg by pressing [Enter] key or by clicking on a button)
- Should allow the user to mark todo item as completed
- Should allow the user to delete completed items
- Should allow the user to delete incomplete items

Once you’re happy with what you have or want to discuss your solution or have any difficulties, please submit your application on GitHub, so we can discuss the code there and send me a message.

---

Michal Szorad
