# PLP Bookstore MongoDB Project

## 🚀 Objective

Learning MongoDB fundamentals and advanced techniques, including installation, CRUD operations, aggregation pipelines, and indexing for performance optimization.

---

## 🛠️ Setup

1. **Install MongoDB**  
   - Install MongoDB Community Edition locally **OR** set up a free MongoDB Atlas cluster.
2. **Clone this repository**  
   ```bash
   git clone <your-repo-url>
   cd PlpMongo
   ```
3. **Database & Collection**  
   - Create a database named `plp_bookstore`.
   - Create a collection named `books`.
4. **Insert Sample Data**  
   - Run the script to insert sample book data:
     ```bash
     node insert_books.js
     ```

---

## 📂 Project Structure

- `insert_books.js` – Script to insert at least 10 sample book documents.
- `queries.js` – All required MongoDB queries (CRUD, advanced, aggregation, indexing).
- `README.md` – Instructions and project outline.
- `screenshot.png` – Screenshot of your MongoDB Compass/Atlas showing your collections and data.

---

## 📝 Tasks

### Task 1: MongoDB Setup

- Install MongoDB or set up Atlas.
- Create `plp_bookstore` database and `books` collection.

### Task 2: Basic CRUD Operations

- Insert at least 10 books with fields:
  - `title` (string)
  - `author` (string)
  - `genre` (string)
  - `published_year` (number)
  - `price` (number)
  - `in_stock` (boolean)
  - `pages` (number)
  - `publisher` (string)
- Write queries to:
  - Find all books in a specific genre.
  - Find books published after a certain year.
  - Find books by a specific author.
  - Update the price of a specific book.
  - Delete a book by its title.

### Task 3: Advanced Queries

- Find books that are both in stock and published after 2010.
- Use projection to return only `title`, `author`, and `price`.
- Sort books by price (ascending and descending).
- Implement pagination (5 books per page) using `limit` and `skip`.

### Task 4: Aggregation Pipeline

- Calculate average price of books by genre.
- Find the author with the most books.
- Group books by publication decade and count them.

### Task 5: Indexing

- Create an index on the `title` field.
- Create a compound index on `author` and `published_year`.
- Use `explain()` to demonstrate performance improvements.

---

## 🧪 Expected Outcome

- A functioning MongoDB database with properly structured data.
- MongoDB queries demonstrating CRUD, advanced filtering, projection, and sorting.
- Aggregation pipelines for data analysis.
- Properly implemented indexes with performance analysis.

---



## 💡 Tips

- Use MongoDB Shell (`mongosh`) or MongoDB Compass for queries and data exploration.
- Save all your queries in `queries.js`.
- add `screenshot.png` showing your collections and data.
