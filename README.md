# text-editor
Module 19 Challenge Assignment: Progressive Web Applications (PWA) Challenge -- Text Editor


## Badges
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents
  * [License](#license)
  * [Description](#description)
  * [User Story](#user-story)
  * [Acceptance Criteria](#user-story)
  * [Installation](#installation)
  * [Setup](#setup)
  * [Usage](#usage)
  * [Screenshots of Application in Use](#screenshots-of-application-in-use)
  * [Technologies](#technologies)
  * [How to Contribute](#how-to-contribute)
  * [Tests](#tests)
  * [Questions?](#questions)


## License
  Read more about MIT here:
  [MIT](https://opensource.org/licenses/MIT)


## Description
A text editor that meets the PWA criteria and feature a number of data persistence techniques that serve as redundancy in case of the options is not supported by the browser. The application will also function offline.


## User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```


## Acceptance Criteria 
```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
    

## Installation
```
  * npm install express (express.js)
  * npm install --save-dev webpack (Webpack)
  * npm install webpack-dev-server --save-dev (webpack-dev-server)
  * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
  * npm install babel (Babel)
  * npm install --save-dev css-loader (CSS-loader)
  * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
  * npm install idb (IndexedDB)
```

## Setup
* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

* Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using npm init. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization.

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in npm run install, the modules will be installed.
        
        
## Usage
To use the application from the command line (after installing dependencies):

- Step 1: Open the root directory of the repository in your terminal or bash.
- Step 2: Bundle the front-end code by entering ```npm i``` in the command line.
- Step 3: Start the server by entering ```npm run start``` in the command line.
- step 4: Go to the port on your local host in Google Chrome.
- step 5: Click the "Install" button.
- step 6: Alternatively, to use the live application, click [here](https://text-editor1111.herokuapp.com).


## Screenshots of Application in Use

The following animation demonstrates the application functionality:

![image](https://user-images.githubusercontent.com/114618684/224472060-f27e30c0-3b47-4314-a595-b51b777b2fd8.gif)

The following image shows the application's manifest.json file:

![image](https://user-images.githubusercontent.com/114618684/224472067-e29ddb18-861f-42ac-9d1b-f423b90a7859.png)

The following image shows the application's registered service worker:

![image](https://user-images.githubusercontent.com/114618684/224472081-6ebaaec2-88eb-4304-897f-ba8635de67a3.png)

The following image shows the application's IndexedDB storage:

![image](https://user-images.githubusercontent.com/114618684/224472085-ef870ef3-475a-4028-9737-bbdcee866b20.png)


## Technologies
* [Node.js](https://nodejs.org/en/)
* [Express.js](https://expressjs.com)
* [Heroku](https://www.heroku.com)
* [Babel](https://babeljs.io)
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
* [Webpack & WebpackPwaManifest Plugins](https://www.npmjs.com/package/webpack-pwa-manifest)


  ## How to Contribute
  [Contributor Covenant](https://www.contributor-covenant.org/)  


  ## Questions?
  ### Reach me here: 
  [DominiqueGarrett](https://github.com/DominiqueGarrett)  
  Dominique.garrett1212@yahoo.com