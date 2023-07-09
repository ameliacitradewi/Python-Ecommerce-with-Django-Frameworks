# Django eCommerce with Python

This project is an eCommerce website built with Django, utilizing a Bootstrap template for the front-end design. It includes features such as user authentication (login/logout), product details, pagination, and a checkout process with PayPal Sandbox for testing purposes.

![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/1.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/2.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/3.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/5.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/6.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/9.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/7.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/4.png)
![alt text](https://github.com/ameliacitradewi/Python-Ecommerce-with-Django-Frameworks/blob/main/Documentation/8.png)

## Prerequisites

Before running this project, make sure you have the following prerequisites installed on your machine:

- Python (version 3.6 or higher)
- Django (version 3.2 or higher)
- PayPal Developer Account (for PayPal Sandbox testing)
- Bootstrap template (e.g., obtained from https://getbootstrap.com/)

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/django-ecommerce.git
```

2. Navigate to the project directory:

```
cd django-ecommerce
```

3. Create and activate a virtual environment (recommended):

```
python3 -m venv env
source env/bin/activate  # for macOS/Linux
env\Scripts\activate  # for Windows
```

4. Install the required dependencies:

```
pip install -r requirements.txt
```

5. Set up the database:

```
python manage.py migrate
```

6. Create a superuser (admin account):

```
python manage.py createsuperuser
```

7. Run the development server:

```
python manage.py runserver
```

8. Access the application in your web browser:

```
http://localhost:8000/
```

## Configuration

Before using the PayPal Sandbox for checkout, you need to configure your PayPal credentials:

1. Create a PayPal Developer Account at https://developer.paypal.com/.
2. Obtain your Sandbox API credentials (Client ID and Secret).
3. In the Django project settings (`settings.py`), update the `PAYPAL_CLIENT_ID` and `PAYPAL_CLIENT_SECRET` variables with your credentials.

## Usage

Once the project is up and running, you can perform the following actions:

- Visit the home page to browse the available products.
- Click on a product to view its details.
- Register a new user account or login with an existing account.
- Add products to the cart and proceed to the checkout page.
- On the checkout page, select PayPal as the payment method.
- Complete the payment using the PayPal Sandbox (you can use test PayPal accounts).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request or open an issue on the GitHub repository.

## Acknowledgments

- Bootstrap template and Fashe template from ColorLib used for the front-end design
- Django web framework: [Django](https://www.djangoproject.com/)
- PayPal integration: [PayPal Developer](https://developer.paypal.com/)
