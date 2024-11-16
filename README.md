Features
User Roles:

Owner: Can add administrators and manage the system. (login Owner password:12345)
Admin: Can manage books and files.
User: Can browse books, add them to the cart, and download files.
Database Models:

User: Stores user credentials and roles.
Book: Contains book details such as title, author, price, description, and category.
CartItem: Manages books added to the cart by users.
Functionality:

Authentication:
Login and registration for users.
Owner and admin-specific functionalities.
Books:
Add, delete, and manage books via the admin panel.
View books by category.
Cart:
Add books to the cart and calculate total price.
File Management:
Upload and download files.
APIs:
Add books via API.
Get book details and listings in JSON format.
Upload and download files through API endpoints.
Basic authentication for API access.
Error Handling:

Make sure the following dependencies are installed on your system:

Python: Version 3.7 or above
Flask: Web framework
SQLite: For database management
Required Python Libraries:
Flask
Flask-SQLAlchemy
Flask-Login
Flask-Migrate
Werkzeug
requests
Proper error messages for unauthorized actions or invalid inputs.
UI:

Clean and responsive design for ease of navigation.
