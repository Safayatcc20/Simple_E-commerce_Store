# Simple E-commerce Store

A full-stack e-commerce web application built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application provides a product browsing experience, shopping cart functionality, user authentication, and an admin dashboard for product management.

## Live Demo

* **Frontend:** [E-commerce Store](https://simple-e-commerce-store-bzi6.vercel.app/)
* **Backend:** [E-commerce Store](https://simple-e-commerce-store-1.onrender.com/)
* **Admin Panel:** [Product Management](https://simple-e-commerce-store-1oyn.vercel.app/addproduct)

## Features

* **Product Browsing:** Explore products through dedicated category pages, including Men, Women, and Kids.
* **Product Details:** View individual product information.
* **Shopping Cart:** Manage selected products before checkout.
* **User Authentication:** Secure user authentication using JSON Web Tokens (JWT).
* **Admin Dashboard:** Add, update, and delete products through CRUD operations.
* **Image Uploads:** Handle product image uploads using Multer.
* **Checkout:** Support the order and checkout workflow.
## Screenshots

| Home Page                     | Men's Collection            |
| ----------------------------- | --------------------------- |
| ![Home](screenshots/home.png) | ![Men](screenshots/men.png) |

| Women's Collection              | Kids' Collection              |
| ------------------------------- | ----------------------------- |
| ![Women](screenshots/women.png) | ![Kids](https://github.com/user-attachments/assets/1b2c359e-2ccb-45b7-adb7-322b39bf9c62) |

### Admin Panel

![Admin Panel](screenshots/admin.png)

## Tech Stack

**Frontend**

* React.js
* JavaScript
* HTML5 and CSS3

**Backend**

* Node.js
* Express.js
* RESTful APIs
* JSON Web Token (JWT)
* Multer

**Database**

* MongoDB

**Deployment**

* Vercel

## Project Structure

```text
Simple_E-commerce_Store/
├── frontend/
│   └── React application
├── backend/
│   └── Express API and server logic
└── README.md
```

*Note: Adjust the project structure above to match the actual folders in your repository.*

## Getting Started

### Prerequisites

* Node.js and npm
* MongoDB database
* Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Safayatcc20/Simple_E-commerce_Store.git
   cd Simple_E-commerce_Store
   ```

2. Install dependencies in the frontend and backend directories, according to their respective `package.json` files.

3. Configure the required environment variables for the database connection, authentication secret, and other application settings.

4. Start the backend and frontend using the development scripts defined in their respective `package.json` files.

## Environment Variables

Configure the required variables in your local environment. Typical examples include:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=your_backend_port
```

Use the actual variable names expected by your application. Never commit real credentials or secret keys to GitHub.

## Future Improvements

* Online payment gateway integration
* Order history and order management
* Enhanced product search and filtering
* Improved validation and error handling

## Author

**Md. Safayat Bin Nasir**

* [GitHub](https://github.com/Safayatcc20)
* [LinkedIn](https://www.linkedin.com/in/md-safayat-bin-nasir/)
