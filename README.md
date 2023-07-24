
<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End 👋</h1>
  
   
## Description
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to create a walkthrough video that demonstrates its functionality and all of the following acceptance criteria being met. You’ll need to submit a link to the video and add it to the README of your project.

Refer to the Video Submission GuideLinks to an external site. on the Full-Stack Blog for additional guidance on creating a video.
  
![DB Setup and Start](./animations/DB%20setup%20and%20start.gif)

![GET All](./animations/GET%20all.gif)

![GET All by ID](./animations/GET%20by%20ID.gif)

![POST PUT DELETE Products and Tags](./animations/POST%20PUT%20DELETE%20Tags%20and%20Products.gif)

![POST PUT DELETE Categories](./animations/POST%20PUT%20DELETE%20Categories.gif)
  
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
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
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
💾   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
💻   
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## Testing
✏️

No testing is currently set up

## Contributing
:octocat: [Yago Lira](https://github.com/yago-pixel/Object-Relational-Mapping-ORM-Challenge-E-commerce-Back-End.git)

