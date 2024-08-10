# Module 13 Challenge: ORM E-Commerce Backend

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Description
This project is an ORM-based backend for an e-commerce platform. It provides RESTful API routes to manage products, categories, tags, and their relationships. The backend is built using Node.js, Express.js, and Sequelize, and it connects to a PostgreSQL database.

## Installation
To install and run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/laxsonii/e-commerce-backend-project.git
   cd module-13-challenge-orm
   category --< product


   Database Schema
The database schema consists of the following tables:

category: Stores product categories (id, category_name).
product: Stores products (id, product_name, price, stock, category_id).
tag: Stores tags (id, tag_name).
product_tag: Stores the many-to-many relationship between products and tags (product_id, tag_id).
product --< product_tag >-- tag
   ### Explanation:
- **Installation**: Detailed steps to get the project up and running.
- **Usage**: Basic usage instructions with example API endpoints.
- **Database Schema**: A simple description of the schema and relationships.
- **License**: MIT License for open-source distribution.

YouTube Link - 
