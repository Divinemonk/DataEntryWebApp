# Data Entry WebApp

<div align="center">
  <img src="https://github.com/Divinemonk/dataentry_webapp/assets/82360546/2efe0eb3-1e44-4711-9a4a-f718173e05a1" alt="DataEntry_WebApp" align="left">
</div>

Data Entry Web App is a sleek and user-friendly web application designed to streamline data entry and management processes. Built with Flask, a powerful Python web framework, this application offers a hassle-free solution for efficient data handling, making it the perfect tool for small to medium-sized data-driven projects.

## Features

- **Effortless Data Entry**: With its clean and intuitive interface, DataEntry_WebApp ensures a smooth data entry experience. Users can quickly input information like names, genders, emails, addresses, and roles. The application includes robust validation checks, ensuring data integrity and completeness.

- **Secure Data Storage and Retrieval**: All entered data is securely stored in an Excel file (.xlsx) on the server, powered by the reliable openpyxl library. This guarantees easy data storage and retrieval, giving you peace of mind knowing your data is safe.

- **Seamless Data Exploration**: The tabular data view provides a comprehensive overview of your entered data. Browse, search, sort, and filter records effortlessly. This enables efficient data analysis and quick access to specific information.

- **Flexible Data Editing and Deletion**: DataEntry_WebApp allows users to edit or delete existing records directly from the web interface. This simplifies data management, facilitating updates and corrections as needed.

## Installation and Usage

1. Clone the repository: `git clone https://github.com/<username>/dataentry_webapp.git`
2. Navigate to the project directory: `cd dataentry_webapp`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the application: `python app.py`
5. Access the application in your web browser at `http://localhost:7777`

## Deployment

Ready to deploy DataEntry_WebApp in a production environment? Follow these steps:

1. Ensure you have a compatible server or cloud platform.
2. Install the necessary dependencies outlined in the requirements.txt file.
3. Set the Flask environment variable to "production": `export FLASK_ENV=production`
4. Utilize a production-grade WSGI server like Gunicorn to run the application: `gunicorn app:app`
5. Configure any required environment variables for your deployment.
6. Access the application through the appropriate URL or IP address.

## Contributing

We welcome contributions from the community! If you encounter any issues or have suggestions for improvements, please open an issue on the project's GitHub repository.

## License

DataEntry_WebApp is released under the [MIT License](LICENSE).

## Acknowledgements

DataEntry_WebApp was built using the Flask web framework and leverages the openpyxl library for Excel file management. We extend our gratitude to the Flask and openpyxl communities for their invaluable contributions and support.

## Contact

For any inquiries or questions, please reach out to the project maintainer at your-email@example.com. We're excited to hear from you!
