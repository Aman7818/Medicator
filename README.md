## Medicator (Medication and Health Management Project)

This project is a Django-based web application for managing medications and health-related activities. It allows users to keep track of their medications, set reminders, and log their daily activities.

## Features

- Medication management: Add, view, and delete medications.
- Reminder management: Create reminders for medication intake.
- Activity tracking: Log daily activities with date and duration.
- Activity management: Add, view, and delete activities.

## Installation

1. Clone the repository to your local machine: git clone https://github.com/Aman7818/Medicator.git
2. Install the required dependencies: pip install -r requirements.txt
3. Apply database migrations: python manage.py migrate
4. Run the development server: python manage.py runserver

The application will be accessible at `http://localhost:8000/`.

## API Endpoints

The following API endpoints are available for interacting with the application:

- **GET** `/medications/`: Get a list of all medications.
- **GET** `/reminders/`: Get a list of all reminders.
- **POST** `/medications/create/`: Create a new medication.
- **POST** `/reminders/create/`: Create a new reminder.
- **DELETE** `/medications/delete/<medication_id>/`: Delete a medication.
- **DELETE** `/reminders/delete/<reminder_id>/`: Delete a reminder.
- **GET** `/activities/`: Get a list of all activities.
- **POST** `/activities/log/`: Log a new activity.
- **DELETE** `/activities/delete/<log_id>/`: Delete an activity log.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

## Credits

This project was developed by [Aman Yadav](https://github.com/Aman7818).

## Contact

For any inquiries or issues, please contact [yadavaman4491@gmail.com](mailto:yadavaman4491@gmail.com).

