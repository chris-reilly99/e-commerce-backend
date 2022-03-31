# e-commerce-backend

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

## **Table of contents**

- [E-Commerce Backend](#e-commerce-backend)
  - [Table of contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Built With](#built-with)
  - [License](#license)

  ---
## **Installation**

Start with cloning this repo on your local machine:

```sh
$ git clone https://github.com/chris-reilly99/e-commerce-backend
$ cd e-commerce-backend
```

To install and set up the application, run:
```sh
$ npm i
```

You will also need to place a .env file in the root directory of the project, in order to connect to your MySQL database. Here's an example:

file: .env
```
DB_NAME=library_db
DB_PASSWORD=
DB_USER=root
```

---
## **Usage**
<sub><sup>This section assumes you have installed the application, and created the .env file in the root directory.</sub></sup>

To finish the set-up the application, complete the following steps:
1. Create a MySQL database on your local machine using the *schema.sql* file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)
2. Seed the database with sample data to be used for testing purposes(Run *npm run seed* from inside the root directory of the project)

Now you're ready to start the application! You can start the server by running: 
```
npm start
```
---

## **Built With**
* [**Node.js**](https://nodejs.org/en/about/)
*  - [Sequelize](https://www.npmjs.com/package/sequelize)
*  - [Express.js](https://www.npmjs.com/package/express)
* [**Visual Studio Code**](https://code.visualstudio.com/)

---

## **License**
This application is licensed under the MIT License, you can find the full license information [here](http://github.com/)

---