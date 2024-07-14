# Django Razorpay Payment Integration
<h3>Description</h3>
This project demonstrates how to integrate Razorpay payment gateway with a Django application. It includes setting up payment processing for a fictional "Buy Me a Coffee" scenario, where users can donate 500 INR.

# Features
Payment Form: Provides a form for users to enter their name and make a donation.<br>
Razorpay Integration: Utilizes Razorpay's API for handling payments securely.<br>
Success Page: Displays a confirmation message after successful payment<br>

# Technologies Used
Django<br>
HTML/CSS<br>
Bootstrap<br>
Razorpay API<br>

# Installation
<h3>Clone the Repository</h3>
git clone https://github.com/Sanketarali/Django-Razorpay-Payment.git<br>
cd Django-Razorpay-Payment<br>

<h3>Install Dependencies</h3>
pip install -r requirements.txt

# Set Up Razorpay Credentials
In your Django project settings (settings.py), configure your Razorpay test API credentials:
<h4>RAZORPAY_KEY_ID = 'your_razorpay_key_id'</h4>
<h4>RAZORPAY_KEY_SECRET = 'your_razorpay_key_secret'</h4>

# Run Migrations
python manage.py migrate

# Start the Development Server
python manage.py runserver

# Usage
Navigate to http://127.0.0.1:8000/ in your web browser.<br>
Fill in your name and proceed with the payment using Razorpay's secure checkout.<br>
Upon successful payment, you will be redirected to a success page confirming your donation.<br>


