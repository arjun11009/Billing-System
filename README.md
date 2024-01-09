# Billing Software

## Overview
AD Billing Software is a simple billing application developed using Python and Tkinter. This software enables users to manage customer information, add products to the cart, generate bills, save bills, and search for existing bills.

## Features
- Add customer details (Name, Mobile Number, Email)
- Add products to the cart with product details (Product ID, Product Name, Category, Price, Quantity)
- Generate and display bills
- Save bills to a local directory
- Search for existing bills by Bill Number
- View and manage customer details in a database

## Prerequisites
- Python 3.x installed
- Required Python packages: Tkinter, Pillow (PIL), mysql-connector

## Installation
1. Clone the repository: `git clone https://github.com/your-username/AD-Billing-Software.git`
2. Install the required packages: `pip install Pillow mysql-connector-python`
3. Run the application: `python billing_app.py`

## Usage
1. Launch the application using `python billing_app.py`.
2. Fill in customer details and add products to the cart.
3. Click on the "Generate Bill" button to create a bill.
4. Optionally, click on "Save Bill" to save the bill locally.
5. Use the "Search" feature to find existing bills by Bill Number.
6. Explore the "Add Data" button to insert new product information into the database.

## Database Configuration
- Ensure you have a MySQL server running locally or update the connection details in the code (`billing_app.py`).
- Modify the database details in the `mysql.connector.connect` function.

## Contributors
- Arjunsingh Kuldeepsingh Rana

## License
This project is licensed under the [MIT License](LICENSE).

Feel free to contribute, report issues, or suggest improvements!
