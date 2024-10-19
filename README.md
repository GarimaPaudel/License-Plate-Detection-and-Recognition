# Parking Management System with ANPR

## Overview

This project is a comprehensive parking management system that utilizes Automatic Number Plate Recognition (ANPR) technology to manage and monitor parking spaces. The system is designed to automate the process of vehicle identification, parking space allocation, and overall parking management.

## Features

- **Automatic Number Plate Recognition (ANPR)**: Efficiently reads and processes vehicle number plates using state-of-the-art image processing techniques.
- **Real-time Monitoring**: View available parking spaces and track parking status in real-time.
- **Database Integration**: Store and manage parking records, including vehicle information and parking history.
- **User Interface**: Intuitive web-based interface for both administrators and users.
- **Image Processing**: Handles image uploads, resizing, and storage for ANPR and other functionalities.
- **Migration Support**: Database migrations to handle schema changes seamlessly.

## Technologies Used

- **Backend**: Python with Django framework
- **Database**: SQLite
- **ANPR**: YOLOv9 for license plate detection and easyOCR for character recognition
- **Frontend**: HTML, CSS

## Installation

### Prerequisites

- Python 3.x
- Django
- OpenCV
- Other dependencies listed in `requirements.txt` inside the `yolov9` folder

### Steps

1. **Clone the Repository**

    ```sh
    git clone https://github.com/NiShApOkHaReL/myproject.git
    ```

2. **Navigate to the Project Directory**

    ```sh
    cd myproject
    ```

3. **Run Database Migrations**

    ```sh
    python manage.py migrate
    ```

4. **Run the Development Server**

    ```sh
    python manage.py runserver
    ```

5. **Open your Browser**

    Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to view the application.

## Usage

-  Provides real-time monitoring of parking spaces and user management.
-  Allows users to check available parking spaces, vehicle history, and other details.

## License

This project is licensed under the MIT License.
