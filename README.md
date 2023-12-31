# Data Entry Web App

<div align="center">
  <img src="https://github.com/Divinemonk/DataEntryWebApp/assets/82360546/2efe0eb3-1e44-4711-9a4a-f718173e05a1" alt="DataEntry_WebApp" align="left">
</div>

Data Entry Web App is a sleek and user-friendly web application designed to streamline data entry and management processes. Built with Flask, a powerful Python web framework, this application offers a hassle-free solution for efficient data handling, making it the perfect tool for small to medium-sized data-driven projects.


## Features

- **Effortless Data Entry**: With its clean and intuitive interface, Data Entry WebApp ensures a smooth data entry experience. Users can quickly input information like names, genders, emails, addresses, and roles. The application includes robust validation checks, ensuring data integrity and completeness.

- **Secure Data Storage and Retrieval**: All entered data is securely stored in an Excel file (.xlsx) on the server, powered by the reliable openpyxl library. This guarantees easy data storage and retrieval, giving you peace of mind knowing your data is safe.

- **Seamless Data Exploration**: The tabular data view provides a comprehensive overview of your entered data. Browse, search, sort, and filter records effortlessly. This enables efficient data analysis and quick access to specific information.

- **Flexible Data Editing and Deletion**: Data Entry WebApp allows users to edit or delete existing records directly from the web interface. This simplifies data management, facilitating updates and corrections as needed.

<br>

## Installation and Usage

> After running the .py/.exe, the program will open the web application in the default browser

#### 1. Using `git`:
- Clone the repository: `git clone https://github.com/Divinemonk/DataEntryWebApp.git`
- Navigate to the project directory: `cd DataEntryWebApp`
- Install the required dependencies: `pip install -r requirements.txt`
- Run the application: `python DataEntryWebApp.py`
- Access the application in your web browser at `http://localhost:7777`

#### 2. Windows executable (`.exe`) file:
- Download latest windows executable file from [here](https://github.com/Divinemonk/DataEntryWebApp/releases/latest/download/DataEntryWebApp.exe)
- Double click the executable to run the program
- Access the application in your web browser at `http://localhost:7777`

#### 2. Linux LSB executable file:
- Download latest windows executable file from [here](https://github.com/Divinemonk/DataEntryWebApp/releases/latest/download/DataEntryWebApp)
- Double click the executable to run the program
- Access the application in your web browser at `http://localhost:7777`

> Check out [releases](https://github.com/Divinemonk/DataEntryWebApp/releases) for all avaliable versions

<br>

## Contributing

We welcome contributions from the community! If you encounter any issues or have suggestions for improvements, please open an issue on the project's GitHub repository.

## License

Data Entry Web App is released under the [MIT License](LICENSE).

## Acknowledgements

We would like to express our sincere appreciation to the following projects and their respective communities for their valuable contributions to the development of the Data Entry Web App.

[Flask](https://github.com/pallets/flask), a powerful Python web framework, provided the foundation for our application. Its simplicity, flexibility, and extensive ecosystem enabled us to create a robust and user-friendly web application. We are grateful for the Flask community's continuous support and for making web development in Python a breeze.

[Openpyxl](https://github.com/theorchard/openpyxl), an essential component of our project, greatly enhanced the accessibility and user experience of our application by enabling it to open in the default web browser. We extend our thanks to the OpenXGL community for their efforts in developing this useful tool.

WebBrowser, another crucial component, facilitated seamless interaction between our application and the user's preferred web browser. Its integration allowed for a smoother and more intuitive user experience. We are grateful for the WebBrowser project and its developers' dedication.

[Gunicorn](https://github.com/benoitc/gunicorn), a high-performance WSGI HTTP server, played a vital role in deploying our application in a production environment. Its ability to handle concurrent requests efficiently ensured optimal performance and reliability. We would like to extend our appreciation to the Gunicorn community for their exceptional work.

We would also like to acknowledge the wider open-source community for their continuous support, knowledge sharing, and feedback. The collaborative spirit and contributions from developers around the world have greatly enriched our project.
