# Docker Apache Website - Deployed on AWS EC2

This project demonstrates how to containerize a simple static website using **Apache HTTP Server in Docker**, and deploy it on an **AWS EC2** instance using **Amazon Linux 2023**.

> ✅ Live from: [http://<your-ec2-public-ip>](http://<your-ec2-public-ip>)

---

## 📦 Technologies Used

- **Docker** – Containerized Apache HTTP Server
- **Apache 2.4** – Web server serving static HTML
- **AWS EC2** – Hosted on Amazon Linux 2023
- **Git & GitHub** – Source control and versioning

---

## 🛠 Project Structure

```bash
docker-apache-website/
├── Dockerfile
└── index.html
Dockerfile: Uses httpd:2.4 as the base image and copies a custom index.html into the web root.

index.html: A simple welcome page hosted by Apache.

🚀 How to Run This Project
🐳 Build the Docker Image
docker build -t asha-apache:v1 .
▶️ Run the Container

docker run -d -p 80:80 --name my-apache asha-apache:v1
🌐 Access the Website
Open your browser and go to:


http://<your-ec2-public-ip>
🧠 What I Learned
Building Docker images with real-world use cases

Hosting static websites inside containers

Running containers on EC2 using Amazon Linux 2023

Connecting GitHub workflow to cloud-based deployments

Debugging real network, DNS, and Git issues like a pro

📌 Author
👩‍💻 Asha 
🔗 LinkedIn
📁 GitHub Portfolio

⭐ If you found this project helpful or inspiring, consider giving it a star on GitHub!


