# Hello World Project in Python Language

This is a basic "Hello World" project in the Python programming language. We will use Docker to create a container for the program, and Railway to deploy the project in the cloud.

## Prerequisites

It is required to verify the installation of Python on your computer. To check, open a terminal and run:

```bash
python --version
```

If Python is not installed, download it from [https://www.python.org/downloads/](https://www.python.org/downloads/).

## Clone the Project

1. Locate a folder of your choice and clone the project with the following command:

    ```bash
    git clone https://github.com/Karen020701/aplication-python.git
    ```

2. To run the project locally, navigate to the project folder and execute:

    ```bash
    python app.py
    ```

3. Then, in your browser, go to [http://localhost:5000](http://localhost:5000). You should see the message: **"Hello World python language"**.

## Running with Docker

To run this project in a Docker container:

1. First, pull the Docker image. In the project directory, download the image with the command:

    ```bash
    docker pull karenchicaiza/aplicationpython
    ```

2. To start the container, use the command:

    ```bash
    docker run -p 5000:5000 karenchicaiza/aplicationpython
    ```

3. In your browser, go to [http://localhost:5000](http://localhost:5000) and you will see the message: **"Hello World python language"**.

## Deployment on Railway

This project has been deployed on Railway. The Railway account was connected, and access to the GitHub repository was configured. Once deployed, the following link was generated:

[https://aplication-python-production.up.railway.app/](https://aplication-python-production.up.railway.app/)

![image](https://github.com/user-attachments/assets/47b4e7d0-fc6d-4253-85a3-f9beb5657687)

