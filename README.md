# Tech-blog
My task was to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts. Also I have built this site completely from scratch and deployed it to Heroku. The app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication, as well as using MySQL.

## Deployed URL

[Click here for the deployed URL](https://lit-wave-21461.herokuapp.com/)

## Installation

* To install the necessary packages to run this application, run ``npm install`` in your CLI and in order to use the database: change the credientials in ``config/connection.js`` to your own and run ``schema.sql`` in your database management application. In order to use the application locally run ``node server.js``.

## License

> This project was created under the [MIT License](https://opensource.org/licenses/MIT)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://shields.io/)