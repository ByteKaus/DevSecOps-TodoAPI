# DevSecOps-TodoAPI
Repositorio de pruebas para una api de gestión de tareas

# Estructura del proyecto:

```
DevSecOps-TodoAPI/
│── .github/
│ └── workflows/
│ └── ci-cd.yml # Pipeline CI/CD en GitHub Actions
│── src/
│ ├── app.py # API Flask
│ ├── models.py # Base de datos SQLite
│ ├── routes.py # Rutas de la API
│ ├── auth.py # Autenticación JWT
│ ├── database.db # Base de datos SQLite
│ ├── requirements.txt # Dependencias de Python
│── Dockerfile # Dockerfile para contenedor
│── docker-compose.yml # Docker Compose para local
│── terraform/
│ ├── main.tf # Infraestructura en AWS
│ ├── variables.tf # Variables de Terraform
│ ├── outputs.tf # Salida de Terraform
│── README.md # Descripción del proyecto

```