# 🗄️ Week 1: MongoDB – Data Layer Fundamentals and Advanced Techniques

## 🚀 Objective
Learn the fundamentals of MongoDB, including installation, creating collections, performing CRUD operations, using aggregation pipelines, and implementing indexing for performance optimization.

## 📂 Tasks (COMPLETED)

### Task 1: MongoDB Setup
- [x] Install MongoDB on your local machine OR set up a free MongoDB Atlas cluster
- [x] Create a new database called `plp_bookstore`
- [x] Create a collection called `books`

### Task 2: Basic CRUD Operations
- [x] Use the provided `insert_books.js` script to insert at least 10 book documents into your collection
- [x] Each book has the required fields (see `insert_books.js`)
- [x] MongoDB queries for:
  - [x] Find all books in a specific genre
  - [x] Find books published after a certain year
  - [x] Find books by a specific author
  - [x] Update the price of a specific book
  - [x] Delete a book by its title

### Task 3: Advanced Queries
- [x] Query to find books that are both in stock and published after 2010
- [x] Use projection to return only the title, author, and price fields
- [x] Implement sorting by price (ascending and descending)
- [x] Use `limit` and `skip` for pagination (5 books per page)

### Task 4: Aggregation Pipeline
- [x] Aggregation pipeline to calculate the average price of books by genre
- [x] Aggregation pipeline to find the author with the most books
- [x] Pipeline that groups books by publication decade and counts them

### Task 5: Indexing
- [x] Create an index on the `title` field
- [x] Create a compound index on `author` and `published_year`
- [x] Use the `explain()` method to demonstrate performance improvement

## 🤩 Expected Outcome
- A functioning MongoDB database with properly structured data
- A set of MongoDB queries that demonstrate understanding of CRUD operations
- Advanced queries showing filtering, projection, and sorting capabilities
