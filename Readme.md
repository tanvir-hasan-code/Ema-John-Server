# Ema-John E-commerce Server API

## 🌐 Live Client Application
This server powers the following client-side application:
[https://ema-john-test-poject.netlify.app/](https://ema-john-test-poject.netlify.app/)

---

## 📄 Description
This is the server-side API for the Ema-John E-commerce project. It's built with Node.js and Express.js and is responsible for handling all product data and backend logic. The API connects to a MongoDB database to store and retrieve product information, which is then served to the client-side application.

---

## ✨ Features & API Endpoints
This server provides the following key functionalities:
-   **Product Management:** Manages product data, including retrieving and serving product lists.
-   **Product Pagination:** Provides paginated product lists to improve client-side performance.
-   **Dynamic Shopping Cart:** Serves product data for items stored in the user's shopping cart.
-   **Authentication:** Utilizes JSON Web Tokens (JWT) for secure user authentication.

Here are the main API endpoints:
-   `GET /products`: Fetches a list of products with support for pagination (`?page=...&size=...`).
-   `GET /productCount`: Returns the total number of products in the database.
-   `POST /productsByIds`: Retrieves a list of products based on their IDs (sent in the request body).

---

## 🛠️ Technologies Used
-   **Backend:** Node.js, Express.js
-   **Database:** MongoDB
-   **API Utilities:** CORS, JSON Web Tokens (JWT)
-   **Environment Variables:** `dotenv`

---

## 💻 Getting Started

### Prerequisites
-   Node.js (v14 or higher)
-   MongoDB Atlas account or a local MongoDB installation

### Installation
1.  Clone the repository to your local machine:
    `git clone <repository-url-here>`
2.  Navigate to the project directory:
    `cd ema-john-server`
3.  Install the dependencies:
    `npm install`

### Environment Variables
Create a `.env` file in the root directory of the project and add the following variables:
**Note:** Replace `<Your-MongoDB-Connection-String>` with your actual MongoDB connection string.

### Running the Server
To start the server locally, use one of the following commands:
-   **Development mode (with `nodemon`):**
    `npm run dev`
-   **Production mode:**
    `npm start`

The server should now be running on `http://localhost:5000`.

---

## 🤝 Author
Authored by **Tanvir Hasan**

**Note:** Please replace `[repository-url-here]` with your actual repository URL.