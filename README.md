# midterm-assignment

## Description
This project is a web application built using Node.js, Express, MongoDB, HTML, CSS, and JavaScript. The application includes functionalities such as user authentication, product management, and user account management.

## Project Structure
- **db/**
  - `db.js`: MongoDB connection setup and configuration.
  - `index.js`: Index file for database operations.

- **public/**
  - **images/**: Directory for storing image files.
  - `account.html`: User account page.
  - `add-product.html`: Page for adding a new product.
  - `add.css`: CSS file for the add product page.
  - `home.html`: Homepage of the application.
  - `login.css`: CSS file for the login page.
  - `login.html`: User login page.
  - `login.js`: JavaScript file for login functionalities.
  - `manage-products.html`: Page for managing products.
  - `products.html`: Page displaying a list of products.
  - `signup.css`: CSS file for the signup page.
  - `signup.html`: User signup page.
  - `styles.css`: General styles for the application.

- **routes/**
  - `account.js`: Routes for user account management.
  - `auth.js`: Authentication routes.
  - `products.js`: Routes for product management.

- `.env`: Environment variables file.
- `.gitignore`: Git ignore file.
- `app.js`: Main application file.
- `package-lock.json`: Automatically generated file for locking the versions of the project’s dependencies.
- `package.json`: Contains the project’s metadata and dependencies.
- `README.md`: Project description and setup instructions (you are reading it).
- `tree.txt`: Text representation of the project structure.
- `tsconfig.json`: TypeScript configuration file.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/bhanuasc/midterm-assignment.git
2. **Navigate to the project directory:**
   ```bash
    cd your-repository
3. **Install the dependencies:**
   ```bash
   npm install
   npm install express body-parser path express-session connect-mongo bcryptjs mongodb
4. **Set up your environment variables:**
   Create a .env file in the root of your project.
   Add the following environment variables to the .env file:
   ```makefile
        MONGO_URI=mongodb+srv://bhanudb:bhanudb@ecommerce.ugrcsly.mongodb.net/?retryWrites=true&w=majority
        SESSION_SECRET = e2885203e9ffd5ab3dab9f39bf1f9e8e5b3e0c47f7fa6d2abba5fb8f80e214eb8ee38e892358af8951d1e4dc67cd88ca78a956915c8d8a13639c536f835de551
5. **Run the application:**
   ```bash
   npm start
6. **Open your browser and navigate to:**
   http://localhost:4084

**Usage**
   Sign Up: Create a new user account.
   Log In: Access your account using your credentials.
   Manage Products: Add, edit, or delete products.
   User Account: View and manage your account details.

**Features**
   User authentication (login/signup)
   Product management (add, edit, delete)

