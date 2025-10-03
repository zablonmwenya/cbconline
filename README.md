CBC Online

CBC Online is a PHP-based e-commerce web application that provides customers with a smooth shopping experience and an admin panel to manage products, categories, and orders.

Features
Customer Side

User registration and login

Product browsing and category filtering

Shopping cart and checkout process

Profile management (update details, change password)

Order tracking

Contact and FAQ pages

Admin Side

Secure login for administrators

Manage products and categories

Manage customer accounts and orders

Update country/region settings

Project Structure
cbconline/

│── about.php

│── index.php

│── login.php

│── registration.php

│── cart.php

│── checkout.php

│── customer-*.php

│── product-*.php

│── ...

│── admin/

│   ├── country-add.php

│   ├── country-delete.php

│   └── ...

└── assets/ (CSS, JS, Images - if available)

Requirements

Web Server: Apache/Nginx with PHP support

PHP: Version 7.4+ recommended

Database: MySQL/MariaDB

Browser: Chrome/Firefox/Edge

Installation

Clone the repository:

git clone https://github.com/Zablonmwenya/cbconline.git


Move the project into your server directory (e.g., htdocs for XAMPP):

mv cbconline /path-to-xampp/htdocs/


Import the database:

Look for a .sql file in the project .

Import it into MySQL using phpMyAdmin or command line.

Update database configuration:

Open the config file .

Set your database host, username, password, and database name.

Start your server (XAMPP, WAMP, or LAMP).

Visit http://localhost/cbconline in your browser.

Admin Login

The admin login credentials are provided in the file:

admin Login details.txt

Contributing

Feel free to fork this repository, submit issues, and send pull requests.

License

This project is for educational purposes. You may modify and use it as needed.
