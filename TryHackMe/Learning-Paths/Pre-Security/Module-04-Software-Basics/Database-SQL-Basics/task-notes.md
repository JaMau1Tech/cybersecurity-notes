# Database SQL Basics

## Room Information

- **Room:** Database SQL Basics
- **Module:** Module 04 – Software Basics
- **Difficulty:** Easy
- **Status:** Completed

---

## Objective

Understand how databases organize information and learn how to write simple SQL queries to retrieve, filter, and sort data.

---

## Task 1 - Introduction

A database stores information in an organized and persistent form.

The café example demonstrated why a structured database is more useful than a paper notebook when the amount of information grows.

A single row in a café database represents one complete order.

---

## Task 2 - Databases, Tables, Rows, and Columns

### Database

A database is an organized collection of information that can be searched and managed efficiently.

### Tables

Tables store database information in a structure similar to a spreadsheet.

### Columns

Columns represent individual types of information.

Examples:

- `id`
- `drink`
- `price`
- `time`

### Rows

A row represents one complete record.

Each new café order creates a new row.

### SQL

SQL stands for Structured Query Language.

SQL is used to ask databases questions through commands called queries.

---

## Task 3 - Basic SQL Queries

Two tables were used in the lab:

```text
Orders (id, drink, price, time)
Menu (drink, price)
```

### Display All Columns

```sql
SELECT * FROM Orders;
```

- `SELECT` chooses the information to display.
- `*` represents all columns.
- `FROM` identifies the table.

### Display Specific Columns

```sql
SELECT drink, price FROM Orders;
```

This query displays only the `drink` and `price` columns.

### Filter Records

```sql
SELECT * FROM Orders WHERE drink = 'Coffee';
```

`WHERE` keeps only rows matching the specified condition.

### Sort Results in Ascending Order

```sql
SELECT * FROM Orders ORDER BY price;
```

`ORDER BY` sorts the returned records.

Ascending order is the default.

### Sort Results in Descending Order

```sql
SELECT * FROM Orders ORDER BY price DESC;
```

`DESC` reverses the sort order from highest to lowest.

### Combine Filtering and Sorting

```sql
SELECT *
FROM Orders
WHERE drink = 'Coffee'
ORDER BY price DESC;
```

This query:

1. Retrieves records from `Orders`.
2. Keeps only Coffee orders.
3. Sorts the matching records from highest to lowest price.

### Sort the Menu

```sql
SELECT *
FROM Menu
ORDER BY price DESC;
```

This query sorts the café menu from most expensive to least expensive.

---

## SQL Keywords Learned

| Keyword | Purpose |
|---|---|
| `SELECT` | Chooses the data to display |
| `FROM` | Identifies the source table |
| `WHERE` | Filters rows using a condition |
| `ORDER BY` | Sorts query results |
| `DESC` | Sorts from highest to lowest |
| `*` | Selects all columns |

---

## Security Consideration

Unauthorized database access could allow an attacker to:

- View sensitive information
- Modify legitimate records
- Delete records
- Add false records

Database permissions are required to protect the confidentiality and integrity of stored information.

---

## Lessons Learned

- Databases store structured and persistent information.
- Tables consist of rows and columns.
- One row represents one complete record.
- SQL queries retrieve information from a database.
- `SELECT` chooses displayed data.
- `FROM` identifies the table.
- `WHERE` filters records.
- `ORDER BY` sorts results.
- SQL clauses can be combined in a single query.