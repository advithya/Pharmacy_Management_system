# Pharmacy_Management_system

### Database Structure

The database is defined in [pharmacy.sql] and includes several tables to manage different entities:


- **admin**: Stores admin credentials.
- **cashier**: Stores cashier details.
- **customer**: Stores customer information.
- **drug**: Stores drug details.
- **drugtype**: Stores types of drugs.
- **ids**: Stores user and invoice IDs.
- **invoice**: Stores invoice details.
- **invoice_details**: Stores details of each invoice.
- **manager**: Stores manager details.
- **paymenttypes**: Stores different payment methods.
- **pharmacist**: Stores pharmacist details.
- **prescription**: Stores prescription details.
- **prescription_details**: Stores details of each prescription.
- **receipts**: Stores receipt details.
- **sales**: Stores sales records.
- **stock**: Stores stock details.
- **tempo** and **tempprescri**: Temporary tables for prescriptions.

 ## Installation
Follow these steps to install the application.

- Clone the Repository
git clone https://github.com/advithya/Pharmacy_Management_system.git

- Go to project directory
cd Pharmacy-management-system

- Install packages with composer
composer install

- Install npm packages with
npm install; npm run dev


- Create your database

Rename .env.example to .env Or copy it and paste at project root directory and name the file .env.You can also use this command.

cp .env.example ./.env

- Generate app key with this command
php artisan key:generate

- Set database connection to your database in the .env file.
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=doccure
DB_USERNAME=root
DB_PASSWORD=

- Import full database sql file in the database folder, or run migrations Use this command to run migrations
php artisan migrate --seed

- Start the local server and browser to your app. This command will start the development server
php artisan serve

- Open the address in the terminal in your browser.Usually address is usually like this:
http://127.0.0.1:8000

- Enjoy and make sure to star the repo :).Report bugs,features and also send your pull requests.
admin login credentials
 email: admin@admin.com
 password: admin
Theme: https://themeforest.net/item/doccure-doctor-appointment-booking-system-bootstrap-angular-template/28201296


### PHP Files

The PHP files handle various functionalities of the system:

- **stock.php**: Manages stock, including viewing, adding, and updating stock levels.
  
- 
- **view_prescription.php**: Displays prescription details.
- **stock_pharmacist.php**: Allows pharmacists to manage stock.
- 
- **update_manager.php**: Updates manager details.
- 
- **update_cashier.php**: Updates cashier details.

- **update_pharmacist.php**: Updates pharmacist details.

- **add.php**: Handles adding new stock items.

## Features
1  Products
2  Product categories
3  Purchases
4  Sales
5  Supplier
6  Reports
7  Access Control (roles and permissions)
8  Users
9  User Profile
10 Settings (Application settings)
11 Application backup
12 Dashboard
Stock notifications
