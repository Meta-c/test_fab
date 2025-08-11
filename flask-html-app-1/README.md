# Flask HTML App

This project is a simple Flask application that serves an HTML page with integrated Watson Orchestrate service configuration.

## Project Structure

```
flask-html-app
├── src
│   ├── app.py                # Main application file
│   └── templates
│       └── test.html        # HTML page served by the application
├── requirements.txt          # Python dependencies
├── Dockerfile                # Docker configuration for the application
├── README.md                 # Project documentation
└── .dockerignore             # Files to ignore when building the Docker image
```

## Requirements

To run this project, you need to have Python and Flask installed. The dependencies are listed in `requirements.txt`.

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd flask-html-app
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the Flask application locally, execute the following command:
```
python src/app.py
```
The application will be available at `http://127.0.0.1:5000`.

## Docker Setup

To build and run the application using Docker, follow these steps:

1. Build the Docker image:
   ```
   docker build -t flask-html-app .
   ```

2. Run the Docker container:
   ```
   docker run -p 5000:5000 flask-html-app
   ```

The application will be accessible at `http://localhost:5000`.

## License

This project is licensed under the MIT License.