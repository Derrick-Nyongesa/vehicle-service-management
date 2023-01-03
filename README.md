# Vehicle Service Management

![developer](https://img.shields.io/badge/Developer-Derrick%20Daniel%20Nyongesa-blue)

#

A Django application that enables customers to request mechanical service for their vehicles by providing vehicle details. A mechanic can apply for a job by providing details like (skills, address, mobile etc.). The admin then assigns the vehicle to the mechanic and sends the invoice to the user.

This is a Django project was generated with [Python](https://www.python.org/) version 3.9

## Known Bugs

- The Project upload functionality may not work properly, if you encounter an error, reload the page and try again.

## Contact Information

Any query? Contact me at [nyongesaderrick@gmail.com]

## Project setup instructions

1. Pull project from github Repository.

```bash
git clone https://github.com/Derrick-Nyongesa/vehicle-service-management
```

2. Move to the folder and create a virtual environment
3. Install requirements

```bash
pip install -r requirements.txt
```

4. Create a new postgress database

5. Make migrations on postgres using django
   ```bash
   $ python manage.py makemigrations <database name>
   ```
   ```bash
   $ python3 manage.py migrate
   ```
6. Run the application
   ```bash
   $ python3 manage.py runserver
   ```
7. Open the application on your browser `http://127.0.0.1:8000/`
