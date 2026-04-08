# python-flask

A basic Hello World Flask application.

## Installation

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

Run the application:
```
python ap.py
```

The app will start on http://127.0.0.1:5000/

Visit http://127.0.0.1:5000/ in your browser to see "Hello, World!"

## Docker

Build the Docker image:
```
docker build -t python-flask .
```

Run the container:
```
docker run -p 5000:5000 python-flask
```

The app will be available at http://localhost:5000/