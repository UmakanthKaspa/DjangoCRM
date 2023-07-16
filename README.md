
# My First Django Project: Lead Management Playground 🌱

Welcome to **My First Django Project: Lead Management Playground**! 🚀 This project is a small and tiny playground I've built to explore and learn Django.

## Notable Features ✨
- **User Registration and Login**: Create your account and get ready for a personalized experience. It's like having your own secret portal to the Django world! 🚪🔐
- **Lead Management**: Easily add, view, update, and delete lead records with just a few clicks. Managing leads has never been more fun and efficient! 💼✍️

## Technologies and Tools Utilized 💻
To bring this project to life, I've utilized an incredible lineup of technologies and tools:

- **Django**: The superheroic web framework that forms the sturdy backbone of this project. It will make your development process a breeze! 💪🕸️
- **HTML, CSS, and Bootstrap**: These mighty trio powers have been harnessed to create stunning and responsive user interfaces. Get ready for some eye candy! 🎨🌟
- **MySQL**: The database management system used to store and manage your data efficiently. Say hello to seamless data management! 💾🗄️
- **Git and GitHub**: With the power of version control and collaboration at your fingertips, you can fearlessly experiment and work with others. Let the code sharing begin! 🤝🚀

## Getting Started 🌟

1. Clone the repository:
   ```
   git clone https://github.com/UmakanthKaspa/DjangoCRM.git
   ```

2. (Optional) Set up a virtual environment (recommended):
   - Create a virtual environment:
     ```
     python3 -m venv env
     ```
   - Activate the virtual environment:
     - For macOS and Linux:
       ```
       source env/bin/activate
       ```
     - For Windows:
       ```
       .\env\Scripts\activate
       ```

3. Install Django and other dependencies:
   ```
   pip3 install django mysql mysql-connector
   ```

4. Navigate to the project directory:
   ```
   cd DjangoCRM/DjangoCRM
   ```

5. Update the database configuration in `settings.py`:
   - Locate the `DATABASES` dictionary in the `settings.py` file.
   - Update the `'USER'` and `'PASSWORD'` fields with your MySQL database credentials.
   - Save the changes.

6. (Optional) Create the MySQL database:
   - Open your MySQL client (e.g., MySQL Workbench, phpMyAdmin) and log in with your credentials.
   - Create a new database named `DjangoCRMdb`.
   - Update the `settings.py` file with your database name.

7. Apply database migrations:
   ```
   python3 manage.py makemigrations
   python3 manage.py migrate
   ```

8. Create a superuser (admin):
   ```
   python3 manage.py createsuperuser
   ```

9. Start the development server:
   ```
   python3 manage.py runserver
   ```

10. Open your preferred browser and visit `http://localhost:8000`

## Screenshots 📷

![Screenshot 1](https://github.com/UmakanthKaspa/DjangoCRM/assets/124495588/ed581876-fc52-4ccc-8195-7df8384efbbd)
![Screenshot 2](https://github.com/UmakanthKaspa/DjangoCRM/assets/124495588/4966904d-5a7c-4fc8-a94f-55250a96e148)

