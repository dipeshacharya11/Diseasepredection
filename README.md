Disease Prediction System
A web application for predicting various diseases using machine learning models.

Features
User authentication system
Diabetes prediction
Heart disease prediction
Kidney disease prediction
Dataset browser for each disease type
Prediction history storage in database
Technologies Used
Backend: Django, Django REST Framework
Frontend: Streamlit
Database: SQLite
Machine Learning: Scikit-learn
Setup Instructions
Prerequisites
Python 3.8+
pip
Installation
Clone the repository:

git clone <repository-url>
cd djbackendps
Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run database migrations:

python manage.py migrate
Running the Application
Start the Django backend:

python manage.py runserver
Start the Streamlit frontend:

cd streamlit_app
python -m streamlit run app.py
Access the application:

Django admin: http://localhost:8000/admin
Streamlit app: http://localhost:8501
Usage
Log in using one of the following demo accounts:

Username: admin, Password: admin123
Username: doctor, Password: doctor123
Username: nurse, Password: nurse123
Username: user, Password: password
Username: test, Password: test
Select a disease type from the sidebar menu

Browse the dataset or enter your own values

Click the "Predict" button to get a prediction

View the prediction result, risk score, and recommendation

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Dataset sources
Machine learning model references
Any other acknowledgements
