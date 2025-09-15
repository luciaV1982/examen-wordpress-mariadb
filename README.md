# Examen – WordPress + MariaDB en Kubernetes y Docker Compose

Este repositorio contiene los manifiestos de **Kubernetes** y el archivo de **Docker Compose** para levantar un stack con:

- **MariaDB**
- **WordPress**
- **phpMyAdmin** (opcional, solo en Compose)

---

## 🚀 Opción 1 – Desplegar en Kubernetes (Minikube)

1. Clonar este repositorio:

```bash
git clone https://github.com/luciaV1982/examen-wordpress-mariadb.git
cd examen-wordpress-mariadb/k8s
cd examen-wordpress-mariadb/compose

docker compose up -d

Acceder a:

WordPress → http://localhost:8080

phpMyAdmin → http://localhost:8081
