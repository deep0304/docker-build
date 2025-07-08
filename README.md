🚀 Docker Static Site (HTML + CSS)

This project runs a simple and elegant static website using Docker and Nginx.

📦 Clone the Project

git clone https://github.com/deep0304/docker-build.git
cd docker-build

🐳 Install Docker

Make sure Docker is installed on your system:

Install Docker (Windows/Mac/Linux)

You can verify Docker installation using:

docker --version

🔨 Build the Docker Image

Ensure your project contains the Dockerfile and a folder like html/ with your website content.

Now build the image:

docker build -t image-name .

🚀 Run the Container

docker run -d -p 8081:80 --name yoursite image-name

🌐 View the Website

Now open your browser and visit:

http://localhost:8081

You will see your HTML + CSS site running inside a Docker container.

🖼️ Sample Preview



📁 Project Structure

.
├── Dockerfile 
├── index.html
└── style.css

🩹 To Stop and Clean Up

docker stop mysite
docker rm mysite

-----
EXAMPLE
![image](https://github.com/user-attachments/assets/0db2d5aa-9b96-4d53-9a62-8c92f6f1d44c)
------


