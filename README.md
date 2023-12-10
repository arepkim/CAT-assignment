# PDF to TXT Converter
This project is a collaborative effort between a team aiming in developing a user-friendly web application with a graphical interface using a web programming languages. The objective of this assignment is to set up a Linux Apache web server using Docker and create a seamless platform option allowing users to connvert PDF files to TXT files format and vice versa.

# ⚙️ Prerequisite
User will need [Docker Desktop](https://www.docker.com/products/docker-desktop/) in your system for this project to run execute properly


# 🔥 Getting Started
To run this project, you will need to follow the given instructions below:

  1. Open your daily terminal
  2. Navigate to the project folder
  3. Run the following command to build and run the container
     
  <pre>
    #building the image
    docker build -t pdftxt

    #running the container
    docker run -dit --name pdftxt -p 8081:80 pdftxt  
    
  </pre>
  
  4. Docker will start to build image and run the container. You can check if the container is running using this command.
  <pre>
    docker ps
  </pre>

  5. Open your browser and navigate to (https://localhost:8081/) to see the website
  6. Finally, to stop the running container, you can run this command.
  <pre>
    docker stop pdftxt
  </pre>

  7. Later you will enter the website for this application, then you can choose whether to convert a pdf to txt or vice versa. Just choose to upload a file in the given segment then choose to convert it. You will   get a new file in transform version.
  8. There is also a contact information for each group member regarding the website development process.

