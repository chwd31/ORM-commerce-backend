# E-commerce Back End 

## Description
This project is a backend for an e-commerce website built with Express.js and Sequelize, and uses a MySQL database. It provides API routes for categories, products, and tags, allowing users to perform CRUD operations on the data. The application also includes seed files to populate the database with test data.   

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Walkthrough Video](#walkthrough-video)
* [Contributing](#contributing)
* [License](#license)
* [Author](#author)]   

## Installation
To use this project, you need to have Node.js and MySQL installed on your system. You can clone this repository and install the necessary dependencies by running the following command:
```
npm install
```
You will also need to create a .env file in the root directory of the project and add the following lines to it, replacing the values in brackets with your MySQL credentials:
```
DB_NAME='ecommerce_db'
DB_USER='[your MySQL username]'
DB_PW='[your MySQL password]'
```

## Usage
To start the application, run the following command:
```
npm start
```
You can then use an API testing tool such as Insomnia Core to test the API routes. The routes are as follows:
* Categories
    * GET all categories
    * GET a single category by ID
    * POST a new category
    * PUT update a category by ID
    * DELETE a category by ID
* Products
    * GET all products
    * GET a single product by ID
    * POST a new product
    * PUT update a product by ID
    * DELETE a product by ID
* Tags
    * GET all tags
    * GET a single tag by ID
    * POST a new tag
    * PUT update a tag by ID
    * DELETE a tag by ID

## Walkthrough Video
A walkthrough video demonstrating the functionality of the application can be found [here](https://drive.google.com/file/d/1ZbMVikjYq5BEaiyeJl0b_zu7TWxlOP4U/view).  

## Contributing
Contributions to this project are welcome! If you would like to contribute to this project, please clone the repository and submit a pull request for review.

## License
This project is licensed under the MIT license.[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Author
This project was created by [Chad Ward](http://www.github.com/chwd31)   

