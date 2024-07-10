Customer Management Plugin
Username : admin
Password : customer_management

Description
The Customer Management Plugin is a comprehensive solution for managing customer information within your WordPress site. It allows administrators to add, edit, delete, and list customers.
Features
•	Add, edit, and delete customers from the admin dashboard.
•	Display a list of customers with pagination.
•	Customer signup and login forms.
•	Redirect users to a welcome page upon login.
•	Role based access on backend WordPress admin
Installation
1.	Upload the Plugin Files to Your WordPress Site:
o	Download the customer-management plugin files and extract them.
o	Upload the extracted folder to the /wp-content/plugins/ directory on your WordPress site.
o	Download the customer-theme theme files and extract them.
o	Upload the extracted folder to the /wp-content/theme/ directory on your WordPress site.
2.	Steps to Import the SQL Dump
Using phpMyAdmin 
o	Open phpMyAdmin and select your WordPress database. 
o	Click the "Import" tab.
o	Click "Choose File" and select the ` customer_management` 
o	Click "Go" to import the SQL file.

3.	Activate the Plugin:
o	Log in to your WordPress admin dashboard using XAMPP:
o	Start Apache and MySQL from the XAMPP control panel.
o	Open your web browser and go to http://localhost/ to access the XAMPP dashboard.
o	Navigate to your WordPress project folder, e.g., http://localhost/’your_project_folder’/wp-admin.
o	Log in to your WordPress admin dashboard using your admin credentials. Username : admin
Password : customer_management 
o	Go to Plugins > Installed Plugins.
o	Find the Customer Management plugin in the list and click Activate.

3. Redirect Users After Login
To ensure users are redirected to the welcome page upon login, the plugin includes a custom login redirect function.

4. Admin Dashboard Configuration
The plugin adds a Customer Management menu item in the admin dashboard. Administrators can manage customers through this interface.
5. Pagination Styling
Ensure the pagination styling in the customer list is visually appealing and consistent with your site's theme. 
Usage
Adding and Managing Customers
1.	Add New Customer:
o	Go to Customer Management > Add New in the admin dashboard.
o	Fill out the customer details and click Save.
2.	Edit Customer:
o	Go to Customer Management.
o	Click Edit next to the customer you want to edit.
o	Update the customer details and click Save.
3.	Delete Customer:
o	Go to Customer Management.
o	Click Delete next to the customer you want to delete.
o	Confirm the deletion.
Code Structure
Main Plugin File
•	customer-management.php: The main plugin file that includes the plugin class and methods for managing customers.
Admin Templates
•	admin/add_customer.php: Template for adding a new customer.
•	admin/edit_customer.php: Template for editing a customer.
•	admin/list_customers.php: Template for listing customers with pagination.
Frontend Templates
•	templates/customer-signup.php: Template for the customer signup form.
•	templates/customer-login.php: Template for the customer login form.
•	templates/customer-list.php: Template for displaying the list of customers on the frontend.
Assets
•	assets/css/style.css: CSS file for frontend styling.
•	assets/css/admin-style.css: CSS file for admin dashboard styling.

