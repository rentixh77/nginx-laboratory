# Nginx Static Server
Развертывание статического сервера Nginx в Docker.

## Сборка и запуск
```bash
docker build -t my-nginx-site:latest .
docker run -d -p 80:80 --name nginx-site my-nginx-site:latest
