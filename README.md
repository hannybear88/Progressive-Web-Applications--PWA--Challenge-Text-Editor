# Progressive-Web-Applications--PWA--Challenge-Text-Editor
HW CHALLENGE #19


## Description
Our task for this challenge is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor,we will start with an existing application and implement methods for getting and storing data to an IndexedDB database. We will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla. [click here](https://github.com/hannybear88/Progressive-Web-Applications--PWA--Challenge-Text-Editor/tree/main/client/src/js)to see my code for this project.


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
1. Clone the repo
2. Install all dependencies 
    - `npm init -y`
    - `npm` install 
3. Start the server 
4.   - `npm` start

5. Open Insomnia Core to test API routes


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

Walkthrough Video

Please [click here] (link here) for a walkthrough video that demonstrates the application's functionality.

<!-- Click on the button below to be directed straight to the Heroku deployed application

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://model-view-controller--mvc.herokuapp.com/) -->

Screenshots
**TAGS**

* GET all tags 
![Get all tags](assets/images/GET_all_tags_screenshot.png)

* GET one tag by id
![GET one tag by id](assets/images/GET_one_tag_by_id_screenshot.png)

* CREATE new tag
![CREATE new tag](assets/images/CREATE_new_tag_screenshot.png)

* CREATE one tag by id after creating new tag
![CREATE one tag by id after creating new tag](assets/images/GET_one_tag_by_id_after_creating_new_tag_screenshot.png)

* UPDATE tag by id
![UPDATE tag by id](/assets/images/UPDATE_tag_by_id.png)

* GET one tag by id after updating new tag 
![GET one tag by id after updating new tag ](/assets/images/GET_one_tag_by_id_after_updating_new_tag_screenshot.png)

* DELETE tag by id
![DELETE tag by id](assets/images/DELETE_tag_by_id_screenshot.png)

**PRODUCTS**

* GET all products
![GET all products](/assets/images/GET_all_products_screenshot.png)

* GET one product by id
![GET one product by id](/assets/images/GET_one_product_by_id_screenshot.png)

* CREATE new product
![CREATE new product](/assets/images/CREATE_new_product_screenshot.png)

* CREATE one product by id after creating new product
![CREATE one tag by id after creating new tag](assets/images/GET_one_product_by_id_after_creating_new_product_screenshot.png)

* UPDATE product by id
![UPDATE product by id](/assets/images/UPDATE_product_by_id.png)

* GET one product by id after updating new product
![GET one tag by id after updating new tag ](/assets/images/GET_one_product_by_id_after_updating_new_product_screenshot.png)

* DELETE product by id
![DELETE product by id](/assets/images/DELETE_product_by_id_screenshot.png)

**CATEGORIES**

* GET all categories
    ![GET all categories](/assets/images/GET_all_categories_screenshot.png)

* GET one cateogry by id
    ![GET one category by id](/assets/images/GET_one_category_by_id_screenshot.png)

* CREATE new category
![CREATE new category](/assets/images/CREATE_new_category_screenshot.png)

* CREATE one category by id after creating new category
![CREATE one tag by id after creating new tag](assets/images/GET_one_category_by_id_after_creating_new_category_screenshot.png)


* UPDATE category by id
![UPDATE category by id](/assets/images/UPDATE_category_by_id.png)

* GET one category by id after updating new category
![GET one tag by id after updating new tag ](/assets/images/GET_one_category_by_id_after_updating_new_category_screenshot.png)

* DELETE category by id
![DELETE category by id](/assets/images/DELETE_category_by_id_screenshot.png)



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
