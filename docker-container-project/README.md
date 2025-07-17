# Docker Container Project

This project is a simple Docker containerized application built with Python. Below are the instructions on how to build and run the Docker container.

## Project Structure

```
docker-container-project
├── src
│   └── app.py
├── Dockerfile
├── requirements.txt
└── README.md
```

## Prerequisites

- Docker installed on your machine.
- Basic knowledge of Docker and Python.

## Getting Started

1. **Clone the repository:**

   ```
   git clone <repository-url>
   cd docker-container-project
   ```

2. **Build the Docker image:**

   Run the following command in the project root directory:

   ```
   docker build -t my-python-app .
   ```

3. **Run the Docker container:**

   After building the image, you can run the container with:

   ```
   docker run -p 5000:5000 my-python-app
   ```

4. **Access the application:**

   Open your web browser and go to `http://localhost:5000` to see the application in action.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.