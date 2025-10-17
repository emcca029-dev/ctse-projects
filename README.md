# 🛒 Project 3: Full-Stack E-commerce Application (Frontend)

This is the frontend client for a multi-page e-commerce platform, built as a core project in the Coding Temple Full-Stack curriculum.

## Project Overview

This application focuses on delivering a smooth, responsive shopping experience. It interacts asynchronously with the custom-built **E-commerce API** (located in the `project-1-e-commerce-api` branch) to manage products, user accounts, and cart state.

## Key Features

* **Product Catalog:** Displays products fetched from the backend API with filtering and search capabilities.
* **User Authentication:** Handles sign-up and log-in, managing user state via tokens/session.
* **Shopping Cart:** Allows users to add, update quantities, and remove items before checkout.
* **Responsive Design:** Optimized for seamless viewing and interaction across desktop, tablet, and mobile devices.

## Technical Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Framework** | **React** | Component-based UI architecture and state management. |
| **Language** | **JavaScript (ES6+)** | Core application logic and DOM manipulation. |
| **Styling** | **[CSS/Styled-Components/Tailwind]** | Modular, maintainable styling and UI theming. |
| **API Integration** | **Axios / Fetch** | Asynchronous requests (GET, POST, PUT, DELETE) to the backend. |
| **Routing** | **React Router DOM** | Client-side navigation without full page reloads. |

## Installation & Setup

1.  Clone this repository's branch:
    ```bash
    git clone -b project-1-ecommerce-application YOUR_REPO_URL
    cd YOUR_REPO_NAME
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Ensure the E-commerce API is running locally (refer to its README).
4.  Run the application:
    ```bash
    npm start
    ```

---
**[← Back to Frontend Module Readme](https://github.com/emcca029-dev/ctse-projects/tree/main)**