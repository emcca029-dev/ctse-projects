# 🛒 Project 2: E-commerce API (Backend)

A robust RESTful API built to serve data and handle business logic for the E-commerce Application (located in the `project-1-ecommerce-application` branch).

## Project Goal

The primary objective was to design and implement a secure, scalable API using Python, demonstrating mastery of **database modeling, routing, and authentication.**

## Core Functionality (Endpoints)

| Route | Method | Description |
| :--- | :--- | :--- |
| `/products` | GET | Retrieve a list of all products. |
| `/products/<id>` | GET, PUT, DELETE | CRUD operations on a specific product. |
| `/auth/register` | POST | User registration. |
| `/auth/login` | POST | Generates an authentication token (JWT/Session). |
| `/cart` | GET, POST, PUT | Manages the authenticated user's shopping cart. |

## Technical Stack

* **Language:** **Python**
* **Framework:** **[Flask / Django]** - Lightweight web framework for API development.
* **Database:** **[PostgreSQL / SQLite]** - Used for persistence of user and product data.
* **ORM:** **[SQLAlchemy / Django ORM]** - Object-Relational Mapping for database interaction.
* **Authentication:** **[JWT (JSON Web Tokens)]** - Secure, stateless user authentication.

## Installation & Setup

1.  Clone this repository's branch:
    ```bash
    git clone -b project-1-e-commerce-api YOUR_REPO_URL
    cd YOUR_REPO_NAME
    ```
2.  Create and activate a virtual environment.
3.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.  Set up the database and run migrations.
5.  Start the API server:
    ```bash
    python run.py # (or appropriate command for your framework)
    ```

---
**[← Back to Backend Module Readme](https://github.com/emcca029-dev/ctse-projects/tree/main)**
