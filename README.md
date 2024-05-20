# COVID-19-AI

This Docker image packages the COVID-19-AI project, a Flask web application with Gunicorn as the WSGI HTTP server. Developed in the Net-Media-Sys Lab at the University of Calgary, this project leverages AI to provide insights and information related to COVID-19.

Docker Hub link: [aliasifm/covid_flask_gunicorn](https://hub.docker.com/r/aliasifm/covid_flask_gunicorn)

## Features

- **Flask Framework**: Lightweight and easy-to-use web framework for Python.
- **Gunicorn**: A high-performance HTTP server for Python web applications, providing better performance and handling multiple requests.
- **Ready to Use**: Pre-configured with all necessary dependencies for running the application.

## Getting Started

### Prerequisites

- Docker installed on your local machine.

### Pulling the Image

To pull the image from Docker Hub, run the following command:

```bash
docker pull aliasifm/covid_flask_gunicorn
```

### Running the Container

To run the container, use the following command:

```bash
docker run -d -p 8000:8000 aliasifm/covid_flask_gunicorn
```

This will start the container and map port 8000 of the container to port 8000 on your local machine. You can access the application by navigating to `http://localhost:8000` in your web browser.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or bug fixes.
