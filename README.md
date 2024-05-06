# Dockerized Web Application

## About This Project
This project is a simple web application Dockerized for easy deployment and scalability. It demonstrates the use of Docker to containerize applications, making them portable across different environments.

## Technologies Used
- Docker: Containerization platform used to package the application and its dependencies into a container.
- Flask: Lightweight WSGI web application framework used for building the web application.
- HTML/CSS: Frontend technologies used for creating the user interface.

## Prerequisites
Make sure you have Docker installed on your system. You can download and install Docker from [here](https://www.docker.com/get-started).

## Getting Started
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Build the Docker image:
    ```
    docker build -t dockerized-web-app .
    ```
4. Run the Docker container:
    ```
    docker run -d -p 5000:5000 dockerized-web-app
    ```
5. Open your web browser and visit `http://localhost:5000` to view the application.

## Project Structure
- `app.py`: Main Python script containing the Flask application.
- `templates/`: Directory containing HTML templates for the web application.
- `static/`: Directory containing static files (e.g., CSS stylesheets, images).

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for any improvements or features you'd like to add.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, feel free to reach out:
