# Electricks Online Shop System

Electricks Online Shop System is an eCommerce website designed to provide customers with an online platform to browse and purchase products from shops or stores. This system includes functionalities for both customers and administrators, making it easy to manage products, suppliers, and orders. The project was presented at Southern Luzon State University - Lucban and developed using PHP/Mysqli, MySQL Database, HTML, CSS, Javascript (jQuery and Ajax), and Bootstrap.

## Features

### Admin Side
- **Manage Suppliers:**
  - Add, edit, and delete supplier information.
  - Keep track of suppliers and their contact details.
- **Manage Products:**
  - Add new products with details such as name, description, price, and images.
  - Edit and update product information.
  - Delete products from the inventory.
- **Manage Stocks:**
  - Monitor and update stock levels for each product.
  - Receive alerts for low stock levels.
- **Manage Users:**
  - Add, edit, and delete user accounts.
  - Assign roles and permissions to different users.
- **Manage System Administrator:**
  - Admin-specific functionalities to oversee the entire system.

### Customer Side
- **Login/Logout:**
  - Secure login and logout functionalities.
  - User registration for new customers.
- **Browse Products:**
  - View a catalog of available products.
  - Filter and sort products based on categories and attributes.
- **Search Product:**
  - Search for products using keywords.
  - Advanced search options for precise results.
- **Add Product to Shopping Cart:**
  - Add desired products to a virtual shopping cart.
  - Update quantities or remove items from the cart.
- **Manage Shopping Cart:**
  - Review items in the shopping cart.
  - Proceed to checkout or continue shopping.
- **Place Order:**
  - Complete the purchase by placing an order.
  - Receive order confirmation and details.

## How to Run

### Requirements
- A local web server such as XAMPP or WAMP

### Installation/Setup
1. **Download and Install a Local Web Server:**
    - Download and install [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](http://www.wampserver.com/en/).
    - Ensure that both Apache and MySQL services are running.

2. **Download Source Code:**
    - Download the provided source code zip file from the repository.

3. **Start Apache and MySQL:**
    - Open your XAMPP/WAMP's Control Panel.
    - Start the "Apache" and "MySQL" services.

4. **Extract the Source Code:**
    - Extract the downloaded source code zip file to a convenient location on your computer.

5. **Move the Extracted Source Code:**
    - If using XAMPP:
      - Copy the extracted source code folder.
      - Paste it into the `htdocs` directory of XAMPP (usually located at `C:\xampp\htdocs`).
    - If using WAMP:
      - Copy the extracted source code folder.
      - Paste it into the `www` directory of WAMP (usually located at `C:\wamp\www`).

6. **Create Database:**
    - Open your web browser and navigate to PHPMyAdmin (usually located at http://localhost/phpmyadmin).
    - Create a new database named `electricks`.
    - Import the provided SQL file (`electricks.sql`) located inside the extracted source code folder:
      - Click on the `electricks` database.
      - Select the "Import" tab.
      - Click "Choose File" and select the `electricks.sql` file.
      - Click "Go" to import the database schema and data.


8. **Run the Application:**
    - Open your web browser and navigate to the Electricks Online Shop System:
      - Customer Side: http://localhost/Electricks/Electricks-shop/
      - Admin Side: http://localhost/Electricks/Electricks-shop/pages/admin_login_page.php

## Usage

### Admin Side
1. **Login:**
   - Access the admin login page: http://localhost/Electricks/Electricks-shop/pages/admin_login_page.php
   - Use the default admin credentials provided or create a new admin user through the database.

2. **Dashboard:**
   - Once logged in, you will be redirected to the admin dashboard.
   - From the dashboard, you can manage suppliers, products, stocks, users, and system administrators.

3. **Managing Suppliers:**
   - Navigate to the "Suppliers" section.
   - Add new suppliers or edit existing ones by filling out the required details.

4. **Managing Products:**
   - Navigate to the "Products" section.
   - Add new products with details such as name, description, price, and images.
   - Edit or delete existing products as needed.

5. **Managing Stocks:**
   - Navigate to the "Stocks" section.
   - Update stock levels for each product.
   - Receive alerts for low stock levels.

6. **Managing Users:**
   - Navigate to the "Users" section.
   - Add, edit, or delete user accounts.
   - Assign roles and permissions to different users.

### Customer Side
1. **Registration and Login:**
   - New users can register by filling out the registration form.
   - Existing users can log in using their credentials.

2. **Browsing Products:**
   - Users can browse through the product catalog.
   - Filter and sort products based on categories and attributes.

3. **Searching Products:**
   - Use the search bar to find products using keywords.
   - Advanced search options are available for more precise results.

4. **Shopping Cart:**
   - Add desired products to the shopping cart.
   - Update quantities or remove items from the cart.
   - Review items before proceeding to checkout.

5. **Placing Orders:**
   - Complete the purchase by placing an order.
   - Receive order confirmation and details via email.




