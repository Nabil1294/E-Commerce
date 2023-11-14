# E-Commerce
Internet retail, also known as **e-commerce**, plays a significant role within the electronics industry, as it empowers businesses and consumers alike to conveniently engage in online buying and selling of electronic products. In the latest available data from 2021, the industry in the United States alone was estimated to have generated the substantial amount of US$2.54 trillion, according to the United Nations Conference on Trade and Development. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes.

## Description.

E-Commerce is a Node.js project utilizing Sequelize ORM (Object-Relational Mapping) for handling database operations in an efficient and developer-friendly manner. The project is structured to manage and interact with a database using models and routes for categories, products, and tags.

## Table Of Contents.
.Usage
.Installation
.Dependencies
.Contributing
.Demo
.Deployed Page Link
.Screen Shots

## Usage

1. Navigate to the project directory in your terminal.
2. Run node <your-main-app-file-name> to start the application.


## Installation

1. Clone the repository to your local machine.

2. Navigate to the project directory in your terminal.

3. Run npm install to install necessary dependencies, which include:
mysql2: For database connections.
This will install necessary packages like express, sequelize, mysql2, dotenv, and nodemon (as a dev dependency).


4. Set up your MySQL database:
Ensure you have MySQL installed and running on your machine.
Use the provided schema.sql file to set up your database.
(Optional) Use the seeds.sql file to populate your tables with sample data.

5. Update the database connection configuration (user, password, database, etc.) in the main application file to match your local MySQL setup.
# To install the necessary dependencies, run:
bash
Copy code
\`\`\`
npm install
\`\`\`
This command will install the required packages.

# Running the Application:
To start the application, in your terminal type:

bash
Copy code
\`\`\`
mysql -u root -p (you will then be asked to provide your password)
\`\`\`

\`\`\`
source db/schema.sql;
\`\`\`

\`\`\`
exit
\`\`\`

\`\`\`
npm run seeds
\`\`\`

\`\`\`
node server.js
\`\`\`


## Contributing
Contributions are always welcome! Please fork the repository and create a Pull Request with your changes.


## Demo.

https://drive.google.com/file/d/1YicwwFdDlumL2Gkq8Z-YipCBA4X4IUsM/view


## Deployed Page Link.

 https://nabil1294.github.io/E-Commerce/