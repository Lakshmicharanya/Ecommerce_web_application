# ShopZone – E-commerce Web Application

## Project Overview
ShopZone is a web-based e-commerce application developed using Python Flask. It allows users to browse products, manage their accounts, and purchase products online. It also provides an admin dashboard to manage products, categories, users, and orders.

## Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Python, Flask
- **Database:** PostgreSQL
- **Tools:** VS Code, Git, GitHub

## Features

### User Module
- User registration and login
- Browse available products
- View product details
- Manage user profile
- Add products to cart
- Place orders
- View order details

### Admin Module
- Admin login
- Admin dashboard
- Manage products (Add, Edit, Delete)
- Manage product categories
- View and manage users
- Manage customer orders

## Project Structure

```text
Ecommerce/
│
├── app.py
├── createTables.py
├── AuthQueries.py
├── AdminQueries.py
├── templates/
│   ├── admin/
│   ├── user/
│   └── ...
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│       └── products/
│
├── .env
├── .gitignore
└── README.md
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Lakshmicharanya/Ecommerce_web_application.git
```

### 2. Navigate to the Project Folder

```bash
cd Ecommerce_web_application
```

### 3. Create a Virtual Environment

```bash
python -m venv e_env
```

### 4. Activate Virtual Environment

**Windows:**

```bash
e_env\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file and configure your database credentials and other required application settings.

### 7. Run the Application

```bash
python app.py
```

### 8. Open in Browser

```text
http://127.0.0.1:5000/
```

## Database

The application uses PostgreSQL for storing application data.

Database configuration should be provided through environment variables in the `.env` file.

## Future Enhancements

- Online payment gateway integration
- Product reviews and ratings
- Wishlist functionality
- Improved product search and filtering
- Order tracking

## Author

**Lakshmi Charanya**

GitHub: https://github.com/Lakshmicharanya

---

*Developed as a Python Flask E-commerce Web Application project.*
