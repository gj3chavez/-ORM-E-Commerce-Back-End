# E-Commerce Back End
![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)  ![Noje.js](https://img.shields.io/badge/-node.js-brightgreen)  ![Screencastify](https://img.shields.io/badge/-Screencastify-red)  


## Description
   This app stores and organices data for E-Commerce website. This application uses Express.js, API and Sequalize to interact with a MySQL database which will allow a devoloper to create, read, update, and delete categories, tags and productos for their online store.

   Link to demo video: https://drive.google.com/file/d/1cUT9L8-MgMVMsf-ZtneuZj-mbmJk_E22/view

## Screenshot
![Profile Generator](./)

## Table of Contents
  - [Description](#Description)
  - [Installation](#Installation)
  - [Usage](#Usage)
  - [Contribution](#Contribution)
  - [License](#License)
 

## Techonologies

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Express.js](https://expressjs.com/)
* [Node.js](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [Sequelize](https://sequelize.org/)
* [Insomnia](https://insomnia.rest/download) 

## Installation 
* In order to use this application you must clone the repository on your local machine.
* Make sure that your repo includes a `package.json` with the require dependencies. You can create one by running npm init when you first set up the project, before installing any dependencies.


## Usage
After installing a `package.json` with the require dependencies you can proceed to:
* Creat, Sync and Seed data:
    * Type `mysql -u root -p` in your terminal and add your password.
    * Then `source db/schema.sql` and `quit`.
    * To seed it: `node seeds/index.js`
    * Type `npm start` to start the server and use [Insomnia](https://insomnia.rest/download) to interact with the app. 


## Contribution
For questions please reach me at: giuliana@gmail.com <br/>
My Github: [Giuliana](https://github.com/gj3chavez)


## License
  ![License](https://img.shields.io/badge/License%20-MIT-orange)
  
  Copyright (c) 2023 gj3chavez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.