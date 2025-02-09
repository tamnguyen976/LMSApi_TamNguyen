# LMS API - Library Management System

This project is a simple Library Management System (LMS) API built using ASP.NET Core Minimal API. It demonstrates the following features:

- **Authentication:** Staff registration and login.
- **Dashboard:** An overview of books, readers, and borrowings.
- **Books Management:** CRUD operations (Create, Read, Update, Delete) for books.
- **Reader Management:** CRUD operations for readers.
- **Borrowing Management:** CRUD operations for borrowing records.
- **Reports:** Generate reports based on criteria like borrowing dates, book types, or reader demographics.
- **Overdue:** Calculate overdue charges for borrowings.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Testing the API](#testing-the-api)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Authentication:**  
  - **POST** `/register` – Register a new user.  
  - **POST** `/login` – Login for staff.
  
- **Dashboard:**  
  - **GET** `/dashboard` – View an overview of all books, readers, and borrowings.

- **Books Management:**  
  - **GET** `/books` – Retrieve all books.  
  - **GET** `/books/{id}` – Retrieve details of a specific book by its ID.  
  - **POST** `/books` – Add a new book.  
  - **PUT** `/books/{id}` – Update a book's details.  
  - **DELETE** `/books/{id}` – Delete a book.

- **Reader Management:**  
  - **GET** `/readers` – Retrieve all readers.  
  - **GET** `/readers/{id}` – Retrieve details of a specific reader by its ID.  
  - **POST** `/readers` – Add a new reader.  
  - **PUT** `/readers/{id}` – Update a reader's details.  
  - **DELETE** `/readers/{id}` – Delete a reader.

- **Borrowing Management:**  
  - **GET** `/borrowings` – Retrieve all borrowing records.  
  - **GET** `/borrowings/{id}` – Retrieve details of a specific borrowing record by its ID.  
  - **POST** `/borrowings` – Create a new borrowing record.  
  - **PUT** `/borrowings/{id}` – Update a borrowing record.  
  - **DELETE** `/borrowings/{id}` – Delete a borrowing record.

- **Additional Endpoints:**  
  - **GET** `/reports` – Generate reports based on various criteria.  
  - **GET** `/overdue` – Calculate overdue charges.

## Getting Started

### Prerequisites

- [.NET 6 SDK or later](https://dotnet.microsoft.com/download)
- [Git](https://git-scm.com/downloads)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or Visual Studio Code (optional)

### Running the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/tamnguyen976/LMSApi_TamNguyen.git
