# Alumni Mobile Application (Backend)

Welcome to the backend repository for the Alumni Mobile Application! This repository contains the Django backend code responsible for managing user authentication, data storage, and API endpoints for the mobile application. The frontend development is currently in progress and will be integrated with this backend to provide a seamless user experience.

## Features

### 1. User Authentication
- **Sign Up**: New users can register with their credentials.
- **Login**: Existing users can log in securely to access their accounts.

### 2. Profile Management
- **Profile Creation**: Users can create and update their profiles with personal and professional information.
- **Profile Visibility**: Define privacy settings to control the visibility of profile details.

### 3. Alumni Networking
- **Connections**: Users can connect with other alumni to expand their network.
- **Messaging**: Private messaging functionality for communication between alumni.

### 4. Event Management
- **Event Creation**: Admins can create and manage events such as workshops, seminars, and reunions.
- **Invitations**: Send event invitations to alumni based on their preferences and interests.

### 5. Job Opportunities
- **Job Posting**: Admins can post job openings within the institution or partner organizations.
- **Job Search**: Alumni can search for job opportunities posted by others in the community.

## Setup Instructions

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/VISHVA1403/alumni-app.git
   ```


2. Install dependencies using pip:
   ```
   pip install -r requirements.txt
   ```

3. Set up the Django project and database:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a superuser for admin access:
   ```
   python manage.py createsuperuser
   ```

5. Start the development server:
   ```
   python manage.py runserver
   ```

6. Access the admin panel at `http://localhost:8000/admin` to manage users, events, and other data.

## Development

The frontend development for the Alumni Mobile Application is currently in progress. Once the frontend is developed, it will be integrated with this backend to create a fully functional mobile application.

## Contributors

- selvakumar
- sabarigirivasan
- sankarmaharajan

## Feedback and Support

If you encounter any issues, have suggestions for improvement, or need assistance, please don't hesitate to send us an email at vishva28sep@gmail.com. Your feedback is invaluable as we strive to enhance and refine the backend for the Alumni Mobile Application.
Let's empower our alumni community with seamless networking and collaboration through this backend platform! 🎓🚀
