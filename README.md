Installation

git clone https://github.com/NasirUdd-in/miniecommerce.git
cd yourproject

2. Set up a virtual environment

python -m venv env

# On Windows use `env\Scripts\activate`

3. Install dependencies

pip install -r requirements.txt

4. Set up the database

python manage.py migrate

5. Create a superuser

python manage.py createsuperuser

6. Run the development server

python manage.py runserver

The project should now be accessible at http://127.0.0.1:8000/.

Usage
Access the admin panel at http://127.0.0.1:8000/admin with the superuser credentials you created.
