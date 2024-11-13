**Hello World” project in Python language**  
This is a basic project of a “Hello World” in python language, we are going to use Docker to create a container of the program and Railway is used to deploy the project in the cloud.  

It is required to verify the installation of the Python extension on the computer, this is done by accessing to the computer and running the command python --version otherwise if you don't have it go to https://www.python.org/downloads/ and download it.  

**Clone the project**  

Locate in a folder of preference to be able to clone the project with the following command:  
https://github.com/Karen020701/aplication-python.git  

To run the project locally, navigate to the project folder and execute the command:  
python app.py  

In the browser enter http://localhost:5000 and the message “Hello World python language” will be displayed.  

**Running with Docker**  
An image is built in Docker. Once inside the directory to download the created image the command is executed:  
docker pull karenchicaiza/aplicationpython  

To run the container the command is used:  
docker run -p 5000:5000 karenchicaiza/aplicationpython  

In the browser enter http://localhost:5000 and the message “Hello World python language” will be displayed.  


**Deployment on Railway**  
This project was deployed in Railway, the connection to the Railway account and access to the repository in Github was done.   
Once deployed I generate the link: https://aplication-python-production.up.railway.app/ 

![image](https://github.com/user-attachments/assets/47b4e7d0-fc6d-4253-85a3-f9beb5657687)

