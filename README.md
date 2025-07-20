# 📚 Online Book Store - SQL Project

This project simulates an **Online Book Store** using SQL. It involves querying data from three CSV files that represent different entities in a bookstore: Books, Customers, and Orders.

## 📁 Dataset

The project uses **3 CSV files**:

- `Books.csv`
- `Customers.csv`
- `Orders.csv`

These files are interrelated using common columns such as `Book_ID` and `Customer_ID`.

## 🧾 Table Schema Assumption

| Table      | Key Columns                      |
|------------|----------------------------------|
| Books      | `Book_ID`, `Genre`, `Stock`, `Price`, `Author`, `Year_Published` |
| Customers  | `Customer_ID`, `Name`, `Country`, `City` |
| Orders     | `Order_ID`, `Book_ID`, `Customer_ID`, `Quantity`, `Order_Date`, `Total_Amount` |

> Ensure the column names and data types are consistent across tables (especially for `Customer_ID` and `Book_ID`).

---

## 🔍 Basic SQL Queries

1. Retrieve all books in the "Fiction" genre
2. Find books published after the year 1950
3. List all customers from Canada
4. Show orders placed in November 2023
5. Retrieve the total stock of books available
6. Find the details of the most expensive book
7. Show all customers who ordered more than 1 quantity of a book
8. Retrieve all orders where the total amount exceeds $20
9. List all genres available in the Books table
10. Find the book with the lowest stock
11. Calculate the total revenue generated from all orders

---

## 🧠 Advanced SQL Queries

1. Retrieve the total number of books sold for each genre
2. Find the average price of books in the "Fantasy" genre
3. List customers who have placed at least 2 orders
4. Find the most frequently ordered book
5. Show the top 3 most expensive books of the "Fantasy" genre
6. Retrieve the total quantity of books sold by each author
7. List the cities where customers who spent over $30 are located
8. Find the customer who spent the most on orders
9. Calculate the stock remaining after fulfilling all orders

---

## 💡 How to Run

1. Import the CSV files into a database (e.g., MySQL, PostgreSQL, SQLite).
2. Create tables corresponding to each CSV file.
3. Write and execute SQL queries using your preferred SQL tool or IDE.

---

## 📊 Project Slides (Optional)

You can include the following slides for presentation:
- Slide 1: Project Title
- Slide 2: Description of CSV Files
- Slide 3: Basic Queries
- Slide 4: Advanced Queries

---

## 🛠 Tools Used

- SQL (MySQL/PostgreSQL/SQLite)
- DB Browser / MySQL Workbench / pgAdmin
- CSV File Handling

---

## 📌 Author

**BRIJMOHAN PRASAD**  


---


