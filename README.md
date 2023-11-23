# E-commerce Back End Starter Code

## Description

This project serves as the back end for an e-commerce website. It is built using Express.js as the server framework, Sequelize as the Object-Relational Mapping (ORM) tool, and MySQL as the database management system. The purpose is to provide a solid foundation for managing products, users, and other essential components of an e-commerce platform. The API is designed for managing categories, products, and tags in the context of an e-commerce platform.
Through the development of this project, several key learnings were achieved:

- Sequelize Integration: Gain proficiency in integrating Sequelize as an Object-Relational Mapping (ORM) tool with Express.js, facilitating efficient communication with a MySQL database.
- API Design: Understand the principles of designing RESTful APIs, implementing routes for CRUD operations, and managing relationships between entities.
- Database Configuration: Learn how to securely manage and configure database credentials using environment variables, enhancing the security of the application.
- Data Seeding: Implement the process of seeding a database with test data, a crucial step in preparing a development environment.
- Express.js Usage: Further develop skills in using Express.js to create a scalable and maintainable server, handling various HTTP requests and responses.

In summary, this project serves as a valuable hands-on experience in building a practical and functional back end for an e-commerce site, covering a spectrum of web development concepts and technologies.

## Contents

- [Technologies](#technologies)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies

- Express.js: A fast and minimalist web framework for Node.js.
- Sequelize: An ORM for Node.js that supports multiple database systems, including MySQL.
- MySQL2: A popular relational database management system.
- dotenv: This library helps manage configuration settings in your Node.js applications, especially sensitive information like API keys, database credentials, and other environment-specific configurations.
- Other dependencies: See `package.json` for a complete list of project dependencies.

## Features

- CRUD operations for managing products, users, and other entities.
- Sequelize models for defining database schema and relationships.
- RESTful API design for easy integration with front-end applications.

## Installation

Please watch video run through: https://drive.google.com/file/d/1_2YHc2blRsqVE6bxi36t8usJgzArL2Ez/view?usp=sharing

npm i

npm install mysql2

npm install sequelize

npm install dotenv

## Usage

Run the following command at the root of your project and answer the prompted questions:

mysql -u root -p

Enter PW when promted

source db/schema.sql

quit

npm run seed

npm start

## Contributing

Please feel free to reach out at Github: MFMcNolt

## License

This project is licensed under the MIT License.
