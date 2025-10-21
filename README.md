# 📚 Book Inventory System
A simple but full-featured web application for managing a book inventory, built with Spring Boot and Thymeleaf. This project serves as a practical example of building a CRUD (Create, Read, Update, Delete) application using modern Java technologies.

## ✨ Features
📖 Add Book: A user-friendly form to add new books to the inventory with details like title, author, price, and quantity.

🔍 Search Book: Search for a specific book in the database using its unique Book ID.

🗑️ Delete Book: Remove unwanted books from the inventory by providing the Book ID.

ℹ️ Book Info & Stats: A dashboard that displays key statistics like the total number of books, the combined price of all books, and the total number of unique authors. It also lists all books currently in the inventory.

## 🛠️ Tech Stack
Backend: Java, Spring Boot, Spring MVC

Database: MongoDB

Frontend & Template Engine: Thymeleaf, HTML, CSS, Bootstrap 5

Build Tool: Gradle

Utilities: Lombok

## 🚀 Getting Started
Follow these instructions to get a local copy of the project up and running.

### Prerequisites
Make sure you have the following software installed on your system:

Java JDK 17 or higher

MongoDB Community Server (running in the background)

An IDE like Spring Tool Suite (STS) or IntelliJ IDEA

### Installation & Setup
Clone the repository

git clone https://github.com/your-username/book-inventory-system.git

Open the project in your IDE

Open your IDE and import the cloned project as a Gradle project.

### Configure the Database

Navigate to src/main/resources/application.properties.

Ensure the MongoDB connection string is correctly configured:

spring.data.mongodb.uri=mongodb://localhost:27017/bookinventory

## Run the Application

Find the BookApplication.java file in the src/main/java/com/book/inventory/app package.

Right-click on the file and select "Run As" > "Java Application".

The server will start on port 8080.


💻 Usage
Once the application is running, open your web browser and navigate to: http://localhost:8080

You can use the navigation bar to access all the features like adding, searching, and deleting books.


## 📸 Screenshots
![Home Page] (https://github.com/Manwatkar27/Book-Inventory-System/blob/main/Screenshot/Home%20Page.png?raw=true)

![AddBook Page] (https://github.com/Manwatkar27/Book-Inventory-System/blob/main/Screenshot/AddBook%20Page.png?raw=true)

![SearchBook Page] (https://github.com/Manwatkar27/Book-Inventory-System/blob/main/Screenshot/SearchBook%20Page.png?raw=true)

![DeleteBook Page] (https://github.com/Manwatkar27/Book-Inventory-System/blob/main/Screenshot/DeleteBook%20Page.png?raw=true)



## 👤 Author
Aman Manwatkar
