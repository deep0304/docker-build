🚀 Docker Static Site (HTML + CSS)

This project runs a simple and elegant static website using Docker and Nginx.

📦 Clone the Project
```bash
git clone https://github.com/deep0304/docker-build.git
cd docker-build
```

🐳 Install Docker

Make sure Docker is installed on your system:

Install Docker (Windows/Mac/Linux)

You can verify Docker installation using:

```bash
docker --version
```

🔨 Build the Docker Image

Ensure your project contains the Dockerfile and a folder like html/ with your website content.

Now build the image:

```bash
docker build -t image-name .
```

🚀 Run the Container
```bash
docker run -d -p 8081:80 --name yoursite image-name
```
🌐 View the Website

Now open your browser and visit:
```bash
http://localhost:8081
```

You will see your HTML + CSS site running inside a Docker container.


🩹 To Stop and Clean Up
```bash
docker stop mysite
```

```bash
docker rm mysite
```

-----

Simple preview

![image](https://github.com/user-attachments/assets/0db2d5aa-9b96-4d53-9a62-8c92f6f1d44c)

------


