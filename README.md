# Bikes Website 

This is a Django-based web application for managing bike-related operations such as user authentication and bike listings.

# 📌 Features

User Authentication (Login/Logout)

Bike Listings

Admin Panel for Management

Static and Media File Handling



# Home Page 
![Screenshot (187)](https://github.com/user-attachments/assets/b556539d-a82f-45d4-b220-fc5a327d2cc3)

# Login Page
![Screenshot (188)](https://github.com/user-attachments/assets/1b1e93e3-4a52-4037-9f14-51770b9bdbdf)


# 🛠 Installation

1️⃣ Clone the Repository

git clone https://github.com/gaduputimahesh/YOUR_REPO.git
cd bikes-project

2️⃣ Create a Virtual Environment & Install Dependencies

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

3️⃣ Apply Migrations & Run the Server

python manage.py migrate
python manage.py runserver

4️⃣ Access the App

Open your browser and go to:

http://127.0.0.1:8000/


#  Environment Variables

Create a .env file (if required) and add secret keys, database credentials, etc.

#  Static & Media Files

python manage.py collectstatic

# Deployment 

For deployment, use services like Heroku, AWS, or DigitalOcean.
# Thank You
