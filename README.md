# 📌 Inception

## 📝 Description
This project aims to broaden your knowledge of system administration by using Docker.
You will virtualize several Docker images .

## 📂 Directory Structure
```
/Inception
│── srcs/
│────── requirements/
│──────────── bonus/
│──────────────────────── adminer/
│──────────────────────── ftp/
│──────────────────────── redis/
│──────────────────────── service/
│──────────────────────── static_site/
│──────────── mariadb/
│──────────── nginx/
│──────────── wordpress/
│────── docker-compose.yml
│── Makefile
│── .env
```

## 🛠 Prerequisites
Before running this project, make sure you have the following installed:
- Docker
- Docker Compose
- Make

## 🔧 Installation
```bash
git clone https://github.com/Salah-Diouane/Inception.git
cd yourproject
```

## ▶️ Running the Project
```bash
make all
```

To stop the project:
```bash
make clean
```
To enter a container:
```bash
docker exec -it container_name bash
```


## 👤 Contributors
- **Salah-Eddine Diouane** - [GitHub](https://github.com/salah-diouane)

## 📜 License
This project is licensed under the MIT License.

## 📚 Resources
- [Medium](https://medium.com/@salahdiouane964/8e0ad67e0eb4)
- [Docker Documentation](https://docs.docker.com/)

