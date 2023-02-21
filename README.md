# Progressive-Web-Applications--PWA--Challenge-Text-Editor
HW CHALLENGE #19


## Description
So far, we have completed multiple projects, our task is to create a portfolio, using our new React skills to help set us apart from other developers whose portfolios don’t use the latest technologies.

To build this text editor,we will start with an existing application and implement methods for getting and storing data to an IndexedDB database. We will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla. [click here](https://github.com/hannybear88/Progressive-Web-Applications--PWA--Challenge-Text-Editor/tree/main/client/src/js) to see my code for this project.


## Table of Contents
* [Installation](#installation)
* [Tests](#Tests)
* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [Usage](#Usage)
* [Demo](#Demo)
* [Technologies Used](#Technologies-Used)
* [Support](#Support)
* [Credits](#Credits)
* [Contributors](#Contributors)


## Installation
* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

    * npm install express (express.js)
    * npm install --save-dev webpack (Webpack)
    * npm install webpack-dev-server --save-dev (webpack-dev-server)
    * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
    * npm install babel (Babel)
    * npm install --save-dev css-loader (CSS-loader)
    * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
    * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.  


## Tests
Testing restful API calls with Insomnia Core
[click here](https://docs.insomnia.rest/insomnia/install) to install Insomnia


## User Story
- AS A developer
- I WANT to create notes or code snippets with or without an internet connection
- SO THAT I can reliably retrieve them for later use


## Acceptance Criteria
- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application


## Usage


## Demo

Click on the button below to be directed straight to the Heroku deployed application

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://pwa-challenge-text-editor.herokuapp.com/)

Screenshots

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure
``````
*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*

![folder structure](/Assets/images/pwa_folder_structure_screenshot.png)


2.
``````
    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
``````
*Below is the screenshot of the running at npm run start and npm run build* 

![npm run start and npm run build](/Assets/images/pwa_npmrunstart_and_npmrunbuild_screenshot.png)

*Below is the screenshot of the generated HTML, service worker and a manifest file*

![genereated HTML](/Assets/images/pwa_generatedHTML_serviceworkerandamanifestfile_screenshot.png)
![service worker](image here)
![manifest.json](image here)

3.
``````
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
``````
*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![Text Editor](/Assets/images/pwa_JATE_Screenshot.png)

4.
``````
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
``````
*Below is the  screenshot of content in the text editor has been retrieved from the IndexedDB"*
![IndexedDB Storage](image here)

![content in the text editor](image here)

5.
``````
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
``````
*Below is the screenshot of icon on the desktop"*

![icon on the desktop](/Assets/images/pwa_JATE_icon_on_desktop_screnshot.png)

6.
``````
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
``````
*Below is the screenshot of the static assets pre cached upon loading with subsequent pages and static assets"*

![static assets pre cached upon loading with subsequent pages and static assets 1](image here)

![static assets pre cached upon loading with subsequent pages and static assets 2](image here)

7.

 ````````
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
````````
![deployed to Heroku screenshot](/Assets/images/pwa_herokudepoyedapp_JATE_screenshot.png)


## Technologies Used

![Technologies](https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/npm%20package-moment-%3CCOLOR%3E?style=flat-square&logo=npm)
![Technologies](https://img.shields.io/badge/npm%20package-express-green?style=flat-square&logo=npm)
![Technologies](https://img.shields.io/badge/npm%20package-mongoose-purple?style=flat-square&logo=npm) 
![Technologies](https://img.shields.io/badge/Database-MongoDB-yellow?style=flat-square&logo=mongoDB) 


## Support
If you need support or have any questions about the repo, please [open an issue](https://github.com/hannybear88/Model-View-Controller--MVC--Challenge-Tech-Blog/issues) or contact me via email at hannahkchung88@gmail.com. You can find more of my work on my GitHub, [hannybear88](https://github.com/hannybear88/).


## Credits
- Starter code provided by UCSD 
- Code by Hannah Chung


## Contributors
- Starter code provided by UCSD 
- Code by Hannah Chung
