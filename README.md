# E-Commerce-BackEnd  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

  ## Description
  My challenge was to build the back end for an e-commerce site. I was given a working Express.js API and 
  configured it to use Sequelize to interact with a MySQL database. Users may now create, read, update and delete (C.R.U.D.) data
  from a database using Sequelize. The database includes tables such as **Categories, Products, Tags, and Product-Tags** which store data
  about products, pricing and inventory. The tables also reference each other through IDs.
  <br/>
  
  ## Table of Contents
  * [Installation](#Installation)
  * [Usage](#Usage)
  * [License](#License)
  * [Contributing](#Contributing)
  * [Questions](#Questions)
  <br/>
  
  ## Installation
  1) clone the repository by entering the following command in the command line: <br/> 
  ```
  git clone git@github.com:BriagasD98/E-Commerce-BackEnd.git
  ```
  2) Install the necessary dependencies by entering the following commands into the command line: <br/>
  ```
  npm init -y
  ```
  ```
  npm i mysql2 sequelize
  ```
  ```
  npm i express
  ```
  ```
  npm i dotenv
  ```
  **I have hidden my sql credentials. You must input your own personal mysql user and password into a new .env file on your local computer to use the application!**
  
  <br/>
  
  ## Usage
  **For a video walkthrough, please follow this link:** https://drive.google.com/file/d/1n2jOKZ81lwKYGBhTHsVk_dmPdWEtLIYu/view 
  <br/>
  In your **MySQL command line**, enter the following commands to setup the database:
  ```
  SOURCE db/schema.sql;
  ```
  ```
  USE ecommerce_db;
  ```
  Once all necessary dependencies have been installed, go to the command line and enter the following commands:
  ```
  npm run seed
  ```
  ```
  npm start
  ```
  <br/>
  
  **npm run seed** will seed data into the database and **npm start** will connect to the database to so users
  may perform RESTful CRUD operations. **Insomnia Core is our testing app of choice!**
  
  <br/>
  
  ![GetRoute-gif](https://user-images.githubusercontent.com/83102464/128663252-0bb3683c-1923-446e-ac3e-7fdfea73bc2d.gif)
  <br/>
  
  ![singleGetRoute-gif](https://user-images.githubusercontent.com/83102464/128663262-f6bc8c5d-4e17-4334-be42-54e6a955127d.gif)
  <br/>
  
  ![PostPutDelete-gif](https://user-images.githubusercontent.com/83102464/128663269-8591fefa-7769-4df5-b59a-6c71b0c88258.gif)
  <br/>
  
  ## License
  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
  For License information, visit:
  [MIT](https://opensource.org/licenses/MIT)
  <br/>
  <br/>
  ## Contributing
  Contact me Via Email or Github for more information on how to contribute!
  <br/>
  <br/>
  
  ## Questions  
  If you have questions about the project you can email me, or you can open an issue in the GitHub repository.
  <br/>
  My GitHub profile is [BriagasD98](https://github.com/BriagasD98)  
    
  My Email: [briagasdavid@yahoo.com](mailto:briagasdavid@yahoo.com).
