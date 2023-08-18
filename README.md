# BackendDeveloperCapstone - Little Lemon Restaurant Back-end API

Welcome to the Little Lemon Restaurant Back-end API project! This project showcases the development of a powerful API for managing table bookings and related data for the Little Lemon restaurant. Built using Django and the Django REST Framework, this API provides seamless integration with a MySQL database, allowing the restaurant to efficiently handle its reservation system.

## Features

- **Table Booking:** Users can make, view, update, and cancel table reservations.
- **Menu Management:** APIs for managing menus, including menu items and courses.
- **User Authentication:** Secure user registration and authentication system.
- **Data Persistence:** Integration with a MySQL database for robust data storage.
- **Interactive Documentation:** Utilize the built-in Swagger UI to interact with the API.

## How to Run

Follow these steps to set up and run the Little Lemon Back-end API on your local machine:

1. **Clone the Repository:** Clone this repository to your local machine using `git clone https://github.com/your-username/little-lemon-backend.git`.

2. **Navigate to the Project Directory:** Open a terminal and navigate to the project directory using `cd little-lemon-backend`.

3. **Create a Virtual Environment (Optional):** It's recommended to create a virtual environment for the project using `python -m venv venv`. Activate the virtual environment with `source venv/bin/activate` (Unix-based systems) or `venv\Scripts\activate` (Windows).

4. **Install Dependencies:** Install the required dependencies by running `pip install -r requirements.txt`.

5. **Configure the Database:** Open the `settings.py` file in the `littlelemon` directory. Update the database settings with your MySQL database credentials.

6. **Run Migrations:** Apply the database migrations using `python manage.py migrate`.

7. **Start the Development Server:** Launch the development server with `python manage.py runserver`.

8. **Access the API:** Open your web browser and go to `http://localhost:8000/swagger/` to access the interactive Swagger documentation.

## API Endpoints

- `/api/bookings/`: Handle table reservations.
- `/api/menus/`: Manage menus and menu items.
- `/api/auth/register/`: Register a new user.
- `/api/auth/login/`: Log in and obtain an authentication token.

## Additional Information

For additional information on using the Little Lemon Back-end API, refer to the provided documentation. The API documentation, available at `http://localhost:8000/swagger/`, offers detailed insights into available endpoints, request and response formats, and authentication requirements.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Thank you for exploring the Little Lemon Restaurant Back-end API project! We hope this API enhances your understanding of Django, RESTful APIs, and database integration. If you have any questions or feedback, please feel free to reach out to our team. Enjoy exploring and experimenting with the API!
