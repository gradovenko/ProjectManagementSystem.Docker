# **ProjectManagementSystem.Docker**

## Deploying [ProjectManagementSystem.WebApi](https://github.com/gradovenko/ProjectManagementSystem.WebApi) on Linux OS family / Windows OS / macOS:

## 1. Install and Run

**Clone application repository:**  
```bash
git clone https://github.com/gradovenko/ProjectManagementSystem.Docker.git
```

**Go to the application repository directory:**  
```bash
cd ProjectManagementSystem.Docker
```

**Download application:**  
```bash
docker-compose pull
```

**Start application:**  
```bash
docker-compose up -d
```

## 2. Update

**Stop application:**  
```bash
docker-compose down
```

**Update repository:**  
```bash
git pull
```

**Update application:**  
```bash
docker-compose pull
```

**Start application:**  
```bash
docker-compose up -d
```