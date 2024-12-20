# Basic E-Commerce Website

This project is a basic e-commerce website using HTML, CSS, JavaScript for the frontend, and PHP with MySQL (phpMyAdmin) for the backend. It features user authentication and basic product listings, allowing users to browse products and log in securely.

---

## Features
- **Frontend**: Product catalog with responsive design.
- **Backend**: User registration/login and admin panel for managing products.
- **Database**: Stores user details and product information.

---

## Installation
1. Import the provided SQL file into phpMyAdmin to set up the database.
2. Update `db_config.php` with your database credentials.
3. Place files in the server's root directory and access via `http://localhost/{project-folder}`.

---

## File Structure
Project Root
├── index.html           # Homepage displaying the product catalog
├── styles.css           # CSS for styling the frontend
├── scripts.js           # JavaScript for frontend interactivity
├── login.php            # Login page for user authentication
├── register.php         # Registration page for new users
├── db_config.php        # Database connection configuration file
├── admin/               # (Optional) Admin functionality folder
│   ├── add_product.php  # Page to add products
│   ├── edit_product.php # Page to edit existing products
│   ├── delete_product.php # Page to delete products
└── assets/              # Directory for images, icons, or other media
    ├── images/          # Product images or site graphics
    └── icons/           # Icons for UI design

---

## Future Enhancements
- Add payment integration.
- Implement order management.
- Enhance security and usability.

---

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP, MySQL
- **Server**: XAMPP/WAMP

---

## License
This project is open-source under the MIT License.
