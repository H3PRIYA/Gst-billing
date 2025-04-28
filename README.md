
# GST Billing System - Python Django

Welcome to the GST Billing System project built with Python and Django! This project allows users to generate GST-compliant invoices, store customer and product data, and calculate taxes automatically. It’s designed to streamline the process of billing and tax calculation for small to medium-sized businesses.

## Project Overview

This is a GST Billing System that enables users to:
- Add and manage products and customers.
- Generate GST-compliant invoices.
- Automatically calculate taxes and totals.
- Store all customer, product, and billing data in a local database (SQLite).

## Features

- **Product Management**: Add and manage products with details such as name, price, and tax rate.
- **Customer Management**: Add and manage customer information.
- **Invoice Generation**: Generate invoices that include tax calculations (GST).
- **Database Integration**: All data is stored securely in a SQLite database.
- **User Interface**: Simple, easy-to-use interface built with Django templates.

## Project Structure

```
Gst-Billing-Python-Django/
│
├── gstbilling/              # Django project settings folder
├── gstbillingapp/           # Django app folder with models, views, templates
├── python-3.8.1-embed-amd64/ # Embedded Python folder (not needed for general use)
│
├── db (gstbillingdb.sqlite3) # SQLite database file
│
├── manage.py                # Django management script
├── requirements.txt         # Python dependencies for the project
├── README.md                # Project documentation (this file)
├── run.bat / migrate.bat     # Batch scripts to automate running/migrating
├── venv/                    # Virtual environment folder
```

## Installation

### Prerequisites
- Python 3.x
- Django 3.x or higher

### Steps to Set Up

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Gst-Billing-Python-Django.git
   cd Gst-Billing-Python-Django
   ```

2. **Set Up Virtual Environment**:
   It's recommended to use a virtual environment for managing dependencies.
   ```bash
   python -m venv venv
   ```

3. **Activate Virtual Environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install Dependencies**:
   Install all required Python packages using `requirements.txt`.
   ```bash
   pip install -r requirements.txt
   ```

5. **Migrate Database**:
   Apply migrations to set up the database schema.
   ```bash
   python manage.py migrate
   ```

6. **Run the Server**:
   Start the Django development server.
   ```bash
   python manage.py runserver
   ```
   The application will be running at `http://127.0.0.1:8000/`.

## Usage

1. Navigate to `http://127.0.0.1:8000/` in your web browser.
2. Use the interface to add products, customers, and generate GST-compliant invoices.
3. You can view and manage all your records in the database.

## Scripts

- **run.bat**: Run the Django development server.
- **migrate.bat**: Apply database migrations.

## Contributing

Feel free to fork this project and submit pull requests if you have improvements or bug fixes. Please follow the guidelines in the `CONTRIBUTING.md` (if available).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



This README file covers the basics and provides clear steps for users to set up the project, along with contact information and licensing details. You can further customize it based on your needs!
