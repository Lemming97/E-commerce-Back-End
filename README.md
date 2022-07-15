# E-commerce-Back-End


![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Description 
Employee Tracker is a content-management system (CMS). It is command-line application that manages a company's employee database, using Node.js, Inquirer, and MySQL.



## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Usage](#usage)
* [Installation](#installation)
* [Video](#video)
* [Screenshots](#screenshots)




 
## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

```

## Usage
To understand the fundamental architecture of e-commerce sites.

## Installation

1. Clone the repository from GitHub
1. Install `node.js`
1. Run `npm install` to install dependencies. Dependencies include mysql, console.table, express, inquirer, and jest.
1. Run `mysql -u root -p` to start the database connection. 
1. Updated `connection.js` file with your own mysql user password. 
1. Create the database by running the command: `source db/schema.sql`.
1. Seed the database by running the command: `source db/seeds.sql`.
1. Start the Database by running the command: `npm start`.



## Video
<p>To View the Video: <a href="https://drive.google.com/file/d/1qtD7d4FfdfFd0vNKPGVtoHt-qCi5MmUU/view?usp=sharing"> Click Here</a></p>



## Screenshots
<br><img src="./Assets/Category1.png" alt="screenshot of Category1" width="350"/>
<br><img src="./Assets/Category2.png" alt="screenshot of Category2" width="350"/>
<br><img src="./Assets/Product1.png" alt="screenshot of Product1" width="350"/>
<br><img src="./Assets/Product2.png" alt="screenshot of Product2" width="350"/>
<br><img src="./Assets/Tag1.png" alt="screenshot of Tag1" width="350"/>
<br><img src="./Assets/Tag2.png" alt="screenshot of Tag2" width="350"/>










