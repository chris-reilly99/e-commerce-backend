# e-commerce-backend

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

## **Table of contents**

  - [E-Commerce Backend](#e-commerce-backend)
  - [Table of contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Tutorial](#tutorial)

  ---
## **Installation**

Start with cloning this repo on your local machine, then navigate into the directory for this newly cloned repo and install:

To install and set up the application, run:
`npm i`

You will also need to place a .env file in the root directory of the project, in order to connect to your MySQL database. Here's an example:

file: .env
```
DB_NAME=library_db
DB_PASSWORD=
DB_USER=root
```

---
## **Usage**

To finish the set-up the application:
1. Create a MySQL database on your local machine using the *schema.sql* file in the db directory
2. Seed the database with: `npm run seed`

Now you're ready to start the application! You can start the server by running: 
`npm start`

---
## **Tutorial**
Check out the video tutorial at this link:
https://drive.google.com/drive/folders/1X0p9tn1QOIzEXHeiB5khjoDUL-5SGAfJ?usp=sharing
