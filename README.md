# ProjectManagementSystem.Docker

### Deploying [ProjectManagementSystem.Api](https://github.com/gradovenko/ProjectManagementSystem.Api) on Linux OS family / Windows OS

### 1. Install and Run

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

### 2. Update

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

## License
This project is not licensed ([NO LICENSE](NOLICENSE)). All rights to the project belong to the author of the project.