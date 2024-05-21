
# Project Title

## Bookshelf Manager

Bookshelf Manager is a web application designed to help you organize and manage your book collection. With features like adding new books, filtering by rating and recency, viewing book details, editing book information, and deleting books, this app is a comprehensive solution for book enthusiasts.

## Table of Contents
+ Features
+ Prerequisites
+ Installation
+ Usage
+ Screenshots
+ Technologies
+ Contributing

## Features 

**Add New Books:** Easily add new books to your collection with details like title, author, ISBN, genre, rating, review, and notes.

**Filter Books:** Filter your books by rating and recency to quickly find what you’re looking for.

**View Book Details:** View detailed information about each book, including an image of the book cover.

**Edit Book Information:** Update the details of an existing book.

**Delete Books:** Remove books from your collection.
View Notes: Read personal notes associated with each book.

## Prerequisites
Before you begin, ensure you have met the following requirements:

**Node.js** (version 14.x or higher)

**npm** (version 6.x or higher)

**PostgreSQL** (version 12.x or higher)

## Installation

**Clone the repository:**

```
git clone https://github.com/yourusername/bookshelf-manager.git
cd bookshelf-manager
```

**Install dependencies:**
```
npm install
```

**Set up the database:**

Ensure you have PostgreSQL installed and running.
Create a new database and update the connection details in `index.js`:

```
const db = new pg.Client({
    user: "postgres",
    host: "localhost",
    database: "Your database name",
    password: "Your password",
    port: 5432
});
```
**Run the server:**
```
npm start
```
The server will run on `http://localhost:3000`.

## Usage

**Home Page:**

* View the list of books.
* Filter books by rating and recency.

**Add a Book:**

* Click the "Add Book" button to open the add book form.
* Fill in the book details and submit the form.

**View and Edit Book Details:**

* Click on the book image or title to view detailed information.
* Use the "Edit" button to modify book details.

**Delete a Book:**

* Click the "Delete" button to remove a book from your collection.

**View Notes:**

* Click "Read Notes" to view personal notes for a book.

## Screenshots
* Home page with book list and filters
![Home page with book list and filters](https://i.ibb.co/TLJCQWp/Home.png)

* Form to add a new book
![Form to add a new book](https://i.ibb.co/8080YyD/Add.png)


* Detailed view of a book with notes
![Detailed view of a book with notes](https://i.ibb.co/PNsJ1BD/Notes.png)

## Technologies
* Backend:
    - Express
    - body-parser
    - axios
    - pg (node-postgres)
* Frontend:
    - EJS for templating
    - date-fns for date formatting
* Database:
    - PostgreSQL

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1.Fork the repository

2.Create a new branch **(git checkout -b feature/your-feature)**

3.Commit your changes **(git commit -am 'Add some feature')**

4.Push to the branch **(git push origin feature/your-feature)**

5.Open a Pull Request
