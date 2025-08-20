# U-of-U-Parking-Application

A website that links to a database containing information on University parking permits, lots, spaces, administrators, and students.  
This project was created for a Web-Based Applications course at the University of Utah.

## Features

- Two user groups: students and administrators
- Secure admin login and session management
- Management of parking permits and lots
- Admin dashboard for university staff

## Getting Started

1. Open the project folder `Parking for U - Web App` in a code editor (e.g., VS Code).
2. CD into the 'parking_project' folder to access 'manage.py':
   ```bash
   cd parking_project
   ```
4. Run and debug the `manage.py` file using Django:
   ```bash
   python manage.py runserver
   ```
5. Visit the development server link in your browser (shown in the terminal).
6. Use the credentials in **Web App Login Info** to log in and explore the app.

## Notes

- Data is for testing/demonstration and not real-time.
- Only administrators can access certain features (configured via Django admin).
- Student accounts are form entries, not Django admin users.
- Only the admin account appears in the Django admin interface.

## License

_No license yet_

## Author

[Carter Jones](https://github.com/carterjones25)
