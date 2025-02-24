#create a virtual environement
python -m venv venv  
# Activate the virtual environment
venv\Scripts\activate
pip install -r requirements.txt
python manage.py runserver
