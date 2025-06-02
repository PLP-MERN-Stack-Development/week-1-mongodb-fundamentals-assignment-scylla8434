# MongoDB Fundamentals Assignment – Comprehensive Guide

Welcome to all-in-one guide for mastering MongoDB fundamentals through this assignment. This document will walk you through every step, from setup to advanced queries, ensuring a smooth and professional experience.

---

## 📦 Project Overview
This project covers:
- MongoDB installation and setup
- Populating your database with sample data
- Performing CRUD operations
- Writing advanced queries (filtering, projection, sorting, pagination)
- Aggregation pipelines
- Indexing for performance

---

## 🚀 Step 1: Environment Setup

### 1. Install Node.js
- Download from: https://nodejs.org/
- Follow the installation instructions for your OS.

### 2. Install MongoDB Community Server
- Download from: https://www.mongodb.com/try/download/community
- Installation guide: https://docs.mongodb.com/manual/installation/
- After installation, start the MongoDB server:
  ```powershell
  mongod
  ```
- (Optional) Install MongoDB Compass for a GUI: https://www.mongodb.com/try/download/compass

### 3. Clone Your Repository
- Clone your repository using:
  ```powershell
  git clone <your-repo-url>
  cd <your-repo-folder>
  ```

### 4. Install Project Dependencies
- In your project folder, run:
  ```powershell
  npm install mongodb
  ```

---

## 📚 Step 2: Populate the Database

- Run the provided script to insert sample books:
  ```powershell
  node insert_books.js
  ```
- This will connect to your local MongoDB, drop the existing `books` collection if it exists, and insert the sample books.
- You will see a summary of inserted books in your terminal.

---

## 🔍 Step 3: Explore and Query Your Data

- Use MongoDB Shell (`mongosh`) or MongoDB Compass to connect to your database:
  ```powershell
  mongosh
  use plp_bookstore
  ```
- All required queries are provided in `queries.js` with clear comments and usage instructions.
- Example queries include:
  - Find books by genre, author, or year
  - Update or delete specific books
  - Advanced queries: projection, sorting, pagination
  - Aggregation pipelines for analytics
  - Creating and using indexes

---

## 🛠️ Troubleshooting & Tips
- If you see `MODULE_NOT_FOUND` for `mongodb`, run `npm install mongodb` again.
- If `mongod` is not recognized, ensure MongoDB is added to your system PATH.
- Use MongoDB Compass for a visual interface to inspect your data.
- Refer to the official docs for more help:
  - [MongoDB Documentation](https://docs.mongodb.com/)
  - [MongoDB University](https://university.mongodb.com/)
  - [MongoDB Node.js Driver](https://mongodb.github.io/node-mongodb-native/)

---

## 📂 Project Structure
- `insert_books.js` – Script to populate your MongoDB database with sample book data
- `queries.js` – All required MongoDB queries for the assignment
- `Week1-Assignment.md` – Detailed assignment instructions
- `assets/` – Screenshots and supporting images
