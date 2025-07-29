# 🍁 Apricot Store - Online Shopping System

A complete e-commerce web application built with PHP and MySQL, featuring both customer-facing storefront and administrative dashboard. This project provides a full-featured online shopping experience with user authentication, product management, shopping cart functionality, and order processing.

## 🚀 Features

### Customer Features
- **User Registration & Authentication** - Secure user registration and login system
- **Product Browsing** - Browse products by categories and brands
- **Advanced Search** - Search products with filters and sorting options
- **Shopping Cart** - Add/remove items with quantity management
- **Checkout Process** - Complete order placement with payment integration
- **Order Tracking** - View order history and status
- **Newsletter Subscription** - Email newsletter signup functionality
- **Responsive Design** - Mobile-friendly interface

### Admin Features
- **Dashboard Analytics** - Sales reports and user statistics
- **Product Management** - Add, edit, and delete products with image uploads
- **Category & Brand Management** - Organize products by categories and brands
- **Order Management** - Process and track customer orders
- **User Management** - View and manage customer accounts
- **Inventory Control** - Stock management and product availability
- **Sales Reports** - Daily sales tracking and analytics

## 🛠️ Tech Stack

### Backend
- **PHP 7.2+** - Server-side scripting language
- **MySQL/MariaDB** - Database management system
- **Apache** - Web server

### Frontend
- **HTML5** - Markup language
- **CSS3** - Styling and responsive design
- **JavaScript/jQuery** - Client-side interactivity
- **Bootstrap 4** - CSS framework for responsive design
- **Font Awesome** - Icon library
- **Material Dashboard** - Admin interface components

### Libraries & Plugins
- **jQuery** - JavaScript library
- **Bootstrap Material Design** - Material design components
- **Chartist.js** - Chart visualization
- **Perfect Scrollbar** - Custom scrollbar
- **SweetAlert** - Beautiful alert dialogs
- **Slick Carousel** - Image carousel/slider

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- **XAMPP** (includes Apache, MySQL, PHP) - [Download here](https://www.apachefriends.org/download.html)
- **Web Browser** (Chrome, Firefox, Safari, Edge)
- **Text Editor** (VS Code, Sublime Text, Notepad++)

## 🔧 Installation

Follow these steps to set up the project locally:

### 1. Install XAMPP
```bash
# Download and install XAMPP from the official website
# Start Apache and MySQL services from XAMPP Control Panel
```

### 2. Clone/Download Project
```bash
# Option 1: Clone from GitHub
git clone https://github.com/shohan-cse/Online-Shopping-System-With-Server.git

# Option 2: Download ZIP and extract to htdocs folder
# Extract the project to: C:\xampp\htdocs\apricot-store\
```

### 3. Database Setup
1. Open your web browser and navigate to `http://localhost/phpmyadmin`
2. Click "New" in the left sidebar
3. Create a new database named `apricot-store`
4. Click on the newly created database
5. Go to "Import" tab
6. Browse and select the file: `database/aprcotstore.sql`
7. Click "Go" to import the database structure and sample data

### 4. Configuration
1. Open `config.php` in your text editor
2. Update database credentials if needed:
   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');  // Default XAMPP username
   define('DB_PASSWORD', '');      // Default XAMPP password is empty
   define('DB_DATABASE', 'apricot-store');
   ```

### 5. Access the Application
1. Open your web browser
2. Navigate to `http://localhost/apricot-store`
3. The application should now be running!

## 👥 Usage

### For Customers
1. **Register/Login** - Create an account or login with existing credentials
2. **Browse Products** - Navigate through categories and view product details
3. **Add to Cart** - Add desired items to shopping cart
4. **Checkout** - Complete the purchase process
5. **Track Orders** - View order history and status

### For Administrators
1. **Admin Login** - Use admin credentials:
   - Email: `admin@apricotstore.com`
   - Username: `admin`
   - Password: `123456789`
2. **Dashboard** - Access admin panel at `http://localhost/apricot-store/admin/`
3. **Manage Products** - Add, edit, or remove products
4. **Process Orders** - Handle customer orders and inventory
5. **View Reports** - Monitor sales and user statistics

## 📁 Project Structure

```
apricot-store/
├── admin/                 # Admin panel files
│   ├── admin/            # Admin dashboard
│   ├── assets/           # Admin CSS, JS, images
│   ├── login.php         # Admin login
│   └── reg.php           # Admin registration
├── css/                  # Frontend stylesheets
├── js/                   # Frontend JavaScript files
├── img/                  # Frontend images
├── product_images/       # Product images
├── database/             # Database SQL file
├── fonts/                # Font files
├── screenshot/           # Project screenshots
├── config.php           # Database configuration
├── index.php            # Main entry point
├── header.php           # Site header
├── footer.php           # Site footer
├── body.php             # Main content
├── product.php          # Product details page
├── cart.php             # Shopping cart
├── checkout.php         # Checkout process
├── login.php            # User login
├── register.php         # User registration
└── README.md            # Project documentation
```

### Key Files Description
- **`config.php`** - Database connection and user authentication logic
- **`index.php`** - Main homepage that includes header, body, and footer
- **`action.php`** - Handles form submissions and AJAX requests
- **`homeaction.php`** - Homepage-specific actions and product loading
- **`admin/admin/index.php`** - Admin dashboard main page

## 🙏 Acknowledgments

- **Bootstrap** - For the responsive framework
- **Material Dashboard** - For admin interface components
- **Font Awesome** - For beautiful icons
- **jQuery** - For enhanced JavaScript functionality

---

**Note**: This project is for educational and commercial use. Make sure to customize the branding, colors, and content according to your business needs before deploying to production.
