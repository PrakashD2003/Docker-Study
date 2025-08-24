
# Docker Study

This repository collects resources and examples for learning **Docker** and containerisation.  
It includes a comprehensive Docker guide along with a simple demonstration of serving a static website using **Nginx** inside a Docker container.

---

## 🚀 Quick Overview

**Goal:** Understand Docker fundamentals and how to package applications into containers.  
**Topics Covered:**
- Docker installation & setup  
- Dockerfile basics  
- Building and running images  
- Serving a static website with Nginx inside Docker  

**Tech Stack:** Docker, Nginx, HTML/CSS  

**Highlights:**
- Step-by-step Docker learning material  
- Example project: running a simple website with Dockerised Nginx  

---

## 📂 Repository Structure

| Path | Description |
|------|-------------|
| [`README.md`](https://github.com/PrakashD2003/Docker-Study/blob/main/README.md) | Detailed notes and study material on Docker concepts |
| [`nginx-docker-website/Dockerfile`](https://github.com/PrakashD2003/Docker-Study/blob/main/nginx-docker-website/Dockerfile) | Dockerfile for building an Nginx container serving a static website |
| [`nginx-docker-website/website/index.html`](https://github.com/PrakashD2003/Docker-Study/blob/main/nginx-docker-website/website/index.html) | Simple HTML file served via Nginx inside the container |

---

## ⚙️ How It Works

### Docker Learning Notes
The [README.md](https://github.com/PrakashD2003/Docker-Study/blob/main/README.md) file serves as a **comprehensive study guide** on Docker basics, commands, and workflows.

### Nginx Website Example
1. The [Dockerfile](https://github.com/PrakashD2003/Docker-Study/blob/main/nginx-docker-website/Dockerfile) uses the **Nginx base image**.  
2. It copies the static website from the `website/` folder into the Nginx HTML directory.  
3. Builds a container that runs a lightweight Nginx server.  

---

## ▶️ Running the Project

### 1. Clone the Repo
```bash
git clone https://github.com/PrakashD2003/Docker-Study.git
cd Docker-Study/nginx-docker-website
````

### 2. Build the Docker Image

```bash
docker build -t docker-study-nginx .
```

### 3. Run the Container

```bash
docker run -d -p 8080:80 docker-study-nginx
```

Now open **[http://localhost:8080](http://localhost:8080)** in your browser to view the sample website.

---

## 📊 Key Learnings

* Writing a **Dockerfile**
* Building and running Docker images
* Understanding container networking (`-p 8080:80`)
* Using Docker to serve static files via **Nginx**

---

## 🔮 Future Improvements

* Add examples for **multi-stage builds**
* Show how to use **Docker Compose** for multi-container setups
* Expand examples with **volumes** and **environment variables**

---

## 🙌 Closing Notes

This repository serves as a **personal Docker learning playground**.
It includes both theoretical notes and practical examples.

👉 [View the Repository on GitHub](https://github.com/PrakashD2003/Docker-Study)


