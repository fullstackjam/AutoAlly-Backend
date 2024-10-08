# AutoAlly-Backend

Backend is a FastAPI-based service designed to preprocess and forward instant messages.

## Features
- Receive and preprocess instant messages (IM).
- Forward the processed messages to other services.
- Easily scalable and built on the robust FastAPI framework.

## Prerequisites
- Python 3.10+
- Docker (for containerization)

## Getting Started
### Setting Up the Development Environment
1. Clone the repository:

```bash
git clone https://github.com/fullstackjam/AutoAlly-Backend.git
cd AutoAlly-Backend
```
2. Set up a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```
3. Install the required dependencies:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```
4. Run the FastAPI application:

```bash
uvicorn app:api --reload
```
Visit http://127.0.0.1:8000/ in your browser to see the application in action.

## Using Docker
1. Build the Docker image:

```bash
docker build -t your_dockerhub_username/backend:latest .
```
2. Run the Docker container:

```bash
docker run -p 8000:8000 your_dockerhub_username/backend:latest
```
Visit http://127.0.0.1:8000/ in your browser to access the service running inside the Docker container.

## Contribution
Feel free to fork this repository, submit issues, or open pull requests to enhance the functionalities of Backend.

## License
[MIT]
